#### Test 8746375758c0eee_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-03 03:40:23.527   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-03 03:40:23.527   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-03 03:40:24.051  5645  5645 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-03 03:40:24.056  5645  5645 D AndroidRuntime: CheckJNI is OFF
10-03 03:40:24.088  5645  5645 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-03 03:40:24.126  5645  5645 I Radio-JNI: register_android_hardware_Radio DONE
10-03 03:40:24.141  5645  5645 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-03 03:40:24.150   928  3657 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-03 03:40:24.204   928  3657 I ActivityManager: Start proc 5654:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-03 03:40:24.228  5645  5645 D AndroidRuntime: Shutting down VM
,10-03 03:40:24.540   928  3395 I WindowManager: Screenshot max retries 4 of Token{577a1c2 ActivityRecord{7598e0d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{69f71c5 u0 Starting com.test.thalitest} drawState=2
,10-03 03:40:24.617  5654  5654 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-03 03:40:24.651  5654  5654 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-03 03:40:24.678  5654  5654 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9974-9993)
10-03 03:40:24.678  5654  5654 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-03 03:40:24.697  5654  5654 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {497d1b7}
,10-03 03:40:24.698  5654  5654 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-03 03:40:24.698  5654  5654 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-03 03:40:24.703  5654  5654 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-03 03:40:24.707  5654  5654 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-03 03:40:24.741  5654  5654 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-03 03:40:24.755  5654  5654 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-03 03:40:24.755  5654  5654 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-03 03:40:24.756  5654  5654 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-03 03:40:24.756  5654  5654 I Adreno  : Build Date                       : 12/06/15
10-03 03:40:24.756  5654  5654 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-03 03:40:24.756  5654  5654 I Adreno  : Local Branch                     : mybranch17112971
10-03 03:40:24.756  5654  5654 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-03 03:40:24.756  5654  5654 I Adreno  : Remote Branch                    : NONE
10-03 03:40:24.756  5654  5654 I Adreno  : Reconstruct Branch               : NOTHING
,10-03 03:40:24.816   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a7040:true
,10-03 03:40:24.848  2618  2618 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34052]" dev="sockfs" ino=34052 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-03 03:40:24.848  2618  2618 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34052]" dev="sockfs" ino=34052 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-03 03:40:24.864  5654  5654 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-03 03:40:24.874  5654  5654 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-03 03:40:24.898  2618  2618 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34937]" dev="sockfs" ino=34937 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-03 03:40:24.898  2618  2618 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34937]" dev="sockfs" ino=34937 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-03 03:40:24.903  5654  5691 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-03 03:40:24.901  3581  3581 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15034]" dev="sockfs" ino=15034 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-03 03:40:24.901  3581  3581 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15034]" dev="sockfs" ino=15034 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-03 03:40:24.909  5654  5678 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-03 03:40:24.928  5654  5691 I OpenGLRenderer: Initialized EGL, version 1.4
,10-03 03:40:25.000   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +455ms (total +826ms)
,10-03 03:40:25.042  5654  5654 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5654
,10-03 03:40:25.129  5654  5654 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-03 03:40:25.240  5654  5693 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -578029264
,10-03 03:40:25.244  5654  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-03 03:40:25.244  5654  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-03 03:40:25.244  5654  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-03 03:40:25.244  5654  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-03 03:40:25.244  5654  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-03 03:40:25.244  5654  5693 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7ed57c added. We now have 1 listener(s)
,10-03 03:40:25.247  5654  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-03 03:40:25.247  5654  5693 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-03 03:40:25.247  5654  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:40:25.248  5654  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-03 03:40:25.249  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-03 03:40:25.250  5654  5693 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f04288b added. We now have 1 listener(s)
10-03 03:40:25.250  5654  5693 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:40:25.254   928  2936 D WifiService: New client listening to asynchronous messages
,10-03 03:40:25.255  5654  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-03 03:40:25.255  5654  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-03 03:40:25.255  5654  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-03 03:40:25.255  5654  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,10-03 03:40:25.255  5654  5693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-03 03:40:25.256  5654  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:25.256  5654  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-03 03:40:25.260  5654  5693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:25.261  5654  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:40:25.261  5654  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-03 03:40:25.261  5654  5693 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:40:25.261  5654  5693 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-03 03:40:25.265  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:40:25.267  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:40:25.276  5654  5654 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-03 03:40:25.559  5654  5700 W jxcore-log: Initializing JXcore engine
10-03 03:40:25.559  5654  5700 W jxcore-log: JXcore engine is ready
,10-03 03:40:25.581  5700  5700 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12625 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-03 03:40:25.581  5700  5700 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13434]" dev="sockfs" ino=13434 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-03 03:40:25.581  5700  5700 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-03 03:40:25.581  5700  5700 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34909]" dev="sockfs" ino=34909 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-03 03:40:25.593  5654  5700 W jxcore-log: Starting JXcore engine
,10-03 03:40:25.641   928  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-03 03:40:25.651  5654  5700 W jxcore-log: Platform android
10-03 03:40:25.651  5654  5700 W jxcore-log: 
,10-03 03:40:25.651  5654  5700 W jxcore-log: Process ARCH arm
10-03 03:40:25.651  5654  5700 W jxcore-log: 
,10-03 03:40:25.749  5654  5700 I jxcore-log: JXcore Cordova bridge is ready!
10-03 03:40:25.749  5654  5700 I jxcore-log: 
,10-03 03:40:25.749  5654  5700 W jxcore-log: JXcore engine is started
,10-03 03:40:25.758  5654  5693 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-03 03:40:25.762  5654  5654 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-03 03:40:33.528   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:34.529   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:35.472  5654  5700 I jxcore-log: 2016-10-03 07:40:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-03 03:40:35.472  5654  5700 I jxcore-log: 
,10-03 03:40:35.474  5654  5700 I jxcore-log: 2016-10-03 07:40:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-03 03:40:35.474  5654  5700 I jxcore-log: 
,10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:35.479  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:40:35.480  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.481  5654  5700 I jxcore-log: 2016-10-03 07:40:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-03 03:40:35.481  5654  5700 I jxcore-log: 
,10-03 03:40:35.483  5654  5700 I jxcore-log: 2016-10-03 07:40:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-03 03:40:35.483  5654  5700 I jxcore-log: 
,10-03 03:40:35.530   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:35.728  5654  5700 I jxcore-log: 2016-10-03 07:40:35 - DEBUG UnitTest_app: 'Running unit tests'
10-03 03:40:35.728  5654  5700 I jxcore-log: 
,10-03 03:40:35.728  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-03 03:40:35.728  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d682af added. We now have 2 listener(s)
,10-03 03:40:35.729  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:40:35.729  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:40:35.729  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:40:35.729  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:40:35.730  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38126bc added. We now have 2 listener(s)
10-03 03:40:35.730  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:40:35.730  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-03 03:40:35.732  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:35.735  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:40:35.736  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.736  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:40:35.737  5654  5700 D executeNativeTests: Running unit tests
,10-03 03:40:35.743  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:40:35.750  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:40:35.776  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-03 03:40:35.776  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a added. We now have 3 listener(s)
10-03 03:40:35.777  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:40:35.777  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-03 03:40:35.777  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:40:35.777  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:40:35.777  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb added. We now have 3 listener(s)
10-03 03:40:35.777  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:40:35.777  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-03 03:40:35.779  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:35.781  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:40:35.782  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.782  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:40:35.783  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-03 03:40:35.783  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-03 03:40:35.783  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-03 03:40:35.783  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-03 03:40:35.784  5654  5700 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-03 03:40:35.784  5654  5700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-03 03:40:35.784  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-03 03:40:35.784  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-03 03:40:35.784  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-03 03:40:35.784  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-03 03:40:35.785  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:35.785  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:35.785  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:35.786  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-03 03:40:35.786  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.786  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:40:35.786  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:35.786  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:40:35.786  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a removed from the list
,10-03 03:40:35.786  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:35.786  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb removed from the list
10-03 03:40:35.791  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:40:35.797  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:40:35.798  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:35.798  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.798  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.798  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:35.799  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:35.799  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:35.799  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:35.799  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:35.800  5654  5700 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-03 03:40:35.800  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:35.800  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:35.800  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:35.800  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:35.800  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.800  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.800  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:35.800  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:35.800  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:35.800  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:35.800  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:35.800  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.800  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.800  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.800  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.801  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:35.801  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:35.801  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:35.801  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-03 03:40:35.804  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-03 03:40:35.805  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:35.805  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:35.805  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:35.805  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:35.805  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.805  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.805  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:35.805  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:35.805  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:35.805  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:35.805  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:35.805  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.805  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.805  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:35.805  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:35.806  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:35.806  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:35.806  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:35.806  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:35.806  5654  5700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-03 03:40:35.807  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:35.809  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:40:35.811  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:35.811  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:40:35.812  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:40:35.812  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-03 03:40:35.812  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-03 03:40:35.812  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:35.812  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-03 03:40:35.815  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:40:35.816  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-03 03:40:35.816  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-03 03:40:35.818  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:40:35.819  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-03 03:40:35.819  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-03 03:40:35.820  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-03 03:40:35.821  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-03 03:40:35.822  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-03 03:40:35.822  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-03 03:40:35.822  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-03 03:40:35.822  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-03 03:40:35.822  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-03 03:40:35.822  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-03 03:40:35.823  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:40:35.825  4602  4827 D BtGatt.GattService: registerClient() - UUID=b0961b68-9356-48b2-8c0f-b8b9afcac7ff
10-03 03:40:35.826  4602  4663 D BtGatt.GattService: onClientRegistered() - UUID=b0961b68-9356-48b2-8c0f-b8b9afcac7ff, clientIf=5
10-03 03:40:35.827  5654  5664 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-03 03:40:35.829  4602  4615 D BtGatt.GattService: start scan with filters
10-03 03:40:35.833  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-03 03:40:35.834  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-03 03:40:35.834  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:40:35.834  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-03 03:40:35.834  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-03 03:40:35.834  4602  4669 D BtGatt.ScanManager: handling starting scan
10-03 03:40:35.834  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-03 03:40:35.834  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-03 03:40:35.837  4602  4669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:40:35.838  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-03 03:40:35.838  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-03 03:40:35.839  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-03 03:40:35.839  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-03 03:40:35.842  5654  5700 I io.jxcore.node.ConnectionHelper: start: OK
10-03 03:40:35.847  4602  4663 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-03 03:40:35.847  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:35.848  4602  4669 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-03 03:40:35.854  4602  4663 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-03 03:40:35.854  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:35.855  4602  4669 D BtGatt.ScanManager: Starting BLE batch scan
10-03 03:40:35.855  4602  4669 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-03 03:40:35.866  4602  4663 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-03 03:40:35.866  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:35.873  4602  4663 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-03 03:40:35.873  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:36.340  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-03 03:40:36.340  5654  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:40:36.341  5654  5654 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-03 03:40:36.374   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-03 03:40:36.531   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:37.532   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:38.533   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-03 03:40:39.402   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-03 03:40:40.846  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-03 03:40:40.846  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:40.846  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-03 03:40:40.846  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:40.846  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-03 03:40:40.847  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:40.847  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-03 03:40:40.847  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-03 03:40:40.847  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:40:40.847  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:40:40.848  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-03 03:40:40.848  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-03 03:40:40.849  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:40:40.850  4602  4827 D BtGatt.GattService: stopScan() - queue size =1
10-03 03:40:40.851  4602  4615 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-03 03:40:40.852  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-03 03:40:40.853  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-03 03:40:40.853  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-03 03:40:40.853  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:40:40.853  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-03 03:40:40.853  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-03 03:40:40.853  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-03 03:40:40.854  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-03 03:40:40.856  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:40:40.857  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-03 03:40:40.857  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-03 03:40:40.858  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-03 03:40:40.858  4602  4602 D BtGatt.ScanManager: awakened up at time 236174
10-03 03:40:40.858  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-03 03:40:40.861  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:40:40.864  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:40.864  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:40:40.864  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:40:40.864  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:40:40.864  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:40:40.864  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:40.864  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:40:40.864  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:40.864  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:40.865  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:40.865  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:40.865  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:40.867  4602  4663 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-03 03:40:40.867  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:40.868  4602  4669 D BtGatt.ScanManager: stopping BLe Batch
,10-03 03:40:40.876  4602  4663 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-03 03:40:40.876  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:40.877  4602  4669 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-03 03:40:40.902  4602  4663 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-03 03:40:40.903  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:40.903  4602  4663 D BtGatt.GattService: current time is 236219130593
10-03 03:40:40.904  4602  4663 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -74, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -76, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -74, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-03 03:40:40.905  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-03 03:40:40.907  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-03 03:40:40.907  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-03 03:40:40.907  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-03 03:40:40.908  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-03 03:40:41.366  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-03 03:40:43.536   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:44.537   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:45.463   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-03 03:40:45.538   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:45.866  5654  5700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-03 03:40:45.873  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:45.885  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:40:45.890  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-03 03:40:45.890  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:40:45.891  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:40:45.891  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-03 03:40:45.891  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-03 03:40:45.892  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:45.892  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-03 03:40:45.900  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:40:45.903  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-03 03:40:45.903  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-03 03:40:45.906  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:40:45.912  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-03 03:40:45.913  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-03 03:40:45.913  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-03 03:40:45.920  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-03 03:40:45.920  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-03 03:40:45.920  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-03 03:40:45.920  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-03 03:40:45.921  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-03 03:40:45.922  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:40:45.925  4602  4827 D BtGatt.GattService: registerClient() - UUID=b77f9216-fe18-4852-9663-f067607d6c76
10-03 03:40:45.926  4602  4663 D BtGatt.GattService: onClientRegistered() - UUID=b77f9216-fe18-4852-9663-f067607d6c76, clientIf=5
,10-03 03:40:45.927  5654  5665 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-03 03:40:45.928  4602  4615 D BtGatt.GattService: start scan with filters
,10-03 03:40:45.933  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-03 03:40:45.933  4602  4669 D BtGatt.ScanManager: handling starting scan
10-03 03:40:45.933  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-03 03:40:45.933  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:40:45.933  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-03 03:40:45.933  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-03 03:40:45.933  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-03 03:40:45.933  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-03 03:40:45.936  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:40:45.937  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-03 03:40:45.937  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:40:45.939  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-03 03:40:45.942  4602  4663 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-03 03:40:45.942  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:45.942  4602  4669 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-03 03:40:45.944  5654  5700 I io.jxcore.node.ConnectionHelper: start: OK
10-03 03:40:45.948  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:45.948  5654  5700 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-03 03:40:45.948  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:45.948  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-03 03:40:45.949  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:45.949  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-03 03:40:45.949  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:45.949  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-03 03:40:45.949  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-03 03:40:45.949  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:40:45.949  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:40:45.949  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-03 03:40:45.949  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-03 03:40:45.950  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:40:45.951  4602  4663 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-03 03:40:45.951  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:45.951  4602  4827 D BtGatt.GattService: stopScan() - queue size =1
10-03 03:40:45.951  4602  4669 D BtGatt.ScanManager: Starting BLE batch scan
10-03 03:40:45.951  4602  4669 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-03 03:40:45.952  4602  4615 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-03 03:40:45.952  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-03 03:40:45.952  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-03 03:40:45.953  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-03 03:40:45.953  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-03 03:40:45.953  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-03 03:40:45.953  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-03 03:40:45.953  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-03 03:40:45.953  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-03 03:40:45.954  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:40:45.954  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-03 03:40:45.955  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-03 03:40:45.955  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-03 03:40:45.955  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-03 03:40:45.955  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:40:45.958  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:40:45.958  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:45.958  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:45.958  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:40:45.958  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:40:45.958  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:40:45.958  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:45.958  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:45.958  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:45.958  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:45.958  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:45.958  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:45.959  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:45.959  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:45.960  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:45.960  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:45.961  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:45.961  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:45.962  5654  5700 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-03 03:40:45.964  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:45.966  4602  4663 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-03 03:40:45.966  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:40:45.970  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:40:45.973  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:40:45.973  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-03 03:40:45.973  4602  4663 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-03 03:40:45.973  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:45.973  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:40:45.973  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-03 03:40:45.973  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-03 03:40:45.973  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:40:45.974  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-03 03:40:45.977  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:40:45.981  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:40:45.982  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-03 03:40:45.982  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-03 03:40:45.984  4602  4663 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-03 03:40:45.984  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:45.984  4602  4669 D BtGatt.ScanManager: stopping BLe Batch
,10-03 03:40:45.986  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-03 03:40:45.987  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-03 03:40:45.987  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-03 03:40:45.990  4602  4663 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-03 03:40:45.990  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:45.990  4602  4669 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-03 03:40:45.991  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-03 03:40:45.991  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-03 03:40:45.991  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-03 03:40:45.991  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-03 03:40:45.991  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-03 03:40:45.992  5654  5700 D BluetoothAdapter: STATE_ON
,10-03 03:40:45.994  4602  4846 D BtGatt.GattService: registerClient() - UUID=24b12790-2a12-438b-be66-6b7a8021b240
10-03 03:40:45.994  4602  4663 D BtGatt.GattService: onClientRegistered() - UUID=24b12790-2a12-438b-be66-6b7a8021b240, clientIf=5
10-03 03:40:45.994  5654  5665 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-03 03:40:45.995  4602  4615 D BtGatt.GattService: start scan with filters
10-03 03:40:45.996  4602  4663 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-03 03:40:45.996  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:45.998  4602  4669 D BtGatt.ScanManager: handling starting scan
,10-03 03:40:45.998  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-03 03:40:45.999  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-03 03:40:45.999  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:40:45.999  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-03 03:40:45.999  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-03 03:40:45.999  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-03 03:40:45.999  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-03 03:40:46.001  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:40:46.001  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-03 03:40:46.001  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:40:46.002  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-03 03:40:46.004  4602  4663 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-03 03:40:46.004  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:46.005  4602  4669 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-03 03:40:46.005  5654  5700 I io.jxcore.node.ConnectionHelper: start: OK
,10-03 03:40:46.010  4602  4663 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-03 03:40:46.010  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:46.010  4602  4669 D BtGatt.ScanManager: Starting BLE batch scan
10-03 03:40:46.010  4602  4669 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-03 03:40:46.020  4602  4663 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-03 03:40:46.020  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:46.025  4602  4663 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-03 03:40:46.026  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:46.503  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-03 03:40:46.503  5654  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-03 03:40:46.503  5654  5654 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-03 03:40:46.539   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:47.540   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:48.493   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-03 03:40:48.541   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-03 03:40:51.006  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-03 03:40:51.006  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:51.006  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-03 03:40:51.007  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:51.007  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-03 03:40:51.007  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-03 03:40:51.007  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-03 03:40:51.007  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-03 03:40:51.007  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:40:51.008  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:40:51.008  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-03 03:40:51.008  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-03 03:40:51.010  5654  5700 D BluetoothAdapter: STATE_ON
,10-03 03:40:51.011  4602  4616 D BtGatt.GattService: stopScan() - queue size =1
10-03 03:40:51.014  4602  4846 D BtGatt.GattService: unregisterClient() - clientIf=5
10-03 03:40:51.015  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-03 03:40:51.015  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-03 03:40:51.015  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-03 03:40:51.015  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:40:51.015  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-03 03:40:51.015  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-03 03:40:51.016  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-03 03:40:51.016  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-03 03:40:51.018  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:40:51.019  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-03 03:40:51.019  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-03 03:40:51.019  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-03 03:40:51.019  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-03 03:40:51.020  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:40:51.023  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:40:51.023  4602  4602 D BtGatt.ScanManager: awakened up at time 246339
10-03 03:40:51.023  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:40:51.023  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-03 03:40:51.029  4602  4663 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-03 03:40:51.029  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:40:51.030  4602  4669 D BtGatt.ScanManager: stopping BLe Batch
,10-03 03:40:51.038  4602  4663 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-03 03:40:51.039  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:51.039  4602  4669 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-03 03:40:51.062  4602  4663 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-03 03:40:51.062  4602  4663 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:40:51.062  4602  4663 D BtGatt.GattService: current time is 246378369170
10-03 03:40:51.063  4602  4663 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -73, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 107, 58, 19, -9, 93, -60, 1, 0, -95, 78, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 81, 34, 97, 112, -14, -5, 1, -128, -81, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -73, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -76, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-03 03:40:51.063  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-03 03:40:51.063  4602  4663 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,10-03 03:40:51.063  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-03 03:40:51.063  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-03 03:40:51.064  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-03 03:40:51.064  4602  4663 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-03 03:40:51.524  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-03 03:40:51.524  5654  5654 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:51.525  5654  5654 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-03 03:40:56.024  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.024  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-03 03:40:56.025  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.025  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.025  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:40:56.025  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-03 03:40:56.025  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.025  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
,10-03 03:40:56.026  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.026  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.026  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.026  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.028  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.028  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:56.031  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.031  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.031  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.031  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
,10-03 03:40:56.033  5654  5700 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-03 03:40:56.034  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.035  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-03 03:40:56.035  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.035  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-03 03:40:56.035  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:40:56.035  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.035  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-03 03:40:56.036  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.036  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.036  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
,10-03 03:40:56.036  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.036  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.036  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.036  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:40:56.037  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.039  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.039  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.039  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:56.039  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.042  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-03 03:40:56.042  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.042  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-03 03:40:56.042  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.042  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.043  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.043  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.043  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-03 03:40:56.043  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.043  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.043  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.043  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.043  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.044  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.044  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.044  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:56.046  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.047  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.047  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.047  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.048  5654  5700 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-03 03:40:56.048  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.048  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:56.049  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.049  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-03 03:40:56.049  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.049  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.049  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.049  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.049  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.049  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.049  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.049  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.050  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:56.050  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.050  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.052  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.052  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.052  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:56.052  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.054  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-03 03:40:56.054  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.054  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:56.054  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.054  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.054  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.054  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:56.055  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.055  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.055  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:56.055  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
,10-03 03:40:56.055  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.055  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.055  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.055  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.055  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:56.057  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.057  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.057  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.057  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.059  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-03 03:40:56.059  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-03 03:40:56.059  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-03 03:40:56.059  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-03 03:40:56.059  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-03 03:40:56.059  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-03 03:40:56.060  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-03 03:40:56.060  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-03 03:40:56.060  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-03 03:40:56.060  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.060  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:56.060  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.060  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.060  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.061  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.061  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.061  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.061  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.061  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.061  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.061  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.061  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.061  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.,061  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.063  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.063  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-03 03:40:56.063  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.064  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.065  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-03 03:40:56.065  5654  5700 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-03 03:40:56.065  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-03 03:40:56.069  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-03 03:40:56.069  5654  5700 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-03 03:40:56.069  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-03 03:40:56.070  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-03 03:40:56.071  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-03 03:40:56.071  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-03 03:40:56.071  5654  5700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-03 03:40:56.072  5654  5700 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-03 03:40:56.072  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-03 03:40:56.072  5654  5700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-03 03:40:56.072  5654  5700 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-03 03:40:56.072  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-03 03:40:56.072  5654  5700 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-03 03:40:56.072  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-03 03:40:56.076  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-03 03:40:56.077  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-03 03:40:56.077  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,10-03 03:40:56.080  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-03 03:40:56.080  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-03 03:40:56.080  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-03 03:40:56.081  5654  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-03 03:40:56.081  5654  5700 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-03 03:40:56.081  5654  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,10-03 03:40:56.081  5654  5700 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-03 03:40:56.081  5654  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-03 03:40:56.081  5654  5701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-03 03:40:56.082  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.083  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-03 03:40:56.083  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.083  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.083  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.083  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.083  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.083  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-03 03:40:56.084  5654  5701 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,10-03 03:40:56.085  5654  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-03 03:40:56.085  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.085  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.085  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.085  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.085  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.085  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.085  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.085  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.085  5654  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-03 03:40:56.085  5654  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
10-03 03:40:56.085  5654  5702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,10-03 03:40:56.088  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:40:56.088  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.088  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.088  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.089  5654  5700 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-03 03:40:56.090  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.090  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:56.090  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.090  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.090  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.090  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.090  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-03 03:40:56.090  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.090  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.090  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.091  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.091  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.091  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.091  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:40:56.091  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.092  5654  5701 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-03 03:40:56.092  5654  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-03 03:40:56.092  5654  5701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
10-03 03:40:56.092  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.092  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.092  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.092  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.088  4846  4846 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34976]" dev="sockfs" ino=34976 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-03 03:40:56.088  4846  4846 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34976]" dev="sockfs" ino=34976 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-03 03:40:56.093  5654  5700 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-03 03:40:56.093  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.093  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:40:56.093  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.094  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.094  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.094  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.094  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.094  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.094  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:40:56.094  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.094  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.094  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.094  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.094  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.094  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.096  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.096  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.096  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.096  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.097  5654  5700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,10-03 03:40:56.097  5654  5700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-03 03:40:56.097  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-03 03:40:56.097  5654  5700 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-03 03:40:56.097  5654  5700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-03 03:40:56.097  5654  5700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-03 03:40:56.097  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-03 03:40:56.097  5654  5700 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-03 03:40:56.098  5654  5700 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-03 03:40:56.098  5654  5700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-03 03:40:56.098  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-03 03:40:56.098  5654  5700 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-03 03:40:56.098  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:40:56.098  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-03 03:40:56.098  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:40:56.098  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.098  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.099  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.099  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.099  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.099  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.099  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.099  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.099  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.099  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:56.099  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.099  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.100  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:40:56.100  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:40:56.100  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.101  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.101  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:40:56.101  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.101  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:40:56.102  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:40:56.102  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:40:56.102  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:40:56.102  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:40:56.102  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:40:56.102  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:40:56.102  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:40:57.576   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-03 03:40:58.542   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:40:59.543   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:00.544   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:01.103  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:01.103  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.103  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.103  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:41:01.103  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.104  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-03 03:41:01.104  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:41:01.104  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-03 03:41:01.104  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-03 03:41:01.105  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-03 03:41:01.105  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.105  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.105  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:01.105  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:41:01.105  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:41:01.106  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:01.106  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.106  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:01.106  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.106  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.107  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.107  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:01.111  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:41:01.111  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:41:01.112  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:01.112  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.117  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-03 03:41:01.118  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:41:01.121  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-03 03:41:01.123  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-03 03:41:01.123  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-03 03:41:01.123  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-03 03:41:01.123  5654  5703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-03 03:41:01.124  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-03 03:41:01.124  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-03 03:41:01.124  5654  5654 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-03 03:41:01.124  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.125  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-03 03:41:01.125  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-03 03:41:01.125  5654  5703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-03 03:41:01.125  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:41:01.125  5654  5654 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-03 03:41:01.125  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:01.125  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:41:01.125  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.125  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.128  5654  5703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-03 03:41:01.128  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-03 03:41:01.128  5654  5703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-03 03:41:01.128  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.128  5654  5703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-03 03:41:01.128  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:41:01.128  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:41:01.128  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-03 03:41:01.129  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:41:01.129  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:41:01.129  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:41:01.121  4616  4616 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34980]" dev="sockfs" ino=34980 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-03 03:41:01.129  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.129  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.129  5654  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-03 03:41:01.129  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.129  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:41:01.129  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
,10-03 03:41:01.129  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:01.129  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.129  5654  5654 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:41:01.121  4616  4616 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34980]" dev="sockfs" ino=34980 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-03 03:41:01.129  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
,10-03 03:41:01.130  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:41:01.130  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:01.130  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.130  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.132  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:41:01.132  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:41:01.132  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:01.132  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.134  5654  5700 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-03 03:41:01.134  5654  5700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-03 03:41:01.134  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-03 03:41:01.134  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-03 03:41:01.135  5654  5700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-03 03:41:01.135  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:41:01.135  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:41:01.135  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:41:01.135  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.135  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.135  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:01.135  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:41:01.135  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:41:01.135  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:01.135  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.135  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:01.135  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.136  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.136  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.136  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.137  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:41:01.138  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:41:01.138  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:01.138  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.144  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:41:01.144  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:41:01.144  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:41:01.145  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.145  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.145  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.145  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:41:01.145  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:41:01.145  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:01.145  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.145  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:01.145  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.145  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.145  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.145  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.147  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:41:01.147  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:41:01.147  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:01.147  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
,10-03 03:41:01.148  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:41:01.148  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:41:01.148  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:41:01.148  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:41:01.148  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.148  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:01.148  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:41:01.148  5654  5700 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86a154a not in the list
10-03 03:41:01.148  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:01.148  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
10-03 03:41:01.148  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:01.148  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.148  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.148  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:01.149  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:01.149  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:41:01.150  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:41:01.150  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:01.150  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e3ccbb not in the list
,10-03 03:41:01.151  5654  5700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-03 03:41:01.151  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-03 03:41:01.151  5654  5700 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-03 03:41:01.151  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-03 03:41:01.151  5654  5700 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-03 03:41:01.151  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-03 03:41:01.153  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-03 03:41:01.153  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-03 03:41:01.154  5654  5700 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-03 03:41:01.155  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-03 03:41:01.155  5654  5700 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-03 03:41:01.155  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-03 03:41:01.155  5654  5700 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-03 03:41:01.155  5654  5700 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-03 03:41:01.155  5654  5700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-03 03:41:01.155  5654  5700 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-03 03:41:01.156  5654  5700 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-03 03:41:01.156  5654  5700 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-03 03:41:01.156  5654  5700 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-03 03:41:01.156  5654  5700 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-03 03:41:01.157  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:41:01.157  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97cfb25 added. We now have 3 listener(s)
10-03 03:41:01.157  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:41:01.159  5654  5700 D BluetoothAdapter: enable(): BT is already enabled..!
10-03 03:41:01.159   928  3581 D WifiService: setWifiEnabled: true pid=5654, uid=10077
10-03 03:41:01.159   928  3581 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-03 03:41:01.214  4602  4819 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-03 03:41:01.214  4602  4824 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-03 03:41:01.545   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:01.630  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-03 03:41:02.546   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:03.546   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-03 03:41:03.631   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-03 03:41:05.644   928  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-03 03:41:06.166  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-03 03:41:06.166  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25a64fa added. We now have 4 listener(s)
,10-03 03:41:06.167  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:41:06.179  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:06.179  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25a64fa removed from the list
,10-03 03:41:06.179  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
,10-03 03:41:06.180  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:41:06.180  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:06.182  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:41:06.182  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9d5aab added. We now have 4 listener(s)
10-03 03:41:06.182  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:41:06.189  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:06.189  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9d5aab removed from the list
,10-03 03:41:06.189  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:06.189  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:06.189  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:06.190  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:41:06.191  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e1e508 added. We now have 4 listener(s)
10-03 03:41:06.191  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:41:06.195   928  3882 D WifiService: setWifiEnabled: false pid=5654, uid=10077
,10-03 03:41:06.195   928  3882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-03 03:41:06.199   928  2929 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-03 03:41:06.199   928  2929 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-03 03:41:06.200   928  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-03 03:41:06.200   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:06.205  4602  4659 D BluetoothAdapterState: Current state: ON, message: 23
,10-03 03:41:06.206  4602  4659 D BluetoothAdapterProperties: Setting state to 13
10-03 03:41:06.206  4602  4659 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-03 03:41:06.207  4602  4659 D BluetoothAdapterProperties: onBluetoothDisable()
10-03 03:41:06.208  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:41:06.210  4602  4659 I BluetoothAdapterState: Entering PendingCommandState
,10-03 03:41:06.213  4602  4663 D BluetoothAdapterProperties: Scan Mode:20
10-03 03:41:06.213  4602  4659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-03 03:41:06.214  4602  4602 D BluetoothMapService: onReceive
10-03 03:41:06.214  4602  4602 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-03 03:41:06.214  4602  4602 D BluetoothMapService: STATE_TURNING_OFF
10-03 03:41:06.215  4602  4602 D BluetoothMapService: MAP Service closeService in
10-03 03:41:06.215  4602  4602 D BluetoothMapMasInstance0: MAP Service shutdown
10-03 03:41:06.215  4602  4602 D ObexServerSockets0: shutdown(block = true)
10-03 03:41:06.216  4602  4602 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-03 03:41:06.216  4602  4602 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-03 03:41:06.216  4602  4847 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-03 03:41:06.216  4602  4824 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-03 03:41:06.217  4602  4848 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-03 03:41:06.219  4602  4602 I BtOppRfcommListener: stopping Accept Thread
10-03 03:41:06.219  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:06.219  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:41:06.219  4602  5315 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-03 03:41:06.220  4602  5315 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-03 03:41:06.220   928  5349 D DhcpClient: Clearing IP address
10-03 03:41:06.220  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.220  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-03 03:41:06.220   506   926 D CommandListener: Clearing all IP addresses on wlan0
10-03 03:41:06.221  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:41:06.224  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:06.228  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.231   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:06.232  3565  5405 V NativeCrypto: Read error: ssl=0x7f84605000: I/O error during system call, Connection timed out
10-03 03:41:06.234  3565  5405 V NativeCrypto: SSL shutdown failed: ssl=0x7f84605000: I/O error during system call, Broken pipe
10-03 03:41:06.235  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:06.236  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:06.236   928  3135 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-03 03:41:06.236  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.237  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:06.237   928  5347 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-03 03:41:06.238   928   941 I ActivityManager: Start proc 5707:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-03 03:41:06.241  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:06.241  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:06.242  4602  4602 D HeadsetService: Received stop request...Stopping profile...
10-03 03:41:06.243  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.243  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:06.244   928   928 D BluetoothHeadset: Proxy object disconnected
,10-03 03:41:06.246  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.246  3110  3123 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:06.246  3110  3110 D HeadsetProfile: Bluetooth service disconnected
10-03 03:41:06.246   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-03 03:41:06.246   928   928 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:06.246   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-03 03:41:06.247  3790  4048 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:06.247   928   928 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:06.248   928  5347 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-03 03:41:06.249  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:06.249  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:06.251   532   532 E Parcel  : Reading a NULL string not supported here.
10-03 03:41:06.251  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.251  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:06.253   928   928 D RttService: SCAN_AVAILABLE : 1
,10-03 03:41:06.253   928  3064 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-03 03:41:06.254  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.254  4602  4602 D A2dpService: Received stop request...Stopping profile...
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.254  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:06.254  4602  4829 D A2dpStateMachine: Exit Disconnected: -1
10-03 03:41:06.255  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.255  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:06.256  4602  4602 D HidService: Received stop request...Stopping profile...
10-03 03:41:06.256  4602  4602 D HidService: Stopping Bluetooth HidService
10-03 03:41:06.256   928  2941 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-03 03:41:06.257  3110  3110 D BluetoothA2dp: Proxy object disconnected
10-03 03:41:06.257  3110  3110 D BluetoothInputDevice: Proxy object disconnected
10-03 03:41:06.257  3110  3110 D HidProfile: Bluetooth service disconnected
10-03 03:41:06.257   928   928 D BluetoothA2dp: Proxy object disconnected
10-03 03:41:06.257  3737  3889 W QCNEJ   : |CORE| network lost: 100
10-03 03:41:06.258  3737  3889 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-03 03:41:06.258  4602  4602 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:06.258  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.258  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.258  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:06.258  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.258  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.259  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.259  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:06.260  4602  4602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-03 03:41:06.261  4602  4819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:06.261  4602  4819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:06.261  4602  4819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:06.262  4602  4663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-03 03:41:06.262  4602  4663 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-03 03:41:06.262  4602  4602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-03 03:41:06.264  4602  4602 D HealthService: Received stop request...Stopping profile...
,10-03 03:41:06.265  4602  4602 D PanService: Received stop request...Stopping profile...
,10-03 03:41:06.266  4602  4602 D BluetoothMapService: Received stop request...Stopping profile...
10-03 03:41:06.266  4602  4602 D BluetoothMapService: stop()
10-03 03:41:06.266  4602  4602 D BluetoothMapAppObserver: deinitObservers()
10-03 03:41:06.266  4602  4602 D BluetoothMapAppObserver: removeReceiver()
10-03 03:41:06.267  4602  4602 D SapService: Received stop request...Stopping profile...
10-03 03:41:06.267  4602  4602 V SapService: stop()
,10-03 03:41:06.268  4602  4602 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:06.268  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.268  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.268  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.269  4602  4819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:06.269  4602  4602 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:06.269  4602  4819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:06.269  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.269  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.269  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.270  4602  4819 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-03 03:41:06.270  4602  4819 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-03 03:41:06.270  4602  4602 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-03 03:41:06.270  4602  4819 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-03 03:41:06.270  4602  4602 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-03 03:41:06.270  4602  4819 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-03 03:41:06.270  4602  4663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.270  4602  4663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.270  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.270  4602  4602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-03 03:41:06.270  4602  4663 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-03 03:41:06.271  4602  4602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-03 03:41:06.271   928  5350 D DhcpClient: Receive thread stopped
10-03 03:41:06.271  4602  4602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-03 03:41:06.271  4602  4602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-03 03:41:06.271  4602  4602 D BluetoothMapService: MAP Service closeService in
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isTurningOff()=true
,10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.272  4602  4602 D BluetoothMapService: cleanup()
10-03 03:41:06.272  4602  4602 D BluetoothMapService: MAP Service closeService in
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.272  4602  4602 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:06.272  4602  4659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-03 03:41:06.272  4602  4659 D BluetoothAdapterProperties: Setting state to 15
10-03 03:41:06.272  4602  4659 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-03 03:41:06.273  4602  4659 I BluetoothAdapterState: Entering BleOnState
,10-03 03:41:06.273  3110  3951 D BluetoothPan: onBluetoothStateChange on: false
10-03 03:41:06.274  3110  3123 D BluetoothA2dp: onBluetoothStateChange: up=false
10-03 03:41:06.274  3110  3125 D BluetoothMap: onBluetoothStateChange: up=false
10-03 03:41:06.275   928  2929 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-03 03:41:06.277  3110  3951 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-03 03:41:06.278   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-03 03:41:06.278  3790  3820 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:06.278  3110  3123 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:06.278   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:06.279   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-03 03:41:06.279   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:06.279  3110  3125 D BluetoothPbap: onBluetoothStateChange: up=false
10-03 03:41:06.280  4602  4659 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-03 03:41:06.280  4602  4659 D BluetoothAdapterProperties: Setting state to 16
10-03 03:41:06.280  4602  4659 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-03 03:41:06.281  4602  4659 D BluetoothAdapterProperties: onBleDisable
10-03 03:41:06.281  4602  4659 I BluetoothAdapterState: Entering PendingCommandState
10-03 03:41:06.281  4602  4660 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-03 03:41:06.281  4602  4663 D BluetoothAdapterProperties: Scan Mode:20
10-03 03:41:06.283  4602  4819 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-03 03:41:06.283  4602  4819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:06.285   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-03 03:41:06.286  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.286  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:06.289   928  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-03 03:41:06.295  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.295  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:06.297  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.298  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-03 03:41:06.299  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.300  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.301  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.304  5707  5707 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-03 03:41:06.307   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-03 03:41:06.308   506   926 D CommandListener: Clearing all IP addresses on wlan0
10-03 03:41:06.308   506   926 D TetherController: Setting IP forward enable = 0
,10-03 03:41:06.309   928  2941 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,10-03 03:41:06.309   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-03 03:41:06.311   928   945 D Tethering: MasterInitialState.processMessage what=3
10-03 03:41:06.312   928  2929 D DhcpClient: doQuit
10-03 03:41:06.312   928  2929 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-03 03:41:06.313  3433  3433 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-03 03:41:06.313  5252  5252 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8478a13 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-03 03:41:06.313  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.313   928  5349 D DhcpClient: onQuitting
,10-03 03:41:06.316  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.317  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:06.317  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.317  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:06.319  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.319  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:06.319  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.319  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:06.320  5021  5034 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-03 03:41:06.320  5021  5034 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-03 03:41:06.320  5021  5034 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-03 03:41:06.320  5021  5034 E SarControlService: no key has been found,reset the power
,10-03 03:41:06.320  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-03 03:41:06.320  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-03 03:41:06.320  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-03 03:41:06.321  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.321  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:06.321  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:06.321  5047  5047 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-03 03:41:06.322  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:06.322  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:06.323  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.324  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.324  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-03 03:41:06.324  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-03 03:41:06.324  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-03 03:41:06.325  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:06.326  5047  5047 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-03 03:41:06.328  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000ea03000000000000ffffffff]
10-03 03:41:06.328  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:06.328  5047  5061 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-03 03:41:06.328  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-03 03:41:06.329  5021  5032 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-03 03:41:06.335  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000eb03000000000000ffffffff]
,10-03 03:41:06.335  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:06.335  5047  5061 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-03 03:41:06.335  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-03 03:41:06.336  5021  5031 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-03 03:41:06.337  3433  3433 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-03 03:41:06.340  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-03 03:41:06.341  3433  3433 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-03 03:41:06.350   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4a758e8:true
,10-03 03:41:06.351  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-03 03:41:06.353   506   926 E Netd    : netlink response contains error (No such file or directory)
,10-03 03:41:06.353   506   926 D TetherController: Setting IP forward enable = 0
10-03 03:41:06.354   928  2941 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-03 03:41:06.354   928  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-03 03:41:06.364   928   938 I ActivityManager: Start proc 5738:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-03 03:41:06.366  3433  3433 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-03 03:41:06.378  5707  5707 D LocalBluetoothProfileManager: Adding local MAP profile
,10-03 03:41:06.382  5707  5707 D BluetoothMap: Create BluetoothMap proxy object
,10-03 03:41:06.390  5707  5707 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-03 03:41:06.395  3433  3433 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-03 03:41:06.410  5707  5707 D DockEventReceiver: finishStartingService: stopping service
,10-03 03:41:06.413  5738  5738 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-03 03:41:06.416   928  3882 I ActivityManager: Killing 4985:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-03 03:41:06.490  4602  4663 I bt_hci  : shut_down
,10-03 03:41:06.494  4602  4672 D bt_hwcfg: hw_epilog_process
,10-03 03:41:06.494  4602  4672 I bt_vendor: low_power_mode_cb
,10-03 03:41:06.497  4602  4672 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-03 03:41:06.497  4602  4672 I bt_vendor: epilog_cb
10-03 03:41:06.497  4602  4672 I bt_hci  : epilog_finished_callback
10-03 03:41:06.498   928  2929 D wifi    : In wifi stop Hal
,10-03 03:41:06.498  4401  4401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-03 03:41:06.498   928  2929 D wifi    : halHandle = 0x7f6e003b80, mVM = 0x7f8a68d140, mCls = 0x100a02
,10-03 03:41:06.499   928  3432 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-03 03:41:06.499   928  3432 D WifiHAL : Got a signal to exit!!!
10-03 03:41:06.499   928  3432 I WifiHAL : Exit wifi_event_loop
10-03 03:41:06.499   928  2929 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-03 03:41:06.499   928  2929 E WifiHAL : Event processing terminated
10-03 03:41:06.500   928  2929 D wifi    : In wifi cleaned up handler
10-03 03:41:06.500   928  2929 I WifiHAL : Internal cleanup completed
10-03 03:41:06.500  4602  4663 I bt_hci_h4: hal_close
10-03 03:41:06.501  3714  4179 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-03 03:41:06.501  4602  4663 I bt_userial_vendor: device fd = 54 close
,10-03 03:41:06.502  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:06.503  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:06.505  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:06.520   928  3432 D wifi    : set interface wlan0 flags (DOWN)
,10-03 03:41:06.520   928  2929 D WifiNative-HAL: HAL event thread stopped successfully
,10-03 03:41:06.609  4602  4660 D bt_stack_manager: event_shut_down_stack finished.
,10-03 03:41:06.610  4602  4659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-03 03:41:06.611  4602  4602 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-03 03:41:06.611  4602  4659 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-03 03:41:06.612  4602  4602 D BtGatt.GattService: Received stop request...Stopping profile...
10-03 03:41:06.612  5738  5738 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.File.exists(File.java:361)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.612  4602  4602 D BtGatt.GattService: stop()
10-03 03:41:06.612  4602  4602 D BtGatt.AdvertiseManager: advertise clients cleared
10-03 03:41:06.612  5738  5738 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-03 03:41:06.612  5738  5738 D StrictMode,: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.612  5738  5738 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.612  5738  5738 D Stric,tMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.612  5738  5738 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.e.b(PG:170)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.612  5738  5738 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.k.d(PG:583)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.e.b(PG:170)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.612  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.613  5738  5738 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.io.File.exists(File.java:361)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.613  5738  5738 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.io.File.exists(File.java:361)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.613  5738  5738 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:41:06.613  5738  5738 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:41:06.613  4602  4602 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:06.613  4602  4602 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:06.613  4602  4602 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:06.613  4602  4602 V BluetoothAdapterState: isBleTurningOff()=true
10-03 03:41:06.614  4602  4659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-03 03:41:06.614  4602  4659 D BluetoothAdapterProperties: Setting state to 10
10-03 03:41:06.614  4602  4659 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-03 03:41:06.615  4602  4659 I BluetoothAdapterState: Entering OffState
10-03 03:41:06.616   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-03 03:41:06.623  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-03 03:41:06.625  4602  4602 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-03 03:41:06.625  4602  4602 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-03 03:41:06.625  4602  4602 I BluetoothServiceJni: cleanupNative: return from cleanup
10-03 03:41:06.627  4602  4660 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-03 03:41:06.639  4602  4660 D bt_stack_manager: event_clean_up_stack finished.
,10-03 03:41:06.654  4602  4602 I art     : System.exit called, status: 0
10-03 03:41:06.654  4602  4602 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-03 03:41:06.659  5707  5707 D DockEventReceiver: finishStartingService: stopping service
10-03 03:41:06.660   928  3797 I ActivityManager: Killing 5095:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-03 03:41:06.699   928  3135 I ActivityManager: Process com.android.bluetooth (pid 4602) has died
,10-03 03:41:06.702  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-03 03:41:06.714   928  3657 I ActivityManager: Start proc 5771:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-03 03:41:06.724   928   945 D Tethering: InitialState.processMessage what=4
,10-03 03:41:06.728   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-03 03:41:06.787  5771  5771 D AdapterServiceConfig: Adding HeadsetService
,10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding A2dpService
10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding HidService
10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding HealthService
10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding PanService
10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding GattService
10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding BluetoothMapService
,10-03 03:41:06.788  5771  5771 D AdapterServiceConfig: Adding SapService
10-03 03:41:06.792   928  3882 I ActivityManager: Killing 5427:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-03 03:41:06.822  3984  3984 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-03 03:41:06.825  3984  3984 D SystemUpdateService: onCreate
,10-03 03:41:06.829  3984  3984 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-03 03:41:06.836  3984  3984 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-03 03:41:06.845  3984  5783 I SystemUpdateService: active receiver: enabled
,10-03 03:41:06.852  3984  3984 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-03 03:41:06.853  3984  3984 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-03 03:41:06.857  3984  5376 I iu.UploadsManager: num queued entries: 0
,10-03 03:41:06.858  3984  5376 I iu.UploadsManager: num updated entries: 0
10-03 03:41:06.859  3984  5376 I iu.SyncManager: NEXT; no task
,10-03 03:41:06.861  3984  5783 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-03 03:41:06.865   928  3875 I ActivityManager: Start proc 5785:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-03 03:41:06.874  3984  5783 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-03 03:41:06.876  3984  5783 I SystemUpdateService: now status is 0 (complete)
10-03 03:41:06.876  3984  5783 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-03 03:41:06.876  3984  5783 I SystemUpdateService: file has been verified
10-03 03:41:06.876  3984  5783 I SystemUpdateService: OTA package size = 21989297
,10-03 03:41:06.898  3984  5783 I SystemUpdateService: showing system update notification
,10-03 03:41:06.899  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-03 03:41:06.902  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-03 03:41:06.916  5785  5785 D SprintDMHelper: simOperator: 
,10-03 03:41:06.916  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-03 03:41:06.929   928  3396 I ActivityManager: Start proc 5797:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-03 03:41:06.942  3984  3984 D SystemUpdateService: onDestroy
,10-03 03:41:06.945   928  3135 I ActivityManager: Killing 5409:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-03 03:41:07.046  4401  5811 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-03 03:41:07.052   928  3396 I ActivityManager: Start proc 5812:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-03 03:41:07.054   928  3396 I ActivityManager: Killing 5252:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-03 03:41:07.111  5812  5812 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-03 03:41:07.160  5738  5763 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-03 03:41:07.278   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@185f3f4:true
,10-03 03:41:07.302   928  3795 I ActivityManager: Killing 4685:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-03 03:41:07.344   928  3135 I ActivityManager: Start proc 5826:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-03 03:41:07.376  5826  5826 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-03 03:41:07.383   928  3875 I ActivityManager: Killing 5512:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-03 03:41:11.227   928  3882 D WifiService: setWifiEnabled: true pid=5654, uid=10077
10-03 03:41:11.227   928  3882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-03 03:41:11.237   506   926 D SoftapController: Softap fwReload - Ok
,10-03 03:41:11.241   506   926 D CommandListener: Setting iface cfg
10-03 03:41:11.241   506   926 D CommandListener: Trying to bring down wlan0
10-03 03:41:11.242   506   926 D CommandListener: Clearing all IP addresses on wlan0
,10-03 03:41:11.247   928  2929 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-03 03:41:11.817   928  2929 D wifi    : set interface wlan0 flags (UP)
,10-03 03:41:11.821   928  2929 I WifiHAL : Initializing wifi
,10-03 03:41:11.821   928  2929 I WifiHAL : Creating socket
10-03 03:41:11.822   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-03 03:41:11.826   928  2929 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-03 03:41:11.826   928  2929 D wifi    : Did set static halHandle = 0x7f6e003b80
,10-03 03:41:11.826   928  2929 D wifi    : halHandle = 0x7f6e003b80, mVM = 0x7f8a68d140, mCls = 0x1942
,10-03 03:41:11.827   928  2929 D wifi    : array field set
,10-03 03:41:11.827   928  2929 I WifiNative-HAL: interface[0] = wlan0
10-03 03:41:11.830   928  5844 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547306355584
10-03 03:41:11.830   928  5844 D wifi    : waitForHalEvents called, vm = 0x7f8a68d140, obj = 0x1942, env = 0x7f6e059880
,10-03 03:41:11.910  5845  5845 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-03 03:41:11.929  5845  5845 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-03 03:41:11.933   928  2929 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-03 03:41:11.935  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:11.936  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:11.937  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:11.962  5845  5845 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-03 03:41:11.963  5845  5845 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-03 03:41:11.977   928  2929 D WifiConfigStore: Loading config and enabling all networks 
,10-03 03:41:11.978  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:11.978  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:11.978  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:11.978  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:11.980  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:11.980  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:11.980  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:11.980  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:11.982  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:11.982  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:11.982  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:11.982  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:11.986   928  2929 D WifiConfigStore: loaded 0 passpoint configs
,10-03 03:41:11.987   928  2929 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-03 03:41:11.987   928  2929 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-03 03:41:11.988   928  2929 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-03 03:41:11.989   928  2929 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-03 03:41:11.990   928  2929 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-03 03:41:11.990   928  2929 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-03 03:41:11.990   928  2929 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-03 03:41:11.994   928  2929 D WifiNative-HAL: Setting external_sim to 1
,10-03 03:41:11.994  4401  4401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-03 03:41:11.995   928  2929 D wifi    : setting dfs flag to true, 0x7f71fffc00
,10-03 03:41:11.995   928  2929 D WifiStateMachine: Setting OUI to DA-A1-19
10-03 03:41:11.995   928  2929 D wifi    : setting scan oui 0x7f71fffc00
10-03 03:41:11.995   928  2929 D WifiHAL : Sending mac address OUI
,10-03 03:41:12.000   928  2929 E native  : do suspend false
,10-03 03:41:12.008   928   928 D RttService: SCAN_AVAILABLE : 3
,10-03 03:41:12.008   928  2929 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-03 03:41:12.008   506   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-03 03:41:12.009   928  3064 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-03 03:41:12.009   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:12.013   928  2928 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-03 03:41:12.013   928  2928 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-03 03:41:12.023   928  2928 D WifiNative-HAL: p2pGetDeviceAddress
,10-03 03:41:12.027   928  2928 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-03 03:41:12.027   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267343 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-03 03:41:15.164  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:15.168  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:15.175  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:15.228   928  2929 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-03 03:41:15.229   928  2929 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-03 03:41:15.229   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:15.240   928  2929 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-03 03:41:15.272   928  2929 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-03 03:41:15.273  5845  5845 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-03 03:41:15.715  5845  5845 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-03 03:41:15.749  5845  5845 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-03 03:41:15.750  5845  5845 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-03 03:41:15.764   928  2929 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-03 03:41:15.764   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:15.764   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-03 03:41:15.785   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:15.798   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:15.804   928  2929 D WifiStateMachine: Start Dhcp Watchdog 2
,10-03 03:41:15.812   928  5853 D DhcpClient: Receive thread started
,10-03 03:41:15.816   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-03 03:41:15.816   928  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-03 03:41:15.816   928  2941 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-03 03:41:15.896   928  2929 E native  : do suspend false
,10-03 03:41:15.909   928  5852 D DhcpClient: Broadcasting DHCPDISCOVER
,10-03 03:41:15.921   928  5853 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,10-03 03:41:15.922   928  5852 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,10-03 03:41:15.924   928  5852 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-03 03:41:15.950   928  5853 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-03 03:41:15.952   928  5852 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-03 03:41:15.955   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:15.960   928  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-03 03:41:15.964   928  5852 D DhcpClient: Scheduling renewal in 86399s
,10-03 03:41:15.975   928  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-03 03:41:15.977   928  2929 D WifiConfigStore: No blacklist allowed without epno enabled
10-03 03:41:15.978   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-03 03:41:15.979   928  2941 D ConnectivityService: Adding iface wlan0 to network 101
,10-03 03:41:15.984   928  2929 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-03 03:41:16.032   928  2941 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-03 03:41:16.032   928  2941 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-03 03:41:16.035   928  2941 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-03 03:41:16.040   928  2941 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
10-03 03:41:16.042   928  2941 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-03 03:41:16.049   928  2941 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-03 03:41:16.053   928  2941 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-03 03:41:16.054   928  2941 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-03 03:41:16.054   928  2941 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-03 03:41:16.054   928  2941 D ConnectivityService:    accepting network in place of null
10-03 03:41:16.054   928  2929 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-03 03:41:16.054   928  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-03 03:41:16.055   928  2941 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-03 03:41:16.074   928  5851 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271390, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-03 03:41:16.077   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-03 03:41:16.099   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-03 03:41:16.102   928  2941 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-03 03:41:16.102  3737  3889 W QCNEJ   : |CORE| network available: 101
10-03 03:41:16.102   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-03 03:41:16.104   928  2941 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-03 03:41:16.104   928   945 D Tethering: MasterInitialState.processMessage what=3
10-03 03:41:16.106  3737  3889 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-03 03:41:16.107  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:16.108  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:16.108  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.108  3737  3889 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-03 03:41:16.108  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:16.108  3737  3889 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-03 03:41:16.111  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:16.112  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:16.112  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.112  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:16.115  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:16.115  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:16.115  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.115  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-03 03:41:16.118  3984  3984 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-03 03:41:16.120  5021  5034 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-03 03:41:16.120  5021  5034 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-03 03:41:16.120  5021  5034 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-03 03:41:16.120  5021  5034 E SarControlService: no key has been found,reset the power
10-03 03:41:16.120  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-03 03:41:16.120  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-03 03:41:16.121  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-03 03:41:16.121  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:16.121  5047  5047 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-03 03:41:16.122  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-03 03:41:16.122  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-03 03:41:16.122  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-03 03:41:16.123  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:16.123  5047  5047 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-03 03:41:16.126  3984  3984 D SystemUpdateService: onCreate
,10-03 03:41:16.128  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000ec03000000000000ffffffff]
,10-03 03:41:16.128  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:16.128  5047  5061 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-03 03:41:16.128  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000ed03000000000000ffffffff]
10-03 03:41:16.128  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:16.128  5047  5061 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-03 03:41:16.129  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-03 03:41:16.129  5021  5032 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-03 03:41:16.129  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-03 03:41:16.129  5021  5031 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-03 03:41:16.131  3984  3984 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-03 03:41:16.140  3984  3984 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-03 03:41:16.145  3984  5376 I iu.UploadsManager: num queued entries: 0
,10-03 03:41:16.145  3984  5376 I iu.UploadsManager: num updated entries: 0
10-03 03:41:16.145  3984  5376 I iu.SyncManager: NEXT; no task
,10-03 03:41:16.148   928  5850 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,10-03 03:41:16.149  3984  5863 I SystemUpdateService: active receiver: enabled
,10-03 03:41:16.151  3984  3984 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-03 03:41:16.153  3984  3984 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-03 03:41:16.154  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-03 03:41:16.158  5785  5785 D SprintDMHelper: simOperator: 
,10-03 03:41:16.158  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-03 03:41:16.186  3984  5863 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-03 03:41:16.194   928  5850 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 03 Oct 2016 07:41:16 GMT], X-Android-Received-Millis=[1475480476194], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475480476172]}
,10-03 03:41:16.195   928  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-03 03:41:16.195   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-03 03:41:16.195   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-03 03:41:16.196  3984  5863 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-03 03:41:16.196  3984  5863 I SystemUpdateService: now status is 0 (complete)
,10-03 03:41:16.196  3984  5863 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-03 03:41:16.196   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-03 03:41:16.196  3984  5863 I SystemUpdateService: file has been verified
10-03 03:41:16.196  3984  5863 I SystemUpdateService: OTA package size = 21989297
,10-03 03:41:16.203  3984  5863 I SystemUpdateService: showing system update notification
,10-03 03:41:16.212  3984  3984 D SystemUpdateService: onDestroy
,10-03 03:41:16.234   928  3795 D WifiService: setWifiEnabled: false pid=5654, uid=10077
10-03 03:41:16.234   928  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-03 03:41:16.235   928  2929 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-03 03:41:16.235   928  2929 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-03 03:41:16.235   928  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-03 03:41:16.235   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:16.244   506   926 D CommandListener: Clearing all IP addresses on wlan0
10-03 03:41:16.244   928  5852 D DhcpClient: Clearing IP address
,10-03 03:41:16.246   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:16.250  4401  5868 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-03 03:41:16.250  3565  5864 V NativeCrypto: SSL handshake aborted: ssl=0x7f6f099700: I/O error during system call, Connection timed out
,10-03 03:41:16.256   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-03 03:41:16.256   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-03 03:41:16.257   532   532 E Parcel  : Reading a NULL string not supported here.
,10-03 03:41:16.262   928  2941 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-03 03:41:16.262   928   928 D RttService: SCAN_AVAILABLE : 1
10-03 03:41:16.262   928  3064 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-03 03:41:16.264  3737  3889 W QCNEJ   : |CORE| network lost: 101
10-03 03:41:16.265  3737  3889 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-03 03:41:16.266   928  2929 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-03 03:41:16.268   928  5853 D DhcpClient: Receive thread stopped
10-03 03:41:16.270   928  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at a,ndroid.os.Looper.loop(Looper.java:148)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
10-03 03:41:16.271  4401  5868 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-03 03:41:16.271  4401  5868 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-03 03:41:16.286   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-03 03:41:16.305   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-03 03:41:16.306   928  2941 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-03 03:41:16.306   506   926 D CommandListener: Clearing all IP addresses on wlan0
10-03 03:41:16.306   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-03 03:41:16.307   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-03 03:41:16.310   928  2929 D DhcpClient: doQuit
,10-03 03:41:16.310   928  2929 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-03 03:41:16.310   928  5852 D DhcpClient: onQuitting
10-03 03:41:16.311  5845  5845 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-03 03:41:16.312  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:16.312  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:16.312  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.312  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:16.313  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:16.313  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:16.313  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.313  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:16.315  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:16.315  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:16.315  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:16.315  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:16.315  5021  5034 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-03 03:41:16.316  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:16.316  3984  3984 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-03 03:41:16.317  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:16.317  5021  5034 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-03 03:41:16.317  5021  5034 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-03 03:41:16.318  5021  5034 E SarControlService: no key has been found,reset the power
10-03 03:41:16.318  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:16.318  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-03 03:41:16.318  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-03 03:41:16.318  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-03 03:41:16.318  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:16.319  5047  5047 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-03 03:41:16.320  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-03 03:41:16.320  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-03 03:41:16.320  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-03 03:41:16.320  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:16.320  5047  5047 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-03 03:41:16.324  3984  3984 D SystemUpdateService: onCreate
,10-03 03:41:16.325  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000ee03000000000000ffffffff]
10-03 03:41:16.325  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-03 03:41:16.325  5047  5061 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-03 03:41:16.326  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-03 03:41:16.326  5021  5031 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-03 03:41:16.326  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000ef03000000000000ffffffff]
10-03 03:41:16.326  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:16.326  5047  5061 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-03 03:41:16.327  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-03 03:41:16.328  5021  5032 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-03 03:41:16.331  3984  3984 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-03 03:41:16.334  3984  5881 I SystemUpdateService: active receiver: enabled
,10-03 03:41:16.339  3984  3984 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-03 03:41:16.344  3984  5376 I iu.UploadsManager: num queued entries: 0
,10-03 03:41:16.344  3984  5376 I iu.UploadsManager: num updated entries: 0
10-03 03:41:16.345  3984  5376 I iu.SyncManager: NEXT; no task
,10-03 03:41:16.348  3984  3984 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-03 03:41:16.349  5845  5845 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-03 03:41:16.349  3984  3984 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-03 03:41:16.352  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-03 03:41:16.352  5845  5845 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-03 03:41:16.356  5785  5785 D SprintDMHelper: simOperator: 
10-03 03:41:16.356  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-03 03:41:16.360   506   926 E Netd    : netlink response contains error (No such file or directory)
10-03 03:41:16.363   928  2941 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-03 03:41:16.365  3984  5881 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-03 03:41:16.368  4401  5885 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-03 03:41:16.373  3984  5881 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-03 03:41:16.373  3984  5881 I SystemUpdateService: now status is 0 (complete)
10-03 03:41:16.373  3984  5881 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-03 03:41:16.373  3984  5881 I SystemUpdateService: file has been verified
10-03 03:41:16.373  3984  5881 I SystemUpdateService: OTA package size = 21989297
,10-03 03:41:16.389  3984  5881 I SystemUpdateService: showing system update notification
,10-03 03:41:16.389  5845  5845 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-03 03:41:16.398  5845  5845 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-03 03:41:16.398  3984  3984 D SystemUpdateService: onDestroy
,10-03 03:41:16.500  4401  4401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-03 03:41:16.500   928  2929 D wifi    : In wifi stop Hal
,10-03 03:41:16.501   928  2929 D wifi    : halHandle = 0x7f6e003b80, mVM = 0x7f8a68d140, mCls = 0x1942
10-03 03:41:16.501   928  5844 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-03 03:41:16.501   928  5844 D WifiHAL : Got a signal to exit!!!
10-03 03:41:16.501   928  5844 I WifiHAL : Exit wifi_event_loop
,10-03 03:41:16.502   928  2929 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-03 03:41:16.502   928  2929 E WifiHAL : Event processing terminated
10-03 03:41:16.502   928  2929 D wifi    : In wifi cleaned up handler
,10-03 03:41:16.502   928  2929 I WifiHAL : Internal cleanup completed
10-03 03:41:16.504  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:16.504  3714  4179 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-03 03:41:16.505  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:16.506  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:16.524   928  5844 D wifi    : set interface wlan0 flags (DOWN)
,10-03 03:41:16.524   928  2929 D WifiNative-HAL: HAL event thread stopped successfully
,10-03 03:41:16.731   928   945 D Tethering: InitialState.processMessage what=4
,10-03 03:41:16.737   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-03 03:41:17.103   928  2941 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-03 03:41:18.547   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:19.548   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:20.549   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:21.271   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5046695:true
,10-03 03:41:21.272  5771  5771 D BluetoothAdapterState: make() - Creating AdapterState
,10-03 03:41:21.278  5771  5771 I bt_bluedroid: init
,10-03 03:41:21.278  5771  5887 I BluetoothAdapterState: Entering OffState
,10-03 03:41:21.282  5771  5888 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-03 03:41:21.283  5771  5888 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-03 03:41:21.283  5771  5888 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-03 03:41:21.283  5771  5888 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-03 03:41:21.284  5771  5771 I bt_bluedroid: get_profile_interface socket
,10-03 03:41:21.288  5771  5771 I bt_bluedroid: get_profile_interface sdp
,10-03 03:41:21.288  5771  5891 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-03 03:41:21.291  5771  5891 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-03 03:41:21.298  5771  5782 I bt_bluedroid: config_hci_snoop_log
,10-03 03:41:21.300   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-03 03:41:21.309  5771  5887 D BluetoothAdapterState: Current state: OFF, message: 0
,10-03 03:41:21.309  5771  5887 D BluetoothAdapterProperties: Setting state to 14
10-03 03:41:21.310  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-03 03:41:21.313  5771  5887 D BluetoothBondStateMachine: make
,10-03 03:41:21.317  5771  5892 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-03 03:41:21.323  5771  5887 I BluetoothAdapterState: Entering PendingCommandState
,10-03 03:41:21.324  5771  5771 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-03 03:41:21.329  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:21.330  5771  5771 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-03 03:41:21.331  5771  5771 D BtGatt.GattService: Received start request. Starting profile...
,10-03 03:41:21.331  5771  5771 D BtGatt.GattService: start()
10-03 03:41:21.331  5771  5771 I bt_bluedroid: get_profile_interface gatt
10-03 03:41:21.333  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:21.333  5771  5771 D BtGatt.AdvertiseManager: advertise manager created
,10-03 03:41:21.341  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:21.341  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:21.341  5771  5771 V BluetoothAdapterState: isBleTurningOn()=true
,10-03 03:41:21.341  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:21.341  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-03 03:41:21.344  5771  5887 I bt_bluedroid: bt_bluedroid
10-03 03:41:21.344  5771  5888 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-03 03:41:21.345  5771  5888 I bt_hci  : start_up
,10-03 03:41:21.353  5771  5888 I bt_vendor: alloc value 0xf4178871
10-03 03:41:21.353  5771  5888 I bt_vendor: init
10-03 03:41:21.353  5771  5888 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-03 03:41:21.353  5771  5888 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-03 03:41:21.464  5771  5888 D bt_hci  : start_up starting async portion
,10-03 03:41:21.465  5771  5895 I bt_hci  : event_finish_startup
,10-03 03:41:21.466  5771  5895 I bt_hci_h4: hal_open
,10-03 03:41:21.466  5771  5895 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-03 03:41:21.467  5771  5895 I bt_userial_vendor: device fd = 54 open
10-03 03:41:21.461  5896  5896 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-03 03:41:21.480  5771  5895 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-03 03:41:21.482  5771  5895 D bt_hwcfg: Chipset BCM4358A3
,10-03 03:41:21.483  5771  5895 D bt_hwcfg: Target name = [BCM4358A3]
10-03 03:41:21.483  5771  5895 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-03 03:41:21.550   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:21.858  5771  5895 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-03 03:41:21.858  5771  5895 D bt_hwcfg: Settlement delay -- 100 ms
10-03 03:41:21.858  5771  5895 I bt_hwcfg: Setting fw settlement delay to 100 
,10-03 03:41:21.993  5771  5895 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-03 03:41:21.994  5771  5895 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-03 03:41:21.995  5771  5895 I bt_hwcfg: vendor lib fwcfg completed
,10-03 03:41:21.995  5771  5895 I bt_vendor: firmware callback
10-03 03:41:21.996  5771  5895 I bt_hci  : firmware_config_callback
,10-03 03:41:22.005  5771  5898 I bt_btu  : btu_task pending for preload complete event
,10-03 03:41:22.005  5771  5898 I bt_btu_task: Bluetooth chip preload is complete
10-03 03:41:22.005  5771  5898 I bt_btu  : btu_task received preload complete event
,10-03 03:41:22.012  5771  5898 I         : BTE_InitTraceLevels -- TRC_HCI
10-03 03:41:22.012  5771  5898 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-03 03:41:22.012  5771  5898 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-03 03:41:22.012  5771  5898 I         : BTE_InitTraceLevels -- TRC_AVDT
10-03 03:41:22.012  5771  5898 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-03 03:41:22.012  5771  5898 I         : BTE_InitTraceLevels -- TRC_A2D
10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_BTM
10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_GAP
,10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_PAN
,10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_SDP
,10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_GATT
10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_SMP
10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-03 03:41:22.013  5771  5898 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-03 03:41:22.098  5771  5898 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40f6549
10-03 03:41:22.098  5771  5898 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40f6549 
,10-03 03:41:22.115  5771  5891 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-03 03:41:22.117  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-03 03:41:22.118  5771  5891 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-03 03:41:22.121  5771  5891 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-03 03:41:22.123  5771  5891 D BluetoothAdapterProperties: Scan Mode:20
,10-03 03:41:22.124  5771  5891 D BluetoothAdapterProperties: Discoverable Timeout:120
10-03 03:41:22.124  5771  5891 D bt_hci  : do_postload posting postload work item
10-03 03:41:22.125  5771  5895 I bt_hci  : event_postload
10-03 03:41:22.125  5771  5895 I bt_vendor: sco_config_cb
10-03 03:41:22.125  5771  5895 I bt_hci  : sco_config_callback postload finished.
10-03 03:41:22.128  5771  5891 D bt_bte_conf: Device ID record 1 : primary
10-03 03:41:22.128  5771  5891 D bt_bte_conf:   vendorId            = 000f
10-03 03:41:22.128  5771  5891 D bt_bte_conf:   vendorIdSource      = 0001
10-03 03:41:22.128  5771  5891 D bt_bte_conf:   product             = 1200
10-03 03:41:22.129  5771  5891 D bt_bte_conf:   version             = 1436
10-03 03:41:22.129  5771  5891 D bt_bte_conf:   clientExecutableURL = 
10-03 03:41:22.129  5771  5891 D bt_bte_conf:   serviceDescription  = 
10-03 03:41:22.129  5771  5891 D bt_bte_conf:   documentationURL    = 
10-03 03:41:22.129  5771  5891 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-03 03:41:22.129  5771  5888 D bt_stack_manager: event_start_up_stack finished
10-03 03:41:22.132  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-03 03:41:22.133  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:22.135  5771  5895 I bt_vendor: low_power_mode_cb
,10-03 03:41:22.138  5771  5887 D BluetoothAdapterProperties: Setting state to 15
10-03 03:41:22.138  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-03 03:41:22.139  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:22.140  5771  5887 I BluetoothAdapterState: Entering BleOnState
10-03 03:41:22.141  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:22.142  5771  5887 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-03 03:41:22.142  5771  5887 D BluetoothAdapterProperties: Setting state to 11
10-03 03:41:22.142  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-03 03:41:22.148  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:22.149  5771  5771 D HeadsetService: Received start request. Starting profile...
10-03 03:41:22.152  5771  5771 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-03 03:41:22.152  5771  5771 D HeadsetStateMachine: make
10-03 03:41:22.152  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:22.154  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:22.155  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:22.162  5771  5771 D HeadsetStateMachine: max_hf_connections = 1
10-03 03:41:22.162  5771  5771 I bt_bluedroid: get_profile_interface handsfree
10-03 03:41:22.162  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-03 03:41:22.162  5771  5891 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-03 03:41:22.165  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:22.165  5771  5887 I BluetoothAdapterState: Entering PendingCommandState
10-03 03:41:22.166  5771  5771 D A2dpService: Received start request. Starting profile...
,10-03 03:41:22.166  5771  5771 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-03 03:41:22.166  5771  5771 I bt_bluedroid: get_profile_interface avrcp
,10-03 03:41:22.172  5771  5771 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-03 03:41:22.172  5771  5771 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-03 03:41:22.172  5771  5771 D A2dpStateMachine: make
10-03 03:41:22.173  5771  5771 I bt_bluedroid: get_profile_interface a2dp
,10-03 03:41:22.174  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-03 03:41:22.178  5771  5906 D A2dpStateMachine: Enter Disconnected: -2
,10-03 03:41:22.180  5771  5771 I BluetoothHidServiceJni: classInitNative: succeeds
,10-03 03:41:22.180  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:22.180  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-03 03:41:22.183  5707  5707 D BluetoothInputDevice: Proxy object connected
,10-03 03:41:22.184  5771  5771 D HidService: Received start request. Starting profile...
10-03 03:41:22.184  5771  5771 I bt_bluedroid: get_profile_interface hidhost
10-03 03:41:22.184  5771  5771 D HidService: setHidService(): set to: null
10-03 03:41:22.184  5771  5891 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40d756d
10-03 03:41:22.184  5707  5707 D HidProfile: Bluetooth service connected
10-03 03:41:22.184  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-03 03:41:22.186  5771  5771 I BluetoothHealthServiceJni: classInitNative: succeeds
10-03 03:41:22.187  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:22.187  5771  5771 D HealthService: Received start request. Starting profile...
,10-03 03:41:22.189  5771  5771 I bt_bluedroid: get_profile_interface health
,10-03 03:41:22.189  5771  5771 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-03 03:41:22.190  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:22.191  5771  5771 D PanService: Received start request. Starting profile...
,10-03 03:41:22.191  5707  5707 D BluetoothPan: BluetoothPAN Proxy object connected
10-03 03:41:22.191  5771  5771 D BluetoothPanServiceJni: initializeNative(L110): pan
10-03 03:41:22.191  5771  5771 I bt_bluedroid: get_profile_interface pan
10-03 03:41:22.192  5707  5707 D PanProfile: Bluetooth service connected
10-03 03:41:22.192  5771  5891 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-03 03:41:22.194  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:22.195  5707  5707 D BluetoothMap: Proxy object connected
10-03 03:41:22.195  5771  5771 D BluetoothMapService: Received start request. Starting profile...
10-03 03:41:22.195  5771  5771 D BluetoothMapService: start()
,10-03 03:41:22.196  5707  5707 D MapProfile: Bluetooth service connected
10-03 03:41:22.196  5707  5707 D BluetoothMap: getConnectedDevices()
10-03 03:41:22.197  5707  5707 D BluetoothMap: Bluetooth is Not enabled
,10-03 03:41:22.198  5771  5771 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-03 03:41:22.199  5771  5771 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-03 03:41:22.199  5771  5771 D BluetoothMapAppObserver: createReceiver()
10-03 03:41:22.200  5771  5771 D BluetoothMapAppObserver: initObservers()
10-03 03:41:22.200  5771  5771 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-03 03:41:22.205  5771  5771 V BluetoothAdapterState: isTurningOff()=false
,10-03 03:41:22.205  5771  5771 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:22.205  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.205  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:22.205  5771  5904 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-03 03:41:22.206  5771  5771 V SapService: SapBinder()
10-03 03:41:22.207  5771  5771 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:22.207  5771  5771 D SapService: Received start request. Starting profile...
10-03 03:41:22.207  5771  5771 V SapService: start()
,10-03 03:41:22.208  5771  5771 V BluetoothAdapterState: isTurningOff()=false
,10-03 03:41:22.208  5771  5771 V BluetoothAdapterState: isTurningOn()=true
,10-03 03:41:22.208  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.208  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
,10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isTurningOn()=true
,10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.209  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:22.210  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:22.211  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:22.211  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-03 03:41:22.211  5771  5887 D BluetoothAdapterProperties: ScanMode =  20
10-03 03:41:22.211  5771  5887 D BluetoothAdapterProperties: State =  11
,10-03 03:41:22.212  5771  5891 D BluetoothAdapterProperties: Scan Mode:21
10-03 03:41:22.212  5771  5891 D BluetoothAdapterProperties: Discoverable Timeout:120
10-03 03:41:22.213  5771  5887 D BluetoothAdapterProperties: Setting state to 12
10-03 03:41:22.213  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-03 03:41:22.213  5771  5887 I BluetoothAdapterState: Entering OnState
10-03 03:41:22.213  5707  5724 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-03 03:41:22.214  5707  5719 D BluetoothMap: onBluetoothStateChange: up=true
10-03 03:41:22.214  5654  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-03 03:41:22.214  3110  3951 D BluetoothPan: onBluetoothStateChange on: true
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:22.217  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:22.217  3110  3110 D BluetoothPan: BluetoothPAN Proxy object connected
10-03 03:41:22.217  3110  3110 D PanProfile: Bluetooth service connected
10-03 03:41:22.218  3110  3125 D BluetoothA2dp: onBluetoothStateChange: up=true
10-03 03:41:22.219  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:22.219  3110  3123 D BluetoothMap: onBluetoothStateChange: up=true
10-03 03:41:22.221  3110  3110 D BluetoothA2dp: Proxy object connected
10-03 03:41:22.221  5707  5724 D BluetoothPan: onBluetoothStateChange on: true
10-03 03:41:22.221  3110  3951 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-03 03:41:22.222  3110  3110 D BluetoothMap: Proxy object connected
10-03 03:41:22.222  3110  3110 D MapProfile: Bluetooth service connected
10-03 03:41:22.222  3110  3110 D BluetoothMap: getConnectedDevices()
10-03 03:41:22.223   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:22.223  5707  5719 D BluetoothPbap: onBluetoothStateChange: up=true
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:22.223  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:22.224  3110  3110 D BluetoothInputDevice: Proxy object connected
10-03 03:41:22.224  3110  3110 D HidProfile: Bluetooth service connected
10-03 03:41:22.224  3790  3820 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:22.225  3110  3123 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:22.225  5771  5771 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-03 03:,41:22.225   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:22.225   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-03 03:41:22.225  5771  5771 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-03 03:41:22.226   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:22.226   928   928 D BluetoothA2dp: Proxy object connected
10-03 03:41:22.226  3110  3951 D BluetoothPbap: onBluetoothStateChange: up=true
10-03 03:41:22.226  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:22.227  5771  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:22.228   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-03 03:41:22.231  5707  5707 D LocalBluetoothProfileManager: Adding local A2DP profile
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:22.232  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:22.232  5771  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:22.234  5771  5771 D ObexServerSockets: Succeed to create listening sockets 
10-03 03:41:22.235  5771  5771 D ObexServerSockets0: startAccept()
10-03 03:41:22.235  5771  5771 D ObexServerSockets0: prepareForNewConnect()
10-03 03:41:22.235  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:22.235  5707  5707 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-03 03:41:22.235  5654  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-03 03:41:22.237  5771  5771 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-03 03:41:22.237  5771  5771 D BluetoothSdpJni: SDP Create record success - handle: 0
10-03 03:41:22.237  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:22.238  5771  5771 D BluetoothMapService: onReceive
10-03 03:41:22.238  5771  5913 D ObexServerSockets0: Accepting socket connection...
10-03 03:41:22.238  5771  5914 D ObexServerSockets0: Accepting socket connection...
10-03 03:41:22.238  5771  5771 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-03 03:41:22.238  5771  5771 D BluetoothMapService: STATE_ON
10-03 03:41:22.239  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:22.240  5771  5915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:22.240  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:22.241  5771  5915 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-03 03:41:22.241  5771  5915 D BluetoothSdpJni: SDP Create record success - handle: 1
10-03 03:41:22.241  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:13,4 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-03 03:41:22.247  5707  5707 D BluetoothA2dp: Proxy object connected
10-03 03:41:22.253  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-03 03:41:22.258  5707  5707 D DockEventReceiver: finishStartingService: stopping service
10-03 03:41:22.259  3110  3110 D BluetoothPbap: Proxy object connected
10-03 03:41:22.259  3110  3110 D PbapServerProfile: Bluetooth service connected
10-03 03:41:22.263  5707  5707 D BluetoothPbap: Proxy object connected
10-03 03:41:22.264  5707  5707 D PbapServerProfile: Bluetooth service connected
10-03 03:41:22.265  5771  5771 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-03 03:41:22.265  5771  5771 D ObexServerSockets0: prepareForNewConnect()
10-03 03:41:22.269  5771  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:22.283  5771  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:22.284  5771  5924 I BtOppRfcommListener: Accept thread started.
,10-03 03:41:22.324   928   928 D BluetoothHeadset: Proxy object connected
,10-03 03:41:22.325  3110  3123 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325  3790  4049 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325  3110  3110 D HeadsetProfile: Bluetooth service connected
10-03 03:41:22.325   928   928 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325  3790  3816 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325  3110  3951 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325   928   928 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325   928   945 D BluetoothHeadset: Proxy object connected
10-03 03:41:22.325   928   945 D BluetoothHeadset: Proxy object connected
,10-03 03:41:22.327  3110  3110 D HeadsetProfile: Bluetooth service connected
,10-03 03:41:22.338  5707  5719 D BluetoothHeadset: Proxy object connected
,10-03 03:41:22.339  5707  5707 D HeadsetProfile: Bluetooth service connected
,10-03 03:41:22.552   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:23.553   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-03 03:41:24.060   928  2941 D ConnectivityService: handlePromptUnvalidated 101
,10-03 03:41:26.247  5771  5887 D BluetoothAdapterState: Current state: ON, message: 23
10-03 03:41:26.248  5771  5887 D BluetoothAdapterProperties: Setting state to 13
,10-03 03:41:26.248  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-03 03:41:26.249  5771  5887 D BluetoothAdapterProperties: onBluetoothDisable()
10-03 03:41:26.251  5771  5887 I BluetoothAdapterState: Entering PendingCommandState
10-03 03:41:26.256  5771  5771 D BluetoothMapService: onReceive
10-03 03:41:26.256  5771  5771 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-03 03:41:26.257  5771  5771 D BluetoothMapService: STATE_TURNING_OFF
10-03 03:41:26.257  5771  5771 D BluetoothMapService: MAP Service closeService in
10-03 03:41:26.258  5771  5771 D BluetoothMapMasInstance0: MAP Service shutdown
10-03 03:41:26.258  5771  5771 D ObexServerSockets0: shutdown(block = true)
10-03 03:41:26.259  5771  5771 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-03 03:41:26.260  5771  5771 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-03 03:41:26.260  5771  5900 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-03 03:41:26.260  5771  5914 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-03 03:41:26.261  5771  5913 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-03 03:41:26.261  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:26.261  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:26.262  5771  5891 D BluetoothAdapterProperties: Scan Mode:20
10-03 03:41:26.262  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-03 03:41:26.263  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:26.264  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:26.268  5771  5771 I BtOppRfcommListener: stopping Accept Thread
,10-03 03:41:26.269  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:26.269  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:26.269  5771  5924 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-03 03:41:26.270  5771  5924 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-03 03:41:26.270  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-03 03:41:26.270  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:26.270  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:26.273  5771  5771 D HeadsetService: Received stop request...Stopping profile...
10-03 03:41:26.274  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:26.275  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-03 03:41:26.276  5654  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-03 03:41:26.276  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:26.278  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.280  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.281  5707  5917 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:26.281  5771  5771 D A2dpService: Received stop request...Stopping profile...
10-03 03:41:26.281   928   928 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:26.281  5771  5906 D A2dpStateMachine: Exit Disconnected: -1
10-03 03:41:26.281  3110  3123 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:26.282  3110  3110 D HeadsetProfile: Bluetooth service disconnected
10-03 03:41:26.282   928   928 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:26.282  3790  4048 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:26.282  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.282   928   928 D BluetoothHeadset: Proxy object disconnected
10-03 03:41:26.283   928   928 D BluetoothA2dp: Proxy object disconnected
10-03 03:41:26.283  3110  3110 D BluetoothA2dp: Proxy object disconnected
10-03 03:41:26.284  5771  5771 D HidService: Received stop request...Stopping profile...
10-03 03:41:26.284  5771  5771 D HidService: Stopping Bluetooth HidService
10-03 03:41:26.285  3110  3110 D BluetoothInputDevice: Proxy object disconnected
10-03 03:41:26.285  3110  3110 D HidProfile: Bluetooth service disconnected
10-03 03:41:26.286  5707  5707 D DockEventReceiver: finishStartingService: stopping service
10-03 03:41:26.287  5771  5771 D HealthService: Received stop request...Stopping profile...
,10-03 03:41:26.287  5707  5707 D HeadsetProfile: Bluetooth service disconnected
10-03 03:41:26.287  5707  5707 D BluetoothA2dp: Proxy object disconnected
10-03 03:41:26.288  5707  5707 D BluetoothInputDevice: Proxy object disconnected
,10-03 03:41:26.288  5707  5707 D HidProfile: Bluetooth service disconnected
10-03 03:41:26.290  5771  5771 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:26.290  5771  5771 V BluetoothAdapterState: isTurningOn()=false
,10-03 03:41:26.290  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:26.290  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:26.291  5771  5771 D PanService: Received stop request...Stopping profile...
10-03 03:41:26.293  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-03 03:41:26.293  5707  5707 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-03 03:41:26.293  5707  5707 D PanProfile: Bluetooth service disconnected
10-03 03:41:26.294  3110  3110 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-03 03:41:26.294  3110  3110 D PanProfile: Bluetooth service disconnected
,10-03 03:41:26.296  5771  5771 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-03 03:41:26.296  5771  5771 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-03 03:41:26.296  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-03 03:41:26.296  5771  5898 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:26.296  5771  5898 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:26.296  5771  5898 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:26.296  5771  5891 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-03 03:41:26.296  5771  5771 D BluetoothMapService: Received stop request...Stopping profile...
10-03 03:41:26.297  5771  5771 D BluetoothMapService: stop()
10-03 03:41:26.297  5771  5771 D BluetoothMapAppObserver: deinitObservers()
,10-03 03:41:26.297  5771  5771 D BluetoothMapAppObserver: removeReceiver()
10-03 03:41:26.299  5707  5707 D BluetoothMap: Proxy object disconnected
10-03 03:41:26.299  5707  5707 D MapProfile: Bluetooth service disconnected
10-03 03:41:26.299  5771  5771 D SapService: Received stop request...Stopping profile...
10-03 03:41:26.299  5771  5771 V SapService: stop()
10-03 03:41:26.298  3110  3110 D BluetoothMap: Proxy object disconnected
10-03 03:41:26.299  3110  3110 D MapProfile: Bluetooth service disconnected
10-03 03:41:26.301  5771  5771 V BluetoothAdapterState: isTurningOff()=true
,10-03 03:41:26.301  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.301  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:26.301  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:26.302  5771  5771 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:26.302  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.302  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:26.302  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:26.302  5771  5771 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-03 03:41:26.302  5771  5771 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-03 03:41:26.302  5771  5771 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:26.302  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.303  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:26.303  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
,10-03 03:41:26.303  5771  5771 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-03 03:41:26.303  5771  5898 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:26.303  5771  5898 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:26.303  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-03 03:41:26.303  5771  5898 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-03 03:41:26.303  5771  5898 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-03 03:41:26.304  5771  5891 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-03 03:41:26.304  5771  5898 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-03 03:41:26.304  5771  5898 W bt_l2cap: btif_in_execute_service_request: Unknown service
10-03 03:41:26.304  5771  5891 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-03 03:41:26.303  5771  5771 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-03 03:41:26.314  3110  3110 D BluetoothPbap: Proxy object disconnected
10-03 03:41:26.314  3110  3110 D PbapServerProfile: Bluetooth service disconnected
,10-03 03:41:26.314  5771  5771 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:26.314  5707  5707 D BluetoothPbap: Proxy object disconnected
10-03 03:41:26.314  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.314  5707  5707 D PbapServerProfile: Bluetooth service disconnected
10-03 03:41:26.314  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
,10-03 03:41:26.314  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:26.314  5771  5771 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-03 03:41:26.314  5771  5771 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-03 03:41:26.315  5771  5771 D BluetoothMapService: MAP Service closeService in
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:26.316  5771  5771 D BluetoothMapService: cleanup()
10-03 03:41:26.316  5771  5771 D BluetoothMapService: MAP Service closeService in
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isTurningOff()=true
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
,10-03 03:41:26.316  5771  5771 V BluetoothAdapterState: isBleTurningOff()=false
,10-03 03:41:26.317  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-03 03:41:26.318  5771  5887 D BluetoothAdapterProperties: Setting state to 15
,10-03 03:41:26.318  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-03 03:41:26.318  5771  5887 I BluetoothAdapterState: Entering BleOnState
10-03 03:41:26.319  5707  5719 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-03 03:41:26.319  5707  5724 D BluetoothMap: onBluetoothStateChange: up=false
10-03 03:41:26.320  3110  3123 D BluetoothPan: onBluetoothStateChange on: false
10-03 03:41:26.320  5707  5917 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:26.321  3110  3951 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-03 03:41:26.321  3110  3125 D BluetoothMap: onBluetoothStateChange: up=false
10-03 03:41:26.322  5707  5719 D BluetoothPan: onBluetoothStateChange on: false
10-03 03:41:26.322  3110  3123 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-03 03:41:26.323   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:26.323  5707  5724 D BluetoothPbap: onBluetoothStateChange: up=false
10-03 03:41:26.323  3790  3820 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:26.324  3110  3951 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:26.324   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:26.324  5707  5917 D BluetoothA2dp: onBluetoothStateChange: up=false
10-03 03:41:26.324   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-03 03:41:26.325   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-03 03:41:26.325  3110  3125 D BluetoothPbap: onBluetoothStateChange: up=false
10-03 03:41:26.325  5771  5887 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-03 03:41:26.325  5771  5887 D BluetoothAdapterProperties: Setting state to 16
10-03 03:41:26.325  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-03 03:41:26.326  5771  5887 D BluetoothAdapterProperties: onBleDisable
10-03 03:41:26.326  5771  5887 I BluetoothAdapterState: Entering PendingCommandState
10-03 03:41:26.326  5771  5888 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-03 03:41:26.327  5771  5898 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-03 03:41:26.327  5771  5898 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-03 03:41:26.328  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.329  5771  5891 D BluetoothAdapterProperties: Scan Mode:20
10-03 03:41:26.329  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.330  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.332  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-03 03:41:26.333  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:26.334  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.336  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:26.338  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-03 03:41:26.344  5707  5707 D DockEventReceiver: finishStartingService: stopping service
,10-03 03:41:26.542  5771  5891 I bt_hci  : shut_down
,10-03 03:41:26.544  5771  5895 D bt_hwcfg: hw_epilog_process
,10-03 03:41:26.545  5771  5895 I bt_vendor: low_power_mode_cb
,10-03 03:41:26.548  5771  5895 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-03 03:41:26.548  5771  5895 I bt_vendor: epilog_cb
,10-03 03:41:26.548  5771  5895 I bt_hci  : epilog_finished_callback
,10-03 03:41:26.551  5771  5891 I bt_hci_h4: hal_close
,10-03 03:41:26.552  5771  5891 I bt_userial_vendor: device fd = 54 close
,10-03 03:41:26.660  5771  5888 D bt_stack_manager: event_shut_down_stack finished.
,10-03 03:41:26.660  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-03 03:41:26.663  5771  5887 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-03 03:41:26.663  5771  5771 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-03 03:41:26.664  5771  5771 D BtGatt.GattService: Received stop request...Stopping profile...
,10-03 03:41:26.664  5771  5771 D BtGatt.GattService: stop()
10-03 03:41:26.664  5771  5771 D BtGatt.AdvertiseManager: advertise clients cleared
10-03 03:41:26.667  5771  5771 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:26.667  5771  5771 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:26.667  5771  5771 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:26.667  5771  5771 V BluetoothAdapterState: isBleTurningOff()=true
,10-03 03:41:26.667  5771  5887 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-03 03:41:26.668  5771  5887 D BluetoothAdapterProperties: Setting state to 10
10-03 03:41:26.668  5771  5887 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-03 03:41:26.669  5771  5887 I BluetoothAdapterState: Entering OffState
10-03 03:41:26.670   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-03 03:41:26.677  5771  5771 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-03 03:41:26.678  5771  5771 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-03 03:41:26.678  5771  5771 I BluetoothServiceJni: cleanupNative: return from cleanup
10-03 03:41:26.679  5771  5888 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-03 03:41:26.684  5771  5771 I art     : System.exit called, status: 0
,10-03 03:41:26.684  5771  5771 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-03 03:41:26.708   928  3875 I ActivityManager: Process com.android.bluetooth (pid 5771) has died
,10-03 03:41:31.247  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
,10-03 03:41:31.247  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:31.252  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:31.252  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e1e508 removed from the list
10-03 03:41:31.252  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:31.252  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:31.252  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:31.255  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:41:31.255  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59d6c6 added. We now have 4 listener(s)
10-03 03:41:31.255  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:41:31.257  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:31.257  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59d6c6 removed from the list
10-03 03:41:31.257  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:31.258  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:31.258  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:31.260  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:41:31.260  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d4f687 added. We now have 4 listener(s)
,10-03 03:41:31.260  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:41:36.271  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:36.310   928   945 I ActivityManager: Start proc 5932:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-03 03:41:36.394  5932  5932 D AdapterServiceConfig: Adding HeadsetService
,10-03 03:41:36.395  5932  5932 D AdapterServiceConfig: Adding A2dpService
10-03 03:41:36.395  5932  5932 D AdapterServiceConfig: Adding HidService
10-03 03:41:36.395  5932  5932 D AdapterServiceConfig: Adding HealthService
10-03 03:41:36.395  5932  5932 D AdapterServiceConfig: Adding PanService
10-03 03:41:36.395  5932  5932 D AdapterServiceConfig: Adding GattService
10-03 03:41:36.395  5932  5932 D AdapterServiceConfig: Adding BluetoothMapService
10-03 03:41:36.396  5932  5932 D AdapterServiceConfig: Adding SapService
,10-03 03:41:36.407   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e55aa6a:true
,10-03 03:41:36.407  5932  5932 D BluetoothAdapterState: make() - Creating AdapterState
,10-03 03:41:36.411  5932  5932 I bt_bluedroid: init
10-03 03:41:36.411  5932  5944 I BluetoothAdapterState: Entering OffState
,10-03 03:41:36.414  5932  5945 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-03 03:41:36.414  5932  5945 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-03 03:41:36.414  5932  5945 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-03 03:41:36.414  5932  5945 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-03 03:41:36.415  5932  5932 I bt_bluedroid: get_profile_interface socket
,10-03 03:41:36.417  5932  5948 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-03 03:41:36.417  5932  5932 I bt_bluedroid: get_profile_interface sdp
10-03 03:41:36.419  5932  5948 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-03 03:41:36.426  5932  5943 I bt_bluedroid: config_hci_snoop_log
10-03 03:41:36.427   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-03 03:41:36.431  5932  5944 D BluetoothAdapterState: Current state: OFF, message: 0
,10-03 03:41:36.431  5932  5944 D BluetoothAdapterProperties: Setting state to 14
10-03 03:41:36.431  5932  5944 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-03 03:41:36.433  5932  5944 D BluetoothBondStateMachine: make
,10-03 03:41:36.436  5932  5949 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-03 03:41:36.439  5932  5944 I BluetoothAdapterState: Entering PendingCommandState
,10-03 03:41:36.440  5932  5932 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-03 03:41:36.442  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:36.444  5932  5932 D BtGatt.DebugUtils: handleDebugAction() action=null
10-03 03:41:36.445  5932  5932 D BtGatt.GattService: Received start request. Starting profile...
10-03 03:41:36.445  5932  5932 D BtGatt.GattService: start()
10-03 03:41:36.445  5932  5932 I bt_bluedroid: get_profile_interface gatt
,10-03 03:41:36.446  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:36.446  5932  5932 D BtGatt.AdvertiseManager: advertise manager created
,10-03 03:41:36.451  5932  5932 V BluetoothAdapterState: isTurningOff()=false
,10-03 03:41:36.451  5932  5932 V BluetoothAdapterState: isTurningOn()=false
10-03 03:41:36.451  5932  5932 V BluetoothAdapterState: isBleTurningOn()=true
10-03 03:41:36.451  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:36.452  5932  5944 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-03 03:41:36.453  5932  5944 I bt_bluedroid: bt_bluedroid
10-03 03:41:36.453  5932  5945 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-03 03:41:36.454  5932  5945 I bt_hci  : start_up
,10-03 03:41:36.459  5932  5945 I bt_vendor: alloc value 0xf41f5871
,10-03 03:41:36.459  5932  5945 I bt_vendor: init
10-03 03:41:36.459  5932  5945 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-03 03:41:36.459  5932  5945 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-03 03:41:36.564  5953  5953 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-03 03:41:36.568  5932  5945 D bt_hci  : start_up starting async portion
,10-03 03:41:36.569  5932  5952 I bt_hci  : event_finish_startup
10-03 03:41:36.569  5932  5952 I bt_hci_h4: hal_open
,10-03 03:41:36.569  5932  5952 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-03 03:41:36.571  5932  5952 I bt_userial_vendor: device fd = 54 open
,10-03 03:41:36.586  5932  5952 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-03 03:41:36.589  5932  5952 D bt_hwcfg: Chipset BCM4358A3
,10-03 03:41:36.589  5932  5952 D bt_hwcfg: Target name = [BCM4358A3]
10-03 03:41:36.589  5932  5952 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-03 03:41:37.100  5932  5952 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-03 03:41:37.101  5932  5952 D bt_hwcfg: Settlement delay -- 100 ms
10-03 03:41:37.101  5932  5952 I bt_hwcfg: Setting fw settlement delay to 100 
,10-03 03:41:37.235  5932  5952 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-03 03:41:37.235  5932  5952 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-03 03:41:37.237  5932  5952 I bt_hwcfg: vendor lib fwcfg completed
10-03 03:41:37.237  5932  5952 I bt_vendor: firmware callback
,10-03 03:41:37.238  5932  5952 I bt_hci  : firmware_config_callback
,10-03 03:41:37.249  5932  5955 I bt_btu  : btu_task pending for preload complete event
,10-03 03:41:37.249  5932  5955 I bt_btu_task: Bluetooth chip preload is complete
10-03 03:41:37.249  5932  5955 I bt_btu  : btu_task received preload complete event
,10-03 03:41:37.256  5932  5955 I         : BTE_InitTraceLevels -- TRC_HCI
10-03 03:41:37.256  5932  5955 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-03 03:41:37.256  5932  5955 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-03 03:41:37.256  5932  5955 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-03 03:41:37.256  5932  5955 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-03 03:41:37.257  5932  5955 I         : BTE_InitTraceLevels -- TRC_A2D
10-03 03:41:37.257  5932  5955 I         : BTE_InitTraceLevels -- TRC_BNEP
10-03 03:41:37.257  5932  5955 I         : BTE_InitTraceLevels -- TRC_BTM
,10-03 03:41:37.257  5932  5955 I         : BTE_InitTraceLevels -- TRC_GAP
10-03 03:41:37.257  5932  5955 I         : BTE_InitTraceLevels -- TRC_PAN
,10-03 03:41:37.257  5932  5955 I         : BTE_InitTraceLevels -- TRC_SDP
10-03 03:41:37.258  5932  5955 I         : BTE_InitTraceLevels -- TRC_GATT
10-03 03:41:37.258  5932  5955 I         : BTE_InitTraceLevels -- TRC_SMP
,10-03 03:41:37.258  5932  5955 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-03 03:41:37.258  5932  5955 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-03 03:41:37.352  5932  5955 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4173549
10-03 03:41:37.352  5932  5955 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4173549 
,10-03 03:41:37.369  5932  5948 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-03 03:41:37.371  5932  5948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-03 03:41:37.372  5932  5948 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-03 03:41:37.375  5932  5948 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-03 03:41:37.379  5932  5948 D BluetoothAdapterProperties: Scan Mode:20
,10-03 03:41:37.379  5932  5948 D BluetoothAdapterProperties: Discoverable Timeout:120
10-03 03:41:37.379  5932  5948 D bt_hci  : do_postload posting postload work item
10-03 03:41:37.380  5932  5952 I bt_hci  : event_postload
10-03 03:41:37.380  5932  5952 I bt_vendor: sco_config_cb
,10-03 03:41:37.380  5932  5952 I bt_hci  : sco_config_callback postload finished.
,10-03 03:41:37.386  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:37.388  5932  5952 I bt_vendor: low_power_mode_cb
10-03 03:41:37.389  5932  5948 D bt_bte_conf: Device ID record 1 : primary
10-03 03:41:37.389  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:37.389  5932  5948 D bt_bte_conf:   vendorId            = 000f
10-03 03:41:37.389  5932  5948 D bt_bte_conf:   vendorIdSource      = 0001
10-03 03:41:37.389  5932  5948 D bt_bte_conf:   product             = 1200
,10-03 03:41:37.389  5932  5948 D bt_bte_conf:   version             = 1436
10-03 03:41:37.389  5932  5948 D bt_bte_conf:   clientExecutableURL = 
10-03 03:41:37.389  5932  5948 D bt_bte_conf:   serviceDescription  = 
10-03 03:41:37.389  5932  5948 D bt_bte_conf:   documentationURL    = 
10-03 03:41:37.389  5932  5948 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-03 03:41:37.390  5932  5945 D bt_stack_manager: event_start_up_stack finished
10-03 03:41:37.391  5932  5944 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-03 03:41:37.391  5932  5944 D BluetoothAdapterProperties: Setting state to 15
,10-03 03:41:37.391  5932  5944 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-03 03:41:37.392  5932  5944 I BluetoothAdapterState: Entering BleOnState
,10-03 03:41:37.397  5932  5944 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-03 03:41:37.398  5932  5944 D BluetoothAdapterProperties: Setting state to 11
10-03 03:41:37.398  5932  5944 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-03 03:41:37.407  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:37.409  5932  5932 D HeadsetService: Received start request. Starting profile...
10-03 03:41:37.413  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:41:37.415  5932  5932 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-03 03:41:37.415  5932  5932 D HeadsetStateMachine: make
10-03 03:41:37.415  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:37.427  5932  5944 I BluetoothAdapterState: Entering PendingCommandState
,10-03 03:41:37.432  5932  5932 D HeadsetStateMachine: max_hf_connections = 1
,10-03 03:41:37.432  5932  5932 I bt_bluedroid: get_profile_interface handsfree
10-03 03:41:37.433  5932  5948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-03 03:41:37.433  5932  5948 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
10-03 03:41:37.436  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:37.437  5932  5932 D A2dpService: Received start request. Starting profile...
,10-03 03:41:37.438  5932  5932 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-03 03:41:37.438  5932  5932 I bt_bluedroid: get_profile_interface avrcp
,10-03 03:41:37.445  5932  5932 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-03 03:41:37.445  5932  5932 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-03 03:41:37.445  5932  5932 D A2dpStateMachine: make
,10-03 03:41:37.447  5932  5932 I bt_bluedroid: get_profile_interface a2dp
10-03 03:41:37.449  5932  5948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-03 03:41:37.452  5932  5932 I BluetoothHidServiceJni: classInitNative: succeeds
,10-03 03:41:37.452  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:37.453  5932  5963 D A2dpStateMachine: Enter Disconnected: -2
10-03 03:41:37.453  5932  5932 D HidService: Received start request. Starting profile...
10-03 03:41:37.453  5932  5932 I bt_bluedroid: get_profile_interface hidhost
10-03 03:41:37.453  5932  5948 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf415456d
10-03 03:41:37.453  5932  5932 D HidService: setHidService(): set to: null
10-03 03:41:37.453  5932  5948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-03 03:41:37.455  5932  5932 I BluetoothHealthServiceJni: classInitNative: succeeds
10-03 03:41:37.456  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-03 03:41:37.457  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:37.458  5932  5932 D HealthService: Received start request. Starting profile...
,10-03 03:41:37.459  5932  5932 I bt_bluedroid: get_profile_interface health
10-03 03:41:37.460  5932  5932 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-03 03:41:37.461  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:37.461  5932  5932 D PanService: Received start request. Starting profile...
,10-03 03:41:37.462  5932  5932 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-03 03:41:37.462  5932  5932 I bt_bluedroid: get_profile_interface pan
10-03 03:41:37.465  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
10-03 03:41:37.466  5932  5932 D BluetoothMapService: Received start request. Starting profile...
10-03 03:41:37.466  5932  5932 D BluetoothMapService: start()
10-03 03:41:37.468  5932  5932 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-03 03:41:37.469  5932  5932 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-03 03:41:37.469  5932  5932 D BluetoothMapAppObserver: createReceiver()
10-03 03:41:37.470  5932  5932 D BluetoothMapAppObserver: initObservers()
10-03 03:41:37.470  5932  5932 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-03 03:41:37.471  5932  5948 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-03 03:41:37.476  5932  5932 V SapService: SapBinder()
10-03 03:41:37.476  5932  5932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:41:37.477  5932  5932 D SapService: Received start request. Starting profile...
10-03 03:41:37.477  5932  5932 V SapService: start()
,10-03 03:41:37.479  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.479  5932  5932 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:37.479  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
,10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.480  5932  5961 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.480  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
,10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isTurningOn()=true
,10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.482  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:37.483  5932  5932 V BluetoothAdapterState: isTurningOff()=false
10-03 03:41:37.483  5932  5932 V BluetoothAdapterState: isTurningOn()=true
10-03 03:41:37.483  5932  5932 V BluetoothAdapterState: isBleTurningOn()=false
10-03 03:41:37.483  5932  5932 V BluetoothAdapterState: isBleTurningOff()=false
10-03 03:41:37.483  5932  5944 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-03 03:41:37.484  5932  5944 D BluetoothAdapterProperties: ScanMode =  20
10-03 03:41:37.484  5932  5944 D BluetoothAdapterProperties: State =  11
,10-03 03:41:37.484  5932  5944 D BluetoothAdapterProperties: Setting state to 12
10-03 03:41:37.484  5932  5944 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-03 03:41:37.485  5707  5719 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-03 03:41:37.485  5932  5944 I BluetoothAdapterState: Entering OnState
,10-03 03:41:37.489  5707  5724 D BluetoothMap: onBluetoothStateChange: up=true
,10-03 03:41:37.489  5932  5948 D BluetoothAdapterProperties: Scan Mode:21
10-03 03:41:37.490  5932  5948 D BluetoothAdapterProperties: Discoverable Timeout:120
10-03 03:41:37.490  5654  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-03 03:41:37.491  3110  3123 D BluetoothPan: onBluetoothStateChange on: true
,10-03 03:41:37.493  5707  5724 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:37.493  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-03 03:41:37.493  3110  3125 D BluetoothA2dp: onBluetoothStateChange: up=true
10-03 03:41:37.494  3110  3110 D BluetoothPan: BluetoothPAN Proxy object connected
10-03 03:41:37.494  3110  3110 D PanProfile: Bluetooth service connected
10-03 03:41:37.495  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:37.495  5932  5932 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-03 03:41:37.495  3110  3123 D BluetoothMap: onBluetoothStateChange: up=true
10-03 03:41:37.495  5932  5932 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-03 03:41:37.497  5932  5932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:37.497  5707  5917 D BluetoothPan: onBluetoothStateChange on: true
10-03 03:41:37.497  3110  3110 D BluetoothMap: Proxy object connected
,10-03 03:41:37.497  3110  3110 D MapProfile: Bluetooth service connected
10-03 03:41:37.497  3110  3110 D BluetoothMap: getConnectedDevices()
10-03 03:41:37.499  5707  5707 D BluetoothInputDevice: Proxy object connected
10-03 03:41:37.499  5707  5707 D HidProfile: Bluetooth service connected
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:37.499  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-03 03:41:37.499  5932  5932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:37.500  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-03 03:41:37.501  3110  3951 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-03 03:41:37.501  5932  5932 D ObexServerSockets: Succeed to create listening sockets 
10-03 03:41:37.501  5932  5932 D ObexServerSockets0: startAccept()
10-03 03:41:37.501  5932  5932 D ObexServerSockets0: prepareForNewConnect()
10-03 03:41:37.502  5707  5707 D BluetoothMap: Proxy object connected
10-03 03:41:37.502  5707  5707 D MapProfile: Bluetooth service connected
10-03 03:41:37.502  5707  5707 D BluetoothMap: getConnectedDevices()
10-03 03:41:37.502  3110  3110 D BluetoothInputDevice: Proxy object connected
10-03 03:41:37.502   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:37.502  3110  3110 D HidProfile: Bluetooth service connected
10-03 03:41:37.503  5707  5724 D BluetoothPbap: onBluetoothStateChange: up=true
,10-03 03:41:37.503  5932  5932 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-03 03:41:37.503  5932  5932 D BluetoothSdpJni: SDP Create record success - handle: 0
10-03 03:41:37.503  5932  5969 D ObexServerSockets0: Accepting socket connection...
10-03 03:41:37.504  5707  5707 D BluetoothPan: BluetoothPAN Proxy object connected
10-03 03:41:37.504  5932  5970 D ObexServerSockets0: Accepting socket connection...
10-03 03:41:37.504  5707  5707 D PanProfile: Bluetooth service connected
10-03 03:41:37.505  3110  3110 D BluetoothA2dp: Proxy object connected
10-03 03:41:37.505  3790  4048 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:37.505  3110  3125 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:37.506   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:37.506  5707  5719 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-03 03:41:37.508   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-03 03:41:37.509   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-03 03:41:37.509   928   928 D BluetoothA2dp: Proxy object connected
10-03 03:41:37.509  3110  3951 D BluetoothPbap: onBluetoothStateChange: up=true
10-03 03:41:37.511  5707  5707 D BluetoothA2dp: Proxy object connected
,10-03 03:41:37.513   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-03 03:41:37.513  5654  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-03 03:41:37.513  5932  5932 D BluetoothMapService: onReceive
10-03 03:41:37.513  5932  5932 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-03 03:41:37.513  5932  5932 D BluetoothMapService: STATE_ON
,10-03 03:41:37.514  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:37.516  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:37.516  5932  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-03 03:41:37.518  5932  5971 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-03 03:41:37.518  5932  5971 D BluetoothSdpJni: SDP Create record success - handle: 1
10-03 03:41:37.520  5707  5707 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-03 03:41:37.527  3565  3565 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-03 03:41:37.529  5707  5707 D DockEventReceiver: finishStartingService: stopping service
,10-03 03:41:37.535  5707  5707 D BluetoothPbap: Proxy object connected
,10-03 03:41:37.536  5707  5707 D PbapServerProfile: Bluetooth service connected
,10-03 03:41:37.536  3110  3110 D BluetoothPbap: Proxy object connected
10-03 03:41:37.537  3110  3110 D PbapServerProfile: Bluetooth service connected
,10-03 03:41:37.540  5932  5932 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-03 03:41:37.540  5932  5932 D ObexServerSockets0: prepareForNewConnect()
,10-03 03:41:37.545  5932  5975 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-03 03:41:37.560  5932  5979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-03 03:41:37.561  5932  5979 I BtOppRfcommListener: Accept thread started.
,10-03 03:41:37.596  5707  5917 D BluetoothHeadset: Proxy object connected
,10-03 03:41:37.596   928   928 D BluetoothHeadset: Proxy object connected
10-03 03:41:37.597  3110  3125 D BluetoothHeadset: Proxy object connected
10-03 03:41:37.597  3110  3110 D HeadsetProfile: Bluetooth service connected
10-03 03:41:37.597   928   928 D BluetoothHeadset: Proxy object connected
10-03 03:41:37.597  3790  3820 D BluetoothHeadset: Proxy object connected
10-03 03:41:37.598   928   928 D BluetoothHeadset: Proxy object connected
10-03 03:41:37.599  5707  5707 D HeadsetProfile: Bluetooth service connected
,10-03 03:41:37.602   928   945 D BluetoothHeadset: Proxy object connected
,10-03 03:41:37.606  3790  4049 D BluetoothHeadset: Proxy object connected
,10-03 03:41:37.606  3110  3951 D BluetoothHeadset: Proxy object connected
10-03 03:41:37.606  3110  3110 D HeadsetProfile: Bluetooth service connected
10-03 03:41:37.606   928   945 D BluetoothHeadset: Proxy object connected
,10-03 03:41:37.610   928   945 D BluetoothHeadset: Proxy object connected
,10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:41.287  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-03 03:41:41.292  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:41.293  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:41:41.293  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d4f687 removed from the list
,10-03 03:41:41.293  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:41.293  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:41.293  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:41:41.295  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-03 03:41:41.295  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93449b4 added. We now have 4 listener(s)
10-03 03:41:41.295  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:41:41.299   928  3797 D WifiService: setWifiEnabled: false pid=5654, uid=10077
10-03 03:41:41.299   928  3797 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-03 03:41:43.554   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:44.555   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:45.557   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:46.309  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:46.310   928  3795 D WifiService: setWifiEnabled: true pid=5654, uid=10077
,10-03 03:41:46.311   928  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-03 03:41:46.319   506   926 D SoftapController: Softap fwReload - Ok
,10-03 03:41:46.325   506   926 D CommandListener: Setting iface cfg
10-03 03:41:46.326   506   926 D CommandListener: Trying to bring down wlan0
,10-03 03:41:46.327   506   926 D CommandListener: Clearing all IP addresses on wlan0
,10-03 03:41:46.336   928  2929 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-03 03:41:46.558   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:47.013   928  2929 D wifi    : set interface wlan0 flags (UP)
,10-03 03:41:47.013   928  2929 I WifiHAL : Initializing wifi
,10-03 03:41:47.014   928  2929 I WifiHAL : Creating socket
,10-03 03:41:47.020   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-03 03:41:47.023   928  2929 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-03 03:41:47.024   928  2929 D wifi    : Did set static halHandle = 0x7f6e003b80
10-03 03:41:47.024   928  2929 D wifi    : halHandle = 0x7f6e003b80, mVM = 0x7f8a68d140, mCls = 0x20141e
,10-03 03:41:47.024   928  2929 D wifi    : array field set
10-03 03:41:47.025   928  2929 I WifiNative-HAL: interface[0] = wlan0
10-03 03:41:47.027   928  5984 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547306355584
10-03 03:41:47.027   928  5984 D wifi    : waitForHalEvents called, vm = 0x7f8a68d140, obj = 0x20141e, env = 0x7f6e8ce2c0
,10-03 03:41:47.089  5985  5985 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-03 03:41:47.110  5985  5985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-03 03:41:47.132   928  2929 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-03 03:41:47.138  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:47.141  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:41:47.160  5985  5985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-03 03:41:47.160  5985  5985 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-03 03:41:47.176   928  2929 D WifiConfigStore: Loading config and enabling all networks 
,10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:47.178  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-03 03:41:47.181  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-03 03:41:47.185  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-03 03:41:47.187  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-03 03:41:47.192   928  2929 D WifiConfigStore: loaded 0 passpoint configs
,10-03 03:41:47.192   928  2929 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-03 03:41:47.193   928  2929 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-03 03:41:47.194   928  2929 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-03 03:41:47.195   928  2929 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-03 03:41:47.195   928  2929 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-03 03:41:47.195   928  2929 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-03 03:41:47.196   928  2929 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-03 03:41:47.199   928  2929 D WifiNative-HAL: Setting external_sim to 1
,10-03 03:41:47.199  4401  4401 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-03 03:41:47.200   928  2929 D wifi    : setting dfs flag to true, 0x7f70fbfe80
10-03 03:41:47.200   928  2929 D WifiStateMachine: Setting OUI to DA-A1-19
10-03 03:41:47.201   928  2929 D wifi    : setting scan oui 0x7f70fbfe80
10-03 03:41:47.201   928  2929 D WifiHAL : Sending mac address OUI
,10-03 03:41:47.205   928  2929 E native  : do suspend false
,10-03 03:41:47.211   928  2929 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-03 03:41:47.212   506   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-03 03:41:47.212   928   928 D RttService: SCAN_AVAILABLE : 3
10-03 03:41:47.212   928  3064 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-03 03:41:47.213   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:47.216   928  2928 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-03 03:41:47.217   928  2928 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-03 03:41:47.225   928  2928 D WifiNative-HAL: p2pGetDeviceAddress
,10-03 03:41:47.226   928  2928 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-03 03:41:47.230   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302546 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-03 03:41:47.559   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-03 03:41:48.560   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-03 03:41:50.384  5985  5985 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:50.392  5985  5985 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:50.397  5985  5985 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:50.403  5985  5985 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-03 03:41:50.458   928  2929 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-03 03:41:50.459   928  2929 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-03 03:41:50.459   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:50.471   928  2929 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-03 03:41:50.504   928  2929 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-03 03:41:50.507  5985  5985 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-03 03:41:50.930  5985  5985 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-03 03:41:50.988  5985  5985 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-03 03:41:50.990  5985  5985 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-03 03:41:51.001   928  2929 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-03 03:41:51.002   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
10-03 03:41:51.002   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:51.019   928  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-03 03:41:51.033   506   926 D CommandListener: Setting iface cfg
,10-03 03:41:51.039   928  2929 D WifiStateMachine: Start Dhcp Watchdog 3
,10-03 03:41:51.045   928  5990 D DhcpClient: Receive thread started
,10-03 03:41:51.049   928  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-03 03:41:51.049   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-03 03:41:51.049   928  2941 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-03 03:41:51.129   928  2929 E native  : do suspend false
,10-03 03:41:51.144   928  5989 D DhcpClient: Broadcasting DHCPDISCOVER
,10-03 03:41:51.158   928  5990 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-03 03:41:51.159   928  5989 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-03 03:41:51.161   928  5989 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-03 03:41:51.190   928  5990 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-03 03:41:51.191   928  5989 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-03 03:41:51.195   506   926 D CommandListener: Setting iface cfg
10-03 03:41:51.199   928  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-03 03:41:51.204   928  5989 D DhcpClient: Scheduling renewal in 86399s
,10-03 03:41:51.213   928  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-03 03:41:51.214   928  2929 D WifiConfigStore: No blacklist allowed without epno enabled
10-03 03:41:51.215   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-03 03:41:51.217   928  2941 D ConnectivityService: Adding iface wlan0 to network 102
10-03 03:41:51.226   928  2929 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-03 03:41:51.263   928  2941 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-03 03:41:51.263   928  2941 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-03 03:41:51.265   928  2941 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-03 03:41:51.268   928  2941 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-03 03:41:51.270   928  2941 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-03 03:41:51.279   928  2941 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:41:51.283   928  2941 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-03 03:41:51.283   928  2941 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-03 03:41:51.283   928  2941 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-03 03:41:51.283   928  2929 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-03 03:41:51.283   928  2941 D ConnectivityService:    accepting network in place of null
10-03 03:41:51.283   928  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-03 03:41:51.284   928  2941 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-03 03:41:51.304   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-03 03:41:51.306   928  5988 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306622, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:51.321  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:41:51.322  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:51.323  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:41:51.323  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93449b4 removed from the list
10-03 03:41:51.323  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:41:51.323  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:41:51.323  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:41:51.326  5654  5999 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
10-03 03:41:51.326  5654  5999 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
10-03 03:41:51.326   506   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-03 03:41:51.330   928  2941 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-03 03:41:51.330   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-03 03:41:51.330  3737  3889 W QCNEJ   : |CORE| network available: 102
,10-03 03:41:51.332   928  2941 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-03 03:41:51.332  3737  3889 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-03 03:41:51.334   928   945 D Tethering: MasterInitialState.processMessage what=3
10-03 03:41:51.334  3737  3889 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-03 03:41:51.335  3737  3889 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:51.341  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:41:51.343  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:41:51.347  5654  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:41:51.347  5021  5034 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-03 03:41:51.347  5021  5034 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-03 03:41:51.347  5021  5034 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-03 03:41:51.347  5021  5034 E SarControlService: no key has been found,reset the power
10-03 03:41:51.348  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-03 03:41:51.348  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-03 03:41:51.348  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-03 03:41:51.348  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:51.349  5047  5047 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-03 03:41:51.349  5021  5059 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-03 03:41:51.349  5021  5059 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-03 03:41:51.350  5021  5059 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-03 03:41:51.350  5654  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:41:51.352  3984  3984 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-03 03:41:51.351  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-03 03:41:51.354  5047  5047 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-03 03:41:51.358  3984  3984 D SystemUpdateService: onCreate
,10-03 03:41:51.359  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000f003000000000000ffffffff]
10-03 03:41:51.359  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:51.359  5047  5061 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-03 03:41:51.360  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-03 03:41:51.360  5021  5031 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-03 03:41:51.362  5047  5061 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b25e051 HexData = [00000000f103000000000000ffffffff]
10-03 03:41:51.362  5047  5061 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-03 03:41:51.363  5047  5061 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-03 03:41:51.364  5047  5047 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-03 03:41:51.364  5021  5032 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-03 03:41:51.365  3984  3984 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-03 03:41:51.375  3984  3984 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-03 03:41:51.380  3984  5376 I iu.UploadsManager: num queued entries: 0
,10-03 03:41:51.380  3984  5376 I iu.UploadsManager: num updated entries: 0
,10-03 03:41:51.388  3984  3984 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-03 03:41:51.389  3984  3984 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-03 03:41:51.391   928  5987 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:400d:803::200e
,10-03 03:41:51.392  5785  5785 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-03 03:41:51.398  5785  5785 D SprintDMHelper: simOperator: 
,10-03 03:41:51.398  5785  5785 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-03 03:41:51.398  3984  6002 I SystemUpdateService: active receiver: enabled
,10-03 03:41:51.408  3984  5376 I iu.SyncManager: NEXT; no task
,10-03 03:41:51.424  3984  6002 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-03 03:41:51.429  3984  6002 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-03 03:41:51.429  3984  6002 I SystemUpdateService: now status is 0 (complete)
10-03 03:41:51.430  3984  6002 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-03 03:41:51.430  3984  6002 I SystemUpdateService: file has been verified
10-03 03:41:51.430  3984  6002 I SystemUpdateService: OTA package size = 21989297
,10-03 03:41:51.435  3984  6002 I SystemUpdateService: showing system update notification
10-03 03:41:51.437   928  5987 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 03 Oct 2016 07:41:51 GMT], X-Android-Received-Millis=[1475480511436], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475480511412]}
10-03 03:41:51.437   928  2941 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-03 03:41:51.437   928  2941 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-03 03:41:51.437   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-03 03:41:51.438   928  2941 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-03 03:41:51.446  3984  3984 D SystemUpdateService: onDestroy
,10-03 03:41:51.516  4401  6007 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-03 03:41:54.071   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:41:54.338  5654  6014 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,10-03 03:41:54.338  5654  5999 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
10-03 03:41:54.339  5654  5999 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,10-03 03:41:54.339  5654  6014 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-03 03:41:54.340  5654  6014 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-03 03:41:54.340  5654  5999 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-03 03:41:54.342  5654  5999 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-03 03:41:54.343  5654  6014 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-03 03:41:54.345  5654  6016 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:41:54.345  5654  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-03 03:41:54.345  5654  5999 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-03 03:41:54.346  5654  6018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:41:54.346  5654  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:41:54.347  5654  6018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:41:54.347  5654  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:41:54.347  5654  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:41:54.347  5654  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:41:54.348  5654  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-03 03:41:54.348  5654  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:41:54.348  5654  6014 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-03 03:41:54.348  5654  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:41:54.348  5654  6018 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-03 03:41:54.348  5654  6018 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-03 03:41:54.350  5654  6018 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-03 03:41:54.350  5654  6018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:41:54.350  5654  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-03 03:41:54.350  5654  6016 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 153, thread name: OutgoingSocketThread/Sender): Socket closed
10-03 03:41:54.351  5654  6016 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:41:54.351  5654  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-03 03:41:54.351  5654  6016 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-03 03:41:54.351  5654  6017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:41:54.351  5654  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:41:54.351  5654  6016 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-03 03:41:54.351  5654  6016 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:41:54.351  5654  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 152, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:41:54.352  5654  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:41:54.353  5654  6017 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-03 03:41:54.353  5654  6017 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-03 03:41:54.353  5654  6017 I io.jxcore.node.IncomingSocketThread: The sending thread is done
10-03 03:41:54.354  5654  6017 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 152, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:41:54.354  5654  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-03 03:41:54.355  5654  6019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:41:54.355  5654  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-03 03:41:54.356  5654  6019 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:41:54.356  5654  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:41:54.356  5654  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:41:54.356  5654  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:41:54.356  5654  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-03 03:41:54.356  5654  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:41:54.357  5654  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:41:54.357  5654  6019 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-03 03:41:54.357  5654  6019 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-03 03:41:54.357  5654  6019 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-03 03:41:54.357  5654  6019 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
10-03 03:41:54.357  5654  6019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:41:54.357  5654  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-03 03:41:57.095   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:41:57.340  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-03 03:41:57.341  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-03 03:41:57.346  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e1ee445 Bundle[{}]
,10-03 03:41:57.347  5654  5700 I io.jxcore.node.LifeCycleMonitor: start: OK
10-03 03:41:57.348  5654  5700 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-03 03:41:57.348  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-03 03:41:57.349  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-03 03:41:57.350  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-03 03:41:57.351  5654  5700 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-03 03:41:57.357  5654  5700 I System.out: Running OutgoingSocketThread
,10-03 03:41:57.359  5654  6020 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,10-03 03:41:57.360  5654  6020 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-03 03:41:59.285   928  2941 D ConnectivityService: handlePromptUnvalidated 102
,10-03 03:42:00.108   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:42:00.370  5654  6020 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,10-03 03:42:00.370  5654  6020 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-03 03:42:00.370  5654  6020 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-03 03:42:00.372  5654  6021 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,10-03 03:42:00.372  5654  6021 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-03 03:42:00.373  5654  6021 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-03 03:42:00.375  5654  6021 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-03 03:42:00.375  5654  6020 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-03 03:42:00.378  5654  6024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:42:00.378  5654  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,10-03 03:42:00.380  5654  6021 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,10-03 03:42:00.382  5654  6020 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-03 03:42:00.384  5654  6023 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:42:00.384  5654  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:00.384  5654  6025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:42:00.384  5654  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:42:00.385  5654  6026 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:42:00.385  5654  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-03 03:42:00.385  5654  6025 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:42:00.385  5654  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:42:00.385  5654  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:42:00.385  5654  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-03 03:42:00.386  5654  6025 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:42:00.386  5654  6025 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-03 03:42:00.386  5654  6026 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:42:00.387  5654  6026 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-03 03:42:00.387  5654  6026 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-03 03:42:00.387  5654  6026 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-03 03:42:00.387  5654  6026 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
10-03 03:42:00.387  5654  6026 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-03 03:42:00.387  5654  6024 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 165, thread name: IncomingSocketThread/Sender): Socket closed
,10-03 03:42:00.387  5654  6024 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:42:00.387  5654  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-03 03:42:00.387  5654  6024 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-03 03:42:00.387  5654  6024 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-03 03:42:00.388  5654  6024 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:42:00.388  5654  6024 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-03 03:42:00.388  5654  6023 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 164, thread name: OutgoingSocketThread/Sender): Socket closed
,10-03 03:42:00.389  5654  6023 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 164, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:42:00.389  5654  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-03 03:42:00.389  5654  6023 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-03 03:42:00.389  5654  6023 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-03 03:42:00.389  5654  6023 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
10-03 03:42:00.389  5654  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-03 03:42:02.227   928  2929 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-03 03:42:03.138   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:42:03.370  5654  5700 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,10-03 03:42:03.372  5654  5700 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,10-03 03:42:03.372  5654  5700 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,10-03 03:42:03.378  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-03 03:42:03.378  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef069dd added. We now have 3 listener(s)
,10-03 03:42:03.381  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-03 03:42:03.381  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.381  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.382  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-03 03:42:03.382  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c9952 added. We now have 4 listener(s)
10-03 03:42:03.382  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-03 03:42:03.383  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-03 03:42:03.389  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:42:03.397  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:42:03.399  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.400  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-03 03:42:03.400  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.400  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a64d20 added. We now have 4 listener(s)
10-03 03:42:03.402  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.402  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.402  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.402  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.402  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ec6d9 added. We now have 5 listener(s)
10-03 03:42:03.402  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.403  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:42:03.403  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.403  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:42:03.403  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.403  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-03 03:42:03.403  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.403  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.403  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.403  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.403  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef069dd removed from the list
10-03 03:42:03.403  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.403  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c9952 removed from the list
10-03 03:42:03.406  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.407  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:42:03.407  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:42:03.408  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.408  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:42:03.409  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:42:03.409  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.409  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.409  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8c9952 not in the list
10-03 03:42:03.409  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.409  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:42:03.411  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.411  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:42:03.411  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.411  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0ec6d9 removed from the list
10-03 03:42:03.411  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.411  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.411  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.412  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.412  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.412  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a64d20 removed from the list
10-03 03:42:03.412  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.413  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db6f89e added. We now have 3 listener(s)
,10-03 03:42:03.415  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.415  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.415  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.415  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.415  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc2f7f added. We now have 4 listener(s)
10-03 03:42:03.415  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.416  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-03 03:42:03.419  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:42:03.424  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:42:03.427  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.427  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:42:03.427  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-03 03:42:03.427  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1bf795 added. We now have 4 listener(s)
,10-03 03:42:03.429  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.429  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.429  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.429  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.429  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9600aa added. We now have 5 listener(s)
10-03 03:42:03.429  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.430  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:03.430  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-03 03:42:03.430  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-03 03:42:03.430  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:42:03.430  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-03 03:42:03.430  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:42:03.433  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.434  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-03 03:42:03.434  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-03 03:42:03.438  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-03 03:42:03.439  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-03 03:42:03.439  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-03 03:42:03.442  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-03 03:42:03.443  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-03 03:42:03.443  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-03 03:42:03.443  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-03 03:42:03.443  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-03 03:42:03.443  5654  5700 D BluetoothAdapter: STATE_ON
,10-03 03:42:03.447  5932  5968 D BtGatt.GattService: registerClient() - UUID=d20465a3-895e-4c21-9b0f-3ac49646d546
,10-03 03:42:03.448  5932  5948 D BtGatt.GattService: onClientRegistered() - UUID=d20465a3-895e-4c21-9b0f-3ac49646d546, clientIf=5
10-03 03:42:03.449  5654  5665 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-03 03:42:03.450  5932  5942 D BtGatt.GattService: start scan with filters
,10-03 03:42:03.454  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-03 03:42:03.454  5932  5951 D BtGatt.ScanManager: handling starting scan
10-03 03:42:03.454  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-03 03:42:03.454  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:42:03.454  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-03 03:42:03.454  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-03 03:42:03.454  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-03 03:42:03.454  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-03 03:42:03.455  5932  5951 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@685d08e
,10-03 03:42:03.457  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:42:03.457  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-03 03:42:03.457  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-03 03:42:03.458  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-03 03:42:03.461  5654  5700 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-03 03:42:03.461  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.461  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-03 03:42:03.461  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.461  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-03 03:42:03.461  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.461  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-03 03:42:03.461  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-03 03:42:03.461  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:42:03.461  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:42:03.461  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-03 03:42:03.461  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-03 03:42:03.463  5654  5700 D BluetoothAdapter: STATE_ON
,10-03 03:42:03.463  5932  5942 D BtGatt.GattService: stopScan() - queue size =1
10-03 03:42:03.463  5932  5948 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-03 03:42:03.464  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.464  5932  5951 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-03 03:42:03.464  5932  5960 D BtGatt.GattService: unregisterClient() - clientIf=5
10-03 03:42:03.465  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-03 03:42:03.465  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-03 03:42:03.465  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-03 03:42:03.465  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:42:03.465  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-03 03:42:03.465  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-03 03:42:03.465  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-03 03:42:03.465  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-03 03:42:03.466  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:42:03.467  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-03 03:42:03.467  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-03 03:42:03.467  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-03 03:42:03.467  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-03 03:42:03.468  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.469  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:42:03.469  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:42:03.469  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-03 03:42:03.471  5932  5948 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-03 03:42:03.471  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.473  5932  5951 D BtGatt.ScanManager: Starting BLE batch scan
,10-03 03:42:03.473  5932  5951 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-03 03:42:03.475  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-03 03:42:03.475  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.475  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:42:03.475  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.475  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.475  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.475  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.475  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.475  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db6f89e removed from the list
10-03 03:42:03.475  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.476  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc2f7f removed from the list
,10-03 03:42:03.476  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:42:03.476  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.477  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.477  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.478  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:42:03.478  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.478  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.479  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc2f7f not in the list
10-03 03:42:03.479  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:42:03.479  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.480  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.480  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:42:03.480  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.480  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9600aa removed from the list
10-03 03:42:03.480  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.480  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.480  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:42:03.480  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.480  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.480  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1bf795 removed from the list
10-03 03:42:03.481  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.481  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ab7d76 added. We now have 3 listener(s)
10-03 03:42:03.482  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.482  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.482  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.483  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.483  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828f77 added. We now have 4 listener(s)
,10-03 03:42:03.483  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.483  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-03 03:42:03.484  5932  5948 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-03 03:42:03.484  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.486  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:42:03.490  5932  5948 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-03 03:42:03.490  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:42:03.491  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:42:03.493  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.493  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:42:03.493  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.493  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@104844d added. We now have 4 listener(s)
,10-03 03:42:03.495  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-03 03:42:03.495  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.495  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.496  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.496  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc9fb02 added. We now have 5 listener(s)
10-03 03:42:03.496  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.496  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:03.496  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.496  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:03.496  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-03 03:42:03.497  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-03 03:42:03.497  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:42:03.497  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-03 03:42:03.497  5932  5948 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-03 03:42:03.497  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.498  5932  5951 D BtGatt.ScanManager: stopping BLe Batch
10-03 03:42:03.499  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.500  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-03 03:42:03.500  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-03 03:42:03.503  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-03 03:42:03.503  5932  5948 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-03 03:42:03.503  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.503  5932  5951 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-03 03:42:03.505  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-03 03:42:03.505  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-03 03:42:03.508  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-03 03:42:03.508  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-03 03:42:03.508  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-03 03:42:03.508  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-03 03:42:03.508  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-03 03:42:03.508  5932  5948 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-03 03:42:03.509  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.509  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:42:03.512  5932  5968 D BtGatt.GattService: registerClient() - UUID=0ed5e69f-ff5e-4530-b926-25d9eff7b3c0
,10-03 03:42:03.513  5932  5948 D BtGatt.GattService: onClientRegistered() - UUID=0ed5e69f-ff5e-4530-b926-25d9eff7b3c0, clientIf=5
,10-03 03:42:03.513  5654  5665 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-03 03:42:03.513  5932  5960 D BtGatt.GattService: start scan with filters
,10-03 03:42:03.516  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-03 03:42:03.516  5932  5951 D BtGatt.ScanManager: handling starting scan
10-03 03:42:03.516  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-03 03:42:03.516  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:42:03.516  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-03 03:42:03.516  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-03 03:42:03.516  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-03 03:42:03.516  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-03 03:42:03.518  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:42:03.519  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-03 03:42:03.519  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-03 03:42:03.520  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-03 03:42:03.522  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:03.522  5654  5700 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-03 03:42:03.522  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:42:03.522  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.522  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:42:03.522  5932  5948 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-03 03:42:03.522  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.522  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.522  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.522  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-03 03:42:03.522  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.522  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.522  5932  5951 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-03 03:42:03.522  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ab7d76 removed from the list
10-03 03:42:03.522  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.522  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828f77 removed from the list
10-03 03:42:03.522  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:42:03.522  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.523  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.523  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-03 03:42:03.523  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:42:03.523  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-03 03:42:03.526  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:42:03.526  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.526  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.526  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6828f77 not in the list
10-03 03:42:03.526  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-03 03:42:03.526  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:42:03.526  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:42:03.526  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-03 03:42:03.526  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-03 03:42:03.527  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:42:03.527  5932  5948 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-03 03:42:03.527  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.527  5932  5951 D BtGatt.ScanManager: Starting BLE batch scan
10-03 03:42:03.527  5932  5951 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-03 03:42:03.528  5932  5943 D BtGatt.GattService: stopScan() - queue size =1
10-03 03:42:03.529  5932  5942 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-03 03:42:03.529  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-03 03:42:03.529  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-03 03:42:03.529  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-03 03:42:03.529  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-03 03:42:03.529  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-03 03:42:03.529  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-03 03:42:03.530  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-03 03:42:03.530  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-03 03:42:03.531  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:42:03.531  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-03 03:42:03.531  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-03 03:42:03.531  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-03 03:42:03.531  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-03 03:42:03.531  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.532  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.532  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:42:03.532  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.532  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:42:03.532  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc9fb02 removed from the list
10-03 03:42:03.532  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.532  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:42:03.532  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.532  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:42:03.532  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.532  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.532  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.532  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@104844d removed from the list
,10-03 03:42:03.533  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.533  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@460c54e added. We now have 3 listener(s)
10-03 03:42:03.535  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.535  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.535  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.536  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.536  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f66f added. We now have 4 listener(s)
10-03 03:42:03.536  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.536  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-03 03:42:03.536  5932  5948 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-03 03:42:03.536  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.541  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:42:03.542  5932  5948 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-03 03:42:03.542  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:42:03.545  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-03 03:42:03.548  5932  5948 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-03 03:42:03.548  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.548  5932  5951 D BtGatt.ScanManager: stopping BLe Batch
,10-03 03:42:03.549  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-03 03:42:03.549  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:42:03.549  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.549  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76af005 added. We now have 4 listener(s)
10-03 03:42:03.550  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.550  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.550  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.551  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.551  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@687e85a added. We now have 5 listener(s)
10-03 03:42:03.551  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.551  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:03.551  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-03 03:42:03.551  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-03 03:42:03.551  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-03 03:42:03.551  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-03 03:42:03.553  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.553  5654  5700 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-03 03:42:03.554  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-03 03:42:03.554  5932  5948 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-03 03:42:03.554  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.555  5932  5951 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-03 03:42:03.555  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-03 03:42:03.557  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-03 03:42:03.558  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-03 03:42:03.558  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-03 03:42:03.560  5932  5948 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-03 03:42:03.560  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.560  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-03 03:42:03.560  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-03 03:42:03.561  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-03 03:42:03.561  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-03 03:42:03.561  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-03 03:42:03.561  5654  5700 D BluetoothAdapter: STATE_ON
,10-03 03:42:03.563  5932  5942 D BtGatt.GattService: registerClient() - UUID=83f82a6f-1ae6-4b1c-8c66-367653b86b09
10-03 03:42:03.563  5932  5948 D BtGatt.GattService: onClientRegistered() - UUID=83f82a6f-1ae6-4b1c-8c66-367653b86b09, clientIf=5
10-03 03:42:03.564  5654  5664 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-03 03:42:03.564  5932  5943 D BtGatt.GattService: start scan with filters
10-03 03:42:03.566  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-03 03:42:03.566  5932  5951 D BtGatt.ScanManager: handling starting scan
10-03 03:42:03.566  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-03 03:42:03.566  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:42:03.566  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-03 03:42:03.566  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-03 03:42:03.566  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-03 03:42:03.566  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-03 03:42:03.568  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-03 03:42:03.568  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-03 03:42:03.568  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-03 03:42:03.569  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-03 03:42:03.571  5932  5948 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-03 03:42:03.571  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.572  5932  5951 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-03 03:42:03.573  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:42:03.573  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.573  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:42:03.573  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.573  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.573  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-03 03:42:03.573  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-03 03:42:03.573  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.573  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@460c54e removed from the list
10-03 03:42:03.574  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.574  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f66f removed from the list
10-03 03:42:03.574  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:42:03.574  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.574  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.574  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-03 03:42:03.574  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.574  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.575  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:42:03.575  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.575  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-03 03:42:03.576  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f66f not in the list
10-03 03:42:03.576  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-03 03:42:03.576  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-03 03:42:03.576  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-03 03:42:03.576  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-03 03:42:03.576  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-03 03:42:03.576  5654  5700 D BluetoothAdapter: STATE_ON
10-03 03:42:03.577  5932  5943 D BtGatt.GattService: stopScan() - queue size =1
10-03 03:42:03.577  5932  5948 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-03 03:42:03.577  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.577  5932  5968 D BtGatt.GattService: unregisterClient() - clientIf=5
10-03 03:42:03.577  5932  5951 D BtGatt.ScanManager: Starting BLE batch scan
10-03 03:42:03.577  5932  5951 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-03 03:42:03.577  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-03 03:42:03.577  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-03 03:42:03.578  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-03 03:42:03.578  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-03 03:42:03.578  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-03 03:42:03.578  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-03 03:42:03.578  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-03 03:42:03.578  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-03 03:42:03.579  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:42:03.579  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-03 03:42:03.579  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-03 03:42:03.579  5654  5700 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-03 03:42:03.579  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-03 03:42:03.579  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.580  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.580  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-03 03:42:03.580  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.580  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@687e85a removed from the list
10-03 03:42:03.580  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:42:03.580  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.580  5654  5654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-03 03:42:03.580  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.580  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.580  5654  5654 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-03 03:42:03.580  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.580  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.580  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76af005 removed from the list
,10-03 03:42:03.581  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.581  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcc3026 added. We now have 3 listener(s)
10-03 03:42:03.582  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.582  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.582  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-03 03:42:03.582  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-03 03:42:03.582  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4004467 added. We now have 4 listener(s)
10-03 03:42:03.583  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.585  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-03 03:42:03.587  5932  5948 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-03 03:42:03.587  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.587  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-03 03:42:03.592  5932  5948 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-03 03:42:03.592  5654  5700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-03 03:42:03.592  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.593  5654  5700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-03 03:42:03.594  5654  5700 D io.jxcore.node.ConnectivityMonitor: start: OK
10-03 03:42:03.594  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-03 03:42:03.594  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c1abd added. We now have 4 listener(s)
10-03 03:42:03.595  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-03 03:42:03.595  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-03 03:42:03.595  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-03 03:42:03.595  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-03 03:42:03.595  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb28b2 added. We now have 5 listener(s)
10-03 03:42:03.595  5654  5700 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-03 03:42:03.595  5654  5700 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-03 03:42:03.595  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.595  5654  5700 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-03 03:42:03.596  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.596  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.596  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.596  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-03 03:42:03.596  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.596  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.596  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcc3026 removed from the list
10-03 03:42:03.596  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.596  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4004467 removed from the list
10-03 03:42:03.598  5932  5948 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-03 03:42:03.598  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.598  5932  5951 D BtGatt.ScanManager: stopping BLe Batch
10-03 03:42:03.599  5654  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-03 03:42:03.599  5654  5700 D io.jxcore.node.ConnectivityMonitor: stop
10-03 03:42:03.599  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-03 03:42:03.599  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-03 03:42:03.599  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.600  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:42:03.600  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.600  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.600  5654  5700 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4004467 not in the list
10-03 03:42:03.600  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.600  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.601  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-03 03:42:03.601  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-03 03:42:03.601  5654  5700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-03 03:42:03.601  5654  5700 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb28b2 removed from the list
,10-03 03:42:03.601  5654  5700 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-03 03:42:03.601  5654  5700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-03 03:42:03.601  5654  5700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-03 03:42:03.601  5654  5700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-03 03:42:03.601  5654  5700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-03 03:42:03.601  5654  5700 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84c1abd removed from the list
10-03 03:42:03.602  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-03 03:42:03.602  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-03 03:42:03.602  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-03 03:42:03.602  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:03.602  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-03 03:42:03.602  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:03.603  5932  5948 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-03 03:42:03.603  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-03 03:42:03.603  5932  5951 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-03 03:42:03.608  5932  5948 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-03 03:42:03.608  5932  5948 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-03 03:42:03.971  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-03 03:42:04.033  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-03 03:42:04.081  5654  5654 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-03 03:42:05.753  5654  6027 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-03 03:42:05.753  5654  6027 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:06.170   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:42:06.648  5654  6027 W !!      : call onHalfStreamCopied
,10-03 03:42:06.648  5654  6027 I testCopyDataAndClose: closing input stream
,10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing,
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-03 03:42:07.427  5654  6027 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-03 03:42:11.197  5654  6028 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:11.197  5654  6028 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:12.212   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:42:13.197  5654  5700 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 188. Connection data: Peer properties: [null null].
10-03 03:42:13.197  5654  5700 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:13.197  5654  5700 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 188, name: My test thread name)
,10-03 03:42:13.334  5654  6029 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-03 03:42:13.334  5654  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:13.352  5654  6028 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-03 03:42:13.352  5654  6028 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:13.352  5654  6028 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,10-03 03:42:13.561   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-03 03:42:13.561   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:42:14.959  5654  6029 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-03 03:42:14.960  5654  6029 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-03 03:42:14.960  5654  6029 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-03 03:42:14.960  5654  6029 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-03 03:42:18.261   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:42:18.721  5654  6030 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:18.721  5654  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-03 03:42:18.722  5654  6030 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-03 03:42:18.723  5654  6030 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-03 03:42:18.723  5654  6030 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:18.723  5654  6030 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-03 03:42:18.724  5654  5700 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-03 03:42:18.727  5654  6031 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:18.727  5654  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-03 03:42:18.730  5654  6031 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
,10-03 03:42:18.730  5654  6031 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:18.730  5654  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-03 03:42:18.730  5654  6031 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-03 03:42:18.731  5654  6031 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
10-03 03:42:18.731  5654  6031 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-03 03:42:18.735  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
10-03 03:42:18.735  5654  5700 I jxcore-log: 
,10-03 03:42:18.735  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-03 03:42:18.735  5654  5700 I jxcore-log: 
10-03 03:42:18.735  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Number of failed tests:  2'
10-03 03:42:18.735  5654  5700 I jxcore-log: 
10-03 03:42:18.735  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-03 03:42:18.735  5654  5700 I jxcore-log: 
,10-03 03:42:18.736  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Total duration:  102957'
10-03 03:42:18.736  5654  5700 I jxcore-log: 
10-03 03:42:18.737  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Failures: 
10-03 03:42:18.737  5654  5700 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
10-03 03:42:18.737  5654  5700 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
10-03 03:42:18.737  5654  5700 I jxcore-log:      but: was ""
10-03 03:42:18.737  5654  5700 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
10-03 03:42:18.737  5654  5700 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
10-03 03:42:18.737  5654  5700 I jxcore-log:      but: was ""
10-03 03:42:18.737  5654  5700 I jxcore-log: '
10-03 03:42:18.737  5654  5700 I jxcore-log: 
10-03 03:42:18.738  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-03 03:42:18.738  5654  5700 I jxcore-log: 
,10-03 03:42:18.739  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-03 03:42:18.739  5654  5700 I jxcore-log: 
,10-03 03:42:18.743  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.743  5654  5700 I jxcore-log: 
10-03 03:42:18.743  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.743  5654  5700 I jxcore-log: 
10-03 03:42:18.744  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.744  5654  5700 I jxcore-log: 
10-03 03:42:18.744  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.744  5654  5700 I jxcore-log: 
10-03 03:42:18.745  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-03 03:42:18.745  5654  5700 I jxcore-log: 
10-03 03:42:18.745  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-03 03:42:18.745  5654  5700 I jxcore-log: 
10-03 03:42:18.745  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.745  5654  5700 I jxcore-log: 
10-03 03:42:18.746  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.746  5654  5700 I jxcore-log: 
,10-03 03:42:18.746  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-03 03:42:18.746  5654  5700 I jxcore-log: 
10-03 03:42:18.746  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-03 03:42:18.746  5654  5700 I jxcore-log: 
10-03 03:42:18.746  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-03 03:42:18.746  5654  5700 I jxcore-log: 
10-03 03:42:18.747  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.747  5654  5700 I jxcore-log: 
10-03 03:42:18.747  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.747  5654  5700 I jxcore-log: 
10-03 03:42:18.747  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.747  5654  5700 I jxcore-log: 
10-03 03:42:18.748  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.748  5654  5700 I jxcore-log: 
10-03 03:42:18.748  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.748  5654  5700 I jxcore-log: 
10-03 03:42:18.748  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.748  5654  5700 I jxcore-log: 
10-03 03:42:18.748  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.748  5654  5700 I jxcore-log: 
,10-03 03:42:18.749  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.749  5654  5700 I jxcore-log: 
10-03 03:42:18.749  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.749  5654  5700 I jxcore-log: 
10-03 03:42:18.749  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.749  5654  5700 I jxcore-log: 
,10-03 03:42:18.750  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.750  5654  5700 I jxcore-log: 
,10-03 03:42:18.752  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.752  5654  5700 I jxcore-log: 
10-03 03:42:18.752  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.752  5654  5700 I jxcore-log: 
10-03 03:42:18.752  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.752  5654  5700 I jxcore-log: 
10-03 03:42:18.752  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.752  5654  5700 I jxcore-log: 
10-03 03:42:18.753  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.753  5654  5700 I jxcore-log: 
10-03 03:42:18.753  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.753  5654  5700 I jxcore-log: 
10-03 03:42:18.753  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.753  5654  5700 I jxcore-log: 
10-03 03:42:18.753  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.753  5654  5700 I jxcore-log: 
10-03 03:42:18.754  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.754  5654  5700 I jxcore-log: 
10-03 03:42:18.754  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.754  5654  5700 I jxcore-log: 
,10-03 03:42:18.754  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.754  5654  5700 I jxcore-log: 
10-03 03:42:18.754  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.754  5654  5700 I jxcore-log: 
10-03 03:42:18.755  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.755  5654  5700 I jxcore-log: 
10-03 03:42:18.755  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.755  5654  5700 I jxcore-log: 
10-03 03:42:18.755  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.755  5654  5700 I jxcore-log: 
10-03 03:42:18.755  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-03 03:42:18.755  5654  5700 I jxcore-log: 
,10-03 03:42:18.755  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.755  5654  5700 I jxcore-log: 
10-03 03:42:18.756  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-03 03:42:18.756  5654  5700 I jxcore-log: 
10-03 03:42:18.756  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.756  5654  5700 I jxcore-log: 
10-03 03:42:18.756  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.756  5654  5700 I jxcore-log: 
10-03 03:42:18.756  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.756  5654  5700 I jxcore-log: 
10-03 03:42:18.757  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.757  5654  5700 I jxcore-log: 
10-03 03:42:18.757  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.757  5654  5700 I jxcore-log: 
10-03 03:42:18.757  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-03 03:42:18.757  5654  5700 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,10-03 03:42:18.758  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.758  5654  5700 I jxcore-log: 
10-03 03:42:18.758  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.758  5654  5700 I jxcore-log: 
10-03 03:42:18.758  5654  5700 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-03 03:42:18.758  5654  5700 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-03 03:42:18.758  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-03 03:42:18.758  5654  5700 I jxcore-log: 
10-03 03:42:18.759  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-03 03:42:18.759  5654  5700 I jxcore-log: 
10-03 03:42:18.759  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-03 03:42:18.759  5654  5700 I jxcore-log: 
10-03 03:42:18.759  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-03 03:42:18.759  5654  5700 I jxcore-log: 
10-03 03:42:18.765  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-03 03:42:18.765  5654  5700 I jxcore-log: 
10-03 03:42:18.765  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - WARN testUtils: 'myNameCallback not set!'
10-03 03:42:18.765  5654  5700 I jxcore-log: 
10-03 03:42:18.766  5654  5654 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-03 03:42:18.766  5654  5700 I jxcore-log: 2016-10-03 07:42:18 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-03 03:42:18.766  5654  5700 I jxcore-log: 
,10-03 03:42:19.955   928  5988 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-03 03:42:20.763  5654  5700 I jxcore-log: 2016-10-03 07:42:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-03 03:42:20.763  5654  5700 I jxcore-log: 
,10-03 03:42:21.098  5654  5700 I jxcore-log: 2016-10-03 07:42:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-03 03:42:21.098  5654  5700 I jxcore-log: 
,10-03 03:42:21.112  5654  5700 I jxcore-log: 2016-10-03 07:42:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-03 03:42:21.112  5654  5700 I jxcore-log: 
,10-03 03:42:22.212  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-03 03:42:22.212  5654  5700 I jxcore-log: 
,10-03 03:42:22.372  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-03 03:42:22.372  5654  5700 I jxcore-log: 
,10-03 03:42:22.376  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-03 03:42:22.376  5654  5700 I jxcore-log: 
,10-03 03:42:22.381  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-03 03:42:22.381  5654  5700 I jxcore-log: 
,10-03 03:42:22.921  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-03 03:42:22.921  5654  5700 I jxcore-log: 
,10-03 03:42:22.973  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-03 03:42:22.973  5654  5700 I jxcore-log: 
,10-03 03:42:22.985  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-03 03:42:22.985  5654  5700 I jxcore-log: 
,10-03 03:42:22.990  5654  5700 I jxcore-log: 2016-10-03 07:42:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-03 03:42:22.990  5654  5700 I jxcore-log: 
,10-03 03:42:23.265  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-03 03:42:23.265  5654  5700 I jxcore-log: 
,10-03 03:42:23.388  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-03 03:42:23.388  5654  5700 I jxcore-log: 
,10-03 03:42:23.619  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-03 03:42:23.619  5654  5700 I jxcore-log: 
,10-03 03:42:23.630  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-03 03:42:23.630  5654  5700 I jxcore-log: 
,10-03 03:42:23.634  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-03 03:42:23.634  5654  5700 I jxcore-log: 
,10-03 03:42:23.772  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-03 03:42:23.772  5654  5700 I jxcore-log: 
,10-03 03:42:23.779  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-03 03:42:23.779  5654  5700 I jxcore-log: 
,10-03 03:42:23.806  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-03 03:42:23.806  5654  5700 I jxcore-log: 
,10-03 03:42:23.840  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-03 03:42:23.840  5654  5700 I jxcore-log: 
,10-03 03:42:23.848  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-03 03:42:23.848  5654  5700 I jxcore-log: 
,10-03 03:42:23.854  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-03 03:42:23.854  5654  5700 I jxcore-log: 
,10-03 03:42:23.869  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-03 03:42:23.869  5654  5700 I jxcore-log: 
,10-03 03:42:23.874  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-03 03:42:23.874  5654  5700 I jxcore-log: 
,10-03 03:42:23.880  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-03 03:42:23.880  5654  5700 I jxcore-log: 
,10-03 03:42:23.885  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-03 03:42:23.885  5654  5700 I jxcore-log: 
,10-03 03:42:23.898  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-03 03:42:23.898  5654  5700 I jxcore-log: 
,10-03 03:42:23.918  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-03 03:42:23.918  5654  5700 I jxcore-log: 
,10-03 03:42:23.928  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-03 03:42:23.928  5654  5700 I jxcore-log: 
,10-03 03:42:23.939  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-03 03:42:23.939  5654  5700 I jxcore-log: 
,10-03 03:42:23.948  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-03 03:42:23.948  5654  5700 I jxcore-log: 
,10-03 03:42:23.959  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-03 03:42:23.959  5654  5700 I jxcore-log: 
,10-03 03:42:23.969  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-03 03:42:23.969  5654  5700 I jxcore-log: 
,10-03 03:42:23.974  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-03 03:42:23.974  5654  5700 I jxcore-log: 
,10-03 03:42:23.995  5654  5700 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-03 03:42:23.996  5654  5700 I jxcore-log: 2016-10-03 07:42:23 - INFO testUtils: 'BLE multiple advertisement supported'
10-03 03:42:23.996  5654  5700 I jxcore-log: 
,10-03 03:42:24.310   928  2941 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-03 03:42:24.382  5654  5700 I jxcore-log: 2016-10-03 07:42:24 - DEBUG CoordinatedClient: 'connected to the test server'
10-03 03:42:24.382  5654  5700 I jxcore-log: 
,10-03 03:42:24.537  5654  5700 I jxcore-log: 2016-10-03 07:42:24 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-03 03:42:24.537  5654  5700 I jxcore-log: 
,10-03 03:42:24.541  5654  5700 I jxcore-log: 2016-10-03 07:42:24 - DEBUG CoordinatedClient: 'test client failed'
10-03 03:42:24.541  5654  5700 I jxcore-log: 
,10-03 03:42:24.546  5654  5700 I jxcore-log: 2016-10-03 07:42:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-03 03:42:24.546  5654  5700 I jxcore-log: 
,10-03 03:42:24.553  5654  5700 I jxcore-log: 2016-10-03 07:42:24 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-03 03:42:24.553  5654  5700 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-03 03:42:24.553  5654  5700 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-03 03:42:24.553  5654  5700 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-03 03:42:24.553  5654  5700 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-03 03:42:24.553  5654  5700 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-03 03:42:24.553  5654  5700 I jxcore-log: 
,10-03 03:42:24.553  5654  5700 I jxcore-log: 2016-10-03 07:42:24 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-03 03:42:24.553  5654  5700 I jxcore-log: 
,10-03 03:42:25.114  6040  6040 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-03 03:42:25.120  6040  6040 D AndroidRuntime: CheckJNI is OFF
,10-03 03:42:25.152  6040  6040 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-03 03:42:25.186  6040  6040 I Radio-JNI: register_android_hardware_Radio DONE
,10-03 03:42:25.203  6040  6040 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-03 03:42:25.212   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-03 03:42:25.213   928   941 I ActivityManager: Killing 5654:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-03 03:42:25.313   928  3875 D GraphicsStats: Buffer count: 2
,10-03 03:42:25.313   928  3395 I WindowState: WIN DEATH: Window{dda6970 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-03 03:42:25.314   928  2936 D WifiService: Client connection lost with reason: 4
,10-03 03:42:25.349   928   951 I art     : Starting a blocking GC Explicit
,10-03 03:42:25.348   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-03 03:42:25.350   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-03 03:42:25.351   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-03 03:42:25.351   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-03 03:42:25.351   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.351   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.351   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-03 03:42:25.351   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-03 03:42:25.351   928   941 I ActivityManager:   Force finishing activity ActivityRecord{7598e0d u0 com.test.thalitest/.MainActivity t2}
,10-03 03:42:25.361   928  3826 W ActivityManager: Spurious death for ProcessRecord{c1eef9a 0:com.test.thalitest/u0a77}, curProc for 5654: null
,10-03 03:42:25.365   928   946 W WindowManager: Attempted to add application window with unknown token Token{577a1c2 ActivityRecord{7598e0d u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
10-03 03:42:25.365   928   946 W WindowManager: Token{577a1c2 ActivityRecord{7598e0d u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{577a1c2 ActivityRecord{7598e0d u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-03 03:42:25.365   928   946 W WindowManager: view not successfully added to wm, removing view
10-03 03:42:25.366   928   946 W WindowManager: Exception when adding starting window
10-03 03:42:25.366   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{bd8fefd V.E...... R.....ID 0,0-0,0} not attached to window manager
10-03 03:42:25.366   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-03 03:42:25.366   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-03 03:42:25.366   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-03 03:42:25.366   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-03 03:42:25.366   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-03 03:42:25.366   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.366   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.366   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-03 03:42:25.366   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-03 03:42:25.431   928   951 I art     : Explicit concurrent mark sweep GC freed 58128(3MB) AllocSpace objects, 17(636KB) LOS objects, 33% free, 29MB/43MB, paused 1.540ms total 81.639ms
,10-03 03:42:25.450   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-03 03:42:25.453  6040  6040 I art     : System.exit called, status: 0
,10-03 03:42:25.453  6040  6040 I AndroidRuntime: VM exiting with result code 0.
,10-03 03:42:25.467   928   951 I ActivityManager: Start proc 6050:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-03 03:42:25.467   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-03 03:42:25.472   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-03 03:42:25.478  5932  5932 D BluetoothMapAppObserver: onReceive
,10-03 03:42:25.480  5932  5932 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-03 03:42:25.480  3714  4080 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-03 03:42:25.484  3642  3642 I Keyboard.Facilitator: resetDictionaries() : en_US
10-03 03:42:25.487   928  2921 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-03 03:42:25.509  3642  6062 I Keyboard.Facilitator.DecoderInitializer: run()
,10-03 03:42:25.521  3642  6062 I Decoder : createOrResetDecoder
,10-03 03:42:25.523  3790  3790 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-03 03:42:25.526  3381  6063 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-03 03:42:25.551   421   421 W kworker/4:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-03 03:42:25.554   421   421 W kworker/4:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-03 03:42:25.573  3565  3565 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-03 03:42:25.573  3565  3565 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-03 03:42:25.571   421   421 W kworker/4:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-03 03:42:25.586   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-03 03:42:25.591  3823  3915 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-03 03:42:25.594   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,10-03 03:42:25.595   928   940 E PackageManager: Failed to write settings, restoring backup
10-03 03:42:25.595   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-03 03:42:25.595   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-03 03:42:25.595   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-03 03:42:25.595   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-03 03:42:25.595   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-03 03:42:25.595   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.595   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.595   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-03 03:42:25.597  3381  3406 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjF01D719C7) - 
,10-03 03:42:25.600   928   941 E DropBoxManagerService: Can't write: system_server_wtf
10-03 03:42:25.600   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-03 03:42:25.600   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-03 03:42:25.600   928   941 E DropBoxManagerService: 	... 13 more
,10-03 03:42:25.605   928  3581 I ActivityManager: Start proc 6070:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-03 03:42:25.605  3823  3915 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-03 03:42:25.605  3823  3915 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3823
10-03 03:42:25.605  3823  3915 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.605  3823  3915 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-03 03:42:25.610   928  6077 E DropBoxManagerService: Can't write: system_app_crash
10-03 03:42:25.610   928  6077 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-03 03:42:25.610   928  6077 E DropBoxManagerService: 	... 5 more
,10-03 03:42:25.623  3381  6063 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-03 03:42:25.625  3381  6063 I Process : Sending signal. PID: 3381 SIG: 9
,10-03 03:42:25.631   928  3882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-03 03:42:25.647  3565  3565 I ConfigService: onCreate
,10-03 03:42:25.648  3984  6084 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-03 03:42:25.648  3823  3915 I Process : Sending signal. PID: 3823 SIG: 9
10-03 03:42:25.648  3984  6084 D AccountUtils: Clearing selected account for com.test.thalitest
,10-03 03:42:25.651  3565  6085 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-03 03:42:25.651  3565  6085 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-03 03:42:25.652  3565  6085 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-03 03:42:25.653  3565  6085 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-03 03:42:25.666  3642  6062 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-03 03:42:25.729   928  2920 W InputDispatcher: channel '3b442a0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-03 03:42:25.729   928  2920 E InputDispatcher: channel '3b442a0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-03 03:42:25.731   928  3657 D GraphicsStats: Buffer count: 1
,10-03 03:42:25.731   928  3882 I WindowState: WIN DEATH: Window{3b442a0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-03 03:42:25.731   928  3882 W InputDispatcher: Attempted to unregister already unregistered input channel '3b442a0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-03 03:42:25.741   928  3875 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3823) has died
,10-03 03:42:25.742   928  3875 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
10-03 03:42:25.743   928  3875 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-03 03:42:25.757   928   941 I ActivityManager: Start proc 6089:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-03 03:42:25.757   928  3396 I ActivityManager: Process android.process.acore (pid 3381) has died
10-03 03:42:25.757   928  3396 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-03 03:42:25.801  6089  6089 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:42:25.801  6089  6089 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-03 03:42:25.801  6089  6089 D AndroidRuntime: Shutting down VM
,10-03 03:42:25.807  6089  6089 E AndroidRuntime: FATAL EXCEPTION: main
10-03 03:42:25.807  6089  6089 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6089
10-03 03:42:25.807  6089  6089 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-03 03:42:25.807  6089  6089 E AndroidRuntime: 	... 10 more
10-03 03:42:25.809   928  3795 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-03 03:42:25.810   928  6102 E DropBoxManagerService: Can't write: system_app_crash
10-03 03:42:25.810   928  6102 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-03 03:42:25.810   928  6102 E DropBoxManagerService: 	... 5 more
10-03 03:42:25.810  6089  6089 I Process : Sending signal. PID: 6089 SIG: 9
10-03 03:42:25.825   928   939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6089) has died
10-03 03:42:25.827   928   939 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-03 03:42:25.841   928   941 I ActivityManager: Start proc 6103:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-03 03:42:25.889  6103  6103 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:42:25.889  6103  6103 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-03 03:42:25.890  6103  6103 D AndroidRuntime: Shutting down VM
,10-03 03:42:25.896  6103  6103 E AndroidRuntime: FATAL EXCEPTION: main
10-03 03:42:25.896  6103  6103 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6103
10-03 03:42:25.896  6103  6103 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-03 03:42:25.896  6103  6103 E AndroidRuntime: 	... 10 more
10-03 03:42:25.899   928   938 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-03 03:42:25.899   928  6115 E DropBoxManagerService: Can't write: system_app_crash
10-03 03:42:25.899   928  6115 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-03 03:42:25.899   928  6115 E DropBoxManagerService: 	... 5 more
10-03 03:42:25.899  6103  6103 I Process : Sending signal. PID: 6103 SIG: 9
10-03 03:42:25.917   928  3882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6103) has died
10-03 03:42:25.919   928  3882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-03 03:42:25.933   928   941 I ActivityManager: Start proc 6116:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-03 03:42:25.949   383   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
