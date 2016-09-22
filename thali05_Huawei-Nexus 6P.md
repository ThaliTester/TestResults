#### Test 86333246115ab5f_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 09:47:10.594   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-22 09:47:10.594   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-22 09:47:11.078  5395  5395 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 09:47:11.083  5395  5395 D AndroidRuntime: CheckJNI is OFF
09-22 09:47:11.106  5395  5395 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 09:47:11.142  5395  5395 I Radio-JNI: register_android_hardware_Radio DONE
09-22 09:47:11.157  5395  5395 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 09:47:11.160   928  3102 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 09:47:11.195   928  3102 I ActivityManager: Start proc 5404:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 09:47:11.199  5395  5395 D AndroidRuntime: Shutting down VM
,09-22 09:47:11.539   928  3354 I WindowManager: Screenshot max retries 4 of Token{cc5bb62 ActivityRecord{f4f8a2d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{b94d1e5 u0 Starting com.test.thalitest} drawState=2
,09-22 09:47:11.620  5404  5404 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 09:47:11.652  5404  5404 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-22 09:47:11.679  5404  5404 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 2-22)
,09-22 09:47:11.679  5404  5404 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 09:47:11.699  5404  5404 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {af7ecad}
,09-22 09:47:11.700  5404  5404 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 09:47:11.700  5404  5404 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 09:47:11.705  5404  5404 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-22 09:47:11.707  5404  5404 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 09:47:11.742  5404  5404 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 09:47:11.755  5404  5404 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 09:47:11.755  5404  5404 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 09:47:11.755  5404  5404 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 09:47:11.755  5404  5404 I Adreno  : Build Date                       : 12/06/15
09-22 09:47:11.755  5404  5404 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 09:47:11.755  5404  5404 I Adreno  : Local Branch                     : mybranch17112971
09-22 09:47:11.755  5404  5404 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 09:47:11.755  5404  5404 I Adreno  : Remote Branch                    : NONE
09-22 09:47:11.755  5404  5404 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 09:47:11.810   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e31ae0:true
,09-22 09:47:11.844   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[30020]" dev="sockfs" ino=30020 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 09:47:11.844   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30020]" dev="sockfs" ino=30020 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 09:47:11.862  5404  5404 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 09:47:11.872  5404  5404 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 09:47:11.903  5404  5441 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 09:47:11.901   403   403 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32920]" dev="sockfs" ino=32920 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 09:47:11.901   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32920]" dev="sockfs" ino=32920 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 09:47:11.904  3773  3773 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30024]" dev="sockfs" ino=30024 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 09:47:11.904  3773  3773 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30024]" dev="sockfs" ino=30024 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 09:47:11.911  5404  5428 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 09:47:11.935  5404  5441 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 09:47:12.014   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +471ms (total +842ms)
,09-22 09:47:12.066  5404  5404 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5404
,09-22 09:47:12.163  5404  5404 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 09:47:12.339  5404  5443 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -584058576
,09-22 09:47:12.345  5404  5443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 09:47:12.345  5404  5443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 09:47:12.345  5404  5443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 09:47:12.345  5404  5443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 09:47:12.345  5404  5443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 09:47:12.345  5404  5443 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eb5ab added. We now have 1 listener(s)
,09-22 09:47:12.347  5404  5443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-22 09:47:12.348  5404  5443 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 09:47:12.348  5404  5443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:47:12.348  5404  5443 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 09:47:12.350  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-22 09:47:12.351  5404  5443 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9232dc6 added. We now have 1 listener(s)
09-22 09:47:12.351  5404  5443 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:47:12.361   928  2919 D WifiService: New client listening to asynchronous messages
,09-22 09:47:12.362  5404  5443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 09:47:12.363  5404  5443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 09:47:12.363  5404  5443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 09:47:12.363  5404  5443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 09:47:12.363  5404  5443 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-22 09:47:12.365  5404  5443 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:47:12.366  5404  5443 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-22 09:47:12.372  5404  5443 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:12.372  5404  5443 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:47:12.373  5404  5443 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 09:47:12.373  5404  5443 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:12.373  5404  5443 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 09:47:12.377  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:12.384  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:12.402  5404  5404 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 09:47:12.683  5404  5450 W jxcore-log: Initializing JXcore engine
09-22 09:47:12.684  5404  5450 W jxcore-log: JXcore engine is ready
,09-22 09:47:12.704  5450  5450 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11695 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-22 09:47:12.704  5450  5450 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[17426]" dev="sockfs" ino=17426 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 09:47:12.704  5450  5450 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 09:47:12.704  5450  5450 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31422]" dev="sockfs" ino=31422 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 09:47:12.715   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:47:12.715  5404  5450 W jxcore-log: Starting JXcore engine
,09-22 09:47:12.775  5404  5450 W jxcore-log: Platform android
09-22 09:47:12.775  5404  5450 W jxcore-log: 
,09-22 09:47:12.775  5404  5450 W jxcore-log: Process ARCH arm
09-22 09:47:12.775  5404  5450 W jxcore-log: 
,09-22 09:47:12.875  5404  5450 I jxcore-log: JXcore Cordova bridge is ready!
09-22 09:47:12.875  5404  5450 I jxcore-log: 
,09-22 09:47:12.875  5404  5450 W jxcore-log: JXcore engine is started
,09-22 09:47:12.888  5404  5443 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 09:47:12.895  5404  5404 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 09:47:20.596   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:21.597   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:22.485  5404  5450 I jxcore-log: 2016-09-22 13:47:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-22 09:47:22.485  5404  5450 I jxcore-log: 
,09-22 09:47:22.488  5404  5450 I jxcore-log: 2016-09-22 13:47:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-22 09:47:22.488  5404  5450 I jxcore-log: 
,09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:22.492  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:47:22.494  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.495  5404  5450 I jxcore-log: 2016-09-22 13:47:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-22 09:47:22.495  5404  5450 I jxcore-log: 
,09-22 09:47:22.497  5404  5450 I jxcore-log: 2016-09-22 13:47:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-22 09:47:22.497  5404  5450 I jxcore-log: 
,09-22 09:47:22.598   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:22.738  5404  5450 I jxcore-log: Running unit tests
09-22 09:47:22.738  5404  5450 I jxcore-log: 
,09-22 09:47:22.738  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 09:47:22.738  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fd0430 added. We now have 2 listener(s)
09-22 09:47:22.739  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 09:47:22.739  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:47:22.739  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:47:22.740  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 09:47:22.740  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2198a9 added. We now have 2 listener(s)
09-22 09:47:22.740  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 09:47:22.740  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 09:47:22.742  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:22.745  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:47:22.746  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.746  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:22.747  5404  5450 D executeNativeTests: Running unit tests
,09-22 09:47:22.752  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:22.758  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:22.785  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 09:47:22.785  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf added. We now have 3 listener(s)
09-22 09:47:22.786  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 09:47:22.786  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:47:22.786  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:47:22.786  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:47:22.786  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c added. We now have 3 listener(s)
,09-22 09:47:22.786  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:47:22.786  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 09:47:22.788  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:22.790  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:47:22.791  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 09:47:22.791  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:22.792  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 09:47:22.792  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 09:47:22.792  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 09:47:22.793  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 09:47:22.793  5404  5450 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 09:47:22.793  5404  5450 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 09:47:22.793  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 09:47:22.793  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 09:47:22.793  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 09:47:22.793  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 09:47:22.794  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:22.794  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:22.794  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:22.794  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:22.794  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.794  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:22.794  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 09:47:22.795  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf removed from the list
09-22 09:47:22.795  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:22.795  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c removed from the list
09-22 09:47:22.796  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:22.796  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:22.796  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.797  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.797  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.797  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:22.797  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-,22 09:47:22.797  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:22.797  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:22.798  5404  5450 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 09:47:22.798  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:22.798  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:22.798  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:22.798  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:22.799  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.799  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.799  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:22.799  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:22.799  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:22.801  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:22.802  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:22.802  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.802  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:22.802  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.802  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.802  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:22.803  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:22.803  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:22.803  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 09:47:22.805  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 09:47:22.806  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:22.806  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:22.806  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:22.806  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:22.806  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.806  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.806  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:22.806  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:47:22.806  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:22.806  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:22.806  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.806  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.806  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:22.806  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:22.807  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:22.807  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:22.807  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:22.807  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:22.807  5404  5450 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 09:47:22.808  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:22.810  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:47:22.812  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:22.812  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:22.812  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 09:47:22.812  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 09:47:22.812  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-22 09:47:22.812  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:22.812  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:22.814  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:22.814  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 09:47:22.814  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:22.815  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:22.816  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 09:47:22.817  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:47:22.817  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:47:22.818  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-22 09:47:22.819  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 09:47:22.819  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 09:47:22.820  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 09:47:22.820  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 09:47:22.820  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:47:22.822  4428  4650 D BtGatt.GattService: registerClient() - UUID=7fa3f7b6-a4fb-46d0-8ada-aa3030534d0e
,09-22 09:47:22.823  4428  4489 D BtGatt.GattService: onClientRegistered() - UUID=7fa3f7b6-a4fb-46d0-8ada-aa3030534d0e, clientIf=5
,09-22 09:47:22.823  5404  5415 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 09:47:22.824  4428  4449 D BtGatt.GattService: start scan with filters
,09-22 09:47:22.828  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 09:47:22.828  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 09:47:22.829  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 09:47:22.829  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 09:47:22.830  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 09:47:22.830  4428  4492 D BtGatt.ScanManager: handling starting scan
09-22 09:47:22.830  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 09:47:22.830  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 09:47:22.830  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 09:47:22.832  5404  5450 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 09:47:22.832  4428  4492 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:47:22.840  4428  4489 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-22 09:47:22.840  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:22.841  4428  4492 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 09:47:22.846  4428  4489 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 09:47:22.846  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:47:22.847  4428  4492 D BtGatt.ScanManager: Starting BLE batch scan
09-22 09:47:22.847  4428  4492 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 09:47:22.857  4428  4489 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 09:47:22.857  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:47:22.863  4428  4489 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 09:47:22.863  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:47:23.332  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-22 09:47:23.332  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 09:47:23.332  5404  5404 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 09:47:23.512   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 09:47:23.517   928  2920 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-22 09:47:23.599   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:24.600   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:25.600   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-22 09:47:26.538   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 09:47:26.544   928  2920 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-22 09:47:27.836  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:47:27.836  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:47:27.836  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 09:47:27.836  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:27.836  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-22 09:47:27.836  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:47:27.837  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 09:47:27.841  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-22 09:47:27.841  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 09:47:27.842  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 09:47:27.842  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 09:47:27.844  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:47:27.845  4428  4445 D BtGatt.GattService: stopScan() - queue size =1
,09-22 09:47:27.848  4428  4650 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 09:47:27.848  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 09:47:27.849  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 09:47:27.849  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 09:47:27.849  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-22 09:47:27.849  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 09:47:27.852  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 09:47:27.852  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 09:47:27.853  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-22 09:47:27.853  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:47:27.854  4428  4428 D BtGatt.ScanManager: awakened up at time 236197
09-22 09:47:27.856  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:27.859  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:27.859  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 09:47:27.859  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:27.859  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:27.859  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:27.859  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 09:47:27.859  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:27.860  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:27.860  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:27.860  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:27.860  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:27.863  4428  4489 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 09:47:27.863  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:27.864  4428  4492 D BtGatt.ScanManager: stopping BLe Batch
09-22 09:47:27.865  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:27.865  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 09:47:27.872  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 09:47:27.874  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 09:47:27.875  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:47:27.875  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:27.875  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:27.877  4428  4489 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 09:47:27.877  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:27.877  4428  4492 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 09:47:27.879  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:27.879  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:27.879  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:47:27.882  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:47:27.883  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:27.883  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:27.886  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 09:47:27.897  4428  4489 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-22 09:47:27.897  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:27.898  4428  4489 D BtGatt.GattService: current time is 236241327086
09-22 09:47:27.898  4428  4489 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -74, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -76, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-22 09:47:27.900  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-22 09:47:27.901  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 09:47:27.901  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 09:47:27.902  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 09:47:27.902  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-22 09:47:28.387  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 09:47:30.602   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:31.604   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:32.605   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:32.866  5404  5450 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-22 09:47:32.877  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:32.887  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:47:32.892  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 09:47:32.892  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:32.893  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 09:47:32.893  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 09:47:32.893  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 09:47:32.893  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:32.893  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:47:32.900  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:32.902  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:32.905  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:32.908  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 09:47:32.908  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 09:47:32.908  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 09:47:32.910  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:47:32.914  4428  4449 D BtGatt.GattService: registerClient() - UUID=c3894190-c9b7-49c8-8477-59d25d62aea0
,09-22 09:47:32.916  4428  4489 D BtGatt.GattService: onClientRegistered() - UUID=c3894190-c9b7-49c8-8477-59d25d62aea0, clientIf=5
09-22 09:47:32.917  5404  5414 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 09:47:32.918  4428  4650 D BtGatt.GattService: start scan with filters
,09-22 09:47:32.923  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 09:47:32.923  4428  4492 D BtGatt.ScanManager: handling starting scan
09-22 09:47:32.923  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 09:47:32.923  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 09:47:32.923  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 09:47:32.928  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 09:47:32.929  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 09:47:32.929  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 09:47:32.931  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 09:47:32.934  4428  4489 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 09:47:32.934  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.935  4428  4492 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 09:47:32.935  5404  5450 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 09:47:32.938  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:32.939  5404  5450 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 09:47:32.939  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:32.939  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 09:47:32.939  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:32.939  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 09:47:32.939  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:47:32.939  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 09:47:32.939  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 09:47:32.939  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 09:47:32.939  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 09:47:32.939  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 09:47:32.941  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:32.941  4428  4445 D BtGatt.GattService: stopScan() - queue size =1
09-22 09:47:32.942  4428  4449 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 09:47:32.942  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:32.943  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 09:47:32.943  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 09:47:32.943  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 09:47:32.943  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 09:47:32.944  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:47:32.944  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:32.944  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 09:47:32.944  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:32.945  4428  4489 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 09:47:32.945  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.945  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 09:47:32.946  4428  4492 D BtGatt.ScanManager: Starting BLE batch scan
09-22 09:47:32.946  4428  4492 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 09:47:32.947  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:32.947  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:32.947  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:32.947  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:32.947  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:32.947  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 09:47:32.947  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:32.947  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:32.947  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:32.948  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:32.948  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:32.950  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:32.951  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 09:47:32.960  4428  4489 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 09:47:32.960  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.961  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 09:47:32.962  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:47:32.962  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 09:47:32.962  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:47:32.967  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:32.968  4428  4489 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 09:47:32.968  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.969  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:32.969  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:32.969  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:47:32.972  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:32.973  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:32.973  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:32.975  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:47:32.975  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:32.975  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:32.976  4428  4489 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 09:47:32.977  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.977  4428  4492 D BtGatt.ScanManager: stopping BLe Batch
,09-22 09:47:32.977  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:32.977  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:32.977  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:47:32.978  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:32.978  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:32.978  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:32.978  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:32.978  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:32.979  5404  5450 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 09:47:32.980  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:32.983  4428  4489 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 09:47:32.983  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.983  4428  4492 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:32.985  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:47:32.987  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:32.988  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:32.988  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 09:47:32.988  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 09:47:32.988  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-22 09:47:32.988  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:32.988  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:47:32.990  4428  4489 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 09:47:32.990  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:32.991  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:32.992  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:47:32.994  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:32.996  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 09:47:32.996  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 09:47:32.996  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 09:47:32.997  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:47:32.999  4428  4449 D BtGatt.GattService: registerClient() - UUID=fa039759-5f13-4ab1-a7f9-2087de122325
09-22 09:47:32.999  4428  4489 D BtGatt.GattService: onClientRegistered() - UUID=fa039759-5f13-4ab1-a7f9-2087de122325, clientIf=5
09-22 09:47:32.999  5404  5414 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 09:47:32.999  4428  4650 D BtGatt.GattService: start scan with filters
,09-22 09:47:33.002  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 09:47:33.002  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 09:47:33.002  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 09:47:33.002  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 09:47:33.002  4428  4492 D BtGatt.ScanManager: handling starting scan
,09-22 09:47:33.004  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 09:47:33.004  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 09:47:33.005  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 09:47:33.006  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 09:47:33.008  5404  5450 I io.jxcore.node.ConnectionHelper: start: OK
09-22 09:47:33.010  4428  4489 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 09:47:33.010  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:33.010  4428  4492 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 09:47:33.015  4428  4489 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-22 09:47:33.015  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:33.016  4428  4492 D BtGatt.ScanManager: Starting BLE batch scan
09-22 09:47:33.016  4428  4492 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 09:47:33.025  4428  4489 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 09:47:33.025  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:47:33.031  4428  4489 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 09:47:33.031  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:47:33.507  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-22 09:47:33.507  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 09:47:33.507  5404  5404 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 09:47:33.607   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:34.608   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:35.609   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-22 09:47:35.626   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 09:47:38.009  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:47:38.009  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:47:38.009  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 09:47:38.009  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:38.009  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 09:47:38.009  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:47:38.009  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 09:47:38.009  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-22 09:47:38.010  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 09:47:38.010  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-22 09:47:38.010  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 09:47:38.011  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:47:38.012  4428  4449 D BtGatt.GattService: stopScan() - queue size =1
,09-22 09:47:38.015  4428  4650 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 09:47:38.015  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 09:47:38.016  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-22 09:47:38.016  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 09:47:38.016  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 09:47:38.016  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 09:47:38.019  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:47:38.019  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:38.020  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 09:47:38.020  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:38.021  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 09:47:38.025  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:38.025  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:47:38.025  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:38.024  4428  4428 D BtGatt.ScanManager: awakened up at time 246367
09-22 09:47:38.032  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:38.032  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 09:47:38.033  4428  4489 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 09:47:38.034  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:47:38.034  4428  4492 D BtGatt.ScanManager: stopping BLe Batch
09-22 09:47:38.037  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 09:47:38.038  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:47:38.038  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:47:38.038  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:38.039  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:38.041  4428  4489 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 09:47:38.041  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:38.041  4428  4492 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 09:47:38.041  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:38.042  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:38.042  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:38.045  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:47:38.045  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:38.046  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:38.048  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 09:47:38.058  4428  4489 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-22 09:47:38.058  4428  4489 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:47:38.058  4428  4489 D BtGatt.GattService: current time is 246401841570
09-22 09:47:38.058  4428  4489 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -81, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -76, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -76, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -75, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 09:47:38.059  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 09:47:38.059  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 09:47:38.059  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-22 09:47:38.059  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 09:47:38.059  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-22 09:47:38.059  4428  4489 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-22 09:47:38.549  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 09:47:38.549  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:38.549  5404  5404 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 09:47:38.654   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 09:47:43.025  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:47:43.026  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.026  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.026  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 09:47:43.026  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.027  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:43.027  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
,09-22 09:47:43.027  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.027  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.027  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.027  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:43.029  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.029  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:43.032  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:47:43.033  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 09:47:43.033  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.035  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.035  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.035  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.035  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:47:43.036  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.037  5404  5450 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-22 09:47:43.039  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.039  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.039  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.040  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.040  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.040  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.040  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.040  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.040  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.041  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 09:47:43.041  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.041  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.041  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.041  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.044  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.044  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.044  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.047  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.047  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.047  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.047  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.048  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:43.050  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 09:47:43.050  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.051  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.051  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.051  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.052  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.052  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.052  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.052  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.052  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:43.052  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.053  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.053  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.053  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.053  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.055  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.055  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.055  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.057  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.057  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.057  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.057  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:47:43.057  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.058  5404  5450 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-22 09:47:43.058  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.059  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.059  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.059  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.059  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.059  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.059  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.059  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.059  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.059  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.059  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:47:43.059  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.060  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.060  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.061  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.061  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.061  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.062  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.063  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.063  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 09:47:43.063  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.063  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.064  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-22 09:47:43.064  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.064  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.064  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.064  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.064  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.064  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:43.064  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.064  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.064  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.065  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.065  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.065  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.065  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.065  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:43.066  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.066  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.066  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.067  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.067  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.067  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.067  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.068  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:43.068  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 09:47:43.069  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 09:47:43.069  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 09:47:43.069  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 09:47:43.069  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 09:47:43.069  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 09:47:43.069  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 09:47:43.069  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-22 09:47:43.069  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 09:47:43.069  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.069  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.070  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.070  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.070  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.070  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.070  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.070  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.070  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.070  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.070  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.070  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.070  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.070  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:43.072  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.072  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.072  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.073  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.073  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.073  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.073  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.073  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.074  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 09:47:43.074  5404  5450 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 09:47:43.074  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-22 09:47:43.077  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 09:47:43.078  5404  5450 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-22 09:47:43.078  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 09:47:43.079  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 09:47:43.079  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-22 09:47:43.079  5404  5450 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 09:47:43.080  5404  5450 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-22 09:47:43.080  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-22 09:47:43.080  5404  5450 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 09:47:43.080  5404  5450 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-22 09:47:43.080  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 09:47:43.080  5404  5450 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 09:47:43.080  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-22 09:47:43.083  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-22 09:47:43.084  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-22 09:47:43.084  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-22 09:47:43.085  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-22 09:47:43.085  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-22 09:47:43.085  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-22 09:47:43.085  5404  5450 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 09:47:43.086  5404  5450 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-22 09:47:43.086  5404  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-22 09:47:43.087  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:47:43.087  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.087  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.087  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.087  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.087  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.087  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-22 09:47:43.088  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.088  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.088  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:43.088  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.088  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.088  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.088  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.088  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.089  5404  5452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
,09-22 09:47:43.090  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:47:43.090  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.090  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.090  5404  5451 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:47:43.091  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.091  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.091  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.087  4445  4445 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29356]" dev="sockfs" ino=29356 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 09:47:43.091  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.091  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.092  5404  5450 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-22 09:47:43.092  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.092  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.093  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.093  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.093  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.093  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:43.093  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.093  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.087  4445  4445 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29356]" dev="sockfs" ino=29356 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 09:47:43.093  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.093  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.093  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.093  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.093  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.093  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.094  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.094  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.094  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.095  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.095  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.095  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.095  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.095  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.096  5404  5450 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-22 09:47:43.096  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.096  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:43.097  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.097  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.097  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.097  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.097  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.097  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.097  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.097  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.097  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.097  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.097  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.097  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.098  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.098  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.098  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:47:43.099  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.099  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.099  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 09:47:43.099  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.099  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.100  5404  5450 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-22 09:47:43.100  5404  5450 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-22 09:47:43.101  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 09:47:43.101  5404  5450 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-22 09:47:43.101  5404  5450 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 09:47:43.101  5404  5450 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-22 09:47:43.101  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 09:47:43.101  5404  5450 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-22 09:47:43.101  5404  5450 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 09:47:43.101  5404  5450 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 09:47:43.101  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 09:47:43.101  5404  5450 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-22 09:47:43.101  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:43.101  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:47:43.101  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:43.102  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.102  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.102  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.102  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.102  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.102  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.102  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.102  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.102  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.102  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.102  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.103  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:43.103  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:43.103  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:43.104  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:43.104  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:43.104  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:43.104  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.104  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.105  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:43.105  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.105  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:43.105  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:43.105  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:43.105  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:43.105  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:43.105  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:43.105  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:45.610   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:46.611   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:47.612   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:48.106  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:47:48.107  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.107  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:48.107  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.107  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:48.107  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.108  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:48.108  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:48.108  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:48.108  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:48.108  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:47:48.109  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.109  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.109  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.109  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.109  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 09:47:48.109  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.109  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.110  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.110  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.114  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:48.114  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 09:47:48.114  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:47:48.117  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:47:48.117  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:48.117  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:48.117  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.117  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:48.121  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 09:47:48.122  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:48.124  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-22 09:47:48.127  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-22 09:47:48.127  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-22 09:47:48.128  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-22 09:47:48.128  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:47:48.128  5404  5404 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 09:47:48.129  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:48.129  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 09:47:48.129  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 09:47:48.129  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 09:47:48.129  5404  5453 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 09:47:48.129  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.130  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 09:47:48.130  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.130  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.130  5404  5404 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 09:47:48.130  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 09:47:48.130  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 09:47:48.130  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 09:47:48.130  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 09:47:48.132  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:48.132  5404  5450 D BluetoothLeScanner: could not find callback wrapper
,09-22 09:47:48.132  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:48.132  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:48.132  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 09:47:48.132  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.133  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.131  4449  4449 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31935]" dev="sockfs" ino=31935 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 09:47:48.135  5404  5453 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 09:47:48.135  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:47:48.135  5404  5453 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-22 09:47:48.135  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.135  5404  5453 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 09:47:48.135  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:48.135  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:48.135  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:48.135  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:48.135  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:48.136  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-22 09:47:48.136  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:48.136  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:47:48.136  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:48.136  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.136  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.137  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.137  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:48.137  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.137  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:48.131  4449  4449 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31935]" dev="sockfs" ino=31935 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 09:47:48.141  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:47:48.142  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 09:47:48.149  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 09:47:48.150  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:47:48.151  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:47:48.151  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:47:48.152  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:48.155  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:47:48.155  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:48.156  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:48.157  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:48.157  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:47:48.158  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:48.158  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:48.158  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 09:47:48.158  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.158  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:47:48.158  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:48.158  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:48.158  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:47:48.160  5404  5450 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-22 09:47:48.160  5404  5450 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 09:47:48.160  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 09:47:48.160  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-22 09:47:48.160  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-22 09:47:48.162  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:48.162  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:48.162  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:48.162  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:47:48.162  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:47:48.162  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:48.163  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.163  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.163  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.163  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:48.164  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:47:48.164  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.164  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:47:48.164  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:47:48.165  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:48.169  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 09:47:48.169  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.169  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.169  5404  5404 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 09:47:48.170  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:48.171  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 09:47:48.171  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:48.171  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:48.171  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:48.171  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:48.171  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.172  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
,09-22 09:47:48.176  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:48.176  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:47:48.176  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-22 09:47:48.176  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 09:47:48.176  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.176  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.176  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.176  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.177  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.177  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:48.177  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:47:48.177  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.177  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.177  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.178  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:47:48.178  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:48.178  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:48.179  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:48.179  5404  5450 D BluetoothLeScanner: could not find callback wrapper
,09-22 09:47:48.179  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:48.179  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.179  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.180  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:47:48.180  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:47:48.181  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:47:48.181  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 09:47:48.181  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.181  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:48.181  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c558bf not in the list
09-22 09:47:48.181  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.181  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.181  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:48.181  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.181  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:48.181  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:48.181  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:47:48.183  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:47:48.183  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:47:48.183  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:47:48.184  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:47:48.184  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:47:48.184  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:47:48.184  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:47:48.184  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cb2b8c not in the list
09-22 09:47:48.185  5404  5450 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-22 09:47:48.185  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-22 09:47:48.186  5404  5450 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-22 09:47:48.186  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 09:47:48.186  5404  5450 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-22 09:47:48.186  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 09:47:48.188  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 09:47:48.188  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-22 09:47:48.189  5404  5450 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-22 09:47:48.189  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 09:47:48.189  5404  5450 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-22 09:47:48.189  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 09:47:48.189  5404  5450 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-22 09:47:48.189  5404  5450 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-22 09:47:48.190  5404  5450 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-22 09:47:48.190  5404  5450 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-22 09:47:48.191  5404  5450 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-22 09:47:48.191  5404  5450 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-22 09:47:48.191  5404  5450 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-22 09:47:48.191  5404  5450 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-22 09:47:48.192  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:47:48.192  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4646af2 added. We now have 3 listener(s)
09-22 09:47:48.192  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:47:48.194  5404  5450 D BluetoothAdapter: enable(): BT is already enabled..!
,09-22 09:47:48.194   928  3526 D WifiService: setWifiEnabled: true pid=5404, uid=10077
09-22 09:47:48.195   928  3526 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 09:47:48.219  4428  4634 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-22 09:47:48.219  4428  4646 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-22 09:47:48.220  5404  5451 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,09-22 09:47:48.613   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:48.670  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 09:47:49.614   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:47:50.614   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-22 09:47:52.718   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:47:53.200  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 09:47:53.200  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@837543 added. We now have 4 listener(s)
09-22 09:47:53.201  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:47:53.215  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:47:53.215  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@837543 removed from the list
09-22 09:47:53.216  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 09:47:53.216  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:53.216  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:53.218  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:47:53.218  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8587c0 added. We now have 4 listener(s)
,09-22 09:47:53.219  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:47:53.223  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:47:53.223  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8587c0 removed from the list
09-22 09:47:53.223  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:47:53.224  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:47:53.224  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:47:53.225  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:47:53.225  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b77cf9 added. We now have 4 listener(s)
09-22 09:47:53.226  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:47:53.232   928  3142 D WifiService: setWifiEnabled: false pid=5404, uid=10077
,09-22 09:47:53.232   928  3142 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 09:47:53.241   928  2918 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-22 09:47:53.242   928  2918 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-22 09:47:53.242   928  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 09:47:53.242   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-22 09:47:53.249  4428  4485 D BluetoothAdapterState: Current state: ON, message: 23
09-22 09:47:53.250  4428  4485 D BluetoothAdapterProperties: Setting state to 13
09-22 09:47:53.250  4428  4485 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-22 09:47:53.251  4428  4485 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 09:47:53.253  4428  4485 I BluetoothAdapterState: Entering PendingCommandState
09-22 09:47:53.256  4428  4489 D BluetoothAdapterProperties: Scan Mode:20
,09-22 09:47:53.257  4428  4485 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-22 09:47:53.261   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-22 09:47:53.262  4428  4428 D BluetoothMapService: onReceive
09-22 09:47:53.262  4428  4428 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 09:47:53.263  4428  4428 D BluetoothMapService: STATE_TURNING_OFF
09-22 09:47:53.263  4428  4428 D BluetoothMapService: MAP Service closeService in
09-22 09:47:53.263  4428  4428 D BluetoothMapMasInstance0: MAP Service shutdown
,09-22 09:47:53.263  4428  4428 D ObexServerSockets0: shutdown(block = true)
,09-22 09:47:53.264  4428  4428 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-22 09:47:53.264  4428  4428 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 09:47:53.264  4428  4646 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 09:47:53.265  4428  4659 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-22 09:47:53.265  4428  4660 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 09:47:53.263   928  5151 D DhcpClient: Clearing IP address
09-22 09:47:53.267   506   922 D CommandListener: Setting iface cfg
09-22 09:47:53.267  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:53.267  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:47:53.268  4428  4428 I BtOppRfcommListener: stopping Accept Thread
09-22 09:47:53.269  4428  5117 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 09:47:53.271  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.271  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:53.271  4428  5117 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 09:47:53.273   928  5152 D DhcpClient: Receive thread stopped
09-22 09:47:53.276  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:53.276  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:47:53.277  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.277  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:53.280  5404  5404 V io.jxcore.node.ConnectivityMo,nitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.281   928   941 I ActivityManager: Start proc 5458:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-22 09:47:53.282  3552  5204 V NativeCrypto: Read error: ssl=0x7f807dc280: I/O error during system call, Connection timed out
09-22 09:47:53.282  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:47:53.284  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.284  3552  5204 V NativeCrypto: SSL shutdown failed: ssl=0x7f807dc280: I/O error during system call, Broken pipe
09-22 09:47:53.287  4428  4428 D HeadsetService: Received stop request...Stopping profile...
09-22 09:47:53.287   928   939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-22 09:47:53.288   928  5149 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-22 09:47:53.291   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-22 09:47:53.292   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-22 09:47:53.292   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 09:47:53.292   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 09:47:53.292  3088  3720 D BluetoothHeadset: Proxy object disconnected
09-22 09:47:53.292  3088  3088 D HeadsetProfile: Bluetooth service disconnected
09-22 09:47:53.292  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:47:53.293  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:47:53.293   928  5149 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-22 09:47:53.293  3476  3512 D BluetoothHeadset: Proxy object disconnected
09-22 09:47:53.293   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 09:47:53.296  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.296  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:47:53.296  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:47:53.296   532   532 E Parcel  : Reading a NULL string not supported here.
09-22 09:47:53.297  4428  4428 D A2dpService: Received stop request...Stopping profile...
09-22 09:47:53.298  4428  4653 D A2dpStateMachine: Exit Disconnected: -1
09-22 09:47:53.299   928   928 D BluetoothA2dp: Proxy object disconnected
09-22 09:47:53.300  3088  3088 D BluetoothA2dp: Proxy object disconnected
09-22 09:47:53.301  4428  4428 D HidService: Received stop request...Stopping profile...
09-22 09:47:53.301  4428  4428 D HidService: Stopping Bluetooth HidService
09-22 09:47:53.302   928   928 D RttService: SCAN_AVAILABLE : 1
09-22 09:47:53.302   928  3029 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-22 09:47:53.304  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.304  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:47:53.304   928  2920 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-22 09:47:53.304  4428  4428 D HealthService: Received stop request...Stopping profile...
09-22 09:47:53.305  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.305  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:53.306  3442  3691 W QCNEJ   : |CORE| network lost: 100
09-22 09:47:53.307  4428  4428 V BluetoothAdapterState: isTurningOff()=true
09-22 09:47:53.307  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.307  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.307  3442  3691 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 09:47:53.307  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.308  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.308  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:53.309  3088  3088 D BluetoothInputDevice: Proxy object disconnected
09-22 09:47:53.309  3088  3088 D HidProfile: Bluetooth service disconnected
09-22 09:47:53.310  4428  4428 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 09:47:53.310  4428  4428 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 09:47:53.310  4428  4634 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:47:53.310  4428  4634 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:47:53.310  4428  4634 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:47:53.310  4428  4489 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 09:47:53.311  4428  4489 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 09:47:53.311  4428  4428 D PanService: Received stop request...Stopping profile...
09-22 09:47:53.312  4428  4428 V BluetoothAdapterState: isTurningOff()=true
09-22 09:47:53.312  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.312  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.312  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.312  4428  4428 D BluetoothMapService: Received stop request...Stopping profile...
09-22 09:47:53.312  4428  4428 D BluetoothMapService: stop()
09-22 09:47:53.313  4428  4428 D BluetoothMapAppObserver: deinitObservers()
09-22 09:47:53.313  4428  4428 D BluetoothMapAppObserver: removeReceiver()
09-22 09:47:53.317  4428  4428 V BluetoothAdapterState: isTurningOff()=true
09-22 09:47:53.317  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.317  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.317  4428  4489 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 09:47:53.317  4428  4634 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:47:53.317  4428  4634 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:47:53.317  4428  4634 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 09:47:53.317  4428  4634 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 09:47:53.317  4428  4634 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 09:47:53.317  4428  4634 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 09:47:53.317  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.318  4428  4428 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 09:47:53.320  4428  4489 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 09:47:53.320  4428  4428 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 09:47:53.320  4428  4428 V BluetoothAdapterState: isTurningOff()=true
09-22 09:47:53.320  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.320  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.320  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.321  4428  4428 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 09:47:53.321  4428  4489 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 09:47:53.321  4428  4428 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 09:47:53.321  4428  4428 D SapService: Received stop request...Stopping profile...
09-22 09:47:53.321  4428  4428 V SapService: stop()
09-22 09:47:53.323  4428  4428 V BluetoothAdapterState: isTurningOff()=true
,09-22 09:47:53.323  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.323  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.323  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.323  4428  4428 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 09:47:53.323  4428  4428 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 09:47:53.323   928  2918 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-22 09:47:53.324  4428  4428 D BluetoothMapService: MAP Service closeService in
09-22 09:47:53.324  4428  4428 V BluetoothAdapterState: isTurningOff()=true
09-22 09:47:53.324  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.324  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.324  3088  3088 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 09:47:53.324  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.324  3088  3088 D PanProfile: Bluetooth service disconnected
09-22 09:47:53.325  4428  4428 D BluetoothMapService: cleanup()
09-22 09:47:53.325  3088  3088 D BluetoothMap: Proxy object disconnected
09-22 09:47:53.325  4428  4428 D BluetoothMapService: MAP Service closeService in
09-22 09:47:53.325  3088  3088 D MapProfile: Bluetooth service disconnected
09-22 09:47:53.325  4428  4428 V BluetoothAdapterState: isTurningOff()=true
09-22 09:47:53.325  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.325  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.325  4428  4428 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:47:53.325  4428  4485 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 09:47:53.325  4428  4485 D BluetoothAdapterProperties: Setting state to 15
09-22 09:47:53.325  4428  4485 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 09:47:53.326  4428  4485 I BluetoothAdapterState: Entering BleOnState
09-22 09:47:53.326  3476  3512 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:47:53.326  3088  3721 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 09:47:53.327  3088  3099 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 09:47:53.328   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:47:53.328   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:47:53.328  3088  3720 D BluetoothPan: onBluetoothStateChange on: false
09-22 09:47:53.329  3088  3100 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 09:47:53.329   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 09:47:53.329  3088  3721 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:47:53.330   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:47:53.330  3088  3099 D BluetoothMap: onBluetoothStateChange: up=false
09-22 09:47:53.331  4428  4485 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 09:47:53.331  4428  4485 D BluetoothAdapterProperties: Setting state to 16
09-22 09:47:53.331  4428  4485 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 09:47:53.332  4428  4485 D BluetoothAdapterProperties: onBleDisable
09-22 09:47:53.332  4428  4485 I BluetoothAdapterState: Entering PendingCommandState
09-22 09:47:53.332  4428  4486 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 09:47:53.333  4428  4634 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 09:47:53.333  4428  4634 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:47:53.334  4428  4489 D BluetoothAdapterProperties: Scan Mode:20
09-22 09:47:53.335  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.335  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:53.335  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.336  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:53.340   928  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 09:47:53.348   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 09:47:53.352  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:53.355  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.355  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:53.356  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.358  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.360  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.361  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.369   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 09:47:53.370   506   922 D CommandListener: Clearing all IP addresses on wlan0
09-22 09:47:53.370   506   922 D TetherController: Setting IP forward enable = 0
,09-22 09:47:53.371   928  2920 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-22 09:47:53.372   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-22 09:47:53.374   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-22 09:47:53.376   928  2918 D DhcpClient: doQuit
09-22 09:47:53.376   928  2918 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 09:47:53.376   928  5151 D DhcpClient: onQuitting
,09-22 09:47:53.377  3571  3571 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-22 09:47:53.377  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:53.380  5040  5040 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fe4a469 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-22 09:47:53.380  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.380  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:53.381  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.381  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:53.384  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.384  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:47:53.384  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.384  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:53.386  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:53.386  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:47:53.387  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:47:53.387  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:53.388  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.390  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.390  4837  4850 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-22 09:47:53.390  4837  4850 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-22 09:47:53.390  4837  4850 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 09:47:53.390  4837  4850 E SarControlService: no key has been found,reset the power
09-22 09:47:53.391  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 09:47:53.391  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 09:47:53.391  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 09:47:53.391  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:47:53.391  4863  4863 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-22 09:47:53.393  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 09:47:53.393  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 09:47:53.393  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 09:47:53.394  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:47:53.394  4863  4863 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 09:47:53.396  3571  3571 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-22 09:47:53.397  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000ea03000000000000ffffffff]
,09-22 09:47:53.397  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:47:53.397  4863  4877 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-22 09:47:53.398  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 09:47:53.399  4837  4847 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-22 09:47:53.401  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000eb03000000000000ffffffff]
09-22 09:47:53.401  3571  3571 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-22 09:47:53.401  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:47:53.401  4863  4877 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-22 09:47:53.402  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-22 09:47:53.402  4837  4848 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-22 09:47:53.404  5458  5458 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-22 09:47:53.416  5458  5458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 09:47:53.421   506   922 E Netd    : netlink response contains error (No such file or directory)
,09-22 09:47:53.421   506   922 D TetherController: Setting IP forward enable = 0
09-22 09:47:53.422   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7b38d0:true
,09-22 09:47:53.422   928  2920 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-22 09:47:53.423  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 09:47:53.431  3571  3571 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 09:47:53.437   928  3352 I ActivityManager: Start proc 5490:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-22 09:47:53.441  3571  3571 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 09:47:53.447  5458  5458 D LocalBluetoothProfileManager: Adding local MAP profile
,09-22 09:47:53.450  5458  5458 D BluetoothMap: Create BluetoothMap proxy object
,09-22 09:47:53.457  5458  5458 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-22 09:47:53.469  5458  5458 D DockEventReceiver: finishStartingService: stopping service
,09-22 09:47:53.476  5490  5490 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-22 09:47:53.479   928   938 I ActivityManager: Killing 4801:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-22 09:47:53.543   928  2918 D wifi    : In wifi stop Hal
09-22 09:47:53.543   928  2918 D wifi    : halHandle = 0x7f65457b80, mVM = 0x7f81acd140, mCls = 0x100b32
,09-22 09:47:53.543   928  3569 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 09:47:53.543  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 09:47:53.543   928  3569 D WifiHAL : Got a signal to exit!!!
09-22 09:47:53.543   928  3569 I WifiHAL : Exit wifi_event_loop
09-22 09:47:53.544  4428  4489 I bt_hci  : shut_down
09-22 09:47:53.544   928  2918 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-22 09:47:53.544   928  2918 E WifiHAL : Event processing terminated
,09-22 09:47:53.544   928  2918 D wifi    : In wifi cleaned up handler
09-22 09:47:53.544   928  2918 I WifiHAL : Internal cleanup completed
,09-22 09:47:53.546  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.546  3412  3989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 09:47:53.546  4428  4494 D bt_hwcfg: hw_epilog_process
09-22 09:47:53.547  4428  4494 I bt_vendor: low_power_mode_cb
09-22 09:47:53.548  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.549  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:53.550  4428  4494 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-22 09:47:53.550  4428  4494 I bt_vendor: epilog_cb
09-22 09:47:53.550  4428  4494 I bt_hci  : epilog_finished_callback
,09-22 09:47:53.553  4428  4489 I bt_hci_h4: hal_close
09-22 09:47:53.553  4428  4489 I bt_userial_vendor: device fd = 54 close
,09-22 09:47:53.569   928  3569 D wifi    : set interface wlan0 flags (DOWN)
,09-22 09:47:53.569   928  2918 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 09:47:53.654  5490  5490 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.654  5490  5490 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.654  5490  5490 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5422)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.654  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.655  5490  5490 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.655  5490  5490 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.k.d(PG:583)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.655  5490  5490 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.655  5490  5490 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.655  5490  5490 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 09:47:53.655  5490  5490 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 09:47:53.661  5458  5458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 09:47:53.666  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 09:47:53.667  4428  4486 D bt_stack_manager: event_shut_down_stack finished.
09-22 09:47:53.667  4428  4485 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-22 09:47:53.669  4428  4428 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 09:47:53.670  4428  4485 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 09:47:53.670  4428  4428 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 09:47:53.670  4428  4428 D BtGatt.GattService: stop()
09-22 09:47:53.670  4428  4428 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 09:47:53.671  4428  4428 V BluetoothAdapterState: isTurningOff()=false
09-22 09:47:53.672  4428  4428 V BluetoothAdapterState: isTurningOn()=false
09-22 09:47:53.672  4428  4428 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:47:53.672  4428  4428 V BluetoothAdapterState: isBleTurningOff()=true
09-22 09:47:53.672  5458  5458 D DockEventReceiver: finishStartingService: stopping service
09-22 09:47:53.672  4428  4485 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 09:47:53.672  4428  4485 D BluetoothAdapterProperties: Setting state to 10
09-22 09:47:53.672  4428  4485 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 09:47:53.672  4428  4485 I BluetoothAdapterState: Entering OffState
09-22 09:47:53.673   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-22 09:47:53.676   928  3526 I ActivityManager: Killing 5178:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-22 09:47:53.703  4428  4428 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 09:47:53.704  3827  3827 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-22 09:47:53.706  4428  4428 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 09:47:53.706  4428  4428 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 09:47:53.707  4428  4486 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-22 09:47:53.712  3827  3827 D SystemUpdateService: onCreate
09-22 09:47:53.716  3827  3827 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-22 09:47:53.719  4428  4486 D bt_stack_manager: event_clean_up_stack finished.
09-22 09:47:53.720  4428  4428 I art     : System.exit called, status: 0
09-22 09:47:53.721  4428  4428 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-22 09:47:53.726  3827  3827 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-22 09:47:53.730  3827  5175 I iu.UploadsManager: num queued entries: 0
09-22 09:47:53.731  3827  5175 I iu.UploadsManager: num updated entries: 0
09-22 09:47:53.731  3827  5175 I iu.SyncManager: NEXT; no task
,09-22 09:47:53.760  3827  5522 I SystemUpdateService: active receiver: enabled
,09-22 09:47:53.761  3827  3827 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 09:47:53.763  3827  3827 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 09:47:53.772   928   945 D Tethering: InitialState.processMessage what=4
,09-22 09:47:53.774   928  3353 I ActivityManager: Start proc 5525:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-22 09:47:53.775   928   939 I ActivityManager: Process com.android.bluetooth (pid 4428) has died
,09-22 09:47:53.776   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 09:47:53.787  3827  5522 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 09:47:53.807  5525  5525 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-22 09:47:53.811  5525  5525 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 09:47:53.812  3827  5522 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-22 09:47:53.815  3827  5522 I SystemUpdateService: now status is 0 (complete)
,09-22 09:47:53.815  3827  5522 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-22 09:47:53.815  3827  5522 I SystemUpdateService: file has been verified
09-22 09:47:53.815  3827  5522 I SystemUpdateService: OTA package size = 21989297
,09-22 09:47:53.827  5525  5525 D SprintDMHelper: simOperator: 
09-22 09:47:53.827  5525  5525 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 09:47:53.837  4244  5538 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 09:47:53.850   928  3142 I ActivityManager: Start proc 5539:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-22 09:47:53.852  3827  5522 I SystemUpdateService: showing system update notification
,09-22 09:47:53.880  3827  3827 D SystemUpdateService: onDestroy
,09-22 09:47:53.896  5539  5539 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-22 09:47:53.897   928   938 I ActivityManager: Killing 5040:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-22 09:47:53.936   928   938 I ActivityManager: Killing 4499:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-22 09:47:54.044  5490  5509 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-22 09:47:54.052   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ceb8dad:true
,09-22 09:47:58.298   928   938 D WifiService: setWifiEnabled: true pid=5404, uid=10077
09-22 09:47:58.299   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 09:47:58.309   506   922 D SoftapController: Softap fwReload - Ok
,09-22 09:47:58.317   506   922 D CommandListener: Setting iface cfg
,09-22 09:47:58.317   506   922 D CommandListener: Trying to bring down wlan0
,09-22 09:47:58.321   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-22 09:47:58.327   928  2918 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 09:47:58.894   928  2918 D wifi    : set interface wlan0 flags (UP)
,09-22 09:47:58.894   928  2918 I WifiHAL : Initializing wifi
,09-22 09:47:58.895   928  2918 I WifiHAL : Creating socket
,09-22 09:47:58.897   928  2918 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 09:47:58.897   928  2918 D wifi    : Did set static halHandle = 0x7f65457b80
09-22 09:47:58.897   928  2918 D wifi    : halHandle = 0x7f65457b80, mVM = 0x7f81acd140, mCls = 0x18e6
,09-22 09:47:58.897   928  2918 D wifi    : array field set
09-22 09:47:58.897   928  2918 I WifiNative-HAL: interface[0] = wlan0
09-22 09:47:58.899   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-22 09:47:58.900   928  5558 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547159899008
09-22 09:47:58.900   928  5558 D wifi    : waitForHalEvents called, vm = 0x7f81acd140, obj = 0x18e6, env = 0x7f62ba89c0
,09-22 09:47:58.965  5559  5559 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 09:47:58.983  5559  5559 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 09:47:58.991  5559  5559 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 09:47:58.992  5559  5559 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 09:47:59.000   928  2918 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 09:47:59.002  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:47:59.003  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:59.003  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:59.003   928  2918 D WifiConfigStore: Loading config and enabling all networks 
09-22 09:47:59.003  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:59.004  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:59.005  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:59.005  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:59.005  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:59.005  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:47:59.006  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:47:59.007  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:47:59.007  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:47:59.007  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 09:47:59.008  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:59.009  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:47:59.011   928  2918 D WifiConfigStore: loaded 0 passpoint configs
,09-22 09:47:59.011   928  2918 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 09:47:59.012   928  2918 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-22 09:47:59.012   928  2918 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-22 09:47:59.013   928  2918 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-22 09:47:59.013   928  2918 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 09:47:59.013   928  2918 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-22 09:47:59.013   928  2918 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 09:47:59.015   928  2918 D WifiNative-HAL: Setting external_sim to 1
09-22 09:47:59.016   928  2918 D wifi    : setting dfs flag to true, 0x7f65caf280
09-22 09:47:59.016   928  2918 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 09:47:59.016   928  2918 D wifi    : setting scan oui 0x7f65caf280
09-22 09:47:59.016   928  2918 D WifiHAL : Sending mac address OUI
,09-22 09:47:59.016  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 09:47:59.019   928  2918 E native  : do suspend false
,09-22 09:47:59.025   928  2918 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 09:47:59.025   928   928 D RttService: SCAN_AVAILABLE : 3
,09-22 09:47:59.026   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 09:47:59.026   928  3029 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 09:47:59.027   506   922 D CommandListener: Setting iface cfg
,09-22 09:47:59.030   928  2905 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
09-22 09:47:59.030   928  2905 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 09:47:59.038   928  2905 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 09:47:59.043   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267386 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
09-22 09:47:59.043   928  2905 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 09:48:02.190  5559  5559 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-22 09:48:02.201  5559  5559 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-22 09:48:02.206  5559  5559 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-22 09:48:02.237   928  2918 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-22 09:48:02.238   928  2918 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-22 09:48:02.238   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-22 09:48:02.251   928  2918 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-22 09:48:02.289   928  2918 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-22 09:48:02.291  5559  5559 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-22 09:48:02.727  5559  5559 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-22 09:48:02.766  5559  5559 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-22 09:48:02.767  5559  5559 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-22 09:48:02.778   928  2918 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-22 09:48:02.778   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 09:48:02.778   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-22 09:48:02.799   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-22 09:48:02.814   506   922 D CommandListener: Setting iface cfg
,09-22 09:48:02.820   928  2918 D WifiStateMachine: Start Dhcp Watchdog 2
,09-22 09:48:02.829   928  5565 D DhcpClient: Receive thread started
,09-22 09:48:02.835   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-22 09:48:02.835   928  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-22 09:48:02.835   928  2920 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-22 09:48:02.925   928  2918 E native  : do suspend false
,09-22 09:48:02.946   928  5564 D DhcpClient: Broadcasting DHCPDISCOVER
,09-22 09:48:02.959   928  5565 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
,09-22 09:48:02.960   928  5564 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
,09-22 09:48:02.962   928  5564 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-22 09:48:02.975   928  5565 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-22 09:48:02.976   928  5564 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-22 09:48:02.979   506   922 D CommandListener: Setting iface cfg
09-22 09:48:02.983   928  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-22 09:48:02.991   928  5564 D DhcpClient: Scheduling renewal in 86399s
,09-22 09:48:02.999   928  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-22 09:48:03.000   928  2918 D WifiConfigStore: No blacklist allowed without epno enabled
,09-22 09:48:03.001   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-22 09:48:03.003   928  2920 D ConnectivityService: Adding iface wlan0 to network 101
09-22 09:48:03.014   928  2918 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-22 09:48:03.049   928  2920 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-22 09:48:03.049   928  2920 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-22 09:48:03.054   928  2920 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-22 09:48:03.059   928  2920 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-22 09:48:03.061   928  2920 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-22 09:48:03.066   928  2920 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-22 09:48:03.071   928  2920 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-22 09:48:03.071   928  2920 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-22 09:48:03.071   928  2920 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-22 09:48:03.071   928  2918 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-22 09:48:03.071   928  2920 D ConnectivityService:    accepting network in place of null
09-22 09:48:03.071   928  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 09:48:03.072   928  2920 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-22 09:48:03.084   928  5563 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271427, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-22 09:48:03.095   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 09:48:03.121   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 09:48:03.124   928  2920 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-22 09:48:03.125   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-22 09:48:03.125  3442  3691 W QCNEJ   : |CORE| network available: 101
,09-22 09:48:03.126   928  2920 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-22 09:48:03.129   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-22 09:48:03.131  3442  3691 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-22 09:48:03.131  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:03.132  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:48:03.132  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.132  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:03.134  3442  3691 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-22 09:48:03.134  3442  3691 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-22 09:48:03.134  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:03.134  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:48:03.135  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.135  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 09:48:03.137  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:03.137  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:48:03.137  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.137  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 09:48:03.137  4837  4850 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-22 09:48:03.137  4837  4850 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-22 09:48:03.138  4837  4850 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-22 09:48:03.138  4837  4850 E SarControlService: no key has been found,reset the power
09-22 09:48:03.138  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 09:48:03.138  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 09:48:03.138  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 09:48:03.139  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:48:03.139  4863  4863 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-22 09:48:03.140  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-22 09:48:03.140  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 09:48:03.141  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 09:48:03.143  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:48:03.143  4863  4863 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 09:48:03.145  3827  3827 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-22 09:48:03.147  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000ec03000000000000ffffffff]
09-22 09:48:03.147  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:48:03.147  4863  4877 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-22 09:48:03.149  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000ed03000000000000ffffffff]
09-22 09:48:03.149  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:48:03.149  4863  4877 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-22 09:48:03.150  3827  3827 D SystemUpdateService: onCreate
,09-22 09:48:03.151  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 09:48:03.152  4837  4847 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-22 09:48:03.152  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 09:48:03.152  4837  4848 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-22 09:48:03.155  3827  3827 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-22 09:48:03.155   928  5562 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-22 09:48:03.166  3827  3827 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-22 09:48:03.172  3827  5175 I iu.UploadsManager: num queued entries: 0
,09-22 09:48:03.172  3827  5175 I iu.UploadsManager: num updated entries: 0
09-22 09:48:03.173  3827  5175 I iu.SyncManager: NEXT; no task
,09-22 09:48:03.175  3827  5576 I SystemUpdateService: active receiver: enabled
,09-22 09:48:03.178  3827  3827 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 09:48:03.180  3827  3827 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 09:48:03.183  5525  5525 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 09:48:03.187  5525  5525 D SprintDMHelper: simOperator: 
09-22 09:48:03.187  5525  5525 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 09:48:03.198  3827  5576 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 09:48:03.204   928  5562 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 22 Sep 2016 13:48:03 GMT], X-Android-Received-Millis=[1474552083204], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474552083178]}
,09-22 09:48:03.205   928  2920 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-22 09:48:03.205   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-22 09:48:03.205   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-22 09:48:03.206   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-22 09:48:03.214  3827  5576 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,09-22 09:48:03.219  3827  5576 I SystemUpdateService: now status is 0 (complete)
09-22 09:48:03.220  3827  5576 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-22 09:48:03.220  3827  5576 I SystemUpdateService: file has been verified
09-22 09:48:03.220  3827  5576 I SystemUpdateService: OTA package size = 21989297
,09-22 09:48:03.226  3827  5576 I SystemUpdateService: showing system update notification
,09-22 09:48:03.239  3827  3827 D SystemUpdateService: onDestroy
,09-22 09:48:03.286  4244  5581 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-22 09:48:03.307   928  3535 D WifiService: setWifiEnabled: false pid=5404, uid=10077
,09-22 09:48:03.307   928  3535 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 09:48:03.309   928  2918 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-22 09:48:03.309   928  2918 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-22 09:48:03.309   928  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 09:48:03.309   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-22 09:48:03.318   928  5564 D DhcpClient: Clearing IP address
09-22 09:48:03.318   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-22 09:48:03.320   506   922 D CommandListener: Setting iface cfg
09-22 09:48:03.321  3552  5587 V NativeCrypto: Read error: ssl=0x7f807d8e00: I/O error during system call, Connection timed out
09-22 09:48:03.321  3552  5587 V NativeCrypto: SSL shutdown failed: ssl=0x7f807d8e00: I/O error during system call, Broken pipe
09-22 09:48:03.326   928  3354 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-22 09:48:03.327   928  5562 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,09-22 09:48:03.327   928  5562 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-22 09:48:03.328   928  5565 D DhcpClient: Receive thread stopped
,09-22 09:48:03.336   928  5562 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-22 09:48:03.336   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-22 09:48:03.337   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-22 09:48:03.337   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-22 09:48:03.338   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-22 09:48:03.338   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-22 09:48:03.339   532   532 E Parcel  : Reading a NULL string not supported here.
,09-22 09:48:03.343   928   928 D RttService: SCAN_AVAILABLE : 1
,09-22 09:48:03.343   928  3029 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 09:48:03.345   928  2918 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-22 09:48:03.345   928  2920 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-22 09:48:03.348  3442  3691 W QCNEJ   : |CORE| network lost: 101
09-22 09:48:03.348  3442  3691 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 09:48:03.349   928  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 09:48:03.372   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 09:48:03.390   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 09:48:03.390   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-22 09:48:03.391   928  2920 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-22 09:48:03.391   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-22 09:48:03.393   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-22 09:48:03.395  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:03.395  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:03.395  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.395  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:03.396   928  2918 D DhcpClient: doQuit
09-22 09:48:03.396   928  2918 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 09:48:03.396   928  5564 D DhcpClient: onQuitting
09-22 09:48:03.397  5559  5559 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-22 09:48:03.397  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:03.397  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:03.397  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.397  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:03.398  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:03.398  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:03.398  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:03.399  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 09:48:03.401  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:03.401  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:03.401  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.401  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:03.402  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:03.402  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:03.402  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:03.402  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:03.404  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:03.406  3827  3827 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-22 09:48:03.407  4837  4850 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-22 09:48:03.407  4837  4850 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-22 09:48:03.407  4837  4850 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 09:48:03.407  4837  4850 E SarControlService: no key has been found,reset the power
09-22 09:48:03.407  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 09:48:03.408  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 09:48:03.408  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 09:48:03.408  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:48:03.408  4863  4863 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-22 09:48:03.409  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 09:48:03.409  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 09:48:03.409  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-22 09:48:03.410  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:48:03.410  4863  4863 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 09:48:03.412  5559  5559 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 09:48:03.414  3827  3827 D SystemUpdateService: onCreate
,09-22 09:48:03.415  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000ee03000000000000ffffffff]
09-22 09:48:03.415  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:48:03.415  4863  4877 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-22 09:48:03.415  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 09:48:03.415  4837  4848 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-22 09:48:03.416  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000ef03000000000000ffffffff]
09-22 09:48:03.416  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:48:03.416  4863  4877 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-22 09:48:03.417  5559  5559 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-22 09:48:03.417  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 09:48:03.417  4837  4847 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-22 09:48:03.419  3827  3827 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-22 09:48:03.423  3827  5596 I SystemUpdateService: active receiver: enabled
,09-22 09:48:03.428  3827  3827 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-22 09:48:03.432  3827  5175 I iu.UploadsManager: num queued entries: 0
09-22 09:48:03.433  3827  5175 I iu.UploadsManager: num updated entries: 0
,09-22 09:48:03.435  3827  5596 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 09:48:03.437  3827  3827 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 09:48:03.439  3827  3827 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 09:48:03.441  5525  5525 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 09:48:03.444  5525  5525 D SprintDMHelper: simOperator: 
09-22 09:48:03.444  5525  5525 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 09:48:03.446  5559  5559 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 09:48:03.448   506   922 E Netd    : netlink response contains error (No such file or directory)
,09-22 09:48:03.450   928  2920 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-22 09:48:03.447  3827  5596 I SystemUpdateService: network: null; metered: false; mobile allowed: false
09-22 09:48:03.450   928  2920 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-22 09:48:03.452  3827  5596 I SystemUpdateService: now status is 0 (complete)
09-22 09:48:03.452  3827  5596 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-22 09:48:03.452  3827  5596 I SystemUpdateService: file has been verified
09-22 09:48:03.454  3827  5175 I iu.SyncManager: NEXT; no task
,09-22 09:48:03.455  4244  5600 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 09:48:03.457  5559  5559 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 09:48:03.456  3827  5596 I SystemUpdateService: OTA package size = 21989297
,09-22 09:48:03.474  3827  5596 I SystemUpdateService: showing system update notification
,09-22 09:48:03.481  3827  3827 D SystemUpdateService: onDestroy
,09-22 09:48:03.561   928  2918 D wifi    : In wifi stop Hal
09-22 09:48:03.561   928  2918 D wifi    : halHandle = 0x7f65457b80, mVM = 0x7f81acd140, mCls = 0x18e6
,09-22 09:48:03.561   928  5558 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-22 09:48:03.561   928  5558 D WifiHAL : Got a signal to exit!!!
,09-22 09:48:03.561   928  5558 I WifiHAL : Exit wifi_event_loop
09-22 09:48:03.562   928  2918 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 09:48:03.562   928  2918 E WifiHAL : Event processing terminated
09-22 09:48:03.562   928  2918 D wifi    : In wifi cleaned up handler
09-22 09:48:03.562   928  2918 I WifiHAL : Internal cleanup completed
09-22 09:48:03.565  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:03.567  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:03.568  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 09:48:03.570  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:03.572  3412  3989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 09:48:03.589   928  5558 D wifi    : set interface wlan0 flags (DOWN)
,09-22 09:48:03.590   928  2918 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 09:48:03.795   928   945 D Tethering: InitialState.processMessage what=4
,09-22 09:48:03.801   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 09:48:04.126   928  2920 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-22 09:48:05.616   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:06.617   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:07.618   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:08.345   928   945 I ActivityManager: Start proc 5603:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 09:48:08.442  5603  5603 D AdapterServiceConfig: Adding HeadsetService
,09-22 09:48:08.442  5603  5603 D AdapterServiceConfig: Adding A2dpService
09-22 09:48:08.443  5603  5603 D AdapterServiceConfig: Adding HidService
09-22 09:48:08.443  5603  5603 D AdapterServiceConfig: Adding HealthService
09-22 09:48:08.443  5603  5603 D AdapterServiceConfig: Adding PanService
09-22 09:48:08.443  5603  5603 D AdapterServiceConfig: Adding GattService
09-22 09:48:08.443  5603  5603 D AdapterServiceConfig: Adding BluetoothMapService
,09-22 09:48:08.444  5603  5603 D AdapterServiceConfig: Adding SapService
,09-22 09:48:08.458   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4cf1908:true
,09-22 09:48:08.458  5603  5603 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 09:48:08.462  5603  5603 I bt_bluedroid: init
,09-22 09:48:08.462  5603  5615 I BluetoothAdapterState: Entering OffState
,09-22 09:48:08.466  5603  5616 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 09:48:08.466  5603  5616 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 09:48:08.466  5603  5616 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 09:48:08.466  5603  5616 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-22 09:48:08.467  5603  5603 I bt_bluedroid: get_profile_interface socket
,09-22 09:48:08.469  5603  5619 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 09:48:08.469  5603  5603 I bt_bluedroid: get_profile_interface sdp
09-22 09:48:08.470  5603  5619 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 09:48:08.475  5603  5614 I bt_bluedroid: config_hci_snoop_log
,09-22 09:48:08.476   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 09:48:08.480  5603  5615 D BluetoothAdapterState: Current state: OFF, message: 0
09-22 09:48:08.481  5603  5615 D BluetoothAdapterProperties: Setting state to 14
09-22 09:48:08.481  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 09:48:08.483  5603  5615 D BluetoothBondStateMachine: make
,09-22 09:48:08.485  5603  5620 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 09:48:08.487  5603  5615 I BluetoothAdapterState: Entering PendingCommandState
,09-22 09:48:08.489  5603  5603 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 09:48:08.491  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:08.492  5603  5603 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 09:48:08.492  5603  5603 D BtGatt.GattService: Received start request. Starting profile...
09-22 09:48:08.493  5603  5603 D BtGatt.GattService: start()
09-22 09:48:08.493  5603  5603 I bt_bluedroid: get_profile_interface gatt
,09-22 09:48:08.494  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:08.494  5603  5603 D BtGatt.AdvertiseManager: advertise manager created
,09-22 09:48:08.500  5603  5603 V BluetoothAdapterState: isTurningOff()=false
,09-22 09:48:08.500  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:08.500  5603  5603 V BluetoothAdapterState: isBleTurningOn()=true
09-22 09:48:08.500  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:08.501  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 09:48:08.502  5603  5615 I bt_bluedroid: bt_bluedroid
09-22 09:48:08.502  5603  5616 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 09:48:08.503  5603  5616 I bt_hci  : start_up
,09-22 09:48:08.508  5603  5616 I bt_vendor: alloc value 0xf3c3f871
09-22 09:48:08.508  5603  5616 I bt_vendor: init
09-22 09:48:08.508  5603  5616 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 09:48:08.508  5603  5616 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 09:48:08.618  5603  5616 D bt_hci  : start_up starting async portion
09-22 09:48:08.619   534   534 I ServiceManager: Waiting for service AtCmdFwd...
09-22 09:48:08.619  5603  5623 I bt_hci  : event_finish_startup
09-22 09:48:08.619  5603  5623 I bt_hci_h4: hal_open
09-22 09:48:08.619  5603  5623 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 09:48:08.617  5624  5624 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 09:48:08.621  5603  5623 I bt_userial_vendor: device fd = 54 open
,09-22 09:48:08.633  5603  5623 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 09:48:08.635  5603  5623 D bt_hwcfg: Chipset BCM4358A3
,09-22 09:48:08.635  5603  5623 D bt_hwcfg: Target name = [BCM4358A3]
09-22 09:48:08.635  5603  5623 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 09:48:09.030  5603  5623 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 09:48:09.030  5603  5623 D bt_hwcfg: Settlement delay -- 100 ms
09-22 09:48:09.030  5603  5623 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 09:48:09.164  5603  5623 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 09:48:09.165  5603  5623 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 09:48:09.166  5603  5623 I bt_hwcfg: vendor lib fwcfg completed
09-22 09:48:09.166  5603  5623 I bt_vendor: firmware callback
09-22 09:48:09.167  5603  5623 I bt_hci  : firmware_config_callback
09-22 09:48:09.175  5603  5626 I bt_btu  : btu_task pending for preload complete event
09-22 09:48:09.176  5603  5626 I bt_btu_task: Bluetooth chip preload is complete
09-22 09:48:09.176  5603  5626 I bt_btu  : btu_task received preload complete event
,09-22 09:48:09.183  5603  5626 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 09:48:09.183  5603  5626 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 09:48:09.183  5603  5626 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 09:48:09.184  5603  5626 I         : BTE_InitTraceLevels -- TRC_SDP
09-22 09:48:09.185  5603  5626 I         : BTE_InitTraceLevels -- TRC_GATT
,09-22 09:48:09.185  5603  5626 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 09:48:09.185  5603  5626 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-22 09:48:09.185  5603  5626 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 09:48:09.264  5603  5626 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bbd549
,09-22 09:48:09.264  5603  5626 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bbd549 
,09-22 09:48:09.282  5603  5619 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 09:48:09.284  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 09:48:09.284  5603  5619 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 09:48:09.286  5603  5619 D BluetoothAdapterProperties: Name is: Nexus 6P
09-22 09:48:09.289  5603  5619 D BluetoothAdapterProperties: Scan Mode:20
09-22 09:48:09.289  5603  5619 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-22 09:48:09.289  5603  5619 D bt_hci  : do_postload posting postload work item
09-22 09:48:09.289  5603  5623 I bt_hci  : event_postload
09-22 09:48:09.289  5603  5623 I bt_vendor: sco_config_cb
09-22 09:48:09.289  5603  5623 I bt_hci  : sco_config_callback postload finished.
09-22 09:48:09.291  5603  5619 D bt_bte_conf: Device ID record 1 : primary
09-22 09:48:09.291  5603  5619 D bt_bte_conf:   vendorId            = 000f
09-22 09:48:09.291  5603  5619 D bt_bte_conf:   vendorIdSource      = 0001
09-22 09:48:09.291  5603  5619 D bt_bte_conf:   product             = 1200
,09-22 09:48:09.292  5603  5619 D bt_bte_conf:   version             = 1436
09-22 09:48:09.292  5603  5619 D bt_bte_conf:   clientExecutableURL = 
09-22 09:48:09.292  5603  5619 D bt_bte_conf:   serviceDescription  = 
09-22 09:48:09.292  5603  5619 D bt_bte_conf:   documentationURL    = 
09-22 09:48:09.292  5603  5619 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 09:48:09.292  5603  5616 D bt_stack_manager: event_start_up_stack finished
09-22 09:48:09.293  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-22 09:48:09.293  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:09.293  5603  5615 D BluetoothAdapterProperties: Setting state to 15
09-22 09:48:09.293  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 09:48:09.294  5603  5615 I BluetoothAdapterState: Entering BleOnState
09-22 09:48:09.299  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:09.300  5603  5623 I bt_vendor: low_power_mode_cb
09-22 09:48:09.301  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:09.303  5603  5615 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-22 09:48:09.303  5603  5615 D BluetoothAdapterProperties: Setting state to 11
,09-22 09:48:09.303  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-22 09:48:09.307  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:09.309  5603  5603 D HeadsetService: Received start request. Starting profile...
09-22 09:48:09.309  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:09.310  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:09.311  5603  5603 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-22 09:48:09.311  5603  5603 D HeadsetStateMachine: make
09-22 09:48:09.312  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:09.320  5603  5615 I BluetoothAdapterState: Entering PendingCommandState
,09-22 09:48:09.321  5603  5603 D HeadsetStateMachine: max_hf_connections = 1
09-22 09:48:09.321  5603  5603 I bt_bluedroid: get_profile_interface handsfree
09-22 09:48:09.321  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 09:48:09.321  5603  5619 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-22 09:48:09.324  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:09.325  5603  5603 D A2dpService: Received start request. Starting profile...
,09-22 09:48:09.325  5603  5603 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 09:48:09.325  5603  5603 I bt_bluedroid: get_profile_interface avrcp
,09-22 09:48:09.330  5603  5603 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 09:48:09.331  5603  5603 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 09:48:09.331  5603  5603 D A2dpStateMachine: make
09-22 09:48:09.331  5603  5603 I bt_bluedroid: get_profile_interface a2dp
,09-22 09:48:09.332  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-22 09:48:09.333  5603  5635 D A2dpStateMachine: Enter Disconnected: -2
,09-22 09:48:09.334  5603  5603 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 09:48:09.335  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:09.336  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 09:48:09.336  5458  5458 D BluetoothInputDevice: Proxy object connected
,09-22 09:48:09.336  5603  5603 D HidService: Received start request. Starting profile...
09-22 09:48:09.336  5603  5603 I bt_bluedroid: get_profile_interface hidhost
,09-22 09:48:09.337  5603  5603 D HidService: setHidService(): set to: null
09-22 09:48:09.337  5603  5619 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9e56d
09-22 09:48:09.337  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 09:48:09.337  5603  5603 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 09:48:09.338  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:09.338  5603  5603 D HealthService: Received start request. Starting profile...
09-22 09:48:09.338  5458  5458 D HidProfile: Bluetooth service connected
,09-22 09:48:09.339  5603  5603 I bt_bluedroid: get_profile_interface health
,09-22 09:48:09.340  5603  5603 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-22 09:48:09.341  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:09.342  5603  5603 D PanService: Received start request. Starting profile...
09-22 09:48:09.342  5603  5603 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 09:48:09.342  5603  5603 I bt_bluedroid: get_profile_interface pan
,09-22 09:48:09.343  5603  5619 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-22 09:48:09.346  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:09.346  5458  5458 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 09:48:09.347  5603  5603 D BluetoothMapService: Received start request. Starting profile...
09-22 09:48:09.347  5603  5603 D BluetoothMapService: start()
09-22 09:48:09.347  5458  5458 D PanProfile: Bluetooth service connected
09-22 09:48:09.347  5458  5458 D BluetoothMap: Proxy object connected
09-22 09:48:09.347  5458  5458 D MapProfile: Bluetooth service connected
09-22 09:48:09.347  5458  5458 D BluetoothMap: getConnectedDevices()
09-22 09:48:09.348  5458  5458 D BluetoothMap: Bluetooth is Not enabled
09-22 09:48:09.349  5603  5603 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 09:48:09.350  5603  5603 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-22 09:48:09.351  5603  5603 D BluetoothMapAppObserver: createReceiver()
09-22 09:48:09.352  5603  5603 D BluetoothMapAppObserver: initObservers()
09-22 09:48:09.352  5603  5603 D BluetoothMapAppObserver: getEnabledAccountItems()
09-22 09:48:09.357  5603  5603 V SapService: SapBinder()
09-22 09:48:09.357  5603  5603 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:09.358  5603  5603 D SapService: Received start request. Starting profile...
09-22 09:48:09.358  5603  5603 V SapService: start()
,09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isTurningOff()=false
,09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isTurningOff()=false
,09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.360  5603  5633 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:09.360  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:09.361  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.362  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:09.362  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.362  5603  5603 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:09.362  5603  5603 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:09.363  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:09.363  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:09.363  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 09:48:09.363  5603  5615 D BluetoothAdapterProperties: ScanMode =  20
09-22 09:48:09.363  5603  5615 D BluetoothAdapterProperties: State =  11
,09-22 09:48:09.365  5603  5619 D BluetoothAdapterProperties: Scan Mode:21
09-22 09:48:09.365  5603  5615 D BluetoothAdapterProperties: Setting state to 12
09-22 09:48:09.365  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 09:48:09.365  5603  5619 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 09:48:09.366  5603  5615 I BluetoothAdapterState: Entering OnState
09-22 09:48:09.366  3476  3505 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:09.367  3088  3100 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 09:48:09.368  3088  3099 D BluetoothPbap: onBluetoothStateChange: up=true
,09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:09.369  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:09.369  3088  3088 D BluetoothA2dp: Proxy object connected
09-22 09:48:09.370   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:09.370   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:09.371  3088  3100 D BluetoothPan: onBluetoothStateChange on: true
,09-22 09:48:09.372  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:09.372  3088  3100 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 09:48:09.372  3088  3088 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 09:48:09.372  3088  3088 D PanProfile: Bluetooth service connected
,09-22 09:48:09.374  3088  3088 D BluetoothInputDevice: Proxy object connected
,09-22 09:48:09.374  3088  3088 D HidProfile: Bluetooth service connected
09-22 09:48:09.374  5458  5474 D BluetoothMap: onBluetoothStateChange: up=true
09-22 09:48:09.375   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 09:48:09.375   928   928 D BluetoothA2dp: Proxy object connected
09-22 09:48:09.375  3088  3099 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:09.376  5458  5475 D BluetoothPan: onBluetoothStateChange on: true
09-22 09:48:09.376  5603  5603 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 09:48:09.376  5458  5477 D BluetoothPbap: onBluetoothStateChange: up=true
,09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:09.376  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:09.377  5603  5603 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 09:48:09.378   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:09.378  5458  5474 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 09:48:09.378  3088  3721 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 09:48:09.378  5603  5603 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:48:09.380  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:09.380  3088  3088 D BluetoothMap: Proxy object connected
09-22 09:48:09.380  3088  3088 D MapProfile: Bluetooth service connected
09-22 09:48:09.380  3088  3088 D BluetoothMap: getConnectedDevices()
09-22 09:48:09.381   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-22 09:48:09.384  5603  5603 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:09.385  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:09.385  5603  5603 D ObexServerSockets: Succeed to create listening sockets 
09-22 09:48:09.386  5603  5603 D ObexServerSockets0: startAccept()
09-22 09:48:09.386  5603  5603 D ObexServerSockets0: prepareForNewConnect()
09-22 09:48:09.386  5458  5458 D LocalBluetoothProfileManager: Adding local A2DP profile
09-22 09:48:09.387  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 09:48:09.389  5603  5603 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-22 09:48:09.389  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:09.389  5603  5603 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 09:48:09.389  5603  5643 D ObexServerSockets0: Accepting socket connection...
09-22 09:48:09.389  5603  5603 D BluetoothMapService: onReceive
09-22 09:48:09.389  5603  5603 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 09:48:09.389  5603  5603 D BluetoothMapService: STATE_ON
,09-22 09:48:09.390  5603  5644 D ObexServerSockets0: Accepting socket connection...
09-22 09:48:09.390  5458  5458 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-22 09:48:09.390  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:09.391  5603  5645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 09:48:09.392  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:09.393  5603  5645 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 09:48:09.393  5603  5645 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 09:48:09.398  5458  5458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 09:48:09.399  5458  5458 D BluetoothA2dp: Proxy object connected
,09-22 09:48:09.403  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 09:48:09.405  5458  5458 D DockEventReceiver: finishStartingService: stopping service
,09-22 09:48:09.415  5458  5458 D BluetoothPbap: Proxy object connected
,09-22 09:48:09.415  5458  5458 D PbapServerProfile: Bluetooth service connected
09-22 09:48:09.416  3088  3088 D BluetoothPbap: Proxy object connected
09-22 09:48:09.416  3088  3088 D PbapServerProfile: Bluetooth service connected
,09-22 09:48:09.419  5603  5603 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 09:48:09.419  5603  5603 D ObexServerSockets0: prepareForNewConnect()
,09-22 09:48:09.422  5603  5649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 09:48:09.434  5603  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 09:48:09.436  5603  5653 I BtOppRfcommListener: Accept thread started.
,09-22 09:48:09.468   928   928 D BluetoothHeadset: Proxy object connected
,09-22 09:48:09.468   928   928 D BluetoothHeadset: Proxy object connected
09-22 09:48:09.468  3088  3720 D BluetoothHeadset: Proxy object connected
09-22 09:48:09.468  3088  3088 D HeadsetProfile: Bluetooth service connected
09-22 09:48:09.468  3476  3763 D BluetoothHeadset: Proxy object connected
09-22 09:48:09.469   928   928 D BluetoothHeadset: Proxy object connected
,09-22 09:48:09.470   928   945 D BluetoothHeadset: Proxy object connected
09-22 09:48:09.470   928   945 D BluetoothHeadset: Proxy object connected
,09-22 09:48:09.476  3088  3099 D BluetoothHeadset: Proxy object connected
,09-22 09:48:09.477  3088  3088 D HeadsetProfile: Bluetooth service connected
,09-22 09:48:09.478   928   945 D BluetoothHeadset: Proxy object connected
,09-22 09:48:09.494  5458  5477 D BluetoothHeadset: Proxy object connected
,09-22 09:48:09.495  5458  5458 D HeadsetProfile: Bluetooth service connected
,09-22 09:48:09.619   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:10.620   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-22 09:48:11.078   928  2920 D ConnectivityService: handlePromptUnvalidated 101
,09-22 09:48:13.324  5603  5615 D BluetoothAdapterState: Current state: ON, message: 23
09-22 09:48:13.324  5603  5615 D BluetoothAdapterProperties: Setting state to 13
,09-22 09:48:13.324  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 09:48:13.326  5603  5615 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 09:48:13.330  5603  5603 D BluetoothMapService: onReceive
,09-22 09:48:13.330  5603  5603 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-22 09:48:13.331  5603  5603 D BluetoothMapService: STATE_TURNING_OFF
09-22 09:48:13.331  5603  5603 D BluetoothMapService: MAP Service closeService in
09-22 09:48:13.331  5603  5603 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 09:48:13.331  5603  5603 D ObexServerSockets0: shutdown(block = true)
09-22 09:48:13.333  5603  5603 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-22 09:48:13.334  5603  5628 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 09:48:13.334  5603  5603 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 09:48:13.334  5603  5643 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-22 09:48:13.334  5603  5644 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 09:48:13.337  5603  5615 I BluetoothAdapterState: Entering PendingCommandState
09-22 09:48:13.337  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:13.337  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:13.339  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:13.339  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:13.339  5603  5619 D BluetoothAdapterProperties: Scan Mode:20
09-22 09:48:13.340  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 09:48:13.344  5458  5458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 09:48:13.346  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:13.347  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 09:48:13.348  5603  5603 I BtOppRfcommListener: stopping Accept Thread
09-22 09:48:13.348  5603  5653 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 09:48:13.348  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 09:48:13.349  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:13.349  5603  5653 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-22 09:48:13.353  5603  5603 D HeadsetService: Received stop request...Stopping profile...
,09-22 09:48:13.353  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:13.353  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:13.354  5404  5404 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 09:48:13.354  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:13.356   928   928 D BluetoothHeadset: Proxy object disconnected
,09-22 09:48:13.356   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 09:48:13.356  5458  5474 D BluetoothHeadset: Proxy object disconnected
09-22 09:48:13.357  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.357  5603  5603 D A2dpService: Received stop request...Stopping profile...
09-22 09:48:13.357  5603  5635 D A2dpStateMachine: Exit Disconnected: -1
09-22 09:48:13.357  3088  3099 D BluetoothHeadset: Proxy object disconnected
,09-22 09:48:13.358  3476  3512 D BluetoothHeadset: Proxy object disconnected
09-22 09:48:13.359  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.360   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 09:48:13.360   928   928 D BluetoothA2dp: Proxy object disconnected
09-22 09:48:13.360  5603  5603 D HidService: Received stop request...Stopping profile...
09-22 09:48:13.360  5603  5603 D HidService: Stopping Bluetooth HidService
09-22 09:48:13.361  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.362  3088  3088 D HeadsetProfile: Bluetooth service disconnected
09-22 09:48:13.362  3088  3088 D BluetoothA2dp: Proxy object disconnected
09-22 09:48:13.362  3088  3088 D BluetoothInputDevice: Proxy object disconnected
09-22 09:48:13.363  3088  3088 D HidProfile: Bluetooth service disconnected
09-22 09:48:13.363  5603  5603 D HealthService: Received stop request...Stopping profile...
09-22 09:48:13.364  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 09:48:13.367  5603  5603 D PanService: Received stop request...Stopping profile...
09-22 09:48:13.367  5458  5458 D DockEventReceiver: finishStartingService: stopping service
,09-22 09:48:13.368  3088  3088 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 09:48:13.368  3088  3088 D PanProfile: Bluetooth service disconnected
09-22 09:48:13.369  5458  5458 D HeadsetProfile: Bluetooth service disconnected
09-22 09:48:13.369  5458  5458 D BluetoothA2dp: Proxy object disconnected
09-22 09:48:13.369  5458  5458 D BluetoothInputDevice: Proxy object disconnected
09-22 09:48:13.369  5458  5458 D HidProfile: Bluetooth service disconnected
09-22 09:48:13.370  5603  5603 D BluetoothMapService: Received stop request...Stopping profile...
,09-22 09:48:13.370  5603  5603 D BluetoothMapService: stop()
09-22 09:48:13.371  5458  5458 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 09:48:13.371  5458  5458 D PanProfile: Bluetooth service disconnected
09-22 09:48:13.371  5603  5603 D BluetoothMapAppObserver: deinitObservers()
09-22 09:48:13.372  5603  5603 D BluetoothMapAppObserver: removeReceiver()
,09-22 09:48:13.374  3088  3088 D BluetoothMap: Proxy object disconnected
09-22 09:48:13.374  3088  3088 D MapProfile: Bluetooth service disconnected
09-22 09:48:13.374  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.374  5603  5603 V BluetoothAdapterState: isTurningOn()=false
,09-22 09:48:13.374  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 09:48:13.374  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:13.374  5458  5458 D BluetoothMap: Proxy object disconnected
09-22 09:48:13.375  5458  5458 D MapProfile: Bluetooth service disconnected
09-22 09:48:13.375  5603  5603 D SapService: Received stop request...Stopping profile...
09-22 09:48:13.375  5603  5603 V SapService: stop()
09-22 09:48:13.377  5603  5603 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 09:48:13.377  5603  5603 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 09:48:13.377  5603  5626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 09:48:13.377  5603  5626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:48:13.377  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.377  5603  5626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:48:13.377  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:13.377  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.377  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:13.377  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 09:48:13.377  5603  5619 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 09:48:13.378  5603  5626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 09:48:13.378  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.378  5603  5626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 09:48:13.378  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:13.378  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.378  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:13.378  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 09:48:13.378  5603  5626 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 09:48:13.379  5603  5626 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 09:48:13.379  5603  5626 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 09:48:13.379  5603  5603 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 09:48:13.379  5603  5626 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 09:48:13.379  5603  5603 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 09:48:13.379  5603  5619 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 09:48:13.380  3088  3088 D BluetoothPbap: Proxy object disconnected
,09-22 09:48:13.380  3088  3088 D PbapServerProfile: Bluetooth service disconnected
09-22 09:48:13.381  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.381  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:13.381  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.381  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 09:48:13.381  5603  5603 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-22 09:48:13.382  5603  5603 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 09:48:13.382  5603  5619 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 09:48:13.382  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.382  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:13.382  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.382  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:13.382  5603  5603 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 09:48:13.382  5603  5603 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-22 09:48:13.385  5603  5603 D BluetoothMapService: MAP Service closeService in
,09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:13.385  5603  5603 D BluetoothMapService: cleanup()
09-22 09:48:13.385  5603  5603 D BluetoothMapService: MAP Service closeService in
,09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isTurningOff()=true
09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.385  5603  5603 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:13.385  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 09:48:13.386  5603  5615 D BluetoothAdapterProperties: Setting state to 15
09-22 09:48:13.386  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 09:48:13.386  3476  3505 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:48:13.386  5458  5458 D BluetoothPbap: Proxy object disconnected
09-22 09:48:13.386  5458  5458 D PbapServerProfile: Bluetooth service disconnected
09-22 09:48:13.387  3088  3099 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 09:48:13.387  5603  5615 I BluetoothAdapterState: Entering BleOnState
09-22 09:48:13.387  3088  3721 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 09:48:13.388   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 09:48:13.389   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:48:13.389  3088  3720 D BluetoothPan: onBluetoothStateChange on: false
09-22 09:48:13.389  3088  3100 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 09:48:13.390  5458  5475 D BluetoothMap: onBluetoothStateChange: up=false
09-22 09:48:13.390   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 09:48:13.391  3088  3099 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:48:13.391  5458  5477 D BluetoothPan: onBluetoothStateChange on: false
09-22 09:48:13.391  5458  5474 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 09:48:13.392  5458  5475 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 09:48:13.392   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:48:13.392  5458  5477 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 09:48:13.393  5458  5474 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 09:48:13.393  3088  3721 D BluetoothMap: onBluetoothStateChange: up=false
09-22 09:48:13.394  5603  5615 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 09:48:13.394  5603  5615 D BluetoothAdapterProperties: Setting state to 16
,09-22 09:48:13.394  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 09:48:13.395  5603  5615 D BluetoothAdapterProperties: onBleDisable
09-22 09:48:13.395  5603  5615 I BluetoothAdapterState: Entering PendingCommandState
09-22 09:48:13.395  5603  5616 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 09:48:13.397  5603  5619 D BluetoothAdapterProperties: Scan Mode:20
09-22 09:48:13.397  5458  5458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 09:48:13.398  5603  5626 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 09:48:13.398  5603  5626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 09:48:13.398  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.400  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.401  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 09:48:13.402  5458  5458 D DockEventReceiver: finishStartingService: stopping service
09-22 09:48:13.402  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.404  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.406  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:13.407  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:13.602  5603  5619 I bt_hci  : shut_down
,09-22 09:48:13.607  5603  5623 D bt_hwcfg: hw_epilog_process
,09-22 09:48:13.608  5603  5623 I bt_vendor: low_power_mode_cb
,09-22 09:48:13.610  5603  5623 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 09:48:13.610  5603  5623 I bt_vendor: epilog_cb
09-22 09:48:13.610  5603  5623 I bt_hci  : epilog_finished_callback
,09-22 09:48:13.612  5603  5619 I bt_hci_h4: hal_close
,09-22 09:48:13.612  5603  5619 I bt_userial_vendor: device fd = 54 close
,09-22 09:48:13.724  5603  5616 D bt_stack_manager: event_shut_down_stack finished.
,09-22 09:48:13.725  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-22 09:48:13.728  5603  5615 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-22 09:48:13.728  5603  5603 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 09:48:13.729  5603  5603 D BtGatt.GattService: Received stop request...Stopping profile...
,09-22 09:48:13.729  5603  5603 D BtGatt.GattService: stop()
,09-22 09:48:13.729  5603  5603 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 09:48:13.732  5603  5603 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:13.732  5603  5603 V BluetoothAdapterState: isTurningOn()=false
,09-22 09:48:13.732  5603  5603 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:13.732  5603  5603 V BluetoothAdapterState: isBleTurningOff()=true
09-22 09:48:13.733  5603  5615 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 09:48:13.733  5603  5615 D BluetoothAdapterProperties: Setting state to 10
09-22 09:48:13.733  5603  5615 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-22 09:48:13.735  5603  5615 I BluetoothAdapterState: Entering OffState
09-22 09:48:13.735   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-22 09:48:13.748  5603  5603 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-22 09:48:13.748  5603  5603 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 09:48:13.748  5603  5603 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-22 09:48:13.750  5603  5616 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 09:48:13.756  5603  5603 I art     : System.exit called, status: 0
,09-22 09:48:13.756  5603  5603 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 09:48:13.784   928  3354 I ActivityManager: Process com.android.bluetooth (pid 5603) has died
,09-22 09:48:18.322  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:18.322  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:18.326  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:18.327  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b77cf9 removed from the list
09-22 09:48:18.327  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:18.327  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:18.327  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:18.330  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:18.330  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fde229f added. We now have 4 listener(s)
09-22 09:48:18.331  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 09:48:18.332  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:18.332  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fde229f removed from the list
09-22 09:48:18.332  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:18.333  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:18.333  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:18.335  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:18.336  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b5fec added. We now have 4 listener(s)
09-22 09:48:18.336  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:48:23.345  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:23.381   928   945 I ActivityManager: Start proc 5661:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 09:48:23.490  5661  5661 D AdapterServiceConfig: Adding HeadsetService
,09-22 09:48:23.491  5661  5661 D AdapterServiceConfig: Adding A2dpService
09-22 09:48:23.491  5661  5661 D AdapterServiceConfig: Adding HidService
09-22 09:48:23.491  5661  5661 D AdapterServiceConfig: Adding HealthService
09-22 09:48:23.491  5661  5661 D AdapterServiceConfig: Adding PanService
09-22 09:48:23.491  5661  5661 D AdapterServiceConfig: Adding GattService
09-22 09:48:23.492  5661  5661 D AdapterServiceConfig: Adding BluetoothMapService
09-22 09:48:23.492  5661  5661 D AdapterServiceConfig: Adding SapService
,09-22 09:48:23.506   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4fdfe61:true
,09-22 09:48:23.506  5661  5661 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 09:48:23.509  5661  5661 I bt_bluedroid: init
,09-22 09:48:23.510  5661  5673 I BluetoothAdapterState: Entering OffState
,09-22 09:48:23.512  5661  5674 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 09:48:23.512  5661  5674 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 09:48:23.512  5661  5674 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 09:48:23.513  5661  5674 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-22 09:48:23.514  5661  5661 I bt_bluedroid: get_profile_interface socket
,09-22 09:48:23.515  5661  5677 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 09:48:23.516  5661  5661 I bt_bluedroid: get_profile_interface sdp
09-22 09:48:23.517  5661  5677 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 09:48:23.522  5661  5672 I bt_bluedroid: config_hci_snoop_log
09-22 09:48:23.523   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 09:48:23.528  5661  5673 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 09:48:23.528  5661  5673 D BluetoothAdapterProperties: Setting state to 14
09-22 09:48:23.528  5661  5673 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 09:48:23.531  5661  5673 D BluetoothBondStateMachine: make
,09-22 09:48:23.533  5661  5678 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 09:48:23.536  5661  5673 I BluetoothAdapterState: Entering PendingCommandState
,09-22 09:48:23.537  5661  5661 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 09:48:23.540  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:23.541  5661  5661 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 09:48:23.541  5661  5661 D BtGatt.GattService: Received start request. Starting profile...
09-22 09:48:23.541  5661  5661 D BtGatt.GattService: start()
09-22 09:48:23.541  5661  5661 I bt_bluedroid: get_profile_interface gatt
,09-22 09:48:23.542  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:23.543  5661  5661 D BtGatt.AdvertiseManager: advertise manager created
,09-22 09:48:23.548  5661  5661 V BluetoothAdapterState: isTurningOff()=false
,09-22 09:48:23.548  5661  5661 V BluetoothAdapterState: isTurningOn()=false
09-22 09:48:23.548  5661  5661 V BluetoothAdapterState: isBleTurningOn()=true
09-22 09:48:23.549  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:23.549  5661  5673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 09:48:23.550  5661  5673 I bt_bluedroid: bt_bluedroid
,09-22 09:48:23.550  5661  5674 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 09:48:23.551  5661  5674 I bt_hci  : start_up
,09-22 09:48:23.557  5661  5674 I bt_vendor: alloc value 0xf3c3f871
09-22 09:48:23.557  5661  5674 I bt_vendor: init
09-22 09:48:23.557  5661  5674 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 09:48:23.557  5661  5674 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 09:48:23.667  5661  5674 D bt_hci  : start_up starting async portion
09-22 09:48:23.668  5661  5681 I bt_hci  : event_finish_startup
09-22 09:48:23.668  5661  5681 I bt_hci_h4: hal_open
09-22 09:48:23.668  5661  5681 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 09:48:23.664  5682  5682 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 09:48:23.671  5661  5681 I bt_userial_vendor: device fd = 54 open
,09-22 09:48:23.687  5661  5681 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 09:48:23.691  5661  5681 D bt_hwcfg: Chipset BCM4358A3
09-22 09:48:23.691  5661  5681 D bt_hwcfg: Target name = [BCM4358A3]
,09-22 09:48:23.692  5661  5681 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 09:48:24.195  5661  5681 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 09:48:24.195  5661  5681 D bt_hwcfg: Settlement delay -- 100 ms
09-22 09:48:24.195  5661  5681 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 09:48:24.331  5661  5681 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-22 09:48:24.332  5661  5681 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 09:48:24.333  5661  5681 I bt_hwcfg: vendor lib fwcfg completed
09-22 09:48:24.333  5661  5681 I bt_vendor: firmware callback
09-22 09:48:24.333  5661  5681 I bt_hci  : firmware_config_callback
,09-22 09:48:24.342  5661  5684 I bt_btu  : btu_task pending for preload complete event
,09-22 09:48:24.342  5661  5684 I bt_btu_task: Bluetooth chip preload is complete
,09-22 09:48:24.342  5661  5684 I bt_btu  : btu_task received preload complete event
,09-22 09:48:24.349  5661  5684 I         : BTE_InitTraceLevels -- TRC_HCI
09-22 09:48:24.349  5661  5684 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 09:48:24.350  5661  5684 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-22 09:48:24.350  5661  5684 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 09:48:24.350  5661  5684 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-22 09:48:24.350  5661  5684 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 09:48:24.350  5661  5684 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 09:48:24.350  5661  5684 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_SDP
09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_GATT
,09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-22 09:48:24.351  5661  5684 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 09:48:24.440  5661  5684 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bbd549
09-22 09:48:24.440  5661  5684 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bbd549 
,09-22 09:48:24.453  5661  5677 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 09:48:24.454  5661  5677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 09:48:24.454  5661  5677 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 09:48:24.457  5661  5677 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 09:48:24.462  5661  5677 D BluetoothAdapterProperties: Scan Mode:20
09-22 09:48:24.462  5661  5677 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 09:48:24.463  5661  5677 D bt_hci  : do_postload posting postload work item
09-22 09:48:24.463  5661  5681 I bt_hci  : event_postload
09-22 09:48:24.463  5661  5681 I bt_vendor: sco_config_cb
09-22 09:48:24.463  5661  5681 I bt_hci  : sco_config_callback postload finished.
09-22 09:48:24.466  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:24.469  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:24.470  5661  5681 I bt_vendor: low_power_mode_cb
,09-22 09:48:24.471  5661  5677 D bt_bte_conf: Device ID record 1 : primary
,09-22 09:48:24.471  5661  5677 D bt_bte_conf:   vendorId            = 000f
09-22 09:48:24.471  5661  5677 D bt_bte_conf:   vendorIdSource      = 0001
09-22 09:48:24.472  5661  5677 D bt_bte_conf:   product             = 1200
09-22 09:48:24.472  5661  5677 D bt_bte_conf:   version             = 1436
09-22 09:48:24.472  5661  5677 D bt_bte_conf:   clientExecutableURL = 
09-22 09:48:24.472  5661  5677 D bt_bte_conf:   serviceDescription  = 
09-22 09:48:24.472  5661  5677 D bt_bte_conf:   documentationURL    = 
,09-22 09:48:24.472  5661  5677 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 09:48:24.472  5661  5674 D bt_stack_manager: event_start_up_stack finished
09-22 09:48:24.473  5661  5673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 09:48:24.474  5661  5673 D BluetoothAdapterProperties: Setting state to 15
09-22 09:48:24.474  5661  5673 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 09:48:24.475  5661  5673 I BluetoothAdapterState: Entering BleOnState
,09-22 09:48:24.479  5661  5673 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 09:48:24.479  5661  5673 D BluetoothAdapterProperties: Setting state to 11
09-22 09:48:24.479  5661  5673 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 09:48:24.484  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:24.486  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:24.490  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:24.490  5661  5661 D HeadsetService: Received start request. Starting profile...
,09-22 09:48:24.493  5661  5661 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-22 09:48:24.493  5661  5661 D HeadsetStateMachine: make
,09-22 09:48:24.506  5661  5673 I BluetoothAdapterState: Entering PendingCommandState
,09-22 09:48:24.510  5661  5661 D HeadsetStateMachine: max_hf_connections = 1
,09-22 09:48:24.510  5661  5661 I bt_bluedroid: get_profile_interface handsfree
09-22 09:48:24.510  5661  5677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 09:48:24.510  5661  5677 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-22 09:48:24.515  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:24.516  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 09:48:24.517  5661  5661 D A2dpService: Received start request. Starting profile...
09-22 09:48:24.518  5661  5661 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 09:48:24.518  5661  5661 I bt_bluedroid: get_profile_interface avrcp
,09-22 09:48:24.524  5661  5661 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 09:48:24.524  5661  5661 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 09:48:24.525  5661  5661 D A2dpStateMachine: make
,09-22 09:48:24.526  5661  5661 I bt_bluedroid: get_profile_interface a2dp
,09-22 09:48:24.526  5661  5677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 09:48:24.527  5661  5692 D A2dpStateMachine: Enter Disconnected: -2
09-22 09:48:24.528  5661  5661 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 09:48:24.529  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:24.530  5661  5661 D HidService: Received start request. Starting profile...
09-22 09:48:24.530  5661  5661 I bt_bluedroid: get_profile_interface hidhost
09-22 09:48:24.530  5661  5661 D HidService: setHidService(): set to: null
09-22 09:48:24.531  5661  5661 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 09:48:24.531  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:24.532  5661  5677 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9e56d
09-22 09:48:24.533  5661  5677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 09:48:24.533  5661  5661 D HealthService: Received start request. Starting profile...
,09-22 09:48:24.534  5661  5661 I bt_bluedroid: get_profile_interface health
,09-22 09:48:24.536  5661  5661 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-22 09:48:24.536  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:24.537  5661  5661 D PanService: Received start request. Starting profile...
09-22 09:48:24.537  5661  5661 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 09:48:24.537  5661  5661 I bt_bluedroid: get_profile_interface pan
09-22 09:48:24.538  5661  5677 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 09:48:24.541  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
,09-22 09:48:24.542  5661  5661 D BluetoothMapService: Received start request. Starting profile...
09-22 09:48:24.542  5661  5661 D BluetoothMapService: start()
,09-22 09:48:24.545  5661  5661 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 09:48:24.546  5661  5661 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 09:48:24.546  5661  5661 D BluetoothMapAppObserver: createReceiver()
,09-22 09:48:24.547  5661  5661 D BluetoothMapAppObserver: initObservers()
09-22 09:48:24.547  5661  5661 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 09:48:24.551  5661  5661 V SapService: SapBinder()
,09-22 09:48:24.551  5661  5661 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:24.551  5661  5661 D SapService: Received start request. Starting profile...
09-22 09:48:24.552  5661  5661 V SapService: start()
,09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOn()=true
,09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:24.553  5661  5690 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOn()=true
,09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:24.553  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isTurningOff()=false
,09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isTurningOff()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isTurningOn()=true
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOn()=false
09-22 09:48:24.554  5661  5661 V BluetoothAdapterState: isBleTurningOff()=false
09-22 09:48:24.555  5661  5673 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-22 09:48:24.555  5661  5673 D BluetoothAdapterProperties: ScanMode =  20
09-22 09:48:24.555  5661  5673 D BluetoothAdapterProperties: State =  11
09-22 09:48:24.556  5661  5677 D BluetoothAdapterProperties: Scan Mode:21
09-22 09:48:24.556  5661  5677 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 09:48:24.557  5661  5673 D BluetoothAdapterProperties: Setting state to 12
09-22 09:48:24.557  5661  5673 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 09:48:24.557  5661  5673 I BluetoothAdapterState: Entering OnState
09-22 09:48:24.557  3476  3512 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:24.558  3088  3100 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 09:48:24.562  3088  3721 D BluetoothPbap: onBluetoothStateChange: up=true
,09-22 09:48:24.563  3088  3088 D BluetoothA2dp: Proxy object connected
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:24.563  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:24.567   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 09:48:24.567  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:24.567   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:24.567  3088  3100 D BluetoothPan: onBluetoothStateChange on: true
09-22 09:48:24.569  3088  3099 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 09:48:24.569  3088  3088 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 09:48:24.569  3088  3088 D PanProfile: Bluetooth service connected
09-22 09:48:24.570  5458  5477 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 09:48:24.571  5661  5661 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 09:48:24.571  5661  5661 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:24.571  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:24.572  5661  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:48:24.573  5661  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:48:24.573  5661  5661 D ObexServerSockets: Succeed to create listening sockets 
09-22 09:48:24.573  5661  5661 D ObexServerSockets0: startAccept()
09-22 09:48:24.573  5661  5661 D ObexServerSockets0: prepareForNewConnect()
09-22 09:48:24.574  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:24.574   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 09:48:24.575   928   928 D BluetoothA2dp: Proxy object connected
09-22 09:48:24.575  3088  3721 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:24.575  5661  5661 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 09:48:24.575  5661  5661 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 09:48:24.576  5661  5699 D ObexServerSockets0: Accepting socket connection...
09-22 09:48:24.576  5458  5475 D BluetoothPan: onBluetoothStateChange on: true
09-22 09:48:24.576  3088  3088 D BluetoothInputDevice: Proxy object connected
09-22 09:48:24.576  3088  3088 D HidProfile: Bluetooth service connected
09-22 09:48:24.576  5661  5700 D ObexServerSockets0: Accepting socket connection...
09-22 09:48:24.578  5458  5477 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 09:48:24.579  5458  5475 D BluetoothPbap: onBluetoothStateChange: up=true
,09-22 09:48:24.580   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:24.580  5458  5474 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 09:48:24.581  5458  5477 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 09:48:24.582  3088  3720 D BluetoothMap: onBluetoothStateChange: up=true
09-22 09:48:24.583  3088  3088 D BluetoothMap: Proxy object connected
,09-22 09:48:24.583  3088  3088 D MapProfile: Bluetooth service connected
09-22 09:48:24.583  3088  3088 D BluetoothMap: getConnectedDevices()
09-22 09:48:24.584  5458  5458 D BluetoothMap: Proxy object connected
09-22 09:48:24.584  5458  5458 D MapProfile: Bluetooth service connected
09-22 09:48:24.584  5458  5458 D BluetoothMap: getConnectedDevices()
09-22 09:48:24.584   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-22 09:48:24.586  5661  5661 D BluetoothMapService: onReceive
09-22 09:48:24.586  5661  5661 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 09:48:24.586  5661  5661 D BluetoothMapService: STATE_ON
09-22 09:48:24.588  5458  5458 D BluetoothPan: BluetoothPAN Proxy object connected
,09-22 09:48:24.588  5458  5458 D PanProfile: Bluetooth service connected
09-22 09:48:24.588  5458  5458 D BluetoothA2dp: Proxy object connected
09-22 09:48:24.589  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:24.589  5458  5458 D BluetoothInputDevice: Proxy object connected
09-22 09:48:24.589  5458  5458 D HidProfile: Bluetooth service connected
09-22 09:48:24.590  5661  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:48:24.591  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:24.591  5661  5701 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 09:48:24.592  5661  5701 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 09:48:24.594  5458  5458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 09:48:24.599  3552  3552 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 09:48:24.600  5458  5458 D DockEventReceiver: finishStartingService: stopping service
,09-22 09:48:24.606  5458  5458 D BluetoothPbap: Proxy object connected
,09-22 09:48:24.606  5458  5458 D PbapServerProfile: Bluetooth service connected
,09-22 09:48:24.611  5661  5661 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-22 09:48:24.611  5661  5661 D ObexServerSockets0: prepareForNewConnect()
09-22 09:48:24.612  5661  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 09:48:24.618  3088  3088 D BluetoothPbap: Proxy object connected
09-22 09:48:24.618  3088  3088 D PbapServerProfile: Bluetooth service connected
,09-22 09:48:24.627  5661  5709 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 09:48:24.629  5661  5709 I BtOppRfcommListener: Accept thread started.
,09-22 09:48:24.659   928   928 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.659   928   928 D BluetoothHeadset: Proxy object connected
09-22 09:48:24.659  5458  5474 D BluetoothHeadset: Proxy object connected
09-22 09:48:24.660  3088  3721 D BluetoothHeadset: Proxy object connected
09-22 09:48:24.660  3088  3088 D HeadsetProfile: Bluetooth service connected
09-22 09:48:24.660  3476  3505 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.660   928   928 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.661  5458  5458 D HeadsetProfile: Bluetooth service connected
,09-22 09:48:24.666   928   945 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.666   928   945 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.676  3088  3099 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.676  3088  3088 D HeadsetProfile: Bluetooth service connected
,09-22 09:48:24.681   928   945 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.682  5458  5475 D BluetoothHeadset: Proxy object connected
,09-22 09:48:24.683  5458  5458 D HeadsetProfile: Bluetooth service connected
,09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:28.362  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:28.367  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:28.368  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:28.368  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b5fec removed from the list
09-22 09:48:28.368  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:28.369  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:28.369  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:28.371  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:28.372  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d69efb5 added. We now have 4 listener(s)
09-22 09:48:28.372  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 09:48:28.375   928   938 D WifiService: setWifiEnabled: false pid=5404, uid=10077
,09-22 09:48:28.376   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 09:48:30.621   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:31.622   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:32.623   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:33.387  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:33.388   928  3353 D WifiService: setWifiEnabled: true pid=5404, uid=10077
09-22 09:48:33.388   928  3353 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 09:48:33.398   506   922 D SoftapController: Softap fwReload - Ok
,09-22 09:48:33.404   506   922 D CommandListener: Setting iface cfg
,09-22 09:48:33.404   506   922 D CommandListener: Trying to bring down wlan0
09-22 09:48:33.405   506   922 D CommandListener: Clearing all IP addresses on wlan0
09-22 09:48:33.408   928  2918 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 09:48:33.624   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:34.016   928  2918 D wifi    : set interface wlan0 flags (UP)
,09-22 09:48:34.022   928  2918 I WifiHAL : Initializing wifi
,09-22 09:48:34.024   928  2918 I WifiHAL : Creating socket
,09-22 09:48:34.024   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-22 09:48:34.028   928  2918 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-22 09:48:34.028   928  2918 D wifi    : Did set static halHandle = 0x7f65457b80
09-22 09:48:34.028   928  2918 D wifi    : halHandle = 0x7f65457b80, mVM = 0x7f81acd140, mCls = 0x151a
,09-22 09:48:34.028   928  2918 D wifi    : array field set
09-22 09:48:34.029   928  2918 I WifiNative-HAL: interface[0] = wlan0
09-22 09:48:34.031   928  5714 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547159899008
09-22 09:48:34.031   928  5714 D wifi    : waitForHalEvents called, vm = 0x7f81acd140, obj = 0x151a, env = 0x7f62baa040
,09-22 09:48:34.091  5715  5715 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 09:48:34.112  5715  5715 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 09:48:34.120  5715  5715 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 09:48:34.121  5715  5715 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 09:48:34.132   928  2918 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 09:48:34.145   928  2918 D WifiConfigStore: Loading config and enabling all networks 
,09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:34.149  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:34.152  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 09:48:34.155  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 09:48:34.157   928  2918 D WifiConfigStore: loaded 0 passpoint configs
,09-22 09:48:34.157  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 09:48:34.157   928  2918 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 09:48:34.158   928  2918 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-22 09:48:34.158  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:34.159   928  2918 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-22 09:48:34.159   928  2918 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 09:48:34.159   928  2918 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 09:48:34.159  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:34.160   928  2918 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 09:48:34.160   928  2918 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 09:48:34.164  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 09:48:34.164   928  2918 D WifiNative-HAL: Setting external_sim to 1
09-22 09:48:34.164   928  2918 D wifi    : setting dfs flag to true, 0x7f65cafce0
09-22 09:48:34.165   928  2918 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 09:48:34.165   928  2918 D wifi    : setting scan oui 0x7f65cafce0
09-22 09:48:34.165   928  2918 D WifiHAL : Sending mac address OUI
,09-22 09:48:34.170   928  2918 E native  : do suspend false
,09-22 09:48:34.177   928  2918 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 09:48:34.177   928   928 D RttService: SCAN_AVAILABLE : 3
09-22 09:48:34.177   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 09:48:34.177   928  3029 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 09:48:34.178   506   922 D CommandListener: Setting iface cfg
,09-22 09:48:34.181   928  2905 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '97 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 97 Failed to set address (No such device)'
,09-22 09:48:34.182   928  2905 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 09:48:34.190   928  2905 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 09:48:34.191   928  2905 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 09:48:34.211   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302554 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=30 mControllerEnergyUsed=114 }
,09-22 09:48:34.624   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:48:35.625   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 09:48:37.356  5715  5715 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-22 09:48:37.365  5715  5715 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-22 09:48:37.371  5715  5715 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-22 09:48:37.396   928  2918 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-22 09:48:37.397   928  2918 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-22 09:48:37.397   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-22 09:48:37.407   928  2918 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-22 09:48:37.439   928  2918 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-22 09:48:37.441  5715  5715 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-22 09:48:37.867  5715  5715 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-22 09:48:37.898  5715  5715 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-22 09:48:37.898  5715  5715 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-22 09:48:37.907   928  2918 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-22 09:48:37.907   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 09:48:37.907   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-22 09:48:37.925   928  2918 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-22 09:48:37.936   506   922 D CommandListener: Setting iface cfg
,09-22 09:48:37.942   928  2918 D WifiStateMachine: Start Dhcp Watchdog 3
,09-22 09:48:37.948   928  5720 D DhcpClient: Receive thread started
,09-22 09:48:37.953   928  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-22 09:48:37.953   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-22 09:48:37.953   928  2920 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-22 09:48:38.034   928  2918 E native  : do suspend false
,09-22 09:48:38.048   928  5719 D DhcpClient: Broadcasting DHCPDISCOVER
,09-22 09:48:38.062   928  5720 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-22 09:48:38.063   928  5719 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
09-22 09:48:38.065   928  5719 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-22 09:48:38.096   928  5720 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-22 09:48:38.096   928  5719 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-22 09:48:38.099   506   922 D CommandListener: Setting iface cfg
09-22 09:48:38.104   928  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-22 09:48:38.108   928  5719 D DhcpClient: Scheduling renewal in 86399s
,09-22 09:48:38.116   928  2918 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-22 09:48:38.117   928  2918 D WifiConfigStore: No blacklist allowed without epno enabled
,09-22 09:48:38.118   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-22 09:48:38.120   928  2920 D ConnectivityService: Adding iface wlan0 to network 102
,09-22 09:48:38.130   928  2918 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-22 09:48:38.167   928  2920 E ConnectivityService: Unexpected mtu value: 0, wlan0,
09-22 09:48:38.168   928  2920 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-22 09:48:38.171   928  2920 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-22 09:48:38.173   928  2920 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-22 09:48:38.176   928  2920 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-22 09:48:38.184   928  2920 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-22 09:48:38.188   928  2920 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-22 09:48:38.189   928  2920 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-22 09:48:38.189   928  2920 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-22 09:48:38.189   928  2918 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-22 09:48:38.189   928  2920 D ConnectivityService:    accepting network in place of null
09-22 09:48:38.189   928  2918 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 09:48:38.190   928  2920 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -58]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-22 09:48:38.202   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306545, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-22 09:48:38.214   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 09:48:38.233   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 09:48:38.237   928  2920 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-22 09:48:38.237   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-22 09:48:38.237  3442  3691 W QCNEJ   : |CORE| network available: 102
09-22 09:48:38.238   928  2920 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-22 09:48:38.239   928   945 D Tethering: MasterInitialState.processMessage what=3
09-22 09:48:38.243  3442  3691 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-22 09:48:38.244  3442  3691 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-22 09:48:38.245  3442  3691 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-22 09:48:38.246  4837  4850 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:38.246  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:48:38.246  4837  4850 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-22 09:48:38.246  4837  4850 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-22 09:48:38.246  4837  4850 E SarControlService: no key has been found,reset the power
09-22 09:48:38.246  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-22 09:48:38.246  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-22 09:48:38.248  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 09:48:38.248  3827  3827 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-22 09:48:38.248  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:38.251  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 09:48:38.251  4863  4863 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-22 09:48:38.252  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 09:48:38.252  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 09:48:38.252  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 09:48:38.253  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-22 09:48:38.253  4863  4863 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:38.253  5404  5404 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 09:48:38.256  5404  5404 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:38.257  3827  3827 D SystemUpdateService: onCreate
,09-22 09:48:38.259  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000f003000000000000ffffffff]
,09-22 09:48:38.259  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:48:38.259  4863  4877 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-22 09:48:38.259  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-22 09:48:38.259  4837  4848 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-22 09:48:38.261  4863  4877 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a15e8d7 HexData = [00000000f103000000000000ffffffff]
09-22 09:48:38.261  4863  4877 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 09:48:38.261  4863  4877 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-22 09:48:38.262  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 09:48:38.262  4837  4847 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-22 09:48:38.262  3827  3827 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-22 09:48:38.270   928  5717 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-22 09:48:38.271  3827  3827 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-22 09:48:38.277  3827  5175 I iu.UploadsManager: num queued entries: 0
,09-22 09:48:38.277  3827  5175 I iu.UploadsManager: num updated entries: 0
09-22 09:48:38.278  3827  5175 I iu.SyncManager: NEXT; no task
,09-22 09:48:38.281  3827  3827 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-22 09:48:38.282  3827  3827 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 09:48:38.284  5525  5525 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-22 09:48:38.287  5525  5525 D SprintDMHelper: simOperator: 
09-22 09:48:38.287  5525  5525 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 09:48:38.296  3827  5730 I SystemUpdateService: active receiver: enabled
,09-22 09:48:38.315  3827  5730 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 09:48:38.322  3827  5730 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,09-22 09:48:38.323  3827  5730 I SystemUpdateService: now status is 0 (complete)
,09-22 09:48:38.323  3827  5730 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-22 09:48:38.323  3827  5730 I SystemUpdateService: file has been verified
09-22 09:48:38.323  3827  5730 I SystemUpdateService: OTA package size = 21989297
,09-22 09:48:38.325   928  5717 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 22 Sep 2016 13:48:38 GMT], X-Android-Received-Millis=[1474552118324], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474552118295]}
,09-22 09:48:38.325   928  2920 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-22 09:48:38.325   928  2920 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-22 09:48:38.325   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-22 09:48:38.326   928  2920 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-22 09:48:38.328  3827  5730 I SystemUpdateService: showing system update notification
,09-22 09:48:38.337  3827  3827 D SystemUpdateService: onDestroy
,09-22 09:48:38.391  4244  5734 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:38.400  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:48:38.401  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:38.401  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:38.402  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d69efb5 removed from the list
09-22 09:48:38.402  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:38.402  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:38.402  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:38.405  5404  5742 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-22 09:48:38.405  5404  5742 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 09:48:40.974   928  2920 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-22 09:48:41.416  5404  5742 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-22 09:48:41.416  5404  5743 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-22 09:48:41.417  5404  5743 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-22 09:48:41.418  5404  5742 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-22 09:48:41.418  5404  5742 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:41.418  5404  5743 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-22 09:48:41.420  5404  5742 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:41.421  5404  5743 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:41.421  5404  5742 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-22 09:48:41.424  5404  5745 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender)
,09-22 09:48:41.426  5404  5743 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-22 09:48:41.427  5404  5747 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
,09-22 09:48:41.428  5404  5746 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Sender)
,09-22 09:48:41.429  5404  5747 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
09-22 09:48:41.429  5404  5747 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-22 09:48:41.429  5404  5747 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-22 09:48:41.429  5404  5748 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Receiver)
09-22 09:48:41.431  5404  5748 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: IncomingSocketThread/Receiver)
,09-22 09:48:41.431  5404  5748 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-22 09:48:41.431  5404  5748 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-22 09:48:44.412  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-22 09:48:44.415  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-22 09:48:44.421  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8556f48 Bundle[{}]
,09-22 09:48:44.422  5404  5450 I io.jxcore.node.LifeCycleMonitor: start: OK,
09-22 09:48:44.423  5404  5450 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-22 09:48:44.425  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-22 09:48:44.427  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-22 09:48:44.428  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-22 09:48:44.429  5404  5450 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-22 09:48:44.434  5404  5450 I System.out: Running OutgoingSocketThread
,09-22 09:48:44.436  5404  5749 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-22 09:48:44.436  5404  5749 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 09:48:46.194   928  2920 D ConnectivityService: handlePromptUnvalidated 102
,09-22 09:48:47.448  5404  5749 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-22 09:48:47.448  5404  5749 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-22 09:48:47.449  5404  5749 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:47.449  5404  5749 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:47.450  5404  5750 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-22 09:48:47.451  5404  5750 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-22 09:48:47.451  5404  5752 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender)
,09-22 09:48:47.451  5404  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:47.452  5404  5750 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-22 09:48:47.453  5404  5749 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-22 09:48:47.456  5404  5753 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Sender)
,09-22 09:48:47.458  5404  5754 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
,09-22 09:48:47.459  5404  5750 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-22 09:48:47.460  5404  5754 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
,09-22 09:48:47.460  5404  5755 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Receiver)
09-22 09:48:47.460  5404  5754 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-22 09:48:47.460  5404  5754 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-22 09:48:47.461  5404  5755 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: IncomingSocketThread/Receiver)
09-22 09:48:47.462  5404  5755 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-22 09:48:47.462  5404  5755 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-22 09:48:49.190   928  2918 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-22 09:48:50.446  5404  5450 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-22 09:48:50.448  5404  5450 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-22 09:48:50.448  5404  5450 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
09-22 09:48:50.453  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 09:48:50.453  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@822664a added. We now have 3 listener(s)
,09-22 09:48:50.459  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 09:48:50.459  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:48:50.459  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:48:50.459  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:50.459  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90c49bb added. We now have 4 listener(s)
09-22 09:48:50.459  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 09:48:50.460  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 09:48:50.466  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:50.473  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:48:50.476  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 09:48:50.476  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:48:50.477  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:48:50.477  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:48:50.477  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-22 09:48:50.477  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:50.477  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:48:50.477  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:50.477  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-22 09:48:50.477  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@822664a removed from the list
09-22 09:48:50.477  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:48:50.477  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90c49bb removed from the list
09-22 09:48:50.479  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:50.483  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:50.483  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:50.483  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:50.484  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:48:50.484  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:50.486  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:48:50.486  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:48:50.486  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:50.486  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90c49bb not in the list
09-22 09:48:50.486  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:50.487  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:50.488  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:48:50.489  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:48:50.489  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:50.489  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90c49bb not in the list
09-22 09:48:50.489  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:50.489  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:50.489  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:50.489  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@822664a not in the list
,09-22 09:48:50.490  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 09:48:50.490  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c96d231 added. We now have 3 listener(s)
,09-22 09:48:50.492  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 09:48:50.493  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 09:48:50.493  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:48:50.493  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:50.493  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3289d16 added. We now have 4 listener(s)
09-22 09:48:50.493  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:48:50.494  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 09:48:50.499  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:50.503  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:48:50.505  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:50.506  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 09:48:50.506  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 09:48:50.506  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 09:48:50.506  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 09:48:50.506  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:50.506  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:48:50.510  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:50.510  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:48:50.510  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 09:48:50.514  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 09:48:50.514  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:50.515  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:48:50.515  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 09:48:50.519  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 09:48:50.519  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 09:48:50.519  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 09:48:50.520  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:48:50.523  5661  5671 D BtGatt.GattService: registerClient() - UUID=b58696b8-a7ac-4f1a-a834-8c5e6031fd92
,09-22 09:48:50.524  5661  5677 D BtGatt.GattService: onClientRegistered() - UUID=b58696b8-a7ac-4f1a-a834-8c5e6031fd92, clientIf=5
,09-22 09:48:50.525  5404  5415 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 09:48:50.526  5661  5697 D BtGatt.GattService: start scan with filters
,09-22 09:48:50.529  5661  5680 D BtGatt.ScanManager: handling starting scan
,09-22 09:48:50.529  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 09:48:50.530  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 09:48:50.530  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 09:48:50.530  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 09:48:50.531  5661  5680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@612195c
09-22 09:48:50.532  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 09:48:50.532  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 09:48:50.532  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 09:48:50.534  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 09:48:50.537  5404  5450 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 09:48:50.537  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:48:50.539  5661  5677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 09:48:50.539  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:48:50.537  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 09:48:50.541  5661  5680 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 09:48:50.550  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:50.550  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 09:48:50.550  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:48:50.550  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 09:48:50.550  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 09:48:50.550  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 09:48:50.550  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 09:48:50.550  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 09:48:50.551  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:50.552  5661  5671 D BtGatt.GattService: stopScan() - queue size =1
09-22 09:48:50.553  5661  5697 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 09:48:50.553  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:50.553  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 09:48:50.554  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 09:48:50.554  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 09:48:50.554  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 09:48:50.555  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:48:50.555  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:50.555  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 09:48:50.555  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:48:50.555  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:50.556  5661  5677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 09:48:50.556  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:50.556  5661  5680 D BtGatt.ScanManager: Starting BLE batch scan
09-22 09:48:50.556  5661  5680 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 09:48:50.557  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:48:50.557  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:50.557  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:48:50.561  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:48:50.561  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 09:48:50.565  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 09:48:50.565  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:48:50.565  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:48:50.566  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:48:50.566  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:50.568  5661  5677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 09:48:50.568  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:48:50.568  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:50.568  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:50.568  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:48:50.571  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:48:50.571  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:48:50.572  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:50.573  5661  5677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 09:48:50.573  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:48:50.574  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 09:48:50.580  5661  5677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 09:48:50.580  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:50.581  5661  5680 D BtGatt.ScanManager: stopping BLe Batch
,09-22 09:48:50.586  5661  5677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 09:48:50.586  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:50.586  5661  5680 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 09:48:50.591  5661  5677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 09:48:50.591  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:48:51.076  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-22 09:48:51.076  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:48:51.077  5404  5404 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 09:48:53.557  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:48:53.558  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:48:53.558  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:48:53.558  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:53.558  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:53.558  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:53.559  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 09:48:53.559  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c96d231 removed from the list
09-22 09:48:53.559  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:53.559  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3289d16 removed from the list
09-22 09:48:53.559  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 09:48:53.559  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:53.561  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:53.562  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:53.565  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:48:53.565  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:53.565  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:48:53.567  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:53.567  5404  5450 D BluetoothLeScanner: could not find callback wrapper
,09-22 09:48:53.568  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:53.568  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:53.568  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3289d16 not in the list
09-22 09:48:53.568  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:53.568  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:53.571  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:48:53.574  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:53.574  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:48:53.574  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:53.574  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:48:53.574  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:53.575  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:53.575  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3289d16 not in the list
09-22 09:48:53.575  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:53.575  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:53.575  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:53.575  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c96d231 not in the list
09-22 09:48:53.578  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 09:48:53.578  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1af18f added. We now have 3 listener(s)
09-22 09:48:53.580  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 09:48:53.580  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:48:53.580  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:48:53.580  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:53.580  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9c1c added. We now have 4 listener(s)
09-22 09:48:53.580  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 09:48:53.581  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 09:48:53.585  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:53.589  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:48:53.592  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:53.592  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:48:53.592  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-22 09:48:53.593  5404  5450 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-22 09:48:53.593  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-22 09:48:53.593  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-22 09:48:53.594  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-22 09:48:53.594  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 09:48:53.594  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:53.595  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-22 09:48:53.596  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:53.596  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-22 09:48:53.596  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-22 09:48:53.596  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-22 09:48:53.596  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-22 09:48:53.596  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:53.596  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:48:53.598  5404  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 09:48:53.601  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:48:53.601  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 09:48:53.601  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:53.601  5404  5404 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 09:48:53.597  5671  5671 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33879]" dev="sockfs" ino=33879 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 09:48:53.601  5671  5671 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33879]" dev="sockfs" ino=33879 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 09:48:53.605  5404  5756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-22 09:48:53.606  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 09:48:53.607  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:48:53.607  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:48:53.609  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-22 09:48:53.610  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 09:48:53.610  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-22 09:48:53.611  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-22 09:48:53.611  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-22 09:48:53.611  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-22 09:48:53.612  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:48:53.618  5661  5671 D BtGatt.GattService: registerClient() - UUID=b8179aef-ee0e-4102-81f7-d5cdff470ca8
09-22 09:48:53.618  5661  5677 D BtGatt.GattService: onClientRegistered() - UUID=b8179aef-ee0e-4102-81f7-d5cdff470ca8, clientIf=5
,09-22 09:48:53.618  5404  5415 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-22 09:48:53.620  5661  5679 D BtGatt.AdvertiseManager: message : 0
,09-22 09:48:53.622  5661  5679 D BtGatt.AdvertiseManager: starting multi advertising
,09-22 09:48:53.633  5661  5677 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-22 09:48:53.639  5661  5677 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-22 09:48:53.640  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-22 09:48:53.640  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-22 09:48:53.642  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 09:48:53.643  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-22 09:48:53.643  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-22 09:48:53.643  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-22 09:48:53.643  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-22 09:48:53.643  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-22 09:48:53.643  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-22 09:48:53.645  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-22 09:48:53.647  5404  5404 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-22 09:48:53.647  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-22 09:48:54.148  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-22 09:48:54.148  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-22 09:48:54.148  5404  5404 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 09:48:56.647  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:48:56.647  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-22 09:48:56.648  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 09:48:56.648  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 09:48:56.648  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 09:48:56.648  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 09:48:56.649  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-22 09:48:56.649  5404  5756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 09:48:56.649  5404  5450 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 09:48:56.649  5404  5756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-22 09:48:56.649  5404  5756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 09:48:56.649  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:48:56.649  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-22 09:48:56.649  5404  5404 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 09:48:56.649  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 09:48:56.649  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 09:48:56.650  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 09:48:56.652  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:56.652  5404  5450 D BluetoothLeScanner: could not find callback wrapper
,09-22 09:48:56.652  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:56.653  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-22 09:48:56.655  5661  5679 D BtGatt.AdvertiseManager: message : 1
09-22 09:48:56.656  5661  5679 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-22 09:48:56.671  5661  5677 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-22 09:48:56.671  5661  5677 D BtGatt.GattService: Client app is not null!
09-22 09:48:56.673  5661  5672 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 09:48:56.674  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 09:48:56.674  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-22 09:48:56.674  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-22 09:48:56.674  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-22 09:48:56.675  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-22 09:48:56.677  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:48:56.677  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 09:48:56.678  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:48:56.680  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:56.682  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:56.682  5404  5404 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 09:48:56.682  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:56.683  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:56.683  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 09:48:56.683  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:48:56.683  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1af18f removed from the list
09-22 09:48:56.683  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:56.683  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:56.683  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:48:56.684  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9c1c removed from the list
09-22 09:48:56.684  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:56.684  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-22 09:48:56.689  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 09:48:56.689  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 09:48:56.696  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 09:48:56.697  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:48:56.698  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:48:56.698  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:48:56.698  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:56.702  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:56.702  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:56.704  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:48:56.704  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:56.705  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:48:56.706  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:56.706  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:48:56.706  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:56.706  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:48:56.706  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:48:56.706  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9c1c not in the list
09-22 09:48:56.706  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:56.707  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:48:56.712  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:48:56.712  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:48:56.713  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:56.716  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 09:48:56.716  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:48:56.716  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:56.718  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:48:56.719  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:56.719  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:48:56.719  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:56.719  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:48:56.719  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:56.719  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:56.719  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9c1c not in the list
09-22 09:48:56.719  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:56.720  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:56.720  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:56.720  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1af18f not in the list
,09-22 09:48:56.721  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 09:48:56.721  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39c3edd added. We now have 3 listener(s)
09-22 09:48:56.724  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 09:48:56.724  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:48:56.724  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:48:56.725  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 09:48:56.725  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c4a52 added. We now have 4 listener(s)
09-22 09:48:56.725  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 09:48:56.726  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 09:48:56.731  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:56.738  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:48:56.741  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:56.741  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:48:56.741  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 09:48:56.741  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 09:48:56.742  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 09:48:56.742  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:56.742  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 09:48:56.746  5404  5450 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:48:56.746  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 09:48:56.747  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:56.752  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 09:48:56.752  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 09:48:56.753  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 09:48:56.753  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 09:48:56.757  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 09:48:56.758  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 09:48:56.758  5404  5450 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 09:48:56.758  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:48:56.761  5661  5689 D BtGatt.GattService: registerClient() - UUID=f5f3a303-f9bc-4b7b-9bd0-11a887396cc4
09-22 09:48:56.762  5661  5677 D BtGatt.GattService: onClientRegistered() - UUID=f5f3a303-f9bc-4b7b-9bd0-11a887396cc4, clientIf=5
09-22 09:48:56.762  5404  5414 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 09:48:56.763  5661  5698 D BtGatt.GattService: start scan with filters
,09-22 09:48:56.766  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-22 09:48:56.766  5661  5680 D BtGatt.ScanManager: handling starting scan
09-22 09:48:56.766  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 09:48:56.767  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 09:48:56.767  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 09:48:56.770  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 09:48:56.771  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 09:48:56.771  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 09:48:56.773  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 09:48:56.775  5661  5677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 09:48:56.776  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:48:56.776  5661  5680 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 09:48:56.784  5661  5677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-22 09:48:56.784  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:56.784  5661  5680 D BtGatt.ScanManager: Starting BLE batch scan
09-22 09:48:56.785  5661  5680 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 09:48:56.797  5661  5677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 09:48:56.797  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:48:56.803  5661  5677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 09:48:56.804  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 09:48:57.218  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 09:48:57.271  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-22 09:48:57.271  5404  5404 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 09:48:57.271  5404  5404 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 09:48:59.784  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 09:48:59.784  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 09:48:59.784  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 09:48:59.784  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.785  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-22 09:48:59.785  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 09:48:59.785  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 09:48:59.785  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 09:48:59.785  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-22 09:48:59.785  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 09:48:59.786  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 09:48:59.789  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:48:59.791  5661  5697 D BtGatt.GattService: stopScan() - queue size =1
,09-22 09:48:59.793  5661  5672 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 09:48:59.794  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 09:48:59.794  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-22 09:48:59.794  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 09:48:59.795  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 09:48:59.795  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 09:48:59.797  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:48:59.798  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:59.798  5404  5450 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 09:48:59.798  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:48:59.799  5661  5661 D BtGatt.ScanManager: awakened up at time 328142
09-22 09:48:59.799  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:59.802  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:48:59.802  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:59.802  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:59.802  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:48:59.802  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.802  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-22 09:48:59.802  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 09:48:59.803  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39c3edd removed from the list
09-22 09:48:59.803  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:59.804  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c4a52 removed from the list
09-22 09:48:59.804  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:59.804  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:59.808  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:48:59.808  5404  5404 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 09:48:59.809  5661  5677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 09:48:59.809  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:59.809  5661  5680 D BtGatt.ScanManager: stopping BLe Batch
,09-22 09:48:59.815  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 09:48:59.817  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 09:48:59.817  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 09:48:59.817  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 09:48:59.818  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:59.821  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.821  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:59.822  5661  5677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 09:48:59.822  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:59.822  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:48:59.822  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-22 09:48:59.822  5661  5680 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 09:48:59.822  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:48:59.823  5404  5450 D BluetoothAdapter: STATE_ON
09-22 09:48:59.824  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:48:59.824  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:59.824  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 09:48:59.824  5404  5404 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 09:48:59.824  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c4a52 not in the list
09-22 09:48:59.824  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 09:48:59.824  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 09:48:59.828  5404  5404 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 09:48:59.828  5404  5404 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 09:48:59.829  5404  5404 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:59.831  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.831  5404  5404 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 09:48:59.831  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:59.832  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:48:59.833  5404  5450 D BluetoothAdapter: STATE_ON
,09-22 09:48:59.833  5404  5450 D BluetoothLeScanner: could not find callback wrapper
09-22 09:48:59.833  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 09:48:59.833  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 09:48:59.833  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 09:48:59.833  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:59.833  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c4a52 not in the list
09-22 09:48:59.834  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 09:48:59.834  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.834  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:59.834  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39c3edd not in the list
09-22 09:48:59.834  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 09:48:59.835  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9419b added. We now have 3 listener(s)
09-22 09:48:59.838  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 09:48:59.838  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 09:48:59.838  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 09:48:59.838  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 09:48:59.838  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c05938 added. We now have 4 listener(s)
09-22 09:48:59.838  5404  5450 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 09:48:59.839  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 09:48:59.842  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 09:48:59.846  5404  5450 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 09:48:59.848  5404  5450 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 09:48:59.848  5404  5450 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 09:48:59.848  5404  5450 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 09:48:59.848  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 09:48:59.848  5404  5450 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 09:48:59.848  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:59.848  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.849  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 09:48:59.849  5404  5450 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 09:48:59.849  5404  5450 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9419b removed from the list
09-22 09:48:59.849  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:59.849  5404  5450 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c05938 removed from the list
,09-22 09:48:59.853  5661  5677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-22 09:48:59.853  5661  5677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 09:48:59.853  5661  5677 D BtGatt.GattService: current time is 328197033364
,09-22 09:48:59.854  5661  5677 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -86, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -76, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 09:48:59.854  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:59.854  5404  5450 D io.jxcore.node.ConnectivityMonitor: stop
09-22 09:48:59.855  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:59.855  5661  5677 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-22 09:48:59.855  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.855  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:59.856  5661  5677 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-22 09:48:59.856  5661  5677 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-22 09:48:59.856  5661  5677 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-22 09:48:59.856  5661  5677 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-22 09:48:59.857  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:48:59.857  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 09:48:59.857  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:59.857  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c05938 not in the list
09-22 09:48:59.857  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.857  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 09:48:59.858  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 09:48:59.858  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 09:48:59.858  5404  5450 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 09:48:59.858  5404  5450 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c05938 not in the list
09-22 09:48:59.858  5404  5450 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 09:48:59.858  5404  5450 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 09:48:59.858  5404  5404 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 09:48:59.859  5404  5450 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 09:48:59.859  5404  5450 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9419b not in the list
09-22 09:48:59.859  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-22 09:48:59.860  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-22 09:48:59.860  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-22 09:48:59.860  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 09:48:59.860  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-22 09:48:59.860  5404  5450 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 09:49:00.331  5404  5404 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 09:49:00.625   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-22 09:49:00.626   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-22 09:49:01.871  5404  5757 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-22 09:49:03.870  5404  5450 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 187
,09-22 09:49:03.871  5404  5450 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 187, name: My test thread name)
,09-22 09:49:03.875  5404  5758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,09-22 09:49:03.875  5404  5758 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 188, thread name: My test thread name)
,09-22 09:49:03.875  5404  5758 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-22 09:49:03.880  5404  5450 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-22 09:49:03.887  5404  5759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
,09-22 09:49:03.888  5404  5759 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 192, thread name: My test thread name): Test exception.
09-22 09:49:03.888  5404  5759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-22 09:49:03.895  5404  5450 I jxcore-log: Total number of executed tests:  82
09-22 09:49:03.895  5404  5450 I jxcore-log: 
,09-22 09:49:03.895  5404  5450 I jxcore-log: Number of passed tests:  82
09-22 09:49:03.895  5404  5450 I jxcore-log: 
09-22 09:49:03.895  5404  5450 I jxcore-log: Number of failed tests:  0
09-22 09:49:03.895  5404  5450 I jxcore-log: 
,09-22 09:49:03.896  5404  5450 I jxcore-log: Number of ignored tests:  0
09-22 09:49:03.896  5404  5450 I jxcore-log: 
09-22 09:49:03.896  5404  5450 I jxcore-log: Total duration:  101106
09-22 09:49:03.896  5404  5450 I jxcore-log: 
,09-22 09:49:03.902  5404  5450 I jxcore-log: Unit Test app is loaded
09-22 09:49:03.902  5404  5450 I jxcore-log: 
,09-22 09:49:03.917  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.917  5404  5450 I jxcore-log: 
,09-22 09:49:03.924  5404  5404 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-22 09:49:03.924  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.924  5404  5450 I jxcore-log: 
09-22 09:49:03.924  5404  5757 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-22 09:49:03.926  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.926  5404  5450 I jxcore-log: 
,09-22 09:49:03.928  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.928  5404  5450 I jxcore-log: 
,09-22 09:49:03.929  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-22 09:49:03.929  5404  5450 I jxcore-log: 
,09-22 09:49:03.932  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-22 09:49:03.932  5404  5450 I jxcore-log: 
,09-22 09:49:03.935  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.935  5404  5450 I jxcore-log: 
,09-22 09:49:03.937  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.937  5404  5450 I jxcore-log: 
,09-22 09:49:03.938  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-22 09:49:03.938  5404  5450 I jxcore-log: 
09-22 09:49:03.939  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-22 09:49:03.939  5404  5450 I jxcore-log: 
09-22 09:49:03.940  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-22 09:49:03.940  5404  5450 I jxcore-log: 
09-22 09:49:03.941  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.941  5404  5450 I jxcore-log: 
09-22 09:49:03.941  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.941  5404  5450 I jxcore-log: 
,09-22 09:49:03.942  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.942  5404  5450 I jxcore-log: 
09-22 09:49:03.942  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.942  5404  5450 I jxcore-log: 
09-22 09:49:03.944  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.944  5404  5450 I jxcore-log: 
,09-22 09:49:03.945  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.945  5404  5450 I jxcore-log: 
,09-22 09:49:03.946  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.946  5404  5450 I jxcore-log: 
,09-22 09:49:03.947  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.947  5404  5450 I jxcore-log: 
,09-22 09:49:03.948  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.948  5404  5450 I jxcore-log: 
09-22 09:49:03.949  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.949  5404  5450 I jxcore-log: 
09-22 09:49:03.950  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.950  5404  5450 I jxcore-log: 
,09-22 09:49:03.951  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.951  5404  5450 I jxcore-log: 
,09-22 09:49:03.952  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.952  5404  5450 I jxcore-log: 
,09-22 09:49:03.953  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.953  5404  5450 I jxcore-log: 
,09-22 09:49:03.954  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.954  5404  5450 I jxcore-log: 
,09-22 09:49:03.955  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.955  5404  5450 I jxcore-log: 
,09-22 09:49:03.956  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.956  5404  5450 I jxcore-log: 
,09-22 09:49:03.957  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.957  5404  5450 I jxcore-log: 
,09-22 09:49:03.961  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.961  5404  5450 I jxcore-log: 
,09-22 09:49:03.962  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.962  5404  5450 I jxcore-log: 
09-22 09:49:03.962  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.962  5404  5450 I jxcore-log: 
09-22 09:49:03.963  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.963  5404  5450 I jxcore-log: 
,09-22 09:49:03.964  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.964  5404  5450 I jxcore-log: 
,09-22 09:49:03.965  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.965  5404  5450 I jxcore-log: 
,09-22 09:49:03.966  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.966  5404  5450 I jxcore-log: 
,09-22 09:49:03.967  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.967  5404  5450 I jxcore-log: 
,09-22 09:49:03.968  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.968  5404  5450 I jxcore-log: 
09-22 09:49:03.968  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.968  5404  5450 I jxcore-log: 
09-22 09:49:03.969  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-22 09:49:03.969  5404  5450 I jxcore-log: 
09-22 09:49:03.969  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.969  5404  5450 I jxcore-log: 
09-22 09:49:03.970  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-22 09:49:03.970  5404  5450 I jxcore-log: 
,09-22 09:49:03.971  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.971  5404  5450 I jxcore-log: 
,09-22 09:49:03.972  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.972  5404  5450 I jxcore-log: 
,09-22 09:49:03.973  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.973  5404  5450 I jxcore-log: 
,09-22 09:49:03.974  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.974  5404  5450 I jxcore-log: 
,09-22 09:49:03.975  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.975  5404  5450 I jxcore-log: 
09-22 09:49:03.976  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-22 09:49:03.976  5404  5450 I jxcore-log: 
09-22 09:49:03.977  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.977  5404  5450 I jxcore-log: 
,09-22 09:49:03.977  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-22 09:49:03.977  5404  5450 I jxcore-log: 
,09-22 09:49:03.978  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.978  5404  5450 I jxcore-log: 
,09-22 09:49:03.979  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-22 09:49:03.979  5404  5450 I jxcore-log: 
,09-22 09:49:03.980  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-22 09:49:03.980  5404  5450 I jxcore-log: 
,09-22 09:49:03.981  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-22 09:49:03.981  5404  5450 I jxcore-log: 
09-22 09:49:03.982  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-22 09:49:03.982  5404  5450 I jxcore-log: 
,09-22 09:49:03.985  5404  5450 I jxcore-log: My device name is: Huawei-Nexus 6P
09-22 09:49:03.985  5404  5450 I jxcore-log: 
,09-22 09:49:03.986  5404  5450 I jxcore-log: 2016-09-22 13:49:03 - WARN testUtils: 'myNameCallback not set!'
09-22 09:49:03.986  5404  5450 I jxcore-log: 
09-22 09:49:03.987  5404  5450 I jxcore-log: Running for WIFI network type
09-22 09:49:03.987  5404  5450 I jxcore-log: 
,09-22 09:49:04.356  5404  5450 I jxcore-log: { [Error: Cannot find module './CoordinatedClient'] code: 'MODULE_NOT_FOUND' }
09-22 09:49:04.356  5404  5450 I jxcore-log: 
,09-22 09:49:04.358  5404  5450 E jxcore  : Error!: JXcore: Method Doesn't Exist [
09-22 09:49:04.358  5404  5450 E jxcore  : Stack: [{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"309","_columnNumber":"11","_msg":"    at JXMobile.executeJSON@main.js:309:11"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"main.js","_functionName":"unknown","_lineNumber":"309","_columnNumber":"11","_msg":""}]
,09-22 09:49:07.141   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335483, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-22 09:49:15.627   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:16.629   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:17.630   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:18.170   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:49:18.632   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:19.633   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:20.634   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-22 09:49:25.636   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:26.637   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:27.638   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:28.641   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:29.643   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:30.643   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-22 09:49:36.694   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=365037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-22 09:49:40.645   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:41.647   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:42.648   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:43.650   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:44.651   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:49:45.652   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-22 09:49:58.174   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:50:00.653   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:01.654   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:02.655   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:03.656   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:04.658   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:05.095   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=393438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-22 09:50:05.658   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-22 09:50:16.628   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404971, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-22 09:50:18.176   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:50:25.660   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:26.662   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:27.664   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:28.666   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:29.667   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:50:30.668   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 09:50:45.095   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=433438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-22 09:50:55.669   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-22 09:50:55.669   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-22 09:50:58.181   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:51:15.670   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:16.672   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:17.673   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:18.183   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:51:18.674   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:19.675   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:20.676   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-22 09:51:25.678   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:26.679   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:27.680   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:28.682   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:29.684   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:30.685   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-22 09:51:38.187   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:51:40.686   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:41.688   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:42.689   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:43.690   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:44.692   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:51:45.693   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-22 09:52:00.694   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:52:01.696   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:52:02.697   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:52:03.699   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:52:04.700   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:52:05.700   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-22 09:52:08.242   928  5718 D NetlinkSocketObserver: NeighborEvent{elapsedMs=516584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-22 09:52:18.191   928  2918 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 09:52:25.701   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 09:52:26.704   534   534 I ServiceManager: Waiting for service AtCmdFwd...

```
