#### Test 86174379d95f7ab_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 11:11:01.914   928  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-22 11:11:02.753  5442  5442 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 11:11:02.758  5442  5442 D AndroidRuntime: CheckJNI is OFF
09-22 11:11:02.781  5442  5442 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 11:11:02.812  5442  5442 I Radio-JNI: register_android_hardware_Radio DONE
09-22 11:11:02.827  5442  5442 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 11:11:02.844   928  3599 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 11:11:02.887   928  3599 I ActivityManager: Start proc 5451:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 11:11:02.900  5442  5442 D AndroidRuntime: Shutting down VM
,09-22 11:11:03.234   928  3503 I WindowManager: Screenshot max retries 4 of Token{9c54cd2 ActivityRecord{495bb5d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{4e9f915 u0 Starting com.test.thalitest} drawState=4
,09-22 11:11:03.304  5451  5451 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 11:11:03.339  5451  5451 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-22 11:11:03.398  5451  5451 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 3000-3055)
,09-22 11:11:03.398  5451  5451 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 11:11:03.435  5451  5451 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9575fba}
,09-22 11:11:03.436  5451  5451 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 11:11:03.437  5451  5451 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 11:11:03.443  5451  5451 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-22 11:11:03.445  5451  5451 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 11:11:03.492  5451  5451 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 11:11:03.509  5451  5451 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 11:11:03.510  5451  5451 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 11:11:03.510  5451  5451 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 11:11:03.510  5451  5451 I Adreno  : Build Date                       : 12/06/15
09-22 11:11:03.510  5451  5451 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 11:11:03.510  5451  5451 I Adreno  : Local Branch                     : mybranch17112971
09-22 11:11:03.510  5451  5451 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 11:11:03.510  5451  5451 I Adreno  : Remote Branch                    : NONE
09-22 11:11:03.510  5451  5451 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 11:11:03.563   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@95abdd0:true
,09-22 11:11:03.585   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33794]" dev="sockfs" ino=33794 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 11:11:03.585   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33794]" dev="sockfs" ino=33794 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 11:11:03.597  5451  5451 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 11:11:03.606  5451  5451 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 11:11:03.628   406   406 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31224]" dev="sockfs" ino=31224 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 11:11:03.630  5451  5488 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-22 11:11:03.628   406   406 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31224]" dev="sockfs" ino=31224 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 11:11:03.631  3503  3503 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 11:11:03.631  3503  3503 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-22 11:11:03.636  5451  5475 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 11:11:03.663  5451  5488 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 11:11:03.726   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +486ms (total +866ms)
,09-22 11:11:03.749  5451  5451 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5451
,09-22 11:11:03.821  5451  5451 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 11:11:03.941  5451  5491 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -579335888
,09-22 11:11:03.945  5451  5491 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 11:11:03.945  5451  5491 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 11:11:03.945  5451  5491 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 11:11:03.945  5451  5491 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 11:11:03.945  5451  5491 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 11:11:03.945  5451  5491 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2437a3 added. We now have 1 listener(s)
,09-22 11:11:03.948  5451  5491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-22 11:11:03.948  5451  5491 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 11:11:03.949  5451  5491 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 11:11:03.949  5451  5491 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-22 11:11:03.952  5451  5491 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12321e added. We now have 1 listener(s)
,09-22 11:11:03.952  5451  5491 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:03.957   928  2981 D WifiService: New client listening to asynchronous messages
,09-22 11:11:03.957  5451  5491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 11:11:03.957  5451  5491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 11:11:03.957  5451  5491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 11:11:03.957  5451  5491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 11:11:03.958  5451  5491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-22 11:11:03.959  5451  5491 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:03.959  5451  5491 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-22 11:11:03.963  5451  5491 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:03.963  5451  5491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 11:11:03.964  5451  5491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 11:11:03.964  5451  5491 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:03.964  5451  5491 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 11:11:03.966  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:03.968  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:04.093  5451  5451 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 11:11:04.261  5451  5497 W jxcore-log: Initializing JXcore engine
09-22 11:11:04.261  5451  5497 W jxcore-log: JXcore engine is ready
,09-22 11:11:04.281  5497  5497 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-22 11:11:04.281  5497  5497 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14463]" dev="sockfs" ino=14463 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 11:11:04.281  5497  5497 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-22 11:11:04.285  5497  5497 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31199]" dev="sockfs" ino=31199 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 11:11:04.292  5451  5497 W jxcore-log: Starting JXcore engine
,09-22 11:11:04.302  5451  5460 I art     : Background sticky concurrent mark sweep GC freed 81422(8MB) AllocSpace objects, 19(2MB) LOS objects, 24% free, 24MB/32MB, paused 1.374ms total 102.914ms
,09-22 11:11:04.348  5451  5497 W jxcore-log: Platform android
09-22 11:11:04.348  5451  5497 W jxcore-log: 
,09-22 11:11:04.348  5451  5497 W jxcore-log: Process ARCH arm
09-22 11:11:04.348  5451  5497 W jxcore-log: 
,09-22 11:11:04.452  5451  5497 I jxcore-log: JXcore Cordova bridge is ready!
09-22 11:11:04.452  5451  5497 I jxcore-log: 
09-22 11:11:04.452  5451  5497 W jxcore-log: JXcore engine is started
,09-22 11:11:04.460  5451  5491 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 11:11:04.466  5451  5451 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 11:11:09.773   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 11:11:10.774   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 11:11:11.056  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 11:11:11.056  5451  5497 I jxcore-log: 
,09-22 11:11:11.058  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 11:11:11.058  5451  5497 I jxcore-log: 
,09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.062  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 11:11:11.063  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 11:11:11.065  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 11:11:11.065  5451  5497 I jxcore-log: 
09-22 11:11:11.066  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 11:11:11.066  5451  5497 I jxcore-log: 
,09-22 11:11:11.421  5451  5497 D executeNativeTests: Running unit tests
,09-22 11:11:11.462  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 11:11:11.463  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f added. We now have 2 listener(s)
09-22 11:11:11.463  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:11.463  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 11:11:11.463  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:11.464  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:11.464  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c added. We now have 2 listener(s)
09-22 11:11:11.464  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:11.464  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 11:11:11.466  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.470  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 11:11:11.471  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.471  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:11.474  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 11:11:11.474  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 11:11:11.474  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 11:11:11.475  5451  5497 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-22 11:11:11.475  5451  5497 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 11:11:11.475  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-22 11:11:11.475  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 11:11:11.475  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 11:11:11.476  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.476  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.476  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.476  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.477  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.477  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:11.477  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:11.477  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f removed from the list
09-22 11:11:11.477  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.477  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c removed from the list
09-22 11:11:11.479  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.479  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.479  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.480  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.480  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.481  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 11:11:11.481  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.481  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.481  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.482  5451  5497 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 11:11:11.482  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.482  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.482  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.482  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.482  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:11.482  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.482  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.482  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.482  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
,09-22 11:11:11.489  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.490  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.490  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.490  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.490  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:11.490  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.490  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.490  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.490  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.490  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
,09-22 11:11:11.492  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 11:11:11.492  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 11:11:11.492  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 11:11:11.493  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 11:11:11.493  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 11:11:11.493  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.493  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.493  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.494  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.494  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.494  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
,09-22 11:11:11.494  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.494  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.494  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.494  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.494  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.494  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.494  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:11.494  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.494  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.494  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.494  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.495  5451  5497 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 11:11:11.496  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.498  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 11:11:11.498  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.498  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:11.499  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:11.499  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 11:11:11.499  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 11:11:11.499  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:11.499  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 11:11:11.501  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 11:11:11.501  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 11:11:11.502  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.504  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 11:11:11.504  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 11:11:11.505  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 11:11:11.505  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.506  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in pers,istent storage
09-22 11:11:11.507  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 11:11:11.507  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 11:11:11.508  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 11:11:11.508  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 11:11:11.508  5451  5497 D BluetoothAdapter: STATE_ON
09-22 11:11:11.510  4482  4729 D BtGatt.GattService: registerClient() - UUID=76ac1fd2-a193-4e18-ac0c-7103a9a8249f
,09-22 11:11:11.511  4482  4550 D BtGatt.GattService: onClientRegistered() - UUID=76ac1fd2-a193-4e18-ac0c-7103a9a8249f, clientIf=5
,09-22 11:11:11.512  5451  5461 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 11:11:11.514  4482  4498 D BtGatt.GattService: start scan with filters
09-22 11:11:11.520  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 11:11:11.520  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 11:11:11.520  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 11:11:11.520  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 11:11:11.520  4482  4562 D BtGatt.ScanManager: handling starting scan
,09-22 11:11:11.522  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:11.522  4482  4562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:11.522  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 11:11:11.522  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:11.522  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 11:11:11.524  5451  5497 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 11:11:11.525  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.525  5451  5497 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 11:11:11.525  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.525  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 11:11:11.525  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:11.525  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 11:11:11.525  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 11:11:11.525  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 11:11:11.525  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:11.525  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:11.526  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 11:11:11.526  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 11:11:11.526  5451  5497 D BluetoothAdapter: STATE_ON
,09-22 11:11:11.526  4482  4729 D BtGatt.GattService: stopScan() - queue size =1
09-22 11:11:11.527  4482  4498 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 11:11:11.527  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 11:11:11.527  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 11:11:11.527  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 11:11:11.527  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 11:11:11.527  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 11:11:11.527  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.528  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 11:11:11.528  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 11:11:11.528  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 11:11:11.528  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:11.528  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.528  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:11.529  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:11.529  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.529  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.529  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.529  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.529  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.529  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 11:11:11.529  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.529  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.529  5451  5497 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 11:11:11.529  4482  4550 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 11:11:11.529  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.530  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:11.530  4482  4562 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.533  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 11:11:11.534  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.534  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:11.534  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:11.534  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 11:11:11.534  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 11:11:11.534  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:11.534  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 11:11:11.536  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 11:11:11.536  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 11:11:11.537  4482  4550 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-22 11:11:11.537  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.538  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.538  4482  4562 D BtGatt.ScanManager: Starting BLE batch scan
09-22 11:11:11.538  4482  4562 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 11:11:11.539  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.539  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 11:11:11.540  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 11:11:11.540  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 11:11:11.546  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 11:11:11.546  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 11:11:11.547  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 11:11:11.547  5451  5497 D BluetoothAdapter: STATE_ON
,09-22 11:11:11.549  4482  4550 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 11:11:11.549  4482  4707 D BtGatt.GattService: registerClient() - UUID=8a16c344-3e51-4718-8d78-6ddf7b00a93d
09-22 11:11:11.549  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.549  4482  4550 D BtGatt.GattService: onClientRegistered() - UUID=8a16c344-3e51-4718-8d78-6ddf7b00a93d, clientIf=5
09-22 11:11:11.549  5451  5462 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 11:11:11.550  4482  4497 D BtGatt.GattService: start scan with filters
,09-22 11:11:11.552  4482  4550 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 11:11:11.552  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.552  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 11:11:11.552  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 11:11:11.552  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 11:11:11.552  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 11:11:11.555  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 11:11:11.555  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 11:11:11.555  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:11.556  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 11:11:11.557  5451  5497 I io.jxcore.node.ConnectionHelper: start: OK
,09-22 11:11:11.558  4482  4550 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 11:11:11.558  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.559  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.559  5451  5497 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 11:11:11.559  4482  4562 D BtGatt.ScanManager: stopping BLe Batch
,09-22 11:11:11.559  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.559  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 11:11:11.559  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.559  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 11:11:11.559  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 11:11:11.559  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 11:11:11.559  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:11.559  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:11.559  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 11:11:11.559  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 11:11:11.559  5451  5497 D BluetoothAdapter: STATE_ON
09-22 11:11:11.560  4482  4707 D BtGatt.GattService: stopScan() - queue size =0
09-22 11:11:11.560  4482  4498 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 11:11:11.560  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 11:11:11.560  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 11:11:11.560  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 11:11:11.560  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-22 11:11:11.560  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 11:11:11.562  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.562  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 11:11:11.562  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 11:11:11.562  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 11:11:11.562  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 11:11:11.563  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.563  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.563  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.563  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:11.563  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.563  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.563  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.563  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.563  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.563  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 11:11:11.563  4482  4550 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 11:11:11.563  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.563  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.564  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.564  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.564  4482  4562 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 11:11:11.564  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.564  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.564  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.564  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
,09-22 11:11:11.564  5451  5497 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 11:11:11.565  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.568  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 11:11:11.568  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.568  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:11.569  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:11.569  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 11:11:11.569  4482  4550 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 11:11:11.569  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 11:11:11.569  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:11.569  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.569  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 11:11:11.571  4482  4562 D BtGatt.ScanManager: handling starting scan
,09-22 11:11:11.572  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 11:11:11.572  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 11:11:11.572  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.574  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 11:11:11.574  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.575  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 11:11:11.575  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 11:11:11.576  4482  4550 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 11:11:11.576  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.576  4482  4562 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 11:11:11.577  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 11:11:11.577  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-22 11:11:11.577  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 11:11:11.579  5451  5497 D BluetoothAdapter: STATE_ON
,09-22 11:11:11.579  4482  4550 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 11:11:11.579  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.579  4482  4562 D BtGatt.ScanManager: Starting BLE batch scan
09-22 11:11:11.579  4482  4562 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 11:11:11.583  4482  4729 D BtGatt.GattService: registerClient() - UUID=efd4c891-d8e0-48e4-819a-398c48a4b59c
,09-22 11:11:11.583  4482  4550 D BtGatt.GattService: onClientRegistered() - UUID=efd4c891-d8e0-48e4-819a-398c48a4b59c, clientIf=5
,09-22 11:11:11.583  5451  5461 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 11:11:11.584  4482  4498 D BtGatt.GattService: start scan with filters
,09-22 11:11:11.585  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 11:11:11.585  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 11:11:11.585  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 11:11:11.585  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 11:11:11.585  4482  4550 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 11:11:11.585  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:11.586  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:11.586  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 11:11:11.586  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 11:11:11.587  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 11:11:11.588  5451  5497 I io.jxcore.node.ConnectionHelper: start: OK
09-22 11:11:11.588  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.588  5451  5497 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 11:11:11.588  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.588  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-22 11:11:11.588  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.588  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 11:11:11.588  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 11:11:11.588  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 11:11:11.588  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:11.588  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:11.588  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 11:11:11.588  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 11:11:11.589  5451  5497 D BluetoothAdapter: STATE_ON
,09-22 11:11:11.589  4482  4550 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 11:11:11.590  4482  4498 D BtGatt.GattService: stopScan() - queue size =1
09-22 11:11:11.590  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.590  4482  4707 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 11:11:11.590  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 11:11:11.590  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-22 11:11:11.590  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 11:11:11.590  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 11:11:11.590  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 11:11:11.591  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 11:11:11.591  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 11:11:11.591  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 11:11:11.591  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 11:11:11.592  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 11:11:11.593  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.593  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.593  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.593  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.593  5451  5497 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 11:11:11.593  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.593  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.593  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.594  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.594  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:11.594  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.594  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 11:11:11.594  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.594  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.594  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.594  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.594  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.595  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.595  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.595  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.595  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.595  4482  4550 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 11:11:11.595  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:11.596  4482  4562 D BtGatt.ScanManager: stopping BLe Batch
09-22 11:11:11.596  5451  5497 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-22 11:11:11.596  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.596  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.596  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.596  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.596  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:11.596  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.596  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.596  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.596  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.597  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.597  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.597  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.597  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:11.597  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.597  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.597  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.597  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.597  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.598  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 11:11:11.598  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.598  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.598  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.598  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 11:11:11.598  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.598  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.598  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.598  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.598  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.598  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.598  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.598  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.598  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.598  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.599  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-22 11:11:11.599  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.599  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.599  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.599  5451  5497 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-22 11:11:11.599  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.599  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.599  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.599  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.599  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.600  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.600  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.600  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 11:11:11.600  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.600  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.600  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.600  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.600  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.600  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.600  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.600  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.600  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.600  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.601  4482  4550 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 11:11:11.601  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-22 11:11:11.601  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:11.601  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.601  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.601  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.601  4482  4562 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 11:11:11.601  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.601  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.601  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.601  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.601  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.601  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.601  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.601  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.601  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.601  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.601  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.603  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.603  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.603  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.603  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.603  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 11:11:11.603  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 11:11:11.603  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 11:11:11.603  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 11:11:11.603  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 11:11:11.603  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 11:11:11.603  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.603  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.603  5451  5497, V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.604  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.604  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.604  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.604  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.604  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.604  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.604  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.604  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.604  4482  4550 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 11:11:11.604  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.604  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.604  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.604  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.605  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.605  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.605  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.605  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.605  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 11:11:11.605  5451  5497 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 11:11:11.605  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 11:11:11.605  4482  4562 D BtGatt.ScanManager: handling starting scan
09-22 11:11:11.606  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 11:11:11.606  5451  5497 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-22 11:11:11.606  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 11:11:11.607  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 11:11:11.608  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 11:11:11.608  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 11:11:11.608  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 11:11:11.608  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 11:11:11.608  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-22 11:11:11.608  5451  5497 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 11:11:11.608  5451  5497 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-22 11:11:11.608  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 11:11:11.608  5451  5497 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 11:11:11.608  5451  5497 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-22 11:11:11.608  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 11:11:11.608  5451  5497 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 11:11:11.608  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-22 11:11:11.610  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-22 11:11:11.610  4482  4550 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 11:11:11.611  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.611  4482  4562 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 11:11:11.611  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-22 11:11:11.611  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-22 11:11:11.611  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-22 11:11:11.611  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-22 11:11:11.611  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-22 11:11:11.611  5451  5497 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 11:11:11.611  5451  5497 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-22 11:11:11.612  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-22 11:11:11.612  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.612  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.612  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.612  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.612  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.612  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.612  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-22 11:11:11.613  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.613  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.613  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.613  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.613  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.613  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.613  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.613  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.613  5451  5500 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-22 11:11:11.614  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.614  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.614  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.614  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.614  5451  5497 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-22 11:11:11.615  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.615  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.615  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.615  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.615  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.615  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.615  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.615  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.615  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.615  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.615  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.615  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.615  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.615  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.616  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.616  4482  4550 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 11:11:11.616  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.616  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.616  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.616  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.616  4482  4562 D BtGatt.ScanManager: Starting BLE batch scan
09-22 11:11:11.616  4482  4562 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 11:11:11.617  5451  5497 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-22 11:11:11.617  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.617  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.617  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.617  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.617  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.617  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.617  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.617  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.617  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.617  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.617  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.617  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.617  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.617  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.618  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.618  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.618  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.618  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.618  5451  5497 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-22 11:11:11.619  5451  5497 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-22 11:11:11.619  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 11:11:11.619  5451  5497 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-22 11:11:11.619  5451  5497 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 11:11:11.619  5451  5497 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-22 11:11:11.619  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 11:11:11.619  5451  5497 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-22 11:11:11.619  5451  5497 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 11:11:11.619  5451  5497 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 11:11:11.619  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 11:11:11.619  5451  5497 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-22 11:11:11.619  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.619  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.619  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.619  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.619  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.619  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.619  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.620  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.620  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.620  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.620  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.620  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.620  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.620  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.620  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.621  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.621  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.621  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.621  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.621  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.621  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.621  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.621  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.621  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.621  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.621  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.621  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.621  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.621  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.621  5451  5499 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 11:11:11.621  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.621  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.622  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.622  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.622  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.622  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.622  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.622  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.622  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.622  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.622  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.622  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.623  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.623  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.623  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.623  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.623  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.623  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.621  4707  4707 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15137]" dev="sockfs" ino=15137 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 11:11:11.621  4707  4707 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[15137]" dev="sockfs" ino=15137 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 11:11:11.625  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.625  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.625  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.625  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.626  5451  5497 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 11:11:11.626  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:11.627  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-22 11:11:11.627  5451  5497 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-22 11:11:11.627  5451  5497 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-22 11:11:11.627  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-22 11:11:11.627  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 11:11:11.627  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 11:11:11.628  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.628  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 11:11:11.628  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 11:11:11.628  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 11:11:11.628  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.628  5451  5497 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 11:11:11.628  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.628  5451  5451 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 11:11:11.628  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.628  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 11:11:11.628  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:11.628  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:11.628  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.628  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.629  5451  5501 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 11:11:11.629  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.629  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.629  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.629  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.629  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:11.629  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.629  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:11.630  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.630  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.630  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.630  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.630  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.630  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.630  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.630  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.630  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.630  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.630  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.630  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.631  4482  4550 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 11:11:11.631  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.631  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.631  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.631  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.631  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.631  5451  5497 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-22 11:11:11.631  5451  5497 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 11:11:11.632  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 11:11:11.632  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 11:11:11.632  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.632  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.632  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.632  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.632  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.632  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.632  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.632  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.632  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.632  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.632  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.632  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.632  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.632  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.632  5451  5501 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 11:11:11.633  5451  5501 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-22 11:11:11.633  5451  5501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 11:11:11.633  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.633  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.633  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.628  4729  4729 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31253]" dev="sockfs" ino=31253 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 11:11:11.628  4729  4729 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31253]" dev="sockfs" ino=31253 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 11:11:11.633  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.633  5451  5451 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 11:11:11.635  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.635  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.636  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.636  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.636  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.636  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.636  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.636  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.636  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.636  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.636  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.636  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.636  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.636  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.637  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.637  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.637  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.637  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.637  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:11.637  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:11.637  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:11.637  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:11.637  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.637  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.638  5451  5497 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514440f not in the list
09-22 11:11:11.638  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.638  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.638  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:11.638  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.638  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.638  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:11.638  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:11.639  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:11.639  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:11.639  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:11.639  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f7bc9c not in the list
09-22 11:11:11.640  4482  4550 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 11:11:11.640  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.640  5451  5497 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-22 11:11:11.640  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 11:11:11.640  5451  5497 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-22 11:11:11.640  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 11:11:11.640  5451  5497 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-22 11:11:11.640  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 11:11:11.641  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 11:11:11.641  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-22 11:11:11.642  5451  5497 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-22 11:11:11.642  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 11:11:11.642  5451  5497 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-22 11:11:11.642  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 11:11:11.642  5451  5497 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-22 11:11:11.642  5451  5497 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-22 11:11:11.642  5451  5497 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-22 11:11:11.642  5451  5497 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-22 11:11:11.642  5451  5497 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-22 11:11:11.643  5451  5497 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-22 11:11:11.643  5451  5497 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-22 11:11:11.643  5451  5497 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-22 11:11:11.643  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:11.643  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c5e61e added. We now have 2 listener(s)
09-22 11:11:11.643  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:11.644  5451  5497 D BluetoothAdapter: enable(): BT is already enabled..!
09-22 11:11:11.644   928  3559 D WifiService: setWifiEnabled: true pid=5451, uid=10077
09-22 11:11:11.645   928  3559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 11:11:11.645  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:11.645  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1944eff added. We now have 3 listener(s)
09-22 11:11:11.645  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:11.645  4482  4550 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 11:11:11.645  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.645  4482  4562 D BtGatt.ScanManager: stopping BLe Batch
,09-22 11:11:11.648  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:11.649  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@47184cc added. We now have 4 listener(s)
09-22 11:11:11.649  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:11.650  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:11.650  4482  4550 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 11:11:11.650  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c93e315 added. We now have 5 listener(s)
09-22 11:11:11.650  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.650  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:11.650  4482  4562 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 11:11:11.651   928  3503 D WifiService: setWifiEnabled: false pid=5451, uid=10077
09-22 11:11:11.651   928  3503 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 11:11:11.653   928  2980 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-22 11:11:11.653   928  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-22 11:11:11.653   928  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 11:11:11.653   928  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 11:11:11.655  4482  4541 D BluetoothAdapterState: Current state: ON, message: 23
09-22 11:11:11.655  4482  4541 D BluetoothAdapterProperties: Setting state to 13
09-22 11:11:11.655  4482  4541 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 11:11:11.655  4482  4550 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 11:11:11.655  4482  4550 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:11.656  4482  4541 D BluetoothAdapterProperties: onBluetoothDisable()
09-22 11:11:11.656  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:11.657  4482  4541 I BluetoothAdapterState: Entering PendingCommandState
09-22 11:11:11.658  4482  4550 D BluetoothAdapterProperties: Scan Mode:20
09-22 11:11:11.659  4482  4482 D BluetoothMapService: onReceive
09-22 11:11:11.659  4482  4482 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 11:11:11.659  4482  4482 D BluetoothMapService: STATE_TURNING_OFF
09-22 11:11:11.659  4482  4482 D BluetoothMapService: MAP Service closeService in
09-22 11:11:11.659  4482  4482 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 11:11:11.659  4482  4482 D ObexServerSockets0: shutdown(block = true)
09-22 11:11:11.660  4482  4482 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 11:11:11.660  4482  4730 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-22 11:11:11.660  4482  4482 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 11:11:11.660  4482  4541 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 11:11:11.660  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.660  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 11:11:11.661  4482  4731 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 11:11:11.661  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.661  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.661  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:11.661  4482  4702 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 11:11:11.663  4482  4482 I BtOppRfcommListener: stopping Accept Thread
09-22 11:11:11.664  4482  5141 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 11:11:11.664  4482  5141 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 11:11:11.664   928  5202 D DhcpClient: Clearing IP address
09-22 11:11:11.664   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-22 11:11:11.665  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.667  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.669  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 11:11:11.669  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 11:11:11.670  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.670  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 11:11:11.670   928   941 I ActivityManager: Start proc 5504:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-22 11:11:11.671  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.672  4482  4482 D HeadsetService: Received stop request...Stopping profile...
09-22 11:11:11.672   509   921 D CommandListener: Setting iface cfg
09-22 11:11:11.673   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:11.673   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:11.674  3121  3739 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:11.674   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:11.674  3517  3791 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:11.673   928  5203 D DhcpClient: Receive thread stopped
09-22 11:11:11.675  4482  4482 D A2dpService: Received stop request...Stopping profile...
09-22 11:11:11.676  4482  4713 D A2dpStateMachine: Exit Disconnected: -1
09-22 11:11:11.676  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.676  3121  3121 D HeadsetProfile: Bluetooth service disconnected
09-22 11:11:11.677   928   928 D BluetoothA2dp: Proxy object disconnected
09-22 11:11:11.677  3602  5256 V NativeCrypto: Read error: ssl=0x7f8949b700: I/O error during system call, Connection timed out
09-22 11:11:11.677  3121  3121 D BluetoothA2dp: Proxy object disconnected
09-22 11:11:11.678  4482  4482 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:11.678  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.678  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:11.678  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:11.678  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.678  3602  5256 V NativeCrypto: SSL shutdown failed: ssl=0x7f8949b700: I/O error during system call, Broken pipe
09-22 11:11:11.679  4482  4482 D HidService: Received stop request...Stopping profile...
09-22 11:11:11.679  4482  4482 D HidService: Stopping Bluetooth HidService
09-22 11:11:11.680   928  3409 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-22 11:11:11.680   928  5200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-22 11:11:11.681  3121  3121 D BluetoothInputDevice: Proxy object disconnected
09-22 11:11:11.681  3121  3121 D HidProfile: Bluetooth service disconnected
09-22 11:11:11.682   928  5200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-22 11:11:11.683   928  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-22 11:11:11.683   928  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-22 11:11:11.683   928  2982 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-22 11:11:11.684   928  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-22 11:11:11.684   547   547 E Parcel  : Reading a NULL string not supported here.
,09-22 11:11:11.685   928  2982 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-22 11:11:11.686   928   928 D RttService: SCAN_AVAILABLE : 1
09-22 11:11:11.687   928  3088 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-22 11:11:11.686  4482  4482 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 11:11:11.691  4482  4482 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 11:11:11.691  4482  4550 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 11:11:11.691  4482  4677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:11.691  4482  4677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:11.691  4482  4677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:11.691  4482  4550 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 11:11:11.693  4482  4482 D HealthService: Received stop request...Stopping profile...
09-22 11:11:11.695   928  2982 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-22 11:11:11.695  4482  4482 D PanService: Received stop request...Stopping profile...
,09-22 11:11:11.696  3487  3611 W QCNEJ   : |CORE| network lost: 100
,09-22 11:11:11.697  4482  4482 D BluetoothMapService: Received stop request...Stopping profile...
09-22 11:11:11.697  4482  4482 D BluetoothMapService: stop()
09-22 11:11:11.697  3487  3611 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 11:11:11.697  4482  4482 D BluetoothMapAppObserver: deinitObservers()
09-22 11:11:11.697  4482  4482 D BluetoothMapAppObserver: removeReceiver()
09-22 11:11:11.698  4482  4482 D SapService: Received stop request...Stopping profile...
09-22 11:11:11.698  4482  4482 V SapService: stop()
,09-22 11:11:11.702   928  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-22 11:11:11.703  4482  4482 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:11.703  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.703  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:11.703  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 11:11:11.705  4482  4677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 11:11:11.705  4482  4482 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:11.705  4482  4677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:11.705  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.705  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:11.705  4482  4550 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 11:11:11.705  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:11.705  4482  4677 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-22 11:11:11.705  4482  4677 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-22 11:11:11.706  4482  4677 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 11:11:11.706  4482  4482 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 11:11:11.706  4482  4677 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 11:11:11.706  4482  4482 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 11:11:11.706  4482  4482 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:11.706  4482  4550 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 11:11:11.706  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.706  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 11:11:11.706  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:11.706  4482  4482 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-22 11:11:11.706  4482  4550 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 11:11:11.706  4482  4482 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 11:11:11.706  4482  4482 V BluetoothAdapterState: isTurningOff()=true
,09-22 11:11:11.707  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.707  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:11.707  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:11.707  4482  4482 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 11:11:11.707  4482  4482 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 11:11:11.707  4482  4482 D BluetoothMapService: MAP Service closeService in
09-22 11:11:11.707  4482  4482 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:11.707  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.708  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:11.708  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:11.708  4482  4482 D BluetoothMapService: cleanup()
09-22 11:11:11.708  4482  4482 D BluetoothMapService: MAP Service closeService in
09-22 11:11:11.708  4482  4482 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:11.708  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:11.708  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:11.708  4482  4482 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:11.708  4482  4541 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 11:11:11.708  4482  4541 D BluetoothAdapterProperties: Setting state to 15
09-22 11:11:11.708  4482  4541 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 11:11:11.710  4482  4541 I BluetoothAdapterState: Entering BleOnState
09-22 11:11:11.712  3121  3121 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 11:11:11.712  3121  3121 D PanProfile: Bluetooth service disconnected
09-22 11:11:11.713   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 11:11:11.713  3121  3134 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 11:11:11.714  3121  3136 D BluetoothPan: onBluetoothStateChange on: false
09-22 11:11:11.714   928  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 11:11:11.714  3121  3739 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 11:11:11.715   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 11:11:11.715  3517  3791 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:11.715   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:11.716  3121  3121 D BluetoothMap: Proxy object disconnected
09-22 11:11:11.716  3121  3121 D MapProfile: Bluetooth service disconnected
09-22 11:11:11.716  3121  3740 D BluetoothMap: onBluetoothStateChange: up=false
09-22 11:11:11.716   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:11.716  3121  3739 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 11:11:11.717   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:11.717  3121  3134 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:11.717  4482  4541 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 11:11:11.717  4482  4541 D BluetoothAdapterProperties: Setting state to 16
09-22 11:11:11.717  4482  4541 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 11:11:11.719  4482  4541 D BluetoothAdapterProperties: onBleDisable
09-22 11:11:11.719  4482  4541 I BluetoothAdapterState: Entering PendingCommandState
09-22 11:11:11.722  4482  4550 D BluetoothAdapterProperties: Scan Mode:20
09-22 11:11:11.719  4482  4543 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 11:11:11.722  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConne,ctivityInfo: State changed:
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:11.723  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:11.724  4482  4677 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 11:11:11.724  4482  4677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:11.724  5451  5499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-22 11:11:11.724  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.724  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:11.727  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:11.727  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:11.728  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.728  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:11.730  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.732  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.732   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 11:11:11.732   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-22 11:11:11.733   509   921 D TetherController: Setting IP forward enable = 0
,09-22 11:11:11.733   928  2982 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-22 11:11:11.733   928  2982 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-22 11:11:11.736   928   945 D Tethering: MasterInitialState.processMessage what=3
09-22 11:11:11.736   928  2980 D DhcpClient: doQuit
09-22 11:11:11.736   928  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 11:11:11.737   928  5202 D DhcpClient: onQuitting
09-22 11:11:11.737  3660  3660 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-22 11:11:11.738  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.742  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:11.742  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:11.744  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 11:11:11.744  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:11.746  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:11.746  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:11.746  4247  4247 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5fd6046 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-22 11:11:11.746  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:11.746  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:11.748  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.749  4834  4834 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-22 11:11:11.751  4906  4927 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-22 11:11:11.751  4906  4927 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-22 11:11:11.752  4906  4927 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 11:11:11.752  4906  4927 E SarControlService: no key has been found,reset the power
09-22 11:11:11.752  4906  4947 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 11:11:11.752  4906  4947 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-22 11:11:11.752  4906  4947 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 11:11:11.753  4935  4935 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 11:11:11.753  4935  4935 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-22 11:11:11.755  4906  4947 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 11:11:11.755  4906  4947 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 11:11:11.755  4906  4947 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 11:11:11.756  4935  4935 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-22 11:11:11.756  4935  4935 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 11:11:11.761  4935  4949 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c70ffdc HexData = [00000000ea03000000000000ffffffff]
09-22 11:11:11.761  4935  4949 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 11:11:11.761  4935  4949 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-22 11:11:11.762  4935  4935 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 11:11:11.762  4906  4918 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-22 11:11:11.766  4935  4949 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c70ffdc HexData = [00000000eb03000000000000ffffffff]
,09-22 11:11:11.766  4935  4949 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 11:11:11.766  4935  4949 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-22 11:11:11.767  3660  3660 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-22 11:11:11.767  4935  4935 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-22 11:11:11.767  4906  4916 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-22 11:11:11.772  3660  3660 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-22 11:11:11.772  5504  5504 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-22 11:11:11.774   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 11:11:11.784  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 11:11:11.789   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-22 11:11:11.790  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 11:11:11.790   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34942d5:true
09-22 11:11:11.790   928  2982 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-22 11:11:11.791   509   921 D TetherController: Setting IP forward enable = 0
,09-22 11:11:11.803  3660  3660 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 11:11:11.804   928  3155 I ActivityManager: Start proc 5535:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-22 11:11:11.813  5504  5504 D LocalBluetoothProfileManager: Adding local MAP profile
09-22 11:11:11.815  5504  5504 D BluetoothMap: Create BluetoothMap proxy object
,09-22 11:11:11.823  5504  5504 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-22 11:11:11.823  3660  3660 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 11:11:11.839  5535  5535 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-22 11:11:11.842  5504  5504 D DockEventReceiver: finishStartingService: stopping service
,09-22 11:11:11.846   928  3155 I ActivityManager: Killing 4880:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-22 11:11:11.925  4307  4307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 11:11:11.925   928  2980 D wifi    : In wifi stop Hal
,09-22 11:11:11.925   928  2980 D wifi    : halHandle = 0x7f779fe560, mVM = 0x7f93fcd140, mCls = 0x100b8a
09-22 11:11:11.925   928  3657 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 11:11:11.925   928  3657 D WifiHAL : Got a signal to exit!!!
09-22 11:11:11.925   928  3657 I WifiHAL : Exit wifi_event_loop
09-22 11:11:11.926   928  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 11:11:11.926   928  2980 E WifiHAL : Event processing terminated
,09-22 11:11:11.926   928  2980 D wifi    : In wifi cleaned up handler
09-22 11:11:11.927   928  2980 I WifiHAL : Internal cleanup completed
,09-22 11:11:11.928  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.929  4482  4550 I bt_hci  : shut_down
09-22 11:11:11.930  3625  4063 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 11:11:11.931  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:11.934  4482  4563 I bt_vendor: low_power_mode_cb
,09-22 11:11:11.935  4482  4563 D bt_hwcfg: hw_epilog_process
,09-22 11:11:11.938  4482  4563 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 11:11:11.938  4482  4563 I bt_vendor: epilog_cb
09-22 11:11:11.938  4482  4563 I bt_hci  : epilog_finished_callback
,09-22 11:11:11.940  4482  4550 I bt_hci_h4: hal_close
,09-22 11:11:11.940  4482  4550 I bt_userial_vendor: device fd = 54 close
,09-22 11:11:11.950   928  3657 D wifi    : set interface wlan0 flags (DOWN)
,09-22 11:11:11.950   928  2980 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 11:11:12.050  4482  4543 D bt_stack_manager: event_shut_down_stack finished.
,09-22 11:11:12.050  4482  4541 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-22 11:11:12.051  4482  4541 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 11:11:12.052  4482  4482 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 11:11:12.052  4482  4482 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 11:11:12.052  4482  4482 D BtGatt.GattService: stop()
09-22 11:11:12.052  4482  4482 D BtGatt.AdvertiseManager: advertise clients cleared
,09-22 11:11:12.054  4482  4482 V BluetoothAdapterState: isTurningOff()=false
,09-22 11:11:12.054  4482  4482 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:12.054  4482  4482 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 11:11:12.054  4482  4482 V BluetoothAdapterState: isBleTurningOff()=true
,09-22 11:11:12.054  4482  4541 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 11:11:12.054  4482  4541 D BluetoothAdapterProperties: Setting state to 10
09-22 11:11:12.054  4482  4541 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 11:11:12.055  4482  4541 I BluetoothAdapterState: Entering OffState
09-22 11:11:12.056   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-22 11:11:12.064  4482  4482 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-22 11:11:12.064  4482  4482 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 11:11:12.064  4482  4482 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 11:11:12.064  4482  4543 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 11:11:12.075  4482  4543 D bt_stack_manager: event_clean_up_stack finished.
,09-22 11:11:12.078  4482  4482 I art     : System.exit called, status: 0
,09-22 11:11:12.078  4482  4482 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.k.d(PG:583)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.112  5535  5535 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:12.112  5535  5535 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:12.119   928  3559 I ActivityManager: Process com.android.bluetooth (pid 4482) has died
09-22 11:11:12.124  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 11:11:12.130  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-22 11:11:12.137   928  3532 I ActivityManager: Start proc 5569:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-22 11:11:12.138  5504  5504 D DockEventReceiver: finishStartingService: stopping service
09-22 11:11:12.140   928  3524 I ActivityManager: Killing 4247:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-22 11:11:12.153   928   945 D Tethering: InitialState.processMessage what=4
,09-22 11:11:12.214   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 11:11:12.266  5569  5569 D AdapterServiceConfig: Adding HeadsetService
,09-22 11:11:12.266  5569  5569 D AdapterServiceConfig: Adding A2dpService
09-22 11:11:12.266  5569  5569 D AdapterServiceConfig: Adding HidService
09-22 11:11:12.266  5569  5569 D AdapterServiceConfig: Adding HealthService
09-22 11:11:12.267  5569  5569 D AdapterServiceConfig: Adding PanService
09-22 11:11:12.267  5569  5569 D AdapterServiceConfig: Adding GattService
09-22 11:11:12.267  5569  5569 D AdapterServiceConfig: Adding BluetoothMapService
,09-22 11:11:12.267  5569  5569 D AdapterServiceConfig: Adding SapService
09-22 11:11:12.269   928  3410 I ActivityManager: Killing 5230:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-22 11:11:12.297  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 11:11:12.305  3893  3893 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-22 11:11:12.308  3893  3893 D SystemUpdateService: onCreate
,09-22 11:11:12.314  3893  3893 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-22 11:11:12.319  3893  5581 I SystemUpdateService: active receiver: enabled
,09-22 11:11:12.324  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-22 11:11:12.328  3893  5227 I iu.UploadsManager: num queued entries: 0
,09-22 11:11:12.328  3893  5227 I iu.UploadsManager: num updated entries: 0
09-22 11:11:12.329  3893  5227 I iu.SyncManager: NEXT; no task
,09-22 11:11:12.331  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 11:11:12.333  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 11:11:12.340  3893  5581 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-22 11:11:12.342  3893  5581 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-22 11:11:12.342  3893  5581 I SystemUpdateService: now status is 0 (complete)
,09-22 11:11:12.342  3893  5581 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-22 11:11:12.342  3893  5581 I SystemUpdateService: file has been verified
09-22 11:11:12.345   928  3410 I ActivityManager: Start proc 5583:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-22 11:11:12.346  3893  5581 I SystemUpdateService: OTA package size = 21989297
,09-22 11:11:12.363  3893  5581 I SystemUpdateService: showing system update notification
,09-22 11:11:12.379  5583  5583 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-22 11:11:12.384  5583  5583 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 11:11:12.390  5583  5583 D SprintDMHelper: simOperator: 
09-22 11:11:12.390  5583  5583 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-22 11:11:12.415  4307  5595 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 11:11:12.421   928  3155 I ActivityManager: Start proc 5596:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-22 11:11:12.426  3893  3893 D SystemUpdateService: onDestroy
,09-22 11:11:12.428   928   939 I ActivityManager: Killing 4569:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-22 11:11:12.469  5535  5555 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-22 11:11:12.477  5596  5596 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-22 11:11:12.485   928  3409 I ActivityManager: Killing 5312:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-22 11:11:12.504   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f45cf9:true
,09-22 11:11:12.775   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 11:11:13.776   551   551 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 11:11:14.663   928  3559 D WifiService: setWifiEnabled: true pid=5451, uid=10077
09-22 11:11:14.663   928  3559 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 11:11:14.672   509   921 D SoftapController: Softap fwReload - Ok
,09-22 11:11:14.676   509   921 D CommandListener: Setting iface cfg
09-22 11:11:14.676   509   921 D CommandListener: Trying to bring down wlan0
09-22 11:11:14.678   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-22 11:11:14.682   928  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 11:11:14.777   551   551 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 11:11:15.299   928  2980 D wifi    : set interface wlan0 flags (UP)
,09-22 11:11:15.302   928  2980 I WifiHAL : Initializing wifi
,09-22 11:11:15.302   928  2980 I WifiHAL : Creating socket
,09-22 11:11:15.307   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 11:11:15.309   928  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 11:11:15.309   928  2980 D wifi    : Did set static halHandle = 0x7f779fe560
,09-22 11:11:15.310   928  2980 D wifi    : halHandle = 0x7f779fe560, mVM = 0x7f93fcd140, mCls = 0x101826
09-22 11:11:15.310   928  2980 D wifi    : array field set
,09-22 11:11:15.310   928  2980 I WifiNative-HAL: interface[0] = wlan0
09-22 11:11:15.312   928  5613 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547467814240
09-22 11:11:15.312   928  5613 D wifi    : waitForHalEvents called, vm = 0x7f93fcd140, obj = 0x101826, env = 0x7f788ee200
,09-22 11:11:15.397  5614  5614 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 11:11:15.414   928  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 11:11:15.421  5614  5614 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 11:11:15.422  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:15.429  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:15.449  5614  5614 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 11:11:15.450  5614  5614 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 11:11:15.465  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:15.465  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:15.465  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:15.465  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:15.466   928  2980 D WifiConfigStore: Loading config and enabling all networks 
09-22 11:11:15.467  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:15.467  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:15.467  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:15.467  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 11:11:15.477   928  2980 D WifiConfigStore: loaded 0 passpoint configs
,09-22 11:11:15.478   928  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 11:11:15.478   928  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-22 11:11:15.479   928  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-22 11:11:15.481   928  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 11:11:15.481   928  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 11:11:15.481   928  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 11:11:15.481   928  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 11:11:15.485   928  2980 D WifiNative-HAL: Setting external_sim to 1
,09-22 11:11:15.485  4307  4307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 11:11:15.485   928  2980 D wifi    : setting dfs flag to true, 0x7f7977efe0
09-22 11:11:15.486   928  2980 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 11:11:15.486   928  2980 D wifi    : setting scan oui 0x7f7977efe0
09-22 11:11:15.486   928  2980 D WifiHAL : Sending mac address OUI
,09-22 11:11:15.490   928  2980 E native  : do suspend false
,09-22 11:11:15.497   928  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 11:11:15.497   928   928 D RttService: SCAN_AVAILABLE : 3
,09-22 11:11:15.497   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 11:11:15.497   928  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-22 11:11:15.498   509   921 D CommandListener: Setting iface cfg
,09-22 11:11:15.502   928  2979 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-22 11:11:15.502   928  2979 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 11:11:15.510   928  2979 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 11:11:15.510   928  2979 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 11:11:15.516   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=195173 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-22 11:11:17.671   928  3532 D WifiService: setWifiEnabled: false pid=5451, uid=10077
09-22 11:11:17.671   928  3532 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 11:11:17.677   928   928 D RttService: SCAN_AVAILABLE : 1
,09-22 11:11:17.678   928  3088 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 11:11:17.692   928  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 11:11:17.693   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-22 11:11:17.699   928  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 11:11:17.700  5614  5614 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-22 11:11:17.708  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:17.708  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:17.709  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:17.709  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 11:11:17.712  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:17.712  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:17.712  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 11:11:17.712  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 11:11:17.719  5614  5614 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 11:11:17.724  5614  5614 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 11:11:17.727  5614  5614 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 11:11:17.831   928  2980 D wifi    : In wifi stop Hal
,09-22 11:11:17.831   928  2980 D wifi    : halHandle = 0x7f779fe560, mVM = 0x7f93fcd140, mCls = 0x101826
09-22 11:11:17.831   928  5613 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 11:11:17.831   928  5613 D WifiHAL : Got a signal to exit!!!
09-22 11:11:17.831   928  5613 I WifiHAL : Exit wifi_event_loop
09-22 11:11:17.833   928  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 11:11:17.834   928  2980 E WifiHAL : Event processing terminated
09-22 11:11:17.835  4307  4307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 11:11:17.837   928  2980 D wifi    : In wifi cleaned up handler
,09-22 11:11:17.837   928  2980 I WifiHAL : Internal cleanup completed
09-22 11:11:17.839  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:17.842  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:17.845  3625  4063 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 11:11:17.860   928  5613 D wifi    : set interface wlan0 flags (DOWN)
,09-22 11:11:17.860   928  2980 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 11:11:18.064   928   945 D Tethering: InitialState.processMessage what=4
,09-22 11:11:18.068   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 11:11:20.706  5569  5569 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 11:11:20.706   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8ad18f:true
,09-22 11:11:20.711  5569  5569 I bt_bluedroid: init
09-22 11:11:20.711  5569  5620 I BluetoothAdapterState: Entering OffState
,09-22 11:11:20.714  5569  5621 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-22 11:11:20.714  5569  5621 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 11:11:20.714  5569  5621 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 11:11:20.714  5569  5621 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 11:11:20.715  5569  5569 I bt_bluedroid: get_profile_interface socket
,09-22 11:11:20.718  5569  5569 I bt_bluedroid: get_profile_interface sdp
09-22 11:11:20.718  5569  5624 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 11:11:20.721  5569  5624 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 11:11:20.727  5569  5579 I bt_bluedroid: config_hci_snoop_log
09-22 11:11:20.728   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 11:11:20.733  5569  5620 D BluetoothAdapterState: Current state: OFF, message: 0
09-22 11:11:20.733  5569  5620 D BluetoothAdapterProperties: Setting state to 14
,09-22 11:11:20.733  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 11:11:20.735  5569  5620 D BluetoothBondStateMachine: make
,09-22 11:11:20.738  5569  5625 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 11:11:20.741  5569  5620 I BluetoothAdapterState: Entering PendingCommandState
,09-22 11:11:20.742  5569  5569 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 11:11:20.745  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:20.746  5569  5569 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 11:11:20.747  5569  5569 D BtGatt.GattService: Received start request. Starting profile...
,09-22 11:11:20.747  5569  5569 D BtGatt.GattService: start()
09-22 11:11:20.747  5569  5569 I bt_bluedroid: get_profile_interface gatt
,09-22 11:11:20.748  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:20.748  5569  5569 D BtGatt.AdvertiseManager: advertise manager created
,09-22 11:11:20.755  5569  5569 V BluetoothAdapterState: isTurningOff()=false
,09-22 11:11:20.755  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:20.755  5569  5569 V BluetoothAdapterState: isBleTurningOn()=true
09-22 11:11:20.755  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:20.755  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 11:11:20.758  5569  5620 I bt_bluedroid: bt_bluedroid
09-22 11:11:20.758  5569  5621 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 11:11:20.759  5569  5621 I bt_hci  : start_up
,09-22 11:11:20.766  5569  5621 I bt_vendor: alloc value 0xf4178871
,09-22 11:11:20.766  5569  5621 I bt_vendor: init
09-22 11:11:20.766  5569  5621 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 11:11:20.766  5569  5621 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 11:11:20.875  5569  5621 D bt_hci  : start_up starting async portion
09-22 11:11:20.875  5569  5628 I bt_hci  : event_finish_startup
09-22 11:11:20.876  5569  5628 I bt_hci_h4: hal_open
09-22 11:11:20.876  5569  5628 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 11:11:20.875  5629  5629 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 11:11:20.878  5569  5628 I bt_userial_vendor: device fd = 54 open
,09-22 11:11:20.890  5569  5628 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 11:11:20.892  5569  5628 D bt_hwcfg: Chipset BCM4358A3
,09-22 11:11:20.892  5569  5628 D bt_hwcfg: Target name = [BCM4358A3]
09-22 11:11:20.893  5569  5628 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 11:11:21.287  5569  5628 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 11:11:21.288  5569  5628 D bt_hwcfg: Settlement delay -- 100 ms
09-22 11:11:21.288  5569  5628 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 11:11:21.422  5569  5628 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 11:11:21.422  5569  5628 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-22 11:11:21.424  5569  5628 I bt_hwcfg: vendor lib fwcfg completed
,09-22 11:11:21.424  5569  5628 I bt_vendor: firmware callback
,09-22 11:11:21.424  5569  5628 I bt_hci  : firmware_config_callback
09-22 11:11:21.433  5569  5631 I bt_btu  : btu_task pending for preload complete event
09-22 11:11:21.433  5569  5631 I bt_btu_task: Bluetooth chip preload is complete
,09-22 11:11:21.433  5569  5631 I bt_btu  : btu_task received preload complete event
,09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 11:11:21.439  5569  5631 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_BTM
09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_SDP
09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 11:11:21.440  5569  5631 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 11:11:21.521  5569  5631 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40f6549
,09-22 11:11:21.521  5569  5631 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40f6549 
,09-22 11:11:21.544  5569  5624 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 11:11:21.545  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 11:11:21.546  5569  5624 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 11:11:21.550  5569  5624 D BluetoothAdapterProperties: Name is: Nexus 6P
09-22 11:11:21.552  5569  5624 D BluetoothAdapterProperties: Scan Mode:20
09-22 11:11:21.553  5569  5624 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 11:11:21.553  5569  5624 D bt_hci  : do_postload posting postload work item
,09-22 11:11:21.553  5569  5628 I bt_hci  : event_postload
09-22 11:11:21.553  5569  5628 I bt_vendor: sco_config_cb
09-22 11:11:21.553  5569  5628 I bt_hci  : sco_config_callback postload finished.
,09-22 11:11:21.557  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:21.559  5569  5624 D bt_bte_conf: Device ID record 1 : primary
,09-22 11:11:21.560  5569  5624 D bt_bte_conf:   vendorId            = 000f
,09-22 11:11:21.560  5569  5624 D bt_bte_conf:   vendorIdSource      = 0001
09-22 11:11:21.560  5569  5624 D bt_bte_conf:   product             = 1200
09-22 11:11:21.561  5569  5624 D bt_bte_conf:   version             = 1436
09-22 11:11:21.561  5569  5624 D bt_bte_conf:   clientExecutableURL = 
09-22 11:11:21.561  5569  5624 D bt_bte_conf:   serviceDescription  = 
09-22 11:11:21.561  5569  5624 D bt_bte_conf:   documentationURL    = 
09-22 11:11:21.561  5569  5624 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-22 11:11:21.561  5569  5621 D bt_stack_manager: event_start_up_stack finished
,09-22 11:11:21.562  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:21.562  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-22 11:11:21.562  5569  5620 D BluetoothAdapterProperties: Setting state to 15
09-22 11:11:21.563  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 11:11:21.564  5569  5620 I BluetoothAdapterState: Entering BleOnState
,09-22 11:11:21.568  5569  5620 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-22 11:11:21.568  5569  5620 D BluetoothAdapterProperties: Setting state to 11
09-22 11:11:21.568  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-22 11:11:21.569  5569  5628 I bt_vendor: low_power_mode_cb
,09-22 11:11:21.575  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:21.578  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:21.579  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.580  5569  5569 D HeadsetService: Received start request. Starting profile...
,09-22 11:11:21.582  5569  5569 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-22 11:11:21.582  5569  5569 D HeadsetStateMachine: make
,09-22 11:11:21.588  5569  5620 I BluetoothAdapterState: Entering PendingCommandState
,09-22 11:11:21.592  5569  5569 D HeadsetStateMachine: max_hf_connections = 1
09-22 11:11:21.592  5569  5569 I bt_bluedroid: get_profile_interface handsfree
09-22 11:11:21.593  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 11:11:21.593  5569  5624 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-22 11:11:21.596  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.597  5569  5569 D A2dpService: Received start request. Starting profile...
09-22 11:11:21.598  5569  5569 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 11:11:21.598  5569  5569 I bt_bluedroid: get_profile_interface avrcp
09-22 11:11:21.604  5569  5569 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-22 11:11:21.605  5569  5569 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 11:11:21.605  5569  5569 D A2dpStateMachine: make
09-22 11:11:21.606  5569  5569 I bt_bluedroid: get_profile_interface a2dp
09-22 11:11:21.607  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-22 11:11:21.610  5569  5639 D A2dpStateMachine: Enter Disconnected: -2
09-22 11:11:21.611  5569  5569 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 11:11:21.612  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.612  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 11:11:21.614  5569  5569 D HidService: Received start request. Starting profile...
09-22 11:11:21.614  5569  5569 I bt_bluedroid: get_profile_interface hidhost
09-22 11:11:21.614  5569  5569 D HidService: setHidService(): set to: null
09-22 11:11:21.614  5569  5624 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40d756d
09-22 11:11:21.614  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 11:11:21.615  5569  5569 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 11:11:21.615  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.616  5504  5504 D BluetoothInputDevice: Proxy object connected
09-22 11:11:21.616  5569  5569 D HealthService: Received start request. Starting profile...
09-22 11:11:21.617  5504  5504 D HidProfile: Bluetooth service connected
09-22 11:11:21.617  5569  5569 I bt_bluedroid: get_profile_interface health
09-22 11:11:21.618  5569  5569 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-22 11:11:21.618  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.620  5569  5569 D PanService: Received start request. Starting profile...
09-22 11:11:21.620  5569  5569 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 11:11:21.620  5569  5569 I bt_bluedroid: get_profile_interface pan
09-22 11:11:21.620  5504  5504 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 11:11:21.621  5569  5624 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-22 11:11:21.621  5504  5504 D PanProfile: Bluetooth service connected
09-22 11:11:21.622  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.624  5504  5504 D BluetoothMap: Proxy object connected
09-22 11:11:21.625  5504  5504 D MapProfile: Bluetooth service connected
09-22 11:11:21.625  5504  5504 D BluetoothMap: getConnectedDevices()
09-22 11:11:21.626  5569  5569 D BluetoothMapService: Received start request. Starting profile...
09-22 11:11:21.626  5569  5569 D BluetoothMapService: start()
09-22 11:11:21.628  5569  5569 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-22 11:11:21.629  5569  5569 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 11:11:21.629  5569  5569 D BluetoothMapAppObserver: createReceiver()
09-22 11:11:21.630  5569  5569 D BluetoothMapAppObserver: initObservers()
09-22 11:11:21.630  5569  5569 D BluetoothMapAppObserver: getEnabledAccountItems()
09-22 11:11:21.637  5569  5569 V SapService: SapBinder()
09-22 11:11:21.638  5569  5569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:21.638  5569  5569 D SapService: Received start request. Starting profile...
,09-22 11:11:21.638  5569  5569 V SapService: start()
09-22 11:11:21.641  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:21.641  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.641  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:21.641  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:21.641  5569  5637 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOff()=false
,09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:21.642  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:21.643  5504  5504 D BluetoothMap: Bluetooth is Not enabled
09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 11:11:21.643  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:21.644  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:21.644  5569  5569 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:21.644  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:21.644  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:21.644  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 11:11:21.644  5569  5620 D BluetoothAdapterProperties: ScanMode =  20
09-22 11:11:21.644  5569  5620 D BluetoothAdapterProperties: State =  11
09-22 11:11:21.645  5569  5624 D BluetoothAdapterProperties: Scan Mode:21
09-22 11:11:21.645  5569  5624 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 11:11:21.646  5569  5620 D BluetoothAdapterProperties: Setting state to 12
09-22 11:11:21.646  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 11:11:21.647  3121  3136 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 11:11:21.647  5569  5620 I BluetoothAdapterState: Entering OnState
09-22 11:11:21.649  3121  3121 D BluetoothInputDevice: Proxy object connected
09-22 11:11:21.649  3121  3121 D HidProfile: Bluetooth service connected
09-22 11:11:21.650  3121  3740 D BluetoothPan: onBluetoothStateChange on: true
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:21.650  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:21.652  3121  3134 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 11:11:21.653  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:21.653   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 11:11:21.653  3121  3121 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 11:11:21.653  3121  3121 D PanProfile: Bluetooth service connected
09-22 11:11:21.654  5504  5517 D BluetoothPan: onBluetoothStateChange on: true
09-22 11:11:21.655   928   928 D BluetoothA2dp: Proxy object connected
09-22 11:11:21.655  3517  3542 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:21.655  5569  5569 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 11:11:21.655   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:21.656  3121  3136 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 11:11:21.656  5569  5569 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 11:11:21.658  5569  5569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 11:11:21.658   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:21.658  3121  3121 D BluetoothMap: Proxy object connected
09-22 11:11:21.658  3121  3121 D MapProfile: Bluetooth service connected
09-22 11:11:21.658  3121  3121 D BluetoothMap: getConnectedDevices()
,09-22 11:11:21.658  5504  5515 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:21.658  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:21.659  3121  3739 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 11:11:21.660  5569  5569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 11:11:21.661  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:21.661   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 11:11:21.661  5504  5517 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 11:11:21.662  5504  5515 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 11:11:21.662  3121  3121 D BluetoothA2dp: Proxy object connected
09-22 11:11:21.662  5569  5569 D ObexServerSockets: Succeed to create listening sockets 
09-22 11:11:21.662  5569  5569 D ObexServerSockets0: startAccept()
09-22 11:11:21.662  5569  5569 D ObexServerSockets0: prepareForNewConnect()
09-22 11:11:21.664  3121  3136 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:21.665  5569  5569 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-22 11:11:21.665  5569  5569 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-22 11:11:21.665  5569  5646 D ObexServerSockets0: Accepting socket connection...
,09-22 11:11:21.665   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-22 11:11:21.666  5569  5647 D ObexServerSockets0: Accepting socket connection...
09-22 11:11:21.666  5569  5569 D BluetoothMapService: onReceive
,09-22 11:11:21.666  5569  5569 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-22 11:11:21.666  5569  5569 D BluetoothMapService: STATE_ON
09-22 11:11:21.669  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:21.670  5504  5504 D LocalBluetoothProfileManager: Adding local A2DP profile
09-22 11:11:21.670  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:21.672  5569  5648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:21.673  5569  5648 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 11:11:21.673  5569  5648 D BluetoothSdpJni: SDP Create record success - handle: 1
09-22 11:11:21.674  5504  5504 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-22 11:11:21.681  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 11:11:21.683  5504  5504 D BluetoothA2dp: Proxy object connected
,09-22 11:11:21.686  5569  5569 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-22 11:11:21.686  5569  5569 D ObexServerSockets0: prepareForNewConnect()
09-22 11:11:21.687  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 11:11:21.695  3121  3121 D BluetoothPbap: Proxy object connected
09-22 11:11:21.695  3121  3121 D PbapServerProfile: Bluetooth service connected
,09-22 11:11:21.702  5569  5652 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:21.703  5504  5504 D DockEventReceiver: finishStartingService: stopping service
,09-22 11:11:21.704  5504  5504 D BluetoothPbap: Proxy object connected
09-22 11:11:21.705  5504  5504 D PbapServerProfile: Bluetooth service connected
,09-22 11:11:21.716  5569  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:21.717  5569  5656 I BtOppRfcommListener: Accept thread started.
,09-22 11:11:21.756   928   928 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.757   928   928 D BluetoothHeadset: Proxy object connected
09-22 11:11:21.757  3121  3739 D BluetoothHeadset: Proxy object connected
09-22 11:11:21.757  3121  3121 D HeadsetProfile: Bluetooth service connected
09-22 11:11:21.757   928   928 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.757  3517  3801 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.758   928   945 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.761   928   945 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.765  3121  3134 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.765  3121  3121 D HeadsetProfile: Bluetooth service connected
,09-22 11:11:21.777  5504  5517 D BluetoothHeadset: Proxy object connected
,09-22 11:11:21.779  5504  5504 D HeadsetProfile: Bluetooth service connected
,09-22 11:11:23.689  5569  5620 D BluetoothAdapterState: Current state: ON, message: 23
,09-22 11:11:23.690  5569  5620 D BluetoothAdapterProperties: Setting state to 13
,09-22 11:11:23.690  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 11:11:23.692  5569  5620 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 11:11:23.693  5569  5620 I BluetoothAdapterState: Entering PendingCommandState
,09-22 11:11:23.700  5569  5569 D BluetoothMapService: onReceive
,09-22 11:11:23.700  5569  5569 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-22 11:11:23.700  5569  5569 D BluetoothMapService: STATE_TURNING_OFF
09-22 11:11:23.700  5569  5569 D BluetoothMapService: MAP Service closeService in
09-22 11:11:23.701  5569  5569 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 11:11:23.701  5569  5569 D ObexServerSockets0: shutdown(block = true)
,09-22 11:11:23.702  5569  5569 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 11:11:23.702  5569  5646 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-22 11:11:23.703  5569  5569 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-22 11:11:23.703  5569  5647 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 11:11:23.704  5569  5633 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 11:11:23.705  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:23.706  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:23.710  5569  5569 I BtOppRfcommListener: stopping Accept Thread
09-22 11:11:23.711  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:23.711  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:23.713  5569  5624 D BluetoothAdapterProperties: Scan Mode:20
09-22 11:11:23.714  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-22 11:11:23.711  5569  5656 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 11:11:23.715  5569  5656 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 11:11:23.718  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 11:11:23.718  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:23.718  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:23.719  5569  5569 D HeadsetService: Received stop request...Stopping profile...
09-22 11:11:23.720  5451  5451 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 11:11:23.720  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:23.722  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:23.723   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:23.724  5504  5517 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:23.724   928   928 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:23.725  3121  3740 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:23.725   928   928 D BluetoothHeadset: Proxy object disconnected
,09-22 11:11:23.725  3517  3540 D BluetoothHeadset: Proxy object disconnected
09-22 11:11:23.726  5569  5569 D A2dpService: Received stop request...Stopping profile...
09-22 11:11:23.726  5569  5639 D A2dpStateMachine: Exit Disconnected: -1
09-22 11:11:23.727  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:23.728  5569  5569 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:23.728  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.728  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 11:11:23.728  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:23.729   928   928 D BluetoothA2dp: Proxy object disconnected
09-22 11:11:23.729  5569  5569 D HidService: Received stop request...Stopping profile...
09-22 11:11:23.729  5569  5569 D HidService: Stopping Bluetooth HidService
,09-22 11:11:23.734  5569  5569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-22 11:11:23.734  5569  5569 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 11:11:23.734  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 11:11:23.734  5569  5631 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:23.734  5569  5631 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:23.734  5569  5631 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:23.735  5569  5569 D HealthService: Received stop request...Stopping profile...
09-22 11:11:23.735  5569  5624 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-22 11:11:23.736  3121  3121 D HeadsetProfile: Bluetooth service disconnected
,09-22 11:11:23.737  3121  3121 D BluetoothA2dp: Proxy object disconnected
09-22 11:11:23.737  5569  5569 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:23.737  3121  3121 D BluetoothInputDevice: Proxy object disconnected
09-22 11:11:23.737  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.737  3121  3121 D HidProfile: Bluetooth service disconnected
,09-22 11:11:23.737  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 11:11:23.737  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:23.741  5569  5631 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:23.741  5569  5631 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:23.741  5569  5569 D PanService: Received stop request...Stopping profile...
09-22 11:11:23.741  5569  5631 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 11:11:23.741  5569  5631 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 11:11:23.741  5569  5631 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 11:11:23.742  5569  5631 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-22 11:11:23.741  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-22 11:11:23.742  3121  3121 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 11:11:23.742  3121  3121 D PanProfile: Bluetooth service disconnected
09-22 11:11:23.742  5569  5569 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:23.743  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.743  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:23.743  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:23.744  5504  5504 D DockEventReceiver: finishStartingService: stopping service
,09-22 11:11:23.745  5569  5569 D BluetoothMapService: Received stop request...Stopping profile...
09-22 11:11:23.745  5569  5569 D BluetoothMapService: stop()
09-22 11:11:23.746  5504  5504 D HeadsetProfile: Bluetooth service disconnected
09-22 11:11:23.746  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 11:11:23.749  5504  5504 D BluetoothA2dp: Proxy object disconnected
,09-22 11:11:23.749  5504  5504 D BluetoothInputDevice: Proxy object disconnected
09-22 11:11:23.749  5504  5504 D HidProfile: Bluetooth service disconnected
09-22 11:11:23.749  5504  5504 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 11:11:23.749  5504  5504 D PanProfile: Bluetooth service disconnected
,09-22 11:11:23.750  5569  5569 D BluetoothMapAppObserver: deinitObservers()
09-22 11:11:23.750  5569  5569 D BluetoothMapAppObserver: removeReceiver()
,09-22 11:11:23.752  5569  5569 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 11:11:23.752  5569  5569 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 11:11:23.752  5569  5624 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 11:11:23.752  5569  5569 D SapService: Received stop request...Stopping profile...
09-22 11:11:23.752  5569  5569 V SapService: stop()
,09-22 11:11:23.753  3121  3121 D BluetoothMap: Proxy object disconnected
09-22 11:11:23.753  3121  3121 D MapProfile: Bluetooth service disconnected
09-22 11:11:23.754  5569  5569 V BluetoothAdapterState: isTurningOff()=true
,09-22 11:11:23.754  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.754  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:23.754  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:23.754  5569  5569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 11:11:23.754  5504  5504 D BluetoothMap: Proxy object disconnected
09-22 11:11:23.754  5504  5504 D MapProfile: Bluetooth service disconnected
09-22 11:11:23.754  5569  5569 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 11:11:23.754  5569  5624 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 11:11:23.755  5569  5569 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:23.755  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.755  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:23.755  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 11:11:23.755  5569  5569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-22 11:11:23.755  5569  5569 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 11:11:23.757  5569  5569 D BluetoothMapService: MAP Service closeService in
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:23.758  3121  3121 D BluetoothPbap: Proxy object disconnected
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.758  3121  3121 D PbapServerProfile: Bluetooth service disconnected
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:23.758  5569  5569 D BluetoothMapService: cleanup()
,09-22 11:11:23.758  5569  5569 D BluetoothMapService: MAP Service closeService in
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isTurningOff()=true
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:23.758  5569  5569 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:23.759  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 11:11:23.759  5569  5620 D BluetoothAdapterProperties: Setting state to 15
09-22 11:11:23.759  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 11:11:23.760  5569  5620 I BluetoothAdapterState: Entering BleOnState
,09-22 11:11:23.764  3121  3136 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-22 11:11:23.764  3121  3739 D BluetoothPan: onBluetoothStateChange on: false
,09-22 11:11:23.764  5504  5504 D BluetoothPbap: Proxy object disconnected
09-22 11:11:23.764  5504  5504 D PbapServerProfile: Bluetooth service disconnected
09-22 11:11:23.765  5504  5515 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:23.765  3121  3134 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 11:11:23.766   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 11:11:23.766  5504  5517 D BluetoothPan: onBluetoothStateChange on: false
,09-22 11:11:23.767  3517  3791 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:23.767   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:23.767  3121  3740 D BluetoothMap: onBluetoothStateChange: up=false
09-22 11:11:23.770   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 11:11:23.770  5504  5515 D BluetoothMap: onBluetoothStateChange: up=false
,09-22 11:11:23.771  3121  3136 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 11:11:23.771   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:23.771  5504  5517 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 11:11:23.772  5504  5515 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 11:11:23.772  5504  5517 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 11:11:23.773  3121  3739 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 11:11:23.773  5569  5620 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 11:11:23.773  5569  5620 D BluetoothAdapterProperties: Setting state to 16
09-22 11:11:23.773  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 11:11:23.774  5569  5620 D BluetoothAdapterProperties: onBleDisable
09-22 11:11:23.774  5569  5620 I BluetoothAdapterState: Entering PendingCommandState
09-22 11:11:23.775  5569  5621 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 11:11:23.776  5569  5624 D BluetoothAdapterProperties: Scan Mode:20
09-22 11:11:23.777  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:23.777  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 11:11:23.778  5569  5631 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 11:11:23.778  5569  5631 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 11:11:23.779  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:23.781  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:23.782  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:23.784  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 11:11:23.785  5504  5504 D DockEventReceiver: finishStartingService: stopping service
,09-22 11:11:23.985  5569  5624 I bt_hci  : shut_down
,09-22 11:11:23.989  5569  5628 D bt_hwcfg: hw_epilog_process
09-22 11:11:23.990  5569  5628 I bt_vendor: low_power_mode_cb
,09-22 11:11:23.992  5569  5628 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 11:11:23.992  5569  5628 I bt_vendor: epilog_cb
09-22 11:11:23.992  5569  5628 I bt_hci  : epilog_finished_callback
,09-22 11:11:23.994  5569  5624 I bt_hci_h4: hal_close
,09-22 11:11:23.995  5569  5624 I bt_userial_vendor: device fd = 54 close
,09-22 11:11:24.104  5569  5621 D bt_stack_manager: event_shut_down_stack finished.
,09-22 11:11:24.104  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-22 11:11:24.106  5569  5620 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 11:11:24.106  5569  5569 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 11:11:24.107  5569  5569 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 11:11:24.107  5569  5569 D BtGatt.GattService: stop()
09-22 11:11:24.107  5569  5569 D BtGatt.AdvertiseManager: advertise clients cleared
,09-22 11:11:24.109  5569  5569 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:24.109  5569  5569 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:24.109  5569  5569 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:24.109  5569  5569 V BluetoothAdapterState: isBleTurningOff()=true
,09-22 11:11:24.109  5569  5620 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 11:11:24.109  5569  5620 D BluetoothAdapterProperties: Setting state to 10
09-22 11:11:24.110  5569  5620 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-22 11:11:24.110  5569  5620 I BluetoothAdapterState: Entering OffState
,09-22 11:11:24.111   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-22 11:11:24.117  5569  5569 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 11:11:24.118  5569  5569 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 11:11:24.118  5569  5569 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 11:11:24.119  5569  5621 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 11:11:24.125  5569  5569 I art     : System.exit called, status: 0
,09-22 11:11:24.125  5569  5569 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 11:11:24.147   928  3155 I ActivityManager: Process com.android.bluetooth (pid 5569) has died
,09-22 11:11:26.687  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 11:11:26.687  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:29.694  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 11:11:29.694  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@68dc1b added. We now have 6 listener(s)
09-22 11:11:29.694  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:29.701  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 11:11:29.702  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79821b8 added. We now have 7 listener(s)
09-22 11:11:29.702  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:29.704  5451  5497 I System.out: IsBluetoothEnabled
,09-22 11:11:29.714  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:29.743   928   945 I ActivityManager: Start proc 5664:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 11:11:29.818  5664  5664 D AdapterServiceConfig: Adding HeadsetService
,09-22 11:11:29.818  5664  5664 D AdapterServiceConfig: Adding A2dpService
09-22 11:11:29.818  5664  5664 D AdapterServiceConfig: Adding HidService
09-22 11:11:29.818  5664  5664 D AdapterServiceConfig: Adding HealthService
09-22 11:11:29.818  5664  5664 D AdapterServiceConfig: Adding PanService
09-22 11:11:29.818  5664  5664 D AdapterServiceConfig: Adding GattService
,09-22 11:11:29.819  5664  5664 D AdapterServiceConfig: Adding BluetoothMapService
09-22 11:11:29.819  5664  5664 D AdapterServiceConfig: Adding SapService
,09-22 11:11:29.829   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32c24dc:true
,09-22 11:11:29.829  5664  5664 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 11:11:29.832  5664  5664 I bt_bluedroid: init
,09-22 11:11:29.832  5664  5676 I BluetoothAdapterState: Entering OffState
,09-22 11:11:29.835  5664  5677 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 11:11:29.835  5664  5677 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 11:11:29.835  5664  5677 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 11:11:29.835  5664  5677 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-22 11:11:29.835  5664  5664 I bt_bluedroid: get_profile_interface socket
,09-22 11:11:29.837  5664  5680 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 11:11:29.837  5664  5664 I bt_bluedroid: get_profile_interface sdp
09-22 11:11:29.839  5664  5680 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 11:11:29.842  5664  5675 I bt_bluedroid: config_hci_snoop_log
,09-22 11:11:29.844   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 11:11:29.848  5664  5676 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 11:11:29.848  5664  5676 D BluetoothAdapterProperties: Setting state to 14
09-22 11:11:29.848  5664  5676 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 11:11:29.850  5664  5676 D BluetoothBondStateMachine: make
,09-22 11:11:29.852  5664  5681 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 11:11:29.854  5664  5676 I BluetoothAdapterState: Entering PendingCommandState
,09-22 11:11:29.855  5664  5664 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-22 11:11:29.857  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:29.858  5664  5664 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 11:11:29.858  5664  5664 D BtGatt.GattService: Received start request. Starting profile...
09-22 11:11:29.859  5664  5664 D BtGatt.GattService: start()
09-22 11:11:29.859  5664  5664 I bt_bluedroid: get_profile_interface gatt
,09-22 11:11:29.860  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:29.860  5664  5664 D BtGatt.AdvertiseManager: advertise manager created
,09-22 11:11:29.865  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:29.865  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-22 11:11:29.865  5664  5664 V BluetoothAdapterState: isBleTurningOn()=true
09-22 11:11:29.865  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:29.866  5664  5676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 11:11:29.867  5664  5676 I bt_bluedroid: bt_bluedroid
,09-22 11:11:29.867  5664  5677 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 11:11:29.867  5664  5677 I bt_hci  : start_up
,09-22 11:11:29.874  5664  5677 I bt_vendor: alloc value 0xf41eb871
09-22 11:11:29.874  5664  5677 I bt_vendor: init
,09-22 11:11:29.874  5664  5677 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 11:11:29.874  5664  5677 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 11:11:29.986  5664  5677 D bt_hci  : start_up starting async portion
,09-22 11:11:29.987  5664  5684 I bt_hci  : event_finish_startup
09-22 11:11:29.987  5664  5684 I bt_hci_h4: hal_open
09-22 11:11:29.987  5664  5684 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 11:11:29.990  5664  5684 I bt_userial_vendor: device fd = 54 open
,09-22 11:11:29.985  5685  5685 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 11:11:30.005  5664  5684 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 11:11:30.007  5664  5684 D bt_hwcfg: Chipset BCM4358A3
,09-22 11:11:30.008  5664  5684 D bt_hwcfg: Target name = [BCM4358A3]
09-22 11:11:30.008  5664  5684 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 11:11:30.411  5664  5684 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 11:11:30.412  5664  5684 D bt_hwcfg: Settlement delay -- 100 ms
09-22 11:11:30.412  5664  5684 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 11:11:30.546  5664  5684 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 11:11:30.546  5664  5684 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-22 11:11:30.548  5664  5684 I bt_hwcfg: vendor lib fwcfg completed
,09-22 11:11:30.548  5664  5684 I bt_vendor: firmware callback
,09-22 11:11:30.548  5664  5684 I bt_hci  : firmware_config_callback
,09-22 11:11:30.556  5664  5687 I bt_btu  : btu_task pending for preload complete event
,09-22 11:11:30.556  5664  5687 I bt_btu_task: Bluetooth chip preload is complete
,09-22 11:11:30.557  5664  5687 I bt_btu  : btu_task received preload complete event
,09-22 11:11:30.565  5664  5687 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 11:11:30.565  5664  5687 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 11:11:30.565  5664  5687 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 11:11:30.565  5664  5687 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-22 11:11:30.565  5664  5687 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 11:11:30.565  5664  5687 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 11:11:30.566  5664  5687 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 11:11:30.566  5664  5687 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 11:11:30.567  5664  5687 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 11:11:30.567  5664  5687 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 11:11:30.567  5664  5687 I         : BTE_InitTraceLevels -- TRC_SDP
09-22 11:11:30.567  5664  5687 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 11:11:30.567  5664  5687 I         : BTE_InitTraceLevels -- TRC_SMP
,09-22 11:11:30.568  5664  5687 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-22 11:11:30.568  5664  5687 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 11:11:30.650  5664  5687 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4169549
,09-22 11:11:30.650  5664  5687 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4169549 
,09-22 11:11:30.674  5664  5680 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 11:11:30.675  5664  5680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 11:11:30.675  5664  5680 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 11:11:30.678  5664  5680 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 11:11:30.680  5664  5680 D BluetoothAdapterProperties: Scan Mode:20
,09-22 11:11:30.681  5664  5680 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 11:11:30.681  5664  5680 D bt_hci  : do_postload posting postload work item
09-22 11:11:30.681  5664  5684 I bt_hci  : event_postload
09-22 11:11:30.681  5664  5684 I bt_vendor: sco_config_cb
09-22 11:11:30.681  5664  5684 I bt_hci  : sco_config_callback postload finished.
,09-22 11:11:30.685  5664  5680 D bt_bte_conf: Device ID record 1 : primary
,09-22 11:11:30.685  5664  5680 D bt_bte_conf:   vendorId            = 000f
09-22 11:11:30.685  5664  5680 D bt_bte_conf:   vendorIdSource      = 0001
09-22 11:11:30.685  5664  5680 D bt_bte_conf:   product             = 1200
09-22 11:11:30.685  5664  5680 D bt_bte_conf:   version             = 1436
09-22 11:11:30.686  5664  5680 D bt_bte_conf:   clientExecutableURL = 
09-22 11:11:30.686  5664  5680 D bt_bte_conf:   serviceDescription  = 
,09-22 11:11:30.686  5664  5680 D bt_bte_conf:   documentationURL    = 
09-22 11:11:30.686  5664  5680 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-22 11:11:30.686  5664  5677 D bt_stack_manager: event_start_up_stack finished
09-22 11:11:30.686  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:30.687  5664  5676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 11:11:30.687  5664  5676 D BluetoothAdapterProperties: Setting state to 15
09-22 11:11:30.687  5664  5676 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 11:11:30.690  5664  5676 I BluetoothAdapterState: Entering BleOnState
,09-22 11:11:30.692  5664  5684 I bt_vendor: low_power_mode_cb
,09-22 11:11:30.695  5664  5676 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-22 11:11:30.695  5664  5676 D BluetoothAdapterProperties: Setting state to 11
09-22 11:11:30.695  5664  5676 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 11:11:30.700  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:30.700  5664  5664 D HeadsetService: Received start request. Starting profile...
09-22 11:11:30.704  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:30.705  5664  5664 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-22 11:11:30.705  5664  5664 D HeadsetStateMachine: make
,09-22 11:11:30.711  5664  5676 I BluetoothAdapterState: Entering PendingCommandState
,09-22 11:11:30.718  5664  5664 D HeadsetStateMachine: max_hf_connections = 1
,09-22 11:11:30.718  5664  5664 I bt_bluedroid: get_profile_interface handsfree
09-22 11:11:30.718  5664  5680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 11:11:30.718  5664  5680 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-22 11:11:30.721  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:30.722  5664  5664 D A2dpService: Received start request. Starting profile...
,09-22 11:11:30.722  5664  5664 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-22 11:11:30.723  5664  5664 I bt_bluedroid: get_profile_interface avrcp
,09-22 11:11:30.729  5664  5664 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 11:11:30.729  5664  5664 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 11:11:30.729  5664  5664 D A2dpStateMachine: make
,09-22 11:11:30.731  5664  5664 I bt_bluedroid: get_profile_interface a2dp
,09-22 11:11:30.731  5664  5680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 11:11:30.732  5664  5695 D A2dpStateMachine: Enter Disconnected: -2
09-22 11:11:30.733  5664  5664 I BluetoothHidServiceJni: classInitNative: succeeds
,09-22 11:11:30.733  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:30.734  5664  5664 D HidService: Received start request. Starting profile...
09-22 11:11:30.734  5664  5664 I bt_bluedroid: get_profile_interface hidhost
,09-22 11:11:30.734  5664  5664 D HidService: setHidService(): set to: null
09-22 11:11:30.734  5664  5680 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf414a56d
09-22 11:11:30.735  5664  5664 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 11:11:30.735  5664  5680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 11:11:30.735  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:30.736  5664  5664 D HealthService: Received start request. Starting profile...
,09-22 11:11:30.737  5664  5664 I bt_bluedroid: get_profile_interface health
,09-22 11:11:30.738  5664  5664 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-22 11:11:30.739  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:30.739  5664  5664 D PanService: Received start request. Starting profile...
09-22 11:11:30.739  5664  5664 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 11:11:30.739  5664  5664 I bt_bluedroid: get_profile_interface pan
09-22 11:11:30.740  5664  5680 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 11:11:30.742  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
09-22 11:11:30.743  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 11:11:30.743  5664  5664 D BluetoothMapService: Received start request. Starting profile...
09-22 11:11:30.743  5664  5664 D BluetoothMapService: start()
,09-22 11:11:30.745  5664  5664 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 11:11:30.746  5664  5664 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-22 11:11:30.746  5664  5664 D BluetoothMapAppObserver: createReceiver()
09-22 11:11:30.747  5664  5664 D BluetoothMapAppObserver: initObservers()
09-22 11:11:30.748  5664  5664 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 11:11:30.753  5664  5664 V SapService: SapBinder()
,09-22 11:11:30.753  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:30.753  5664  5664 D SapService: Received start request. Starting profile...
09-22 11:11:30.753  5664  5664 V SapService: start()
,09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 11:11:30.756  5664  5693 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.756  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.757  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:30.758  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.758  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.758  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.758  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:30.758  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-22 11:11:30.759  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-22 11:11:30.759  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-22 11:11:30.759  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-22 11:11:30.759  5664  5676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-22 11:11:30.759  5664  5676 D BluetoothAdapterProperties: ScanMode =  20
09-22 11:11:30.759  5664  5676 D BluetoothAdapterProperties: State =  11
,09-22 11:11:30.762  5664  5680 D BluetoothAdapterProperties: Scan Mode:21
,09-22 11:11:30.762  5664  5676 D BluetoothAdapterProperties: Setting state to 12
,09-22 11:11:30.762  5664  5676 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 11:11:30.762  5664  5680 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 11:11:30.762  3121  3739 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 11:11:30.763  5664  5676 I BluetoothAdapterState: Entering OnState
09-22 11:11:30.764  3121  3134 D BluetoothPan: onBluetoothStateChange on: true
09-22 11:11:30.765  3121  3121 D BluetoothInputDevice: Proxy object connected
,09-22 11:11:30.765  3121  3121 D HidProfile: Bluetooth service connected
,09-22 11:11:30.768  5504  5517 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:30.769  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:30.769  3121  3740 D BluetoothPbap: onBluetoothStateChange: up=true
,09-22 11:11:30.771   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 11:11:30.771  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:30.771  5504  5515 D BluetoothPan: onBluetoothStateChange on: true
09-22 11:11:30.772  3121  3121 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 11:11:30.772  3121  3121 D PanProfile: Bluetooth service connected
09-22 11:11:30.772   928   928 D BluetoothA2dp: Proxy object connected
09-22 11:11:30.773  5664  5664 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 11:11:30.773  5664  5664 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 11:11:30.773  3517  3542 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:30.774   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:30.774  3121  3134 D BluetoothMap: onBluetoothStateChange: up=true
09-22 11:11:30.774  5664  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:30.775  5504  5504 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 11:11:30.776  5504  5504 D PanProfile: Bluetooth service connected
09-22 11:11:30.776   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:30.776  5664  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 11:11:30.776  5504  5517 D BluetoothMap: onBluetoothStateChange: up=true
09-22 11:11:30.777  5664  5664 D ObexServerSockets: Succeed to create listening sockets 
09-22 11:11:30.777  5664  5664 D ObexServerSockets0: startAccept()
09-22 11:11:30.777  5664  5664 D ObexServerSockets0: prepareForNewConnect()
09-22 11:11:30.777  3121  3739 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 11:11:30.779  5664  5664 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 11:11:30.779  5664  5664 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-22 11:11:30.779   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:30.779  5664  5703 D ObexServerSockets0: Accepting socket connection...
09-22 11:11:30.780  3121  3121 D BluetoothA2dp: Proxy object connected
09-22 11:11:30.780  5504  5515 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 11:11:30.780  5664  5702 D ObexServerSockets0: Accepting socket connection...
09-22 11:11:30.782  3121  3121 D BluetoothMap: Proxy object connected
09-22 11:11:30.782  3121  3121 D MapProfile: Bluetooth service connected
09-22 11:11:30.782  3121  3121 D BluetoothMap: getConnectedDevices()
09-22 11:11:30.782  5504  5517 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 11:11:30.784  5504  5701 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 11:11:30.785  3121  3740 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 11:11:30.786  5504  5504 D BluetoothMap: Proxy object connected
09-22 11:11:30.786  5504  5504 D MapProfile: Bluetooth service connected
,09-22 11:11:30.786  5504  5504 D BluetoothMap: getConnectedDevices()
09-22 11:11:30.786   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-22 11:11:30.787  5664  5664 D BluetoothMapService: onReceive
09-22 11:11:30.787  5664  5664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 11:11:30.787  5664  5664 D BluetoothMapService: STATE_ON
09-22 11:11:30.789  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:30.789  5504  5504 D BluetoothA2dp: Proxy object connected
,09-22 11:11:30.790  5664  5704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:30.792  5664  5704 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 11:11:30.792  5664  5704 D BluetoothSdpJni: SDP Create record success - handle: 1
09-22 11:11:30.793  5504  5504 D BluetoothInputDevice: Proxy object connected
09-22 11:11:30.793  5504  5504 D HidProfile: Bluetooth service connected
,09-22 11:11:30.797  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 11:11:30.804  3602  3602 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 11:11:30.804  5504  5504 D DockEventReceiver: finishStartingService: stopping service
,09-22 11:11:30.811  5504  5504 D BluetoothPbap: Proxy object connected
,09-22 11:11:30.811  5504  5504 D PbapServerProfile: Bluetooth service connected
09-22 11:11:30.811  5664  5664 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 11:11:30.811  5664  5664 D ObexServerSockets0: prepareForNewConnect()
09-22 11:11:30.814  3121  3121 D BluetoothPbap: Proxy object connected
09-22 11:11:30.814  3121  3121 D PbapServerProfile: Bluetooth service connected
,09-22 11:11:30.820  5664  5709 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:30.832  5664  5713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 11:11:30.833  5664  5713 I BtOppRfcommListener: Accept thread started.
,09-22 11:11:30.870   928   928 D BluetoothHeadset: Proxy object connected
,09-22 11:11:30.870  5504  5701 D BluetoothHeadset: Proxy object connected
09-22 11:11:30.870   928   928 D BluetoothHeadset: Proxy object connected
09-22 11:11:30.870  3121  3739 D BluetoothHeadset: Proxy object connected
09-22 11:11:30.871  3121  3121 D HeadsetProfile: Bluetooth service connected
,09-22 11:11:30.871   928   928 D BluetoothHeadset: Proxy object connected
,09-22 11:11:30.871  3517  3801 D BluetoothHeadset: Proxy object connected
09-22 11:11:30.873  5504  5504 D HeadsetProfile: Bluetooth service connected
09-22 11:11:30.875  3517  3540 D BluetoothHeadset: Proxy object connected
09-22 11:11:30.875   928   945 D BluetoothHeadset: Proxy object connected
,09-22 11:11:30.876   928   945 D BluetoothHeadset: Proxy object connected
,09-22 11:11:30.880   928   945 D BluetoothHeadset: Proxy object connected
,09-22 11:11:30.886  3121  3136 D BluetoothHeadset: Proxy object connected
,09-22 11:11:30.886  3121  3121 D HeadsetProfile: Bluetooth service connected
,09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:31.731  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:31.739  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 11:11:31.741  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:31.741  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25c9b91 added. We now have 8 listener(s)
09-22 11:11:31.741  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:31.745   928  3155 D WifiService: setWifiEnabled: false pid=5451, uid=10077
,09-22 11:11:31.745   928  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 11:11:31.752  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:31.753   928  3410 D WifiService: setWifiEnabled: true pid=5451, uid=10077
09-22 11:11:31.753   928  3410 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 11:11:31.760   509   921 D SoftapController: Softap fwReload - Ok
,09-22 11:11:31.764   509   921 D CommandListener: Setting iface cfg
,09-22 11:11:31.764   509   921 D CommandListener: Trying to bring down wlan0
09-22 11:11:31.765   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-22 11:11:31.768   928  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 11:11:32.370   928  2980 D wifi    : set interface wlan0 flags (UP)
09-22 11:11:32.373   928  2980 I WifiHAL : Initializing wifi
09-22 11:11:32.374   928  2980 I WifiHAL : Creating socket
,09-22 11:11:32.378   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 11:11:32.380   928  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 11:11:32.381   928  2980 D wifi    : Did set static halHandle = 0x7f779fe560
09-22 11:11:32.381   928  2980 D wifi    : halHandle = 0x7f779fe560, mVM = 0x7f93fcd140, mCls = 0x10190e
09-22 11:11:32.381   928  2980 D wifi    : array field set
09-22 11:11:32.381   928  2980 I WifiNative-HAL: interface[0] = wlan0
,09-22 11:11:32.385   928  5718 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547467814240
,09-22 11:11:32.387   928  5718 D wifi    : waitForHalEvents called, vm = 0x7f93fcd140, obj = 0x10190e, env = 0x7f788ef100
,09-22 11:11:32.391   928  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 11:11:32.393  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:32.441  5719  5719 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 11:11:32.461  5719  5719 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 11:11:32.490  5719  5719 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-22 11:11:32.490  5719  5719 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 11:11:32.511   928  2980 D WifiConfigStore: Loading config and enabling all networks 
,09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:32.514  5451  5451 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:32.518  5451  5451 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 11:11:32.526   928  2980 D WifiConfigStore: loaded 0 passpoint configs
09-22 11:11:32.527   928  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 11:11:32.527   928  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-22 11:11:32.528   928  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-22 11:11:32.530   928  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 11:11:32.530   928  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 11:11:32.530   928  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 11:11:32.530   928  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 11:11:32.534   928  2980 D WifiNative-HAL: Setting external_sim to 1
,09-22 11:11:32.535  4307  4307 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 11:11:32.535   928  2980 D wifi    : setting dfs flag to true, 0x7f7977e8a0
09-22 11:11:32.536   928  2980 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 11:11:32.536   928  2980 D wifi    : setting scan oui 0x7f7977e8a0
,09-22 11:11:32.536   928  2980 D WifiHAL : Sending mac address OUI
,09-22 11:11:32.540   928  2980 E native  : do suspend false
,09-22 11:11:32.547   928  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-22 11:11:32.547   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 11:11:32.547   928   928 D RttService: SCAN_AVAILABLE : 3
09-22 11:11:32.548   928  3088 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 11:11:32.549   509   921 D CommandListener: Setting iface cfg
,09-22 11:11:32.551   928  2979 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
09-22 11:11:32.551   928  2979 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 11:11:32.564   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=212221 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-22 11:11:32.564   928  2979 D WifiNative-HAL: p2pGetDeviceAddress
09-22 11:11:32.565   928  2979 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:32.773  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:32.781  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 11:11:32.787  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-22 11:11:32.789  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-22 11:11:32.793  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@41afde0 Bundle[{}]
,09-22 11:11:32.794  5451  5497 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 11:11:32.794  5451  5497 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-22 11:11:32.795  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-22 11:11:32.796  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-22 11:11:32.797  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-22 11:11:32.799  5451  5497 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-22 11:11:32.806  5451  5497 I System.out: Running OutgoingSocketThread
,09-22 11:11:32.808  5451  5721 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,09-22 11:11:32.811  5451  5721 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39670
,09-22 11:11:32.811  5451  5721 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 11:11:33.809  5451  5497 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-22 11:11:33.810  5451  5497 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,09-22 11:11:33.818  5451  5497 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-22 11:11:33.819  5451  5497 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-22 11:11:33.819  5451  5497 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-22 11:11:33.824  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 11:11:33.825  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfa9af6 added. We now have 2 listener(s)
,09-22 11:11:33.828  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 11:11:33.828  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.828  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.828  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:33.829  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52f1ef7 added. We now have 9 listener(s)
09-22 11:11:33.829  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:33.830  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 11:11:33.834  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:33.838  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:33.840  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:33.841  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:33.841  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:33.841  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31e5fcd added. We now have 3 listener(s)
09-22 11:11:33.843  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:33.844  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:33.844  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.844  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.844  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 11:11:33.845  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aad7082 added. We now have 10 listener(s)
,09-22 11:11:33.845  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:33.845  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:33.845  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:33.845  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:33.846  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:33.846  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.846  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 11:11:33.846  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:33.846  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.846  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfa9af6 removed from the list
09-22 11:11:33.846  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.847  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52f1ef7 removed from the list
09-22 11:11:33.847  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 11:11:33.847  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:33.848  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.848  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:33.850  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.850  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:33.850  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-22 11:11:33.850  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52f1ef7 not in the list
09-22 11:11:33.851  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.851  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:33.853  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 11:11:33.853  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.854  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.854  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aad7082 removed from the list
09-22 11:11:33.854  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.854  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.854  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:33.854  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.854  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31e5fcd removed from the list
09-22 11:11:33.855  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 11:11:33.855  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aacb393 added. We now have 2 listener(s)
09-22 11:11:33.857  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:33.857  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.857  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.857  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:33.858  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16fd0 added. We now have 9 listener(s)
09-22 11:11:33.858  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:33.859  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 11:11:33.862  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:33.865  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:33.866  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:33.867  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:33.867  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:33.867  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c612ce added. We now have 3 listener(s)
09-22 11:11:33.868  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:33.868  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:33.868  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.868  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.869  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 11:11:33.869  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@864f5ef added. We now have 10 listener(s)
09-22 11:11:33.869  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:33.869  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:33.869  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 11:11:33.869  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 11:11:33.869  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:33.869  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 11:11:33.869  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 11:11:33.873  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 11:11:33.873  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 11:11:33.876  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 11:11:33.877  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 11:11:33.877  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 11:11:33.880  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 11:11:33.880  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 11:11:33.880  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 11:11:33.880  5451  5497 D BluetoothAdapter: STATE_ON
09-22 11:11:33.883  5664  5705 D BtGatt.GattService: registerClient() - UUID=0dcc3dd1-e288-4360-b9ea-bfc940ef0621
,09-22 11:11:33.883  5664  5680 D BtGatt.GattService: onClientRegistered() - UUID=0dcc3dd1-e288-4360-b9ea-bfc940ef0621, clientIf=5
,09-22 11:11:33.884  5451  5462 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 11:11:33.885  5664  5700 D BtGatt.GattService: start scan with filters
09-22 11:11:33.888  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 11:11:33.888  5664  5683 D BtGatt.ScanManager: handling starting scan
09-22 11:11:33.888  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 11:11:33.889  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 11:11:33.889  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 11:11:33.890  5664  5683 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ed8f9d
,09-22 11:11:33.892  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:33.892  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 11:11:33.892  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:33.893  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 11:11:33.895  5451  5497 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-22 11:11:33.895  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:33.895  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 11:11:33.895  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.895  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 11:11:33.895  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 11:11:33.895  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 11:11:33.895  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:33.895  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:33.896  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 11:11:33.896  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 11:11:33.897  5451  5497 D BluetoothAdapter: STATE_ON
09-22 11:11:33.897  5664  5680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-22 11:11:33.897  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.897  5664  5683 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 11:11:33.897  5664  5700 D BtGatt.GattService: stopScan() - queue size =1
09-22 11:11:33.898  5664  5675 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 11:11:33.899  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 11:11:33.899  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 11:11:33.899  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 11:11:33.899  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 11:11:33.899  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 11:11:33.900  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:33.901  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 11:11:33.901  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 11:11:33.901  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-22 11:11:33.901  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 11:11:33.903  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:33.903  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:33.903  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 11:11:33.904  5664  5680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 11:11:33.904  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:33.905  5664  5683 D BtGatt.ScanManager: Starting BLE batch scan
09-22 11:11:33.905  5664  5683 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 11:11:33.906  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:33.906  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:33.906  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:33.906  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.907  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.907  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:33.907  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.907  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aacb393 removed from the list
09-22 11:11:33.907  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.907  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16fd0 removed from the list
09-22 11:11:33.907  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:33.907  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:33.908  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.908  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:33.909  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.909  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:33.909  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.909  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16fd0 not in the list
,09-22 11:11:33.910  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.910  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:33.911  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:33.911  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.911  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.911  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@864f5ef removed from the list
09-22 11:11:33.911  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 11:11:33.911  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.911  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:33.911  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.912  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c612ce removed from the list
,09-22 11:11:33.912  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:33.912  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5020b added. We now have 2 listener(s)
,09-22 11:11:33.914  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:33.914  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.914  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.914  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:33.914  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33368e8 added. We now have 9 listener(s)
09-22 11:11:33.915  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:33.915  5664  5680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 11:11:33.915  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.915  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 11:11:33.918  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:33.922  5664  5680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:33.922  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 11:11:33.922  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:33.924  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:33.924  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 11:11:33.924  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:33.924  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ddada6 added. We now have 3 listener(s)
09-22 11:11:33.925  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:33.925  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.925  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:33.925  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.925  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:33.925  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4afb3e7 added. We now have 10 listener(s)
,09-22 11:11:33.925  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:33.925  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:33.926  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:33.926  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 11:11:33.926  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 11:11:33.926  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:33.926  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 11:11:33.927  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:33.928  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 11:11:33.928  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 11:11:33.929  5664  5680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 11:11:33.929  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.930  5664  5683 D BtGatt.ScanManager: stopping BLe Batch
,09-22 11:11:33.931  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 11:11:33.932  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 11:11:33.932  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 11:11:33.934  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 11:11:33.934  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 11:11:33.934  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 11:11:33.934  5664  5680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 11:11:33.934  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:33.935  5451  5497 D BluetoothAdapter: STATE_ON
,09-22 11:11:33.935  5664  5683 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 11:11:33.937  5664  5674 D BtGatt.GattService: registerClient() - UUID=a5b6ab94-34f9-4263-afd6-8a707004e73b
09-22 11:11:33.937  5664  5680 D BtGatt.GattService: onClientRegistered() - UUID=a5b6ab94-34f9-4263-afd6-8a707004e73b, clientIf=5
,09-22 11:11:33.938  5451  5551 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 11:11:33.938  5664  5675 D BtGatt.GattService: start scan with filters
09-22 11:11:33.939  5664  5680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 11:11:33.939  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.940  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 11:11:33.940  5664  5683 D BtGatt.ScanManager: handling starting scan
09-22 11:11:33.940  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 11:11:33.940  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-22 11:11:33.940  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 11:11:33.942  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:33.942  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 11:11:33.942  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:33.943  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 11:11:33.945  5664  5680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 11:11:33.945  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.945  5664  5683 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 11:11:33.945  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:33.946  5451  5497 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-22 11:11:33.946  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:33.946  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:33.946  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:33.946  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.946  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.946  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 11:11:33.946  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.946  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5020b removed from the list
09-22 11:11:33.946  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.946  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33368e8 removed from the list
09-22 11:11:33.946  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:33.946  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:33.947  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.947  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 11:11:33.947  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.947  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 11:11:33.948  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.948  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:33.948  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.948  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33368e8 not in the list
09-22 11:11:33.948  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-22 11:11:33.948  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:33.948  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:33.948  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 11:11:33.948  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 11:11:33.949  5451  5497 D BluetoothAdapter: STATE_ON
09-22 11:11:33.949  5664  5674 D BtGatt.GattService: stopScan() - queue size =1
09-22 11:11:33.949  5664  5680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 11:11:33.949  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.950  5664  5692 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 11:11:33.950  5664  5683 D BtGatt.ScanManager: Starting BLE batch scan
09-22 11:11:33.950  5664  5683 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 11:11:33.950  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 11:11:33.950  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 11:11:33.950  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 11:11:33.950  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 11:11:33.950  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 11:11:33.951  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-22 11:11:33.951  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 11:11:33.951  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 11:11:33.951  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 11:11:33.951  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:33.952  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:33.952  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.952  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.952  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4afb3e7 removed from the list
09-22 11:11:33.952  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:33.952  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.952  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 11:11:33.952  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.952  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:33.952  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:33.953  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.953  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ddada6 removed from the list
09-22 11:11:33.953  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:33.953  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b9a783 added. We now have 2 listener(s)
,09-22 11:11:33.955  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:33.955  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.955  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.955  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:33.955  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7686d00 added. We now have 9 listener(s)
09-22 11:11:33.955  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:33.956  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 11:11:33.958  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 11:11:33.958  5664  5680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 11:11:33.958  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:33.963  5664  5680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-22 11:11:33.963  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:33.963  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:33.966  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:33.966  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 11:11:33.966  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:33.966  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@942cb7e added. We now have 3 listener(s)
,09-22 11:11:33.968  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-22 11:11:33.968  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:33.968  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:33.968  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:33.968  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce538df added. We now have 10 listener(s)
09-22 11:11:33.968  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:33.968  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:33.968  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 11:11:33.968  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 11:11:33.968  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:33.968  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 11:11:33.969  5664  5680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 11:11:33.969  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.969  5664  5683 D BtGatt.ScanManager: stopping BLe Batch
,09-22 11:11:33.969  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:33.970  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:33.971  5451  5497 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 11:11:33.971  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 11:11:33.974  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 11:11:33.974  5664  5680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 11:11:33.975  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.975  5664  5683 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 11:11:33.975  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 11:11:33.975  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 11:11:33.978  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 11:11:33.978  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 11:11:33.978  5451  5497 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 11:11:33.979  5451  5497 D BluetoothAdapter: STATE_ON
09-22 11:11:33.979  5664  5680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 11:11:33.979  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:33.981  5664  5674 D BtGatt.GattService: registerClient() - UUID=e1cf507e-f083-49af-8b54-26eec9900be0
,09-22 11:11:33.981  5664  5680 D BtGatt.GattService: onClientRegistered() - UUID=e1cf507e-f083-49af-8b54-26eec9900be0, clientIf=5
,09-22 11:11:33.982  5451  5462 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 11:11:33.982  5664  5692 D BtGatt.GattService: start scan with filters
,09-22 11:11:33.984  5664  5683 D BtGatt.ScanManager: handling starting scan
,09-22 11:11:33.985  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 11:11:33.985  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 11:11:33.985  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 11:11:33.985  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 11:11:33.986  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 11:11:33.987  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 11:11:33.987  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 11:11:33.987  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 11:11:33.990  5664  5680 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-22 11:11:33.990  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.990  5664  5683 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 11:11:33.991  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 11:11:33.991  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:33.991  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:33.991  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.991  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.991  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 11:11:33.991  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.991  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b9a783 removed from the list
09-22 11:11:33.991  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.991  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7686d00 removed from the list
09-22 11:11:33.992  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 11:11:33.992  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:33.992  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.992  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 11:11:33.992  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.992  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 11:11:33.993  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.993  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:33.993  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.993  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7686d00 not in the list
09-22 11:11:33.993  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 11:11:33.994  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 11:11:33.994  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 11:11:33.994  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 11:11:33.994  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 11:11:33.994  5451  5497 D BluetoothAdapter: STATE_ON
,09-22 11:11:33.995  5664  5674 D BtGatt.GattService: stopScan() - queue size =1
,09-22 11:11:33.995  5664  5692 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 11:11:33.995  5664  5680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 11:11:33.995  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 11:11:33.995  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:33.995  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 11:11:33.995  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 11:11:33.995  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 11:11:33.996  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 11:11:33.996  5664  5683 D BtGatt.ScanManager: Starting BLE batch scan
09-22 11:11:33.996  5664  5683 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 11:11:33.996  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:33.997  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 11:11:33.997  5451  5497 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 11:11:33.997  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 11:11:33.997  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:33.999  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 11:11:33.999  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:33.999  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:33.999  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce538df removed from the list
09-22 11:11:33.999  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:33.999  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:33.999  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:33.999  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:33.999  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@942cb7e removed from the list
,09-22 11:11:34.000  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:34.000  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e83fb added. We now have 2 listener(s)
09-22 11:11:34.001  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:34.001  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:34.001  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:34.001  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 11:11:34.001  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@186dc18 added. We now have 9 listener(s)
09-22 11:11:34.001  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 11:11:34.002  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 11:11:34.003  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:34.004  5451  5451 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 11:11:34.004  5451  5451 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 11:11:34.004  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 11:11:34.004  5664  5680 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 11:11:34.004  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 11:11:34.007  5451  5497 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 11:11:34.009  5451  5497 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 11:11:34.009  5664  5680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 11:11:34.009  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:34.009  5451  5497 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 11:11:34.009  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 11:11:34.009  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc2cc56 added. We now have 3 listener(s)
,09-22 11:11:34.010  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:34.011  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 11:11:34.011  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 11:11:34.011  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 11:11:34.011  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 11:11:34.011  5451  5451 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 11:11:34.011  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb764d7 added. We now have 10 listener(s)
09-22 11:11:34.011  5451  5497 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 11:11:34.011  5451  5497 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 11:11:34.012  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 11:11:34.012  5451  5497 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 11:11:34.012  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:34.012  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:34.012  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 11:11:34.012  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-22 11:11:34.012  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e83fb removed from the list
09-22 11:11:34.012  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:34.012  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@186dc18 removed from the list
09-22 11:11:34.012  5451  5497 D io.jxcore.node.ConnectivityMonitor: stop
09-22 11:11:34.012  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:34.013  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:34.013  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:34.014  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:34.014  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 11:11:34.014  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:34.015  5451  5497 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@186dc18 not in the list
09-22 11:11:34.015  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:34.015  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 11:11:34.015  5664  5680 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 11:11:34.015  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:34.016  5664  5683 D BtGatt.ScanManager: stopping BLe Batch
09-22 11:11:34.016  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-22 11:11:34.016  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 11:11:34.016  5451  5497 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 11:11:34.016  5451  5497 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb764d7 removed from the list
09-22 11:11:34.016  5451  5497 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 11:11:34.016  5451  5497 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 11:11:34.016  5451  5497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 11:11:34.016  5451  5497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 11:11:34.017  5451  5497 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc2cc56 removed from the list
,09-22 11:11:34.017  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-22 11:11:34.017  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-22 11:11:34.018  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-22 11:11:34.018  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 11:11:34.018  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-22 11:11:34.018  5451  5497 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 11:11:34.020  5664  5680 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 11:11:34.020  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 11:11:34.020  5664  5683 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 11:11:34.023  5451  5722 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
,09-22 11:11:34.023  5451  5722 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-22 11:11:34.023  5451  5722 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-22 11:11:34.024  5664  5680 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 11:11:34.024  5664  5680 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 11:11:34.025  5451  5723 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
,09-22 11:11:34.025  5451  5723 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-22 11:11:34.025  5451  5723 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-22 11:11:34.026  5451  5497 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-22 11:11:34.026  5451  5497 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-22 11:11:34.027  5451  5497 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 11:11:34.027  5451  5497 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 11:11:34.027  5451  5497 D com.test.thalitest.ThaliTestRunner: Total duration: 22565 ms
09-22 11:11:34.028  5451  5497 I jxcore-log: *Native tests were executed*
09-22 11:11:34.028  5451  5497 I jxcore-log: 
09-22 11:11:34.028  5451  5497 I jxcore-log: Total number of executed tests:  80
09-22 11:11:34.028  5451  5497 I jxcore-log: 
09-22 11:11:34.028  5451  5497 I jxcore-log: Number of passed tests:  80
09-22 11:11:34.028  5451  5497 I jxcore-log: 
09-22 11:11:34.029  5451  5497 I jxcore-log: Number of failed tests:  0
09-22 11:11:34.029  5451  5497 I jxcore-log: 
,09-22 11:11:34.029  5451  5497 I jxcore-log: Number of ignored tests:  0
09-22 11:11:34.029  5451  5497 I jxcore-log: 
09-22 11:11:34.029  5451  5497 I jxcore-log: Total duration:  22565
09-22 11:11:34.029  5451  5497 I jxcore-log: 
09-22 11:11:34.029  5451  5497 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 11:11:34.029  5451  5497 I jxcore-log: 
,09-22 11:11:34.032  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.032  5451  5497 I jxcore-log: 
09-22 11:11:34.034  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.034  5451  5497 I jxcore-log: 
09-22 11:11:34.035  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.035  5451  5497 I jxcore-log: 
09-22 11:11:34.036  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.036  5451  5497 I jxcore-log: 
09-22 11:11:34.037  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.037  5451  5497 I jxcore-log: 
09-22 11:11:34.039  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.039  5451  5497 I jxcore-log: 
09-22 11:11:34.040  5451  5451 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-22 11:11:34.041  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 11:11:34.041  5451  5497 I jxcore-log: 
09-22 11:11:34.043  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.043  5451  5497 I jxcore-log: 
09-22 11:11:34.044  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.044  5451  5497 I jxcore-log: 
09-22 11:11:34.045  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.045  5451  5497 I jxcore-log: 
09-22 11:11:34.046  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.046  5451  5497 I jxcore-log: 
09-22 11:11:34.047  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 11:11:34.047  5451  5497 I jxcore-log: 
09-22 11:11:34.048  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.048  5451  5497 I jxcore-log: 
09-22 11:11:34.049  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.049  5451  5497 I jxcore-log: 
09-22 11:11:34.049  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.049  5451  5497 I jxcore-log: 
,09-22 11:11:34.050  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.050  5451  5497 I jxcore-log: 
,09-22 11:11:34.051  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.051  5451  5497 I jxcore-log: 
09-22 11:11:34.051  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.051  5451  5497 I jxcore-log: 
,09-22 11:11:34.052  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.052  5451  5497 I jxcore-log: 
09-22 11:11:34.053  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.053  5451  5497 I jxcore-log: 
,09-22 11:11:34.053  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.053  5451  5497 I jxcore-log: 
,09-22 11:11:34.054  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 11:11:34.054  5451  5497 I jxcore-log: 
09-22 11:11:34.055  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.055  5451  5497 I jxcore-log: 
,09-22 11:11:34.055  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.055  5451  5497 I jxcore-log: 
09-22 11:11:34.056  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.056  5451  5497 I jxcore-log: 
09-22 11:11:34.057  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.057  5451  5497 I jxcore-log: 
,09-22 11:11:34.057  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.057  5451  5497 I jxcore-log: 
,09-22 11:11:34.058  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.058  5451  5497 I jxcore-log: 
09-22 11:11:34.059  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 11:11:34.059  5451  5497 I jxcore-log: 
,09-22 11:11:34.404  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 11:11:34.409  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 11:11:34.409  5451  5497 I jxcore-log: 
,09-22 11:11:34.454  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 11:11:34.459  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 11:11:34.459  5451  5497 I jxcore-log: 
,09-22 11:11:34.505  5451  5451 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 11:11:34.508  5451  5497 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 11:11:34.508  5451  5497 I jxcore-log: 
,09-22 11:11:34.539  5724  5724 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 11:11:34.544  5724  5724 D AndroidRuntime: CheckJNI is OFF
,09-22 11:11:34.577  5724  5724 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 11:11:34.610  5724  5724 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 11:11:34.627  5724  5724 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 11:11:34.635   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-22 11:11:34.636   928   941 I ActivityManager: Killing 5451:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-22 11:11:34.713   928   938 I WindowState: WIN DEATH: Window{bc13b00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 11:11:34.713   928  3409 D GraphicsStats: Buffer count: 2
09-22 11:11:34.714   928  2981 D WifiService: Client connection lost with reason: 4
,09-22 11:11:34.777   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-22 11:11:34.777   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-22 11:11:34.778   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-22 11:11:34.778   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-22 11:11:34.778   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:34.778   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:34.778   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 11:11:34.778   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 11:11:34.778   928   941 I ActivityManager:   Force finishing activity ActivityRecord{495bb5d u0 com.test.thalitest/.MainActivity t2}
09-22 11:11:34.780   928   952 I art     : Starting a blocking GC Explicit
,09-22 11:11:34.786   928  3409 W ActivityManager: Spurious death for ProcessRecord{3d358c9 0:com.test.thalitest/u0a77}, curProc for 5451: null
,09-22 11:11:34.790   928   946 W WindowManager: Attempted to add application window with unknown token Token{9c54cd2 ActivityRecord{495bb5d u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-22 11:11:34.791   928   946 W WindowManager: Token{9c54cd2 ActivityRecord{495bb5d u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{9c54cd2 ActivityRecord{495bb5d u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-22 11:11:34.791   928   946 W WindowManager: view not successfully added to wm, removing view
09-22 11:11:34.791   928   946 W WindowManager: Exception when adding starting window
09-22 11:11:34.791   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{c3449e8 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 11:11:34.791   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-22 11:11:34.791   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-22 11:11:34.791   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-22 11:11:34.791   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-22 11:11:34.791   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-22 11:11:34.791   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:34.791   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:34.791   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 11:11:34.791   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 11:11:34.861   928   952 I art     : Explicit concurrent mark sweep GC freed 24602(1570KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.424ms total 81.052ms
,09-22 11:11:34.880   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-22 11:11:34.882  5724  5724 I art     : System.exit called, status: 0
,09-22 11:11:34.883  5724  5724 I AndroidRuntime: VM exiting with result code 0.
,09-22 11:11:34.902   928   952 I ActivityManager: Start proc 5734:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-22 11:11:34.903   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-22 11:11:34.910   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-22 11:11:34.916  5664  5664 D BluetoothMapAppObserver: onReceive
,09-22 11:11:34.916  5664  5664 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-22 11:11:34.917  3625  3961 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-22 11:11:34.923  3411  3411 I Keyboard.Facilitator: resetDictionaries() : en_US
09-22 11:11:34.928   928  2944 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-22 11:11:34.965    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 11:11:34.961  3411  5746 I Keyboard.Facilitator.DecoderInitializer: run()
09-22 11:11:34.972  3602  3602 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-22 11:11:34.972  3602  3602 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-22 11:11:34.973  3427  5747 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-22 11:11:34.974  3517  3517 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-22 11:11:34.971    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 11:11:34.986   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-22 11:11:34.981    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 11:11:34.997   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-22 11:11:34.998   928   940 E PackageManager: Failed to write settings, restoring backup
09-22 11:11:34.998   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-22 11:11:34.998   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-22 11:11:34.998   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-22 11:11:34.998   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-22 11:11:34.998   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-22 11:11:34.998   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:34.998   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:34.998   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 11:11:35.000   928   941 E DropBoxManagerService: Can't write: system_server_wtf
09-22 11:11:35.000   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-22 11:11:35.000   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 11:11:35.000   928   941 E DropBoxManagerService: 	... 13 more
,09-22 11:11:35.004  3557  3688 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-22 11:11:35.009  3411  5746 E native  : dynamic-lm.cc:252 Cannot rename /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict
,09-22 11:11:35.012  3893  5753 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-22 11:11:35.012  3893  5753 D AccountUtils: Clearing selected account for com.test.thalitest
,09-22 11:11:35.013  3411  5746 I Decoder : createOrResetDecoder
,09-22 11:11:35.017   928  3410 I ActivityManager: Start proc 5756:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-22 11:11:35.018  3557  3688 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-22 11:11:35.018  3557  3688 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3557
09-22 11:11:35.018  3557  3688 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.018  3557  3688 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 11:11:35.021   928  3532 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 11:11:35.023   928  5762 E DropBoxManagerService: Can't write: system_app_crash
09-22 11:11:35.023   928  5762 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 11:11:35.023   928  5762 E DropBoxManagerService: 	... 5 more
,09-22 11:11:35.026  3557  3688 I Process : Sending signal. PID: 3557 SIG: 9
,09-22 11:11:35.047  3427  3448 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj4FA5219D2) - 
,09-22 11:11:35.048  3427  3448 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-22 11:11:35.048  3427  3448 E AndroidRuntime: Process: android.process.acore, PID: 3427
09-22 11:11:35.048  3427  3448 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.048  3427  3448 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 11:11:35.071  3893  5753 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-22 11:11:35.087  3602  3602 I ConfigService: onCreate
,09-22 11:11:35.098  3427  5747 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-22 11:11:35.098  3427  5747 I Process : Sending signal. PID: 3427 SIG: 9
,09-22 11:11:35.137   928  3524 D GraphicsStats: Buffer count: 1
,09-22 11:11:35.137   928  3440 I WindowState: WIN DEATH: Window{65d5071 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-22 11:11:35.142   928   939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3557) has died
,09-22 11:11:35.143   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-22 11:11:35.145   928   939 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 11:11:35.165   928   941 I ActivityManager: Start proc 5774:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 11:11:35.183   928   939 I ActivityManager: Process android.process.acore (pid 3427) has died
,09-22 11:11:35.184   928   939 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-22 11:11:35.211  5774  5774 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:35.211  5774  5774 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 11:11:35.211  5774  5774 D AndroidRuntime: Shutting down VM
,09-22 11:11:35.217  5774  5774 E AndroidRuntime: FATAL EXCEPTION: main
09-22 11:11:35.217  5774  5774 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5774
09-22 11:11:35.217  5774  5774 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 11:11:35.217  5774  5774 E AndroidRuntime: 	... 10 more
09-22 11:11:35.219   928  3532 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-22 11:11:35.220   928  5787 E DropBoxManagerService: Can't write: system_app_crash
09-22 11:11:35.220   928  5787 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 11:11:35.220   928  5787 E DropBoxManagerService: 	... 5 more
09-22 11:11:35.220  5774  5774 I Process : Sending signal. PID: 5774 SIG: 9
,09-22 11:11:35.234   928  3559 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5774) has died
,09-22 11:11:35.235   928  3559 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 11:11:35.250   928   941 I ActivityManager: Start proc 5788:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 11:11:35.300  5788  5788 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:35.300  5788  5788 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 11:11:35.300  5788  5788 D AndroidRuntime: Shutting down VM
,09-22 11:11:35.308  5788  5788 E AndroidRuntime: FATAL EXCEPTION: main
09-22 11:11:35.308  5788  5788 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5788
09-22 11:11:35.308  5788  5788 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 11:11:35.308  5788  5788 E AndroidRuntime: 	... 10 more
09-22 11:11:35.311   928   938 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-22 11:11:35.311   928  5800 E DropBoxManagerService: Can't write: system_app_crash
09-22 11:11:35.311   928  5800 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 11:11:35.311   928  5800 E DropBoxManagerService: 	... 5 more
09-22 11:11:35.312  5788  5788 I Process : Sending signal. PID: 5788 SIG: 9
,09-22 11:11:35.333   928  3524 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5788) has died
,09-22 11:11:35.335   928  3524 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 11:11:35.352   928   941 I ActivityManager: Start proc 5801:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 11:11:35.362   385   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
