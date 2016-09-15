#### Test 829140738877506_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 08:05:05.446   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 08:05:05.447   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:05:05.983  5423  5423 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 08:05:05.989  5423  5423 D AndroidRuntime: CheckJNI is OFF
09-15 08:05:06.012  5423  5423 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 08:05:06.043  5423  5423 I Radio-JNI: register_android_hardware_Radio DONE
09-15 08:05:06.058  5423  5423 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 08:05:06.061   929  3715 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 08:05:06.101   929  3715 I ActivityManager: Start proc 5432:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 08:05:06.106  5423  5423 D AndroidRuntime: Shutting down VM
09-15 08:05:06.192  5432  5432 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 08:05:06.209  5432  5432 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 08:05:06.229  5432  5432 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 9944-9961)
09-15 08:05:06.229  5432  5432 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 08:05:06.249  5432  5432 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1661300}
09-15 08:05:06.249  5432  5432 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 08:05:06.249  5432  5432 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 08:05:06.252  5432  5432 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 08:05:06.253  5432  5432 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 08:05:06.284  5432  5432 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-15 08:05:06.293  5432  5432 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 08:05:06.293  5432  5432 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 08:05:06.293  5432  5432 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 08:05:06.293  5432  5432 I Adreno  : Build Date                       : 12/06/15
09-15 08:05:06.293  5432  5432 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 08:05:06.293  5432  5432 I Adreno  : Local Branch                     : mybranch17112971
09-15 08:05:06.293  5432  5432 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 08:05:06.293  5432  5432 I Adreno  : Remote Branch                    : NONE
09-15 08:05:06.293  5432  5432 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 08:05:06.328   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ae030d:true
,09-15 08:05:06.358  2570  2570 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[22450]" dev="sockfs" ino=22450 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 08:05:06.358  2570  2570 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22450]" dev="sockfs" ino=22450 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 08:05:06.371  5432  5432 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 08:05:06.380  5432  5432 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 08:05:06.404  5432  5469 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 08:05:06.398  2570  2570 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31483]" dev="sockfs" ino=31483 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 08:05:06.401  2570  2570 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31483]" dev="sockfs" ino=31483 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 08:05:06.401  3105  3105 W Binder_3: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[22461]" dev="sockfs" ino=22461 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 08:05:06.404  3105  3105 W Binder_3: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[22461]" dev="sockfs" ino=22461 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 08:05:06.410  5432  5456 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 08:05:06.435  5432  5469 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 08:05:06.523   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +381ms (total +448ms)
,09-15 08:05:06.534  5432  5432 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5432
,09-15 08:05:06.631  5432  5432 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 08:05:06.855  5432  5470 D jxcore_app_log: JniHelper::setJavaVM(0xf503c000), pthread_self() = -566494928
,09-15 08:05:06.862  5432  5470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 08:05:06.862  5432  5470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 08:05:06.862  5432  5470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 08:05:06.862  5432  5470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 08:05:06.862  5432  5470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 08:05:06.862  5432  5470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34eaa31 added. We now have 1 listener(s)
,09-15 08:05:06.866  5432  5470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-15 08:05:06.867  5432  5470 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:06.868  5432  5470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:06.868  5432  5470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 08:05:06.876  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 08:05:06.877  5432  5470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8b7884 added. We now have 1 listener(s)
09-15 08:05:06.877  5432  5470 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:05:06.883   929  2946 D WifiService: New client listening to asynchronous messages
,09-15 08:05:06.884  5432  5470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:05:06.884  5432  5470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 08:05:06.884  5432  5470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 08:05:06.885  5432  5470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-15 08:05:06.885  5432  5470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-15 08:05:06.888  5432  5470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:06.888  5432  5470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 08:05:06.895  5432  5470 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:06.895  5432  5470 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:05:06.895  5432  5470 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-15 08:05:06.895  5432  5470 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:06.897  5432  5470 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 08:05:06.899  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:06.903  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:06.921  5432  5432 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 08:05:07.190  5432  5478 W jxcore-log: Initializing JXcore engine
09-15 08:05:07.190  5432  5478 W jxcore-log: JXcore engine is ready
,09-15 08:05:07.211  5478  5478 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12917 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-15 08:05:07.211  5478  5478 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[13364]" dev="sockfs" ino=13364 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 08:05:07.211  5478  5478 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 08:05:07.211  5478  5478 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31463]" dev="sockfs" ino=31463 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 08:05:07.221  5432  5478 W jxcore-log: Starting JXcore engine
,09-15 08:05:07.272  5432  5478 W jxcore-log: Platform android
09-15 08:05:07.272  5432  5478 W jxcore-log: 
09-15 08:05:07.272  5432  5478 W jxcore-log: Process ARCH arm
09-15 08:05:07.272  5432  5478 W jxcore-log: 
,09-15 08:05:07.368  5432  5478 I jxcore-log: JXcore Cordova bridge is ready!
09-15 08:05:07.368  5432  5478 I jxcore-log: 
09-15 08:05:07.368  5432  5478 W jxcore-log: JXcore engine is started
,09-15 08:05:07.371  5432  5470 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 08:05:07.375  5432  5432 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 08:05:14.000  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 08:05:14.000  5432  5478 I jxcore-log: 
,09-15 08:05:14.001  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 08:05:14.001  5432  5478 I jxcore-log: 
,09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.005  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:05:14.007  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 08:05:14.009  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 08:05:14.009  5432  5478 I jxcore-log: 
09-15 08:05:14.010  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 08:05:14.010  5432  5478 I jxcore-log: 
,09-15 08:05:14.365  5432  5478 D executeNativeTests: Running unit tests
,09-15 08:05:14.406  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 08:05:14.406  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 added. We now have 2 listener(s)
,09-15 08:05:14.407  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:05:14.407  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 08:05:14.407  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:14.407  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:14.407  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 added. We now have 2 listener(s)
09-15 08:05:14.407  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:14.408  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:05:14.409  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.413  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:05:14.413  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.414  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:14.416  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 08:05:14.416  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:05:14.416  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:05:14.417  5432  5478 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 08:05:14.417  5432  5478 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 08:05:14.417  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 08:05:14.417  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:05:14.417  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:05:14.417  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.418  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.418  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.418  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.418  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.418  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:14.418  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:14.419  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 removed from the list
09-15 08:05:14.419  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.419  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btco,nnectorlib.DiscoveryManager@121fa66 removed from the list
09-15 08:05:14.421  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.427  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.428  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:05:14.428  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.428  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.428  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.429  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.429  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.429  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.429  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.430  5432  5478 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-15 08:05:14.431  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.431  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.431  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.431  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.431  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.431  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.431  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.431  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.431  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.431  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.431  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.431  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.431  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.431  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.432  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.432  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.432  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.432  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 08:05:14.435  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 08:05:14.436  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:05:14.436  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.436  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.436  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.436  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.436  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.436  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.436  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.436  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
,09-15 08:05:14.436  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.436  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.436  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.436  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.436  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.437  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.437  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:05:14.437  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.437  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.438  5432  5478 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 08:05:14.439  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.448  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:05:14.449  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.449  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:14.449  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:14.449  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:05:14.449  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:05:14.449  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:14.449  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 08:05:14.451  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:05:14.451  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 08:05:14.452  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:14.453  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:05:14.454  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.455  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 08:05:14.455  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 08:05:14.456  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-15 08:05:14.457  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 08:05:14.457  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 08:05:14.457  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 08:05:14.457  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:05:14.458  5432  5478 D BluetoothAdapter: STATE_ON
,09-15 08:05:14.460  4383  4584 D BtGatt.GattService: registerClient() - UUID=0ca4c868-9934-4943-9a37-66a0abc75a79
,09-15 08:05:14.460  4383  4445 D BtGatt.GattService: onClientRegistered() - UUID=0ca4c868-9934-4943-9a37-66a0abc75a79, clientIf=5
,09-15 08:05:14.462  5432  5443 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:05:14.463  4383  4603 D BtGatt.GattService: start scan with filters
,09-15 08:05:14.467  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:05:14.467  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:05:14.468  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:05:14.468  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:05:14.468  4383  4448 D BtGatt.ScanManager: handling starting scan
,09-15 08:05:14.469  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:14.469  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:05:14.469  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:14.469  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 08:05:14.470  4383  4448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:14.471  5432  5478 I io.jxcore.node.ConnectionHelper: start: OK
09-15 08:05:14.472  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:05:14.472  5432  5478 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 08:05:14.472  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.472  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:05:14.472  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.472  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:05:14.472  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:05:14.472  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:05:14.472  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:05:14.472  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:14.472  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 08:05:14.472  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 08:05:14.473  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:14.473  4383  4584 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:05:14.473  4383  4603 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:05:14.473  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:05:14.474  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:05:14.474  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:05:14.474  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:05:14.474  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 08:05:14.474  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.475  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:05:14.475  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:05:14.475  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:05:14.475  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:14.476  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:05:14.476  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.476  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:14.476  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.476  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.476  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.476  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.476  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.476  5432  5478 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 08:05:14.476  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 08:05:14.476  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 08:05:14.476  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.477  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:14.479  4383  4445 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:05:14.479  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:14.479  4383  4448 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.481  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:05:14.483  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.483  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:14.483  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:14.483  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:05:14.483  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:05:14.483  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:14.483  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 08:05:14.485  4383  4445 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 08:05:14.485  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.486  4383  4448 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:05:14.486  4383  4448 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:05:14.486  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 08:05:14.486  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 08:05:14.486  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:14.489  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.489  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:05:14.490  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:05:14.490  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:05:14.494  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 08:05:14.494  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:05:14.494  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:05:14.495  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:14.495  4383  4445 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:05:14.495  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.496  4383  4584 D BtGatt.GattService: registerClient() - UUID=b19ea962-893a-4841-bb20-a98462fabcab
,09-15 08:05:14.496  4383  4445 D BtGatt.GattService: onClientRegistered() - UUID=b19ea962-893a-4841-bb20-a98462fabcab, clientIf=5
09-15 08:05:14.497  5432  5443 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:05:14.497  4383  4397 D BtGatt.GattService: start scan with filters
09-15 08:05:14.500  4383  4445 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:05:14.500  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:14.501  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:05:14.501  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:05:14.501  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:05:14.501  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:05:14.503  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:05:14.503  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:05:14.503  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:14.504  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:05:14.506  5432  5478 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 08:05:14.506  4383  4445 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:05:14.506  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.507  4383  4448 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:05:14.508  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:05:14.508  5432  5478 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 08:05:14.508  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.508  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:05:14.508  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.508  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:05:14.508  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:05:14.508  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:05:14.509  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 08:05:14.509  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:14.509  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:05:14.509  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 08:05:14.509  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:14.510  4383  4584 D BtGatt.GattService: stopScan() - queue size =0
,09-15 08:05:14.510  4383  4397 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:05:14.511  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:05:14.511  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:05:14.511  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 08:05:14.511  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:05:14.511  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:05:14.511  4383  4445 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:05:14.511  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.512  4383  4448 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:05:14.512  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.512  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:05:14.512  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 08:05:14.512  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:05:14.512  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:05:14.513  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.513  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:14.513  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.513  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:14.513  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:14.513  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.513  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.513  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.513  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.514  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.514  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.514  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.514  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.515  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:14.515  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.515  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.515  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.516  5432  5478 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-15 08:05:14.516  4383  4445 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 08:05:14.517  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.517  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:05:14.518  4383  4448 D BtGatt.ScanManager: handling starting scan
,09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.521  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:05:14.523  4383  4445 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 08:05:14.523  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.523  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.523  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:14.523  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:14.523  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:05:14.523  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:05:14.524  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:14.524  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 08:05:14.523  4383  4448 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 08:05:14.525  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:05:14.525  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 08:05:14.526  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.528  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 08:05:14.528  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.529  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:05:14.529  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:05:14.530  4383  4445 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:05:14.530  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.530  4383  4448 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:05:14.531  4383  4448 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 08:05:14.532  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 08:05:14.532  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:05:14.532  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:05:14.533  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:14.534  4383  4603 D BtGatt.GattService: registerClient() - UUID=1b6d9fbd-4528-4320-b54b-9a7124679bcb
09-15 08:05:14.535  4383  4445 D BtGatt.GattService: onClientRegistered() - UUID=1b6d9fbd-4528-4320-b54b-9a7124679bcb, clientIf=5
09-15 08:05:14.536  5432  5442 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 08:05:14.536  4383  4584 D BtGatt.GattService: start scan with filters
,09-15 08:05:14.540  4383  4445 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 08:05:14.540  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:14.541  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:05:14.541  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:05:14.541  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:05:14.541  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:05:14.543  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:14.543  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:05:14.543  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:14.544  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 08:05:14.545  4383  4445 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:05:14.545  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:14.546  5432  5478 I io.jxcore.node.ConnectionHelper: start: OK
09-15 08:05:14.546  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.546  5432  5478 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 08:05:14.546  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:05:14.546  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:05:14.547  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.547  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:05:14.547  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:05:14.547  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 08:05:14.547  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 08:05:14.547  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:14.547  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:05:14.547  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 08:05:14.548  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:14.548  4383  4397 D BtGatt.GattService: stopScan() - queue size =0
09-15 08:05:14.549  4383  4584 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 08:05:14.549  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:05:14.549  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:05:14.549  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:05:14.549  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:05:14.549  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:05:14.550  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.550  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 08:05:14.550  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:05:14.550  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:05:14.551  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:14.552  4383  4445 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:05:14.552  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.552  5432  5478 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 08:05:14.552  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:14.552  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.552  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.552  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:14.552  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.552  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.552  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:14.552  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:14.552  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.552  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.552  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.552  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.552  4383  4448 D BtGatt.ScanManager: stopping BLe Batch
09-15 08:05:14.552  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.552  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.553  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.553  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.554  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.554  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.554  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.554  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.555  5432  5478 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 08:05:14.555  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.555  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.555  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.556  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.556  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.556  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.556  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.556  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.556  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.556  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.556  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.556  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.556  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.556  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.557  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:14.557  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.557  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.557  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.557  4383  4445 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:05:14.557  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.558  4383  4448 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:05:14.558  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 08:05:14.558  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.558  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.558  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.558  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.558  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.558  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.558  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.558  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.558  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
,09-15 08:05:14.559  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.559  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.559  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.559  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.559  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.559  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.560  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.560  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.560  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.560  5432  5478 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 08:05:14.561  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.561  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.561  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.561  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.561  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.561  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.561  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.561  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.561  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.561  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.561  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.561  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.561  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.561  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.562  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.562  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.562  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.562  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.563  4383  4445 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 08:05:14.563  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-15 08:05:14.563  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.563  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.563  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.563  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.563  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:05:14.563  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:05:14.563  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.564  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.564  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.564  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.564  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:05:14.564  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:05:14.564  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.564  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.564  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.565  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.565  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.565  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.566  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.566  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 08:05:14.566  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:05:14.566  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 08:05:14.566  4383  4448 D BtGatt.ScanManager: handling starting scan
09-15 08:05:14.566  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:05:14.566  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-15 08:05:14.567  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:05:14.567  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.567  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:05:14.567  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.567  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.567  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:05:14.567  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.567  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.567  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.567  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.567  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.567  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.567  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.567  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.567  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.569  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.569  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.569  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.569  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.570  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:05:14.570  5432  5478 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 08:05:14.570  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 08:05:14.572  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:05:14.572  5432  5478 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 08:05:14.572  4383  4445 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:05:14.572  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 08:05:14.573  4383  4448 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 08:05:14.573  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 08:05:14.574  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-15 08:05:14.574  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 08:05:14.574  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 08:05:14.574  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 08:05:14.574  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 08:05:14.574  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 08:05:14.574  5432  5478 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 08:05:14.574  5432  5478 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 08:05:14.574  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:05:14.574  5432  5478 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 08:05:14.574  5432  5478 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 08:05:14.575  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-15 08:05:14.575  5432  5478 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 08:05:14.575  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 08:05:14.577  4383  4445 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:05:14.577  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.577  4383  4448 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:05:14.577  4383  4448 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:05:14.578  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 08:05:14.578  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-15 08:05:14.578  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 08:05:14.579  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-15 08:05:14.579  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 08:05:14.579  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 08:05:14.579  5432  5478 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:05:14.579  5432  5478 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 08:05:14.579  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-15 08:05:14.580  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.580  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.580  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.580  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.581  5432  5479 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:05:14.580  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.582  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.582  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 08:05:14.583  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.583  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.583  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.583  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.583  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.581  4397  4397 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30147]" dev="sockfs" ino=30147 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:05:14.581  4397  4397 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30147]" dev="sockfs" ino=30147 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 08:05:14.583  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.583  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.583  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.583  5432  5480 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 08:05:14.583  5432  5480 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-15 08:05:14.583  5432  5480 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-15 08:05:14.584  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.584  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.584  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.584  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.585  5432  5478 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 08:05:14.585  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.585  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.585  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.585  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.585  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.585  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.585  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.585  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.585  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.585  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.586  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.586  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.586  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.586  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.586  4383  4445 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:05:14.586  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.587  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:14.587  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.587  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.587  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.588  5432  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-15 08:05:14.588  5432  5478 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 08:05:14.588  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.588  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.588  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.588  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.589  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.589  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:14.589  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.589  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.589  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.589  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.589  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.589  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.590  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.590  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.591  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.591  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.591  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.591  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.592  5432  5478 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 08:05:14.592  5432  5478 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 08:05:14.592  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 08:05:14.592  5432  5478 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 08:05:14.592  5432  5478 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 08:05:14.592  5432  5478 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 08:05:14.592  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 08:05:14.593  5432  5478 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 08:05:14.593  5432  5478 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-15 08:05:14.593  5432  5478 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 08:05:14.593  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 08:05:14.593  5432  5478 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 08:05:14.593  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.593  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.593  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.593  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.593  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.594  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.594  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.594  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.594  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.594  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.594  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.594  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.594  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.594  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.596  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.596  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.597  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.597  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.597  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:05:14.597  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.597  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.598  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.598  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.598  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.598  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.598  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.598  4383  4445 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:05:14.598  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.598  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.598  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:14.598  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.598  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.598  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.598  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.599  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.599  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.599  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.599  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.599  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.599  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.599  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.599  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.599  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.599  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
,09-15 08:05:14.599  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.599  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.600  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.600  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.600  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.601  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.601  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.601  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.601  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.602  5432  5478 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 08:05:14.602  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:05:14.603  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 08:05:14.604  5432  5478 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 08:05:14.604  5432  5478 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:05:14.605  4383  4445 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:05:14.605  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.605  4383  4448 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 08:05:14.605  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 08:05:14.605  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.605  5432  5478 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 08:05:14.605  5432  5432 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 08:05:14.605  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
,09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.605  5432  5432 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 08:05:14.605  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:05:14.605  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:05:14.605  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:14.605  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.606  5432  5481 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:05:14.606  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.604  4584  4584 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33558]" dev="sockfs" ino=33558 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:05:14.604  4584  4584 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33558]" dev="sockfs" ino=33558 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:05:14.607  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.607  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.608  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.608  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.608  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:14.608  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.608  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.608  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:14.608  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.608  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:14.608  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.608  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.608  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.608  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.608  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.608  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14,.608  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.608  5432  5481 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 08:05:14.608  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.608  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.608  5432  5481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 08:05:14.608  5432  5481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 08:05:14.609  5432  5432 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 08:05:14.609  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.610  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.610  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.610  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.610  4383  4445 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:05:14.610  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.610  4383  4448 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:05:14.611  5432  5478 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 08:05:14.611  5432  5478 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 08:05:14.611  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 08:05:14.611  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:05:14.611  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.611  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.611  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.611  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.611  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.611  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.611  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.611  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.611  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.611  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.612  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.612  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.612  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.612  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.612  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.613  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.613  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.613  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.615  4383  4445 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 08:05:14.615  4383  4445 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:14.617  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.617  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.617  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.617  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.617  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.617  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.617  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.617  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.617  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.617  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.617  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.617  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.617  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.617  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.618  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.618  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.618  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.618  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.619  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:14.619  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:14.619  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:14.619  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:14.619  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.619  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.619  5432  5478 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77112c1 not in the list
09-15 08:05:14.619  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.619  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.619  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:14.619  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.619  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.620  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:14.620  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:14.620  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:14.620  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:14.620  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:14.621  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121fa66 not in the list
09-15 08:05:14.621  5432  5478 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 08:05:14.621  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 08:05:14.621  5432  5478 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 08:05:14.621  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 08:05:14.622  5432  5478 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 08:05:14.622  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 08:05:14.623  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 08:05:14.623  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 08:05:14.623  5432  5478 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 08:05:14.623  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 08:05:14.624  5432  5478 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 08:05:14.624  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 08:05:14.624  5432  5478 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 08:05:14.624  5432  5478 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 08:05:14.625  5432  5478 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 08:05:14.625  5432  5478 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 08:05:14.626  5432  5478 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 08:05:14.626  5432  5478 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 08:05:14.626  5432  5478 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 08:05:14.626  5432  5478 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 08:05:14.627  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:14.627  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e48dad8 added. We now have 2 listener(s)
09-15 08:05:14.627  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:14.628  5432  5478 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 08:05:14.629   929  3714 D WifiService: setWifiEnabled: true pid=5432, uid=10077
09-15 08:05:14.629   929  3714 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 08:05:14.629  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:14.629  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c32e31 added. We now have 3 listener(s)
09-15 08:05:14.630  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:14.633  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:14.633  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13c916 added. We now have 4 listener(s)
09-15 08:05:14.634  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:14.636  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:14.636  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb58297 added. We now have 5 listener(s)
09-15 08:05:14.636  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:14.637   929  3715 D WifiService: setWifiEnabled: false pid=5432, uid=10077
09-15 08:05:14.637   929  3715 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 08:05:14.640   929  2939 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 08:05:14.640   929  2939 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 08:05:14.640   929  2939 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:05:14.640   929  2939 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 08:05:14.642  4383  4441 D BluetoothAdapterState: Current state: ON, message: 23
09-15 08:05:14.642  4383  4441 D BluetoothAdapterProperties: Setting state to 13
09-15 08:05:14.642  4383  4441 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 08:05:14.643  4383  4441 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 08:05:14.644  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:14.645  4383  4441 I BluetoothAdapterState: Entering PendingCommandState
09-15 08:05:14.647   929  2939 E native  : do suspend true
09-15 08:05:14.647  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.647  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:05:14.648  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.648  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.648  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:14.648  4383  4445 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:05:14.649  4383  4441 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 08:05:14.650  4383  4383 D HeadsetService: Received stop request...Stopping profile...
09-15 08:05:14.651  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.653  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.654   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:14.654  3457  3479 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:14.655   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:14.655   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:14.655  3072  3655 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:14.655  3072  3072 D HeadsetProfile: Bluetooth service disconnected
09-15 08:05:14.655  4383  4383 D A2dpService: Received stop request...Stopping profile...
09-15 08:05:14.655  4383  4586 D A2dpStateMachine: Exit Disconnected: -1
09-15 08:05:14.656  3072  3072 D BluetoothA2dp: Proxy object disconnected
09-15 08:05:14.656   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 08:05:14.657  4383  4383 D HidService: Received stop request...Stopping profile...
09-15 08:05:14.657  4383  4383 D HidService: Stopping Bluetooth HidService
09-15 08:05:14.658  3072  3072 D BluetoothInputDevice: Proxy object disconnected
09-15 08:05:14.658  3072  3072 D HidProfile: Bluetooth service disconnected
09-15 08:05:14.658  4383  4383 D HealthService: Received stop request...Stopping profile...
09-15 08:05:14.659  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:05:14.659  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:05:14.659  4383  4383 D PanService: Received stop request...Stopping profile...
09-15 08:05:14.660  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.660  3072  3072 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 08:05:14.660  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:05:14.660  3072  3072 D PanProfile: Bluetooth service disconnected
09-15 08:05:14.660  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.660  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.660  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.660  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.660  4383  4383 D BluetoothMapService: Received stop request...Stopping profile...
09-15 08:05:14.660  4383  4383 D BluetoothMapService: stop()
09-15 08:05:14.661  4383  4383 D BluetoothMapAppObserver: deinitObservers()
09-15 08:05:14.661  4383  4383 D BluetoothMapAppObserver: removeReceiver()
09-15 08:05:14.662  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.662  3072  3072 D BluetoothMap: Proxy object disconnected
09-15 08:05:14.662  3072  3072 D MapProfile: Bluetooth service disconnected
09-15 08:05:14.663  4383  4383 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 08:05:14.663  4383  4383 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 08:05:14.663  4383  4445 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 08:05:14.663  4383  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:14.664  4383  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:14.664  4383  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:14.664  4383  4445 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 08:05:14.664  4383  4383 D SapService: Received stop request...Stopping profile...
09-15 08:05:14.664  4383  4383 V SapService: stop()
09-15 08:05:14.665  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.665  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.665  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.665  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.666  4383  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:14.666  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.666  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.666  4383  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:14.666  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.666  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.666  4383  4445 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 08:05:14.666  4383  4383 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 08:05:14.666  4383  4576 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:05:14.666  4383  4383 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 08:05:14.666  4383  4576 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:05:14.667  4383  4576 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:05:14.667  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.667  4383  4576 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:05:14.667  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.667  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.667  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.667  4383  4383 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 08:05:14.667  4383  4383 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 08:05:14.668  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.668  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.668  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.668  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.668  4383  4383 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 08:05:14.668  4383  4383 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 08:05:14.669  4383  4445 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 08:05:14.669  4383  4383 D BluetoothMapService: MAP Service closeService in
09-15 08:05:14.669  4383  4445 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 08:05:14.669  4383  4383 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 08:05:14.669  4383  4383 D ObexServerSockets0: shutdown(block = true)
09-15 08:05:14.669  4383  4383 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:05:14.669  4383  4605 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 08:05:14.670  4383  4383 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:05:14.670  4383  4581 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 08:05:14.670  4383  4606 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 08:05:14.671  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.671  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.671  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.671  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.671  4383  4383 D BluetoothMapService: cleanup()
09-15 08:05:14.671  4383  4383 D BluetoothMapService: MAP Service closeService in
09-15 08:05:14.672  4383  4383 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:14.672  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:14.672  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:14.673  4383  4383 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:14.673   929  5177 D DhcpClient: Clearing IP address
09-15 08:05:14.674  4383  4441 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 08:05:14.674  4383  4441 D BluetoothAdapterProperties: Setting state to 15
09-15 08:05:14.674  4383  4441 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 08:05:14.674   510   927 D CommandListener: Clearing all IP addresses on wlan0
09-15 08:05:14.674  4383  4441 I BluetoothAdapterState: Entering BleOnState
09-15 08:05:14.677   510   927 D CommandListener: Setting iface cfg
09-15 08:05:14.683  3542  5227 V NativeCrypto: Read error: ssl=0x7f949a2e00: I/O error during system call, Connection timed out
09-15 08:05:14.685  3542  5227 V NativeCrypto: SSL shutdown failed: ssl=0x7f949a2e00: I/O error during system call, Broken pipe
09-15 08:05:14.688   929  2947 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 08:05:14.688   929  2947 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-15 08:05:14.691   929   929 D RttService: SCAN_AVAILABLE : 1
09-15 08:05:14.691   929  3007 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 08:05:14.694  3072  3084 D BluetoothPan: onBluetoothStateChange on: false
,09-15 08:05:14.695   544   544 E Parcel  : Reading a NULL string not supported here.
09-15 08:05:14.696  4383  4383 I BtOppRfcommListener: stopping Accept Thread
09-15 08:05:14.696  4383  5107 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 08:05:14.697  4383  5107 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-15 08:05:14.698  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:14.699  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:05:14.699  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.699  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:14.700   929  5178 D DhcpClient: Receive thread stopped
09-15 08:05:14.701  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:14.702  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:05:14.702  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.702  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:14.707   929   942 I ActivityManager: Start proc 5484:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-15 08:05:14.708   929  2947 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-15 08:05:14.710  3432  3562 W QCNEJ   : |CORE| network lost: 100
09-15 08:05:14.710  3432  3562 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 08:05:14.711  3457  3479 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:14.711  3072  3085 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 08:05:14.711   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:05:14.712  3072  3655 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-15 08:05:14.714  3072  3084 D BluetoothMap: onBluetoothStateChange: up=false
,09-15 08:05:14.715   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 08:05:14.715   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 08:05:14.715  3072  3085 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 08:05:14.715   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:14.716  3072  3655 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:14.716  4383  4441 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 08:05:14.716  4383  4441 D BluetoothAdapterProperties: Setting state to 16
09-15 08:05:14.717  4383  4441 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 08:05:14.717  4383  4441 D BluetoothAdapterProperties: onBleDisable
09-15 08:05:14.717  4383  4441 I BluetoothAdapterState: Entering PendingCommandState
09-15 08:05:14.718  4383  4442 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 08:05:14.720  4383  4576 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-15 08:05:14.720  4383  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:14.722  4383  4445 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:05:14.727  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:14.727  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:14.729  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.729   929  2939 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:14.731  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:14.731   929  2939 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:05:14.731   929  2939 E native  : do suspend true
,09-15 08:05:14.732  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.734  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:14.742   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:05:14.762   510   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:05:14.762   510   927 D CommandListener: Clearing all IP addresses on wlan0
09-15 08:05:14.762   510   927 D TetherController: Setting IP forward enable = 0
09-15 08:05:14.763  5484  5484 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-15 08:05:14.764   929  2947 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 08:05:14.764   929  2947 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-15 08:05:14.767   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-15 08:05:14.768  5079  5079 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c83bf9b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-15 08:05:14.769  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.771  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.772  4805  4820 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 08:05:14.773  4805  4820 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 08:05:14.773  4805  4820 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 08:05:14.773  4805  4820 E SarControlService: no key has been found,reset the power
09-15 08:05:14.773  4805  4846 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 08:05:14.773   929  2939 D DhcpClient: doQuit
09-15 08:05:14.773  4805  4846 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 08:05:14.773  4805  4846 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 08:05:14.773   929  2939 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 08:05:14.774   929  5177 D DhcpClient: onQuitting
,09-15 08:05:14.774  4834  4834 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:05:14.774  4834  4834 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 08:05:14.775  3606  3606 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 08:05:14.775  4805  4846 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 08:05:14.775  4805  4846 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 08:05:14.775  4805  4846 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 08:05:14.776  4834  4834 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:05:14.776  4834  4834 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 08:05:14.779  4834  4848 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@960ec19 HexData = [00000000ea03000000000000ffffffff]
09-15 08:05:14.779  4834  4848 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:05:14.779  4834  4848 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 08:05:14.779  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:14.779  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:14.780  4834  4834 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:05:14.780  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.780  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:14.780  4805  4817 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 08:05:14.782  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:14.782  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:14.783  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:14.783  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:14.794  4834  4848 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@960ec19 HexData = [00000000eb03000000000000ffffffff]
09-15 08:05:14.795  4834  4848 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:05:14.795  4834  4848 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-15 08:05:14.795  4834  4834 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:05:14.795  4805  4816 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 08:05:14.799  3606  3606 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 08:05:14.800  5484  5484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:05:14.804   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3daaf59:true
09-15 08:05:14.805  3606  3606 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-15 08:05:14.806  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:05:14.820   929  3539 I ActivityManager: Start proc 5513:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-15 08:05:14.823   510   927 E Netd    : netlink response contains error (No such file or directory)
09-15 08:05:14.823   510   927 D TetherController: Setting IP forward enable = 0
,09-15 08:05:14.828  3606  3606 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 08:05:14.831  5484  5484 D LocalBluetoothProfileManager: Adding local MAP profile
,09-15 08:05:14.833  5484  5484 D BluetoothMap: Create BluetoothMap proxy object
,09-15 08:05:14.839  5484  5484 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 08:05:14.846  5484  5484 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:05:14.850   929  3359 I ActivityManager: Killing 4773:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 08:05:14.851  3606  3606 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 08:05:14.891  5513  5513 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 08:05:14.930  4383  4445 I bt_hci  : shut_down
,09-15 08:05:14.935  4383  4449 I bt_vendor: low_power_mode_cb
,09-15 08:05:14.936  4383  4449 D bt_hwcfg: hw_epilog_process
,09-15 08:05:14.939  4383  4449 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 08:05:14.939  4383  4449 I bt_vendor: epilog_cb
,09-15 08:05:14.939  4383  4449 I bt_hci  : epilog_finished_callback
,09-15 08:05:14.942  4383  4445 I bt_hci_h4: hal_close
09-15 08:05:14.942  4383  4445 I bt_userial_vendor: device fd = 54 close
,09-15 08:05:14.954   929  2939 D wifi    : In wifi stop Hal
,09-15 08:05:14.954  4243  4243 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 08:05:14.954   929  2939 D wifi    : halHandle = 0x7f79b4e4c0, mVM = 0x7f95c8d140, mCls = 0x100bd2
09-15 08:05:14.954   929  3601 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 08:05:14.954   929  3601 D WifiHAL : Got a signal to exit!!!
09-15 08:05:14.954   929  3601 I WifiHAL : Exit wifi_event_loop
09-15 08:05:14.955   929  2939 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 08:05:14.955   929  2939 E WifiHAL : Event processing terminated
09-15 08:05:14.955   929  2939 D wifi    : In wifi cleaned up handler
09-15 08:05:14.955   929  2939 I WifiHAL : Internal cleanup completed
09-15 08:05:14.956  3566  3969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:05:14.957  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:14.958  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:14.978   929  3601 D wifi    : set interface wlan0 flags (DOWN)
,09-15 08:05:14.978   929  2939 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 08:05:15.049  4383  4442 D bt_stack_manager: event_shut_down_stack finished.
,09-15 08:05:15.049  4383  4441 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 08:05:15.051  4383  4441 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-15 08:05:15.051  4383  4383 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 08:05:15.052  4383  4383 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 08:05:15.052  4383  4383 D BtGatt.GattService: stop()
09-15 08:05:15.052  4383  4383 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 08:05:15.053  4383  4383 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:15.053  4383  4383 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:15.053  4383  4383 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:15.054  4383  4383 V BluetoothAdapterState: isBleTurningOff()=true
09-15 08:05:15.054  4383  4441 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 08:05:15.054  4383  4441 D BluetoothAdapterProperties: Setting state to 10
09-15 08:05:15.054  4383  4441 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 08:05:15.054  4383  4441 I BluetoothAdapterState: Entering OffState
,09-15 08:05:15.055   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-15 08:05:15.061  4383  4383 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 08:05:15.061  4383  4383 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 08:05:15.061  4383  4383 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-15 08:05:15.063  4383  4442 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 08:05:15.066  4383  4383 I art     : System.exit called, status: 0
,09-15 08:05:15.067  4383  4383 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 08:05:15.092  5513  5513 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 08:05:15.092  5513  5513 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.092  5513  5513 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.092  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.093  5513  5513 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.093  5513  5513 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.093  5513  5513 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.093  5513  5513 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.093  5513  5513 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:05:15.093  5513  5513 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:05:15.098  5484  5484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:05:15.108  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-15 08:05:15.125  5484  5484 D DockEventReceiver: finishStartingService: stopping service
09-15 08:05:15.126   929  3111 I ActivityManager: Killing 5201:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-15 08:05:15.149   929   939 I ActivityManager: Process com.android.bluetooth (pid 4383) has died
09-15 08:05:15.152  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:05:15.164   929  3716 I ActivityManager: Start proc 5546:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-15 08:05:15.181   929   946 D Tethering: InitialState.processMessage what=4
,09-15 08:05:15.186   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 08:05:15.231  5546  5546 D AdapterServiceConfig: Adding HeadsetService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding A2dpService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding HidService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding HealthService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding PanService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding GattService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding BluetoothMapService
09-15 08:05:15.232  5546  5546 D AdapterServiceConfig: Adding SapService
,09-15 08:05:15.245   929  3539 I ActivityManager: Killing 5214:com.android.chrome/u0a39 (adj 15): empty #17
,09-15 08:05:15.315  3869  3869 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 08:05:15.325  3869  5199 I iu.UploadsManager: num queued entries: 0
,09-15 08:05:15.325  3869  5199 I iu.UploadsManager: num updated entries: 0
09-15 08:05:15.326  3869  5199 I iu.SyncManager: NEXT; no task
,09-15 08:05:15.327  3869  3869 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 08:05:15.329  3869  3869 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 08:05:15.342   929  3716 I ActivityManager: Start proc 5560:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-15 08:05:15.379  5560  5560 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-15 08:05:15.385  5560  5560 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 08:05:15.391  5560  5560 D SprintDMHelper: simOperator: 
,09-15 08:05:15.391  5560  5560 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 08:05:15.403   929  3714 I ActivityManager: Start proc 5572:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-15 08:05:15.404   929  3714 I ActivityManager: Killing 5237:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-15 08:05:15.447   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:15.478  5513  5537 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 08:05:15.501  4243  5586 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 08:05:15.508   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c32d0e7:true
,09-15 08:05:15.509   929  3715 I ActivityManager: Start proc 5588:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-15 08:05:15.511   929  3715 I ActivityManager: Killing 5079:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-15 08:05:15.570  5588  5588 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-15 08:05:15.748   929  3714 I ActivityManager: Killing 4455:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 08:05:15.778   929  3715 I ActivityManager: Start proc 5601:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 08:05:15.810  5601  5601 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 08:05:15.818   929  3714 I ActivityManager: Killing 5294:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-15 08:05:16.448   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:17.449   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:17.650   929  3111 D WifiService: setWifiEnabled: true pid=5432, uid=10077
09-15 08:05:17.651   929  3111 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:05:17.658   510   927 D SoftapController: Softap fwReload - Ok
,09-15 08:05:17.663   510   927 D CommandListener: Setting iface cfg
,09-15 08:05:17.663   510   927 D CommandListener: Trying to bring down wlan0
,09-15 08:05:17.665   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-15 08:05:17.670   929  2939 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 08:05:18.284   929  2939 D wifi    : set interface wlan0 flags (UP)
,09-15 08:05:18.288   929  2939 I WifiHAL : Initializing wifi
09-15 08:05:18.288   929  2939 I WifiHAL : Creating socket
,09-15 08:05:18.291   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 08:05:18.297   929  2939 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 08:05:18.298   929  2939 D wifi    : Did set static halHandle = 0x7f79b4e4c0
09-15 08:05:18.298   929  2939 D wifi    : halHandle = 0x7f79b4e4c0, mVM = 0x7f95c8d140, mCls = 0x1019ce
,09-15 08:05:18.298   929  2939 D wifi    : array field set
09-15 08:05:18.298   929  2939 I WifiNative-HAL: interface[0] = wlan0
09-15 08:05:18.300   929  5619 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547502744768
09-15 08:05:18.300   929  5619 D wifi    : waitForHalEvents called, vm = 0x7f95c8d140, obj = 0x1019ce, env = 0x7f7a4619c0
,09-15 08:05:18.384  5620  5620 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 08:05:18.401   929  2939 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-15 08:05:18.406  5620  5620 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:05:18.409  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:18.414  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:18.427  5620  5620 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:05:18.427  5620  5620 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 08:05:18.442   929  2939 D WifiConfigStore: Loading config and enabling all networks 
09-15 08:05:18.443  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:18.444  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:18.444  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:18.444  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:18.445  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:18.445  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:18.445  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:18.445  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:18.449   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:18.453   929  2939 D WifiConfigStore: loaded 0 passpoint configs
,09-15 08:05:18.453   929  2939 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:05:18.453   929  2939 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 08:05:18.454   929  2939 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-15 08:05:18.455   929  2939 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:05:18.455   929  2939 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 08:05:18.455   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-15 08:05:18.455   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 08:05:18.459  4243  4243 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:05:18.460   929  2939 D WifiNative-HAL: Setting external_sim to 1
09-15 08:05:18.461   929  2939 D wifi    : setting dfs flag to true, 0x7f7b77faa0
09-15 08:05:18.461   929  2939 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 08:05:18.461   929  2939 D wifi    : setting scan oui 0x7f7b77faa0
09-15 08:05:18.461   929  2939 D WifiHAL : Sending mac address OUI
,09-15 08:05:18.476   929  2939 E native  : do suspend true
,09-15 08:05:18.482   929   929 D RttService: SCAN_AVAILABLE : 3
09-15 08:05:18.482   929  2939 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 08:05:18.482   510   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-15 08:05:18.482   929  3007 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 08:05:18.483   510   927 D CommandListener: Setting iface cfg
,09-15 08:05:18.488   929  2933 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
09-15 08:05:18.488   929  2933 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 08:05:18.498   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=232231 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
09-15 08:05:18.499   929  2933 D WifiNative-HAL: p2pGetDeviceAddress
09-15 08:05:18.499   929  2933 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 08:05:19.450   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:20.451   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:05:20.655   929  3715 D WifiService: setWifiEnabled: false pid=5432, uid=10077
,09-15 08:05:20.655   929  3715 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:05:20.662   929   929 D RttService: SCAN_AVAILABLE : 1
,09-15 08:05:20.662   929  3007 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 08:05:20.670   929  2939 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:05:20.670   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-15 08:05:20.672   929  2939 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 08:05:20.672  5620  5620 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 08:05:20.676  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:20.676  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:20.676  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:20.676  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:20.677  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:20.677  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:20.677  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:20.677  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:20.681  5620  5620 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 08:05:20.689  5620  5620 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 08:05:20.697  5620  5620 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 08:05:20.705   929  2939 D wifi    : In wifi stop Hal
,09-15 08:05:20.705   929  2939 D wifi    : halHandle = 0x7f79b4e4c0, mVM = 0x7f95c8d140, mCls = 0x1019ce
09-15 08:05:20.706   929  5619 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 08:05:20.706   929  5619 D WifiHAL : Got a signal to exit!!!
09-15 08:05:20.706   929  5619 I WifiHAL : Exit wifi_event_loop
09-15 08:05:20.706   929  2939 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-15 08:05:20.706   929  2939 E WifiHAL : Event processing terminated
09-15 08:05:20.707   929  2939 D wifi    : In wifi cleaned up handler
09-15 08:05:20.708   929  2939 I WifiHAL : Internal cleanup completed
09-15 08:05:20.709  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:20.710  4243  4243 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 08:05:20.710  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:20.714  3566  3969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:05:20.737   929  5619 D wifi    : set interface wlan0 flags (DOWN)
,09-15 08:05:20.738   929  2939 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 08:05:20.943   929   946 D Tethering: InitialState.processMessage what=4
,09-15 08:05:20.950   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 08:05:23.693   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7233f30:true
,09-15 08:05:23.694  5546  5546 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 08:05:23.700  5546  5546 I bt_bluedroid: init
,09-15 08:05:23.701  5546  5624 I BluetoothAdapterState: Entering OffState
,09-15 08:05:23.705  5546  5625 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 08:05:23.705  5546  5625 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-15 08:05:23.705  5546  5625 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-15 08:05:23.706  5546  5625 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 08:05:23.707  5546  5546 I bt_bluedroid: get_profile_interface socket
,09-15 08:05:23.711  5546  5546 I bt_bluedroid: get_profile_interface sdp
,09-15 08:05:23.711  5546  5628 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 08:05:23.714  5546  5628 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:05:23.721  5546  5556 I bt_bluedroid: config_hci_snoop_log
,09-15 08:05:23.723   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 08:05:23.732  5546  5624 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 08:05:23.733  5546  5624 D BluetoothAdapterProperties: Setting state to 14
09-15 08:05:23.733  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 08:05:23.737  5546  5624 D BluetoothBondStateMachine: make
,09-15 08:05:23.741  5546  5629 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 08:05:23.746  5546  5624 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:05:23.748  5546  5546 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 08:05:23.753  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:23.754  5546  5546 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 08:05:23.755  5546  5546 D BtGatt.GattService: Received start request. Starting profile...
09-15 08:05:23.755  5546  5546 D BtGatt.GattService: start()
09-15 08:05:23.756  5546  5546 I bt_bluedroid: get_profile_interface gatt
,09-15 08:05:23.757  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:23.757  5546  5546 D BtGatt.AdvertiseManager: advertise manager created
,09-15 08:05:23.765  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:23.766  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:23.766  5546  5546 V BluetoothAdapterState: isBleTurningOn()=true
09-15 08:05:23.766  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:23.766  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 08:05:23.768  5546  5624 I bt_bluedroid: bt_bluedroid
09-15 08:05:23.769  5546  5625 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 08:05:23.769  5546  5625 I bt_hci  : start_up
,09-15 08:05:23.778  5546  5625 I bt_vendor: alloc value 0xf3c78871
,09-15 08:05:23.779  5546  5625 I bt_vendor: init
09-15 08:05:23.779  5546  5625 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 08:05:23.779  5546  5625 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 08:05:23.891  5546  5625 D bt_hci  : start_up starting async portion
09-15 08:05:23.891  5546  5632 I bt_hci  : event_finish_startup
,09-15 08:05:23.891  5546  5632 I bt_hci_h4: hal_open
09-15 08:05:23.892  5546  5632 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 08:05:23.888  5633  5633 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 08:05:23.895  5546  5632 I bt_userial_vendor: device fd = 54 open
,09-15 08:05:23.910  5546  5632 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 08:05:23.913  5546  5632 D bt_hwcfg: Chipset BCM4358A3
,09-15 08:05:23.913  5546  5632 D bt_hwcfg: Target name = [BCM4358A3]
09-15 08:05:23.913  5546  5632 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 08:05:24.317  5546  5632 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-15 08:05:24.318  5546  5632 D bt_hwcfg: Settlement delay -- 100 ms
,09-15 08:05:24.318  5546  5632 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 08:05:24.452  5546  5632 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 08:05:24.452  5546  5632 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 08:05:24.453  5546  5632 I bt_hwcfg: vendor lib fwcfg completed
,09-15 08:05:24.453  5546  5632 I bt_vendor: firmware callback
09-15 08:05:24.454  5546  5632 I bt_hci  : firmware_config_callback
,09-15 08:05:24.464   929   929 E WifiNative-wlan0: set PNO failure
,09-15 08:05:24.468  5546  5635 I bt_btu  : btu_task pending for preload complete event
09-15 08:05:24.469  5546  5635 I bt_btu_task: Bluetooth chip preload is complete
09-15 08:05:24.469  5546  5635 I bt_btu  : btu_task received preload complete event
,09-15 08:05:24.474  5546  5635 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 08:05:24.474  5546  5635 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_BTM
,09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 08:05:24.475  5546  5635 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 08:05:24.476  5546  5635 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 08:05:24.476  5546  5635 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-15 08:05:24.476  5546  5635 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 08:05:24.554  5546  5635 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bf6549
,09-15 08:05:24.554  5546  5635 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bf6549 
,09-15 08:05:24.565  5546  5628 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 08:05:24.568  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 08:05:24.568  5546  5628 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 08:05:24.571  5546  5628 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:05:24.573  5546  5628 D BluetoothAdapterProperties: Scan Mode:20
,09-15 08:05:24.573  5546  5628 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 08:05:24.573  5546  5628 D bt_hci  : do_postload posting postload work item
,09-15 08:05:24.573  5546  5632 I bt_hci  : event_postload
09-15 08:05:24.574  5546  5632 I bt_vendor: sco_config_cb
09-15 08:05:24.574  5546  5632 I bt_hci  : sco_config_callback postload finished.
09-15 08:05:24.576  5546  5628 D bt_bte_conf: Device ID record 1 : primary
09-15 08:05:24.576  5546  5628 D bt_bte_conf:   vendorId            = 000f
,09-15 08:05:24.576  5546  5628 D bt_bte_conf:   vendorIdSource      = 0001
09-15 08:05:24.576  5546  5628 D bt_bte_conf:   product             = 1200
09-15 08:05:24.576  5546  5628 D bt_bte_conf:   version             = 1436
09-15 08:05:24.577  5546  5628 D bt_bte_conf:   clientExecutableURL = 
09-15 08:05:24.577  5546  5628 D bt_bte_conf:   serviceDescription  = 
09-15 08:05:24.577  5546  5628 D bt_bte_conf:   documentationURL    = 
09-15 08:05:24.577  5546  5628 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 08:05:24.577  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:24.577  5546  5625 D bt_stack_manager: event_start_up_stack finished
,09-15 08:05:24.578  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 08:05:24.578  5546  5624 D BluetoothAdapterProperties: Setting state to 15
09-15 08:05:24.579  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 08:05:24.581  5546  5624 I BluetoothAdapterState: Entering BleOnState
09-15 08:05:24.584  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:24.587  5546  5624 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 08:05:24.587  5546  5624 D BluetoothAdapterProperties: Setting state to 11
09-15 08:05:24.587  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-15 08:05:24.588  5546  5632 I bt_vendor: low_power_mode_cb
,09-15 08:05:24.596  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:24.598  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:24.600  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:24.604  5546  5546 D HeadsetService: Received start request. Starting profile...
,09-15 08:05:24.607  5546  5546 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 08:05:24.607  5546  5546 D HeadsetStateMachine: make
,09-15 08:05:24.617  5546  5624 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:05:24.617  5546  5546 D HeadsetStateMachine: max_hf_connections = 1
,09-15 08:05:24.617  5546  5546 I bt_bluedroid: get_profile_interface handsfree
09-15 08:05:24.617  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-15 08:05:24.618  5546  5628 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 08:05:24.621  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:24.621  5546  5546 D A2dpService: Received start request. Starting profile...
,09-15 08:05:24.622  5546  5546 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 08:05:24.622  5546  5546 I bt_bluedroid: get_profile_interface avrcp
,09-15 08:05:24.628  5546  5546 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 08:05:24.628  5546  5546 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 08:05:24.629  5546  5546 D A2dpStateMachine: make
,09-15 08:05:24.630  5546  5546 I bt_bluedroid: get_profile_interface a2dp
09-15 08:05:24.630  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 08:05:24.632  5546  5643 D A2dpStateMachine: Enter Disconnected: -2
,09-15 08:05:24.633  5546  5546 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 08:05:24.635  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:24.635  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:05:24.637  5484  5484 D BluetoothInputDevice: Proxy object connected
09-15 08:05:24.637  5546  5546 D HidService: Received start request. Starting profile...
,09-15 08:05:24.638  5546  5546 I bt_bluedroid: get_profile_interface hidhost
09-15 08:05:24.638  5546  5546 D HidService: setHidService(): set to: null
09-15 08:05:24.638  5546  5628 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bd756d
09-15 08:05:24.638  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 08:05:24.638  5484  5484 D HidProfile: Bluetooth service connected
09-15 08:05:24.638  5546  5546 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 08:05:24.639  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:24.640  5546  5546 D HealthService: Received start request. Starting profile...
,09-15 08:05:24.641  5546  5546 I bt_bluedroid: get_profile_interface health
,09-15 08:05:24.642  5546  5546 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 08:05:24.643  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:24.644  5546  5546 D PanService: Received start request. Starting profile...
09-15 08:05:24.644  5484  5484 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:05:24.644  5546  5546 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 08:05:24.645  5546  5546 I bt_bluedroid: get_profile_interface pan
09-15 08:05:24.645  5484  5484 D PanProfile: Bluetooth service connected
09-15 08:05:24.645  5546  5628 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 08:05:24.647  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:24.649  5484  5484 D BluetoothMap: Proxy object connected
,09-15 08:05:24.649  5546  5546 D BluetoothMapService: Received start request. Starting profile...
09-15 08:05:24.649  5546  5546 D BluetoothMapService: start()
09-15 08:05:24.650  5484  5484 D MapProfile: Bluetooth service connected
09-15 08:05:24.650  5484  5484 D BluetoothMap: getConnectedDevices()
09-15 08:05:24.650  5484  5484 D BluetoothMap: Bluetooth is Not enabled
,09-15 08:05:24.652  5546  5546 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 08:05:24.653  5546  5546 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 08:05:24.653  5546  5546 D BluetoothMapAppObserver: createReceiver()
,09-15 08:05:24.655  5546  5546 D BluetoothMapAppObserver: initObservers()
,09-15 08:05:24.655  5546  5546 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 08:05:24.663  5546  5546 V SapService: SapBinder()
,09-15 08:05:24.663  5546  5546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:24.663  5546  5546 D SapService: Received start request. Starting profile...
09-15 08:05:24.664  5546  5546 V SapService: start()
,09-15 08:05:24.665  5546  5546 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:05:24.665  5546  5546 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:24.665  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:24.665  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 08:05:24.666  5546  5641 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:05:24.666  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:24.667  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:24.668  5546  5546 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:24.668  5546  5546 V BluetoothAdapterState: isTurningOn()=true
,09-15 08:05:24.668  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:05:24.668  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 08:05:24.668  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 08:05:24.668  5546  5624 D BluetoothAdapterProperties: ScanMode =  20
09-15 08:05:24.668  5546  5624 D BluetoothAdapterProperties: State =  11
09-15 08:05:24.668  5546  5624 D BluetoothAdapterProperties: Setting state to 12
09-15 08:05:24.668  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 08:05:24.669  5546  5624 I BluetoothAdapterState: Entering OnState
09-15 08:05:24.669  3072  3655 D BluetoothPan: onBluetoothStateChange on: true
09-15 08:05:24.671  3072  3072 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:05:24.671  3457  3671 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:24.671  3072  3072 D PanProfile: Bluetooth service connected
09-15 08:05:24.671  5546  5628 D BluetoothAdapterProperties: Scan Mode:21
09-15 08:05:24.671  5546  5628 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 08:05:24.672  3072  3084 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:24.675  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:24.675  5484  5501 D BluetoothPan: onBluetoothStateChange on: true
09-15 08:05:24.676   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 08:05:24.677  3072  3655 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:05:24.677   929   929 D BluetoothA2dp: Proxy object connected
,09-15 08:05:24.678  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:24.678  3072  3084 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:05:24.678  3072  3072 D BluetoothInputDevice: Proxy object connected
09-15 08:05:24.678  3072  3072 D HidProfile: Bluetooth service connected
09-15 08:05:24.680   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:24.680   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:24.680  3072  3085 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 08:05:24.681  5546  5546 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 08:05:24.681  5546  5546 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 08:05:24.683  5546  5546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:05:24.683  3072  3072 D BluetoothMap: Proxy object connected
09-15 08:05:24.683  3072  3072 D MapProfile: Bluetooth service connected
09-15 08:05:24.683  3072  3072 D BluetoothMap: getConnectedDevices()
09-15 08:05:24.684   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:24.684  3072  3655 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 08:05:24.685  5484  5500 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:05:24.685  5484  5501 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:24.685  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:24.686  5484  5500 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 08:05:24.686  3072  3072 D BluetoothA2dp: Proxy object connected
09-15 08:05:24.687  5546  5546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:05:24.687  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:24.689   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-15 08:05:24.690  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:24.690  5546  5546 D ObexServerSockets: Succeed to create listening sockets 
09-15 08:05:24.690  5546  5546 D ObexServerSockets0: startAccept()
09-15 08:05:24.690  5546  5546 D ObexServerSockets0: prepareForNewConnect()
09-15 08:05:24.690  5484  5484 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 08:05:24.691  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:24.693  5546  5546 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-15 08:05:24.693  5546  5546 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 08:05:24.696  5484  5484 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-15 08:05:24.696  5546  5650 D ObexServerSockets0: Accepting socket connection...
09-15 08:05:24.696  5546  5651 D ObexServerSockets0: Accepting socket connection...
09-15 08:05:24.696  5546  5546 D BluetoothMapService: onReceive
09-15 08:05:24.696  5546  5546 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 08:05:24.696  5546  5546 D BluetoothMapService: STATE_ON
,09-15 08:05:24.698  5546  5652 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:05:24.700  5546  5652 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-15 08:05:24.700  5546  5652 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 08:05:24.703  5484  5484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 08:05:24.706  5484  5484 D BluetoothA2dp: Proxy object connected
,09-15 08:05:24.710  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:05:24.711  5484  5484 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:05:24.716  5484  5484 D BluetoothPbap: Proxy object connected
,09-15 08:05:24.716  3072  3072 D BluetoothPbap: Proxy object connected
09-15 08:05:24.716  3072  3072 D PbapServerProfile: Bluetooth service connected
09-15 08:05:24.717  5484  5484 D PbapServerProfile: Bluetooth service connected
,09-15 08:05:24.721  5546  5546 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 08:05:24.721  5546  5546 D ObexServerSockets0: prepareForNewConnect()
,09-15 08:05:24.723  5546  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:05:24.735  5546  5660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:05:24.736  5546  5660 I BtOppRfcommListener: Accept thread started.
,09-15 08:05:24.773   929   929 D BluetoothHeadset: Proxy object connected
,09-15 08:05:24.773  3457  3477 D BluetoothHeadset: Proxy object connected
09-15 08:05:24.774   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:05:24.774   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:05:24.774  3072  3084 D BluetoothHeadset: Proxy object connected
09-15 08:05:24.774  3072  3072 D HeadsetProfile: Bluetooth service connected
,09-15 08:05:24.779   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:05:24.781   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:05:24.785   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:05:24.785  3072  3655 D BluetoothHeadset: Proxy object connected
09-15 08:05:24.785  3072  3072 D HeadsetProfile: Bluetooth service connected
,09-15 08:05:24.799  5484  5501 D BluetoothHeadset: Proxy object connected
,09-15 08:05:24.801  5484  5484 D HeadsetProfile: Bluetooth service connected
,09-15 08:05:25.452   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:26.453   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:26.673  5546  5624 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 08:05:26.674  5546  5624 D BluetoothAdapterProperties: Setting state to 13
,09-15 08:05:26.674  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-15 08:05:26.675  5546  5624 D BluetoothAdapterProperties: onBluetoothDisable()
,09-15 08:05:26.676  5546  5624 I BluetoothAdapterState: Entering PendingCommandState
09-15 08:05:26.681  5546  5546 D BluetoothMapService: onReceive
09-15 08:05:26.682  5546  5546 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 08:05:26.682  5546  5546 D BluetoothMapService: STATE_TURNING_OFF
09-15 08:05:26.682  5546  5546 D BluetoothMapService: MAP Service closeService in
09-15 08:05:26.682  5546  5546 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 08:05:26.683  5546  5546 D ObexServerSockets0: shutdown(block = true)
09-15 08:05:26.684  5546  5546 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:05:26.685  5546  5650 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 08:05:26.685  5546  5546 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:05:26.685  5546  5637 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 08:05:26.686  5546  5651 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 08:05:26.687  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:26.687  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:26.689  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:26.689  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:26.692  5546  5546 I BtOppRfcommListener: stopping Accept Thread
09-15 08:05:26.693  5546  5660 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 08:05:26.693  5546  5660 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-15 08:05:26.695  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:26.696  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:26.697  5432  5432 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:05:26.697  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:26.697  5546  5628 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:05:26.698  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 08:05:26.699  5484  5484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:05:26.700  5546  5546 D HeadsetService: Received stop request...Stopping profile...
09-15 08:05:26.702  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:26.705  5546  5546 D A2dpService: Received stop request...Stopping profile...
09-15 08:05:26.705  5484  5501 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:26.705  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:26.705  5546  5643 D A2dpStateMachine: Exit Disconnected: -1
,09-15 08:05:26.706   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:26.706  3457  3479 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:26.707   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:05:26.707   929   929 D BluetoothHeadset: Proxy object disconnected
,09-15 08:05:26.707  3072  3084 D BluetoothHeadset: Proxy object disconnected
,09-15 08:05:26.707   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 08:05:26.708  5484  5484 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:05:26.708  5546  5546 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:26.708  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:26.708  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:05:26.708  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.709  5484  5484 D HeadsetProfile: Bluetooth service disconnected
09-15 08:05:26.710  5484  5484 D BluetoothA2dp: Proxy object disconnected
09-15 08:05:26.712  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:05:26.714  5546  5546 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 08:05:26.714  5546  5546 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 08:05:26.714  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 08:05:26.714  5546  5635 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:26.714  5546  5635 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:26.714  5546  5635 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-15 08:05:26.715  5546  5628 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 08:05:26.715  5546  5546 D HidService: Received stop request...Stopping profile...
,09-15 08:05:26.715  5546  5546 D HidService: Stopping Bluetooth HidService
09-15 08:05:26.716  3072  3072 D BluetoothA2dp: Proxy object disconnected
09-15 08:05:26.717  3072  3072 D HeadsetProfile: Bluetooth service disconnected
09-15 08:05:26.717  5546  5546 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:26.717  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:26.717  5484  5484 D BluetoothInputDevice: Proxy object disconnected
,09-15 08:05:26.717  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:26.717  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.717  5484  5484 D HidProfile: Bluetooth service disconnected
09-15 08:05:26.717  3072  3072 D BluetoothInputDevice: Proxy object disconnected
09-15 08:05:26.717  3072  3072 D HidProfile: Bluetooth service disconnected
09-15 08:05:26.719  5546  5635 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:26.719  5546  5635 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:26.720  5546  5635 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-15 08:05:26.720  5546  5546 D HealthService: Received stop request...Stopping profile...
09-15 08:05:26.720  5546  5635 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:05:26.720  5546  5635 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:05:26.720  5546  5635 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:05:26.720  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 08:05:26.722  5546  5546 D PanService: Received stop request...Stopping profile...
09-15 08:05:26.723  5484  5484 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 08:05:26.723  5484  5484 D PanProfile: Bluetooth service disconnected
09-15 08:05:26.724  5484  5484 D BluetoothPbap: Proxy object disconnected
09-15 08:05:26.725  5484  5484 D PbapServerProfile: Bluetooth service disconnected
,09-15 08:05:26.725  3072  3072 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 08:05:26.725  3072  3072 D PanProfile: Bluetooth service disconnected
09-15 08:05:26.725  3072  3072 D BluetoothPbap: Proxy object disconnected
09-15 08:05:26.725  3072  3072 D PbapServerProfile: Bluetooth service disconnected
,09-15 08:05:26.727  5546  5546 D BluetoothMapService: Received stop request...Stopping profile...
,09-15 08:05:26.727  5546  5546 D BluetoothMapService: stop()
09-15 08:05:26.728  5546  5546 D BluetoothMapAppObserver: deinitObservers()
09-15 08:05:26.728  5546  5546 D BluetoothMapAppObserver: removeReceiver()
09-15 08:05:26.729  3072  3072 D BluetoothMap: Proxy object disconnected
09-15 08:05:26.729  5484  5484 D BluetoothMap: Proxy object disconnected
09-15 08:05:26.729  3072  3072 D MapProfile: Bluetooth service disconnected
09-15 08:05:26.729  5484  5484 D MapProfile: Bluetooth service disconnected
09-15 08:05:26.729  5546  5546 D SapService: Received stop request...Stopping profile...
09-15 08:05:26.729  5546  5546 V SapService: stop()
09-15 08:05:26.730  5546  5546 V BluetoothAdapterState: isTurningOff()=true
,09-15 08:05:26.730  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:26.730  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:26.730  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.731  5546  5546 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 08:05:26.731  5546  5628 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 08:05:26.731  5546  5546 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 08:05:26.732  5546  5546 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:26.732  5546  5546 V BluetoothAdapterState: isTurningOn()=false
,09-15 08:05:26.732  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:26.732  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.733  5546  5546 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 08:05:26.733  5546  5628 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 08:05:26.733  5546  5546 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 08:05:26.737  5546  5546 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:26.737  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:26.737  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:26.737  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.738  5546  5546 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 08:05:26.738  5546  5546 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-15 08:05:26.739  5546  5546 D BluetoothMapService: MAP Service closeService in
09-15 08:05:26.739  5546  5546 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:26.739  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:26.739  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:26.739  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.739  5546  5546 D BluetoothMapService: cleanup()
09-15 08:05:26.739  5546  5546 D BluetoothMapService: MAP Service closeService in
09-15 08:05:26.740  5546  5546 V BluetoothAdapterState: isTurningOff()=true
09-15 08:05:26.740  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:26.740  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:26.740  5546  5546 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:26.740  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 08:05:26.740  5546  5624 D BluetoothAdapterProperties: Setting state to 15
09-15 08:05:26.740  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 08:05:26.741  3072  3085 D BluetoothPan: onBluetoothStateChange on: false
09-15 08:05:26.741  5546  5624 I BluetoothAdapterState: Entering BleOnState
,09-15 08:05:26.743  3457  3671 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:26.744  3072  3655 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 08:05:26.745  5484  5500 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 08:05:26.745  5484  5664 D BluetoothPan: onBluetoothStateChange on: false
09-15 08:05:26.746   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:05:26.746  3072  3084 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 08:05:26.747  5484  5501 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:05:26.748  3072  3085 D BluetoothMap: onBluetoothStateChange: up=false
,09-15 08:05:26.748   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:26.748   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:26.748  3072  3655 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:05:26.748   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:26.749  3072  3084 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:05:26.749  5484  5500 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 08:05:26.749  5484  5664 D BluetoothMap: onBluetoothStateChange: up=false
09-15 08:05:26.750  5484  5501 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 08:05:26.750  5546  5624 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 08:05:26.750  5546  5624 D BluetoothAdapterProperties: Setting state to 16
09-15 08:05:26.750  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 08:05:26.751  5546  5624 D BluetoothAdapterProperties: onBleDisable
09-15 08:05:26.751  5546  5624 I BluetoothAdapterState: Entering PendingCommandState
09-15 08:05:26.752  5546  5625 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 08:05:26.753  5546  5635 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 08:05:26.753  5546  5635 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:05:26.753  5546  5628 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:05:26.755  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:26.756  5484  5484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 08:05:26.756  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:26.758  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:26.759  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:26.763  5484  5484 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:05:26.763  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:05:26.967  5546  5628 I bt_hci  : shut_down
,09-15 08:05:26.973  5546  5632 D bt_hwcfg: hw_epilog_process
,09-15 08:05:26.974  5546  5632 I bt_vendor: low_power_mode_cb
,09-15 08:05:26.977  5546  5632 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 08:05:26.977  5546  5632 I bt_vendor: epilog_cb
09-15 08:05:26.978  5546  5632 I bt_hci  : epilog_finished_callback
,09-15 08:05:26.982  5546  5628 I bt_hci_h4: hal_close
,09-15 08:05:26.983  5546  5628 I bt_userial_vendor: device fd = 54 close
,09-15 08:05:27.102  5546  5625 D bt_stack_manager: event_shut_down_stack finished.
,09-15 08:05:27.103  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 08:05:27.107  5546  5624 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-15 08:05:27.108  5546  5546 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 08:05:27.109  5546  5546 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 08:05:27.109  5546  5546 D BtGatt.GattService: stop()
,09-15 08:05:27.109  5546  5546 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 08:05:27.112  5546  5546 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:05:27.112  5546  5546 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:27.113  5546  5546 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:27.113  5546  5546 V BluetoothAdapterState: isBleTurningOff()=true
09-15 08:05:27.113  5546  5624 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 08:05:27.113  5546  5624 D BluetoothAdapterProperties: Setting state to 10
,09-15 08:05:27.114  5546  5624 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 08:05:27.115  5546  5624 I BluetoothAdapterState: Entering OffState
09-15 08:05:27.116   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 08:05:27.127  5546  5546 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 08:05:27.129  5546  5546 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 08:05:27.129  5546  5546 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 08:05:27.130  5546  5625 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 08:05:27.136  5546  5546 I art     : System.exit called, status: 0
,09-15 08:05:27.136  5546  5546 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 08:05:27.166   929  3716 I ActivityManager: Process com.android.bluetooth (pid 5546) has died
,09-15 08:05:27.454   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:28.455   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:29.456   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:05:29.672  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:05:29.672  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:30.456   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:05:32.679  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 08:05:32.679  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c6b7c6d added. We now have 6 listener(s)
,09-15 08:05:32.679  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:05:32.682  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:32.683  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fb60a2 added. We now have 7 listener(s)
09-15 08:05:32.683  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:05:32.685  5432  5478 I System.out: IsBluetoothEnabled
,09-15 08:05:32.692  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:32.723   929   946 I ActivityManager: Start proc 5669:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 08:05:32.801  5669  5669 D AdapterServiceConfig: Adding HeadsetService
,09-15 08:05:32.801  5669  5669 D AdapterServiceConfig: Adding A2dpService
09-15 08:05:32.801  5669  5669 D AdapterServiceConfig: Adding HidService
09-15 08:05:32.802  5669  5669 D AdapterServiceConfig: Adding HealthService
09-15 08:05:32.802  5669  5669 D AdapterServiceConfig: Adding PanService
09-15 08:05:32.802  5669  5669 D AdapterServiceConfig: Adding GattService
09-15 08:05:32.802  5669  5669 D AdapterServiceConfig: Adding BluetoothMapService
,09-15 08:05:32.802  5669  5669 D AdapterServiceConfig: Adding SapService
,09-15 08:05:32.813   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecb569:true
,09-15 08:05:32.814  5669  5669 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 08:05:32.817  5669  5669 I bt_bluedroid: init
,09-15 08:05:32.817  5669  5681 I BluetoothAdapterState: Entering OffState
09-15 08:05:32.819  5669  5682 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 08:05:32.819  5669  5682 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 08:05:32.819  5669  5682 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 08:05:32.819  5669  5682 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 08:05:32.820  5669  5669 I bt_bluedroid: get_profile_interface socket
09-15 08:05:32.821  5669  5685 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 08:05:32.822  5669  5669 I bt_bluedroid: get_profile_interface sdp
09-15 08:05:32.823  5669  5685 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:05:32.826  5669  5680 I bt_bluedroid: config_hci_snoop_log
,09-15 08:05:32.827   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 08:05:32.831  5669  5681 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 08:05:32.831  5669  5681 D BluetoothAdapterProperties: Setting state to 14
09-15 08:05:32.831  5669  5681 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 08:05:32.833  5669  5681 D BluetoothBondStateMachine: make
,09-15 08:05:32.834  5669  5686 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 08:05:32.837  5669  5681 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:05:32.838  5669  5669 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 08:05:32.840  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:32.840  5669  5669 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 08:05:32.841  5669  5669 D BtGatt.GattService: Received start request. Starting profile...
09-15 08:05:32.841  5669  5669 D BtGatt.GattService: start()
09-15 08:05:32.841  5669  5669 I bt_bluedroid: get_profile_interface gatt
09-15 08:05:32.842  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:32.842  5669  5669 D BtGatt.AdvertiseManager: advertise manager created
,09-15 08:05:32.847  5669  5669 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:05:32.847  5669  5669 V BluetoothAdapterState: isTurningOn()=false
09-15 08:05:32.847  5669  5669 V BluetoothAdapterState: isBleTurningOn()=true
09-15 08:05:32.847  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:32.848  5669  5681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 08:05:32.849  5669  5681 I bt_bluedroid: bt_bluedroid
09-15 08:05:32.849  5669  5682 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 08:05:32.849  5669  5682 I bt_hci  : start_up
,09-15 08:05:32.855  5669  5682 I bt_vendor: alloc value 0xf3ceb871
,09-15 08:05:32.855  5669  5682 I bt_vendor: init
09-15 08:05:32.855  5669  5682 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 08:05:32.855  5669  5682 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 08:05:32.967  5669  5682 D bt_hci  : start_up starting async portion
09-15 08:05:32.968  5669  5689 I bt_hci  : event_finish_startup
,09-15 08:05:32.968  5669  5689 I bt_hci_h4: hal_open
09-15 08:05:32.968  5669  5689 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 08:05:32.964  5690  5690 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 08:05:32.972  5669  5689 I bt_userial_vendor: device fd = 54 open
,09-15 08:05:32.986  5669  5689 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 08:05:32.988  5669  5689 D bt_hwcfg: Chipset BCM4358A3
09-15 08:05:32.989  5669  5689 D bt_hwcfg: Target name = [BCM4358A3]
,09-15 08:05:32.989  5669  5689 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 08:05:33.396  5669  5689 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 08:05:33.396  5669  5689 D bt_hwcfg: Settlement delay -- 100 ms
,09-15 08:05:33.397  5669  5689 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 08:05:33.532  5669  5689 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 08:05:33.532  5669  5689 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 08:05:33.534  5669  5689 I bt_hwcfg: vendor lib fwcfg completed
09-15 08:05:33.534  5669  5689 I bt_vendor: firmware callback
09-15 08:05:33.534  5669  5689 I bt_hci  : firmware_config_callback
,09-15 08:05:33.542  5669  5692 I bt_btu  : btu_task pending for preload complete event
,09-15 08:05:33.542  5669  5692 I bt_btu_task: Bluetooth chip preload is complete
,09-15 08:05:33.542  5669  5692 I bt_btu  : btu_task received preload complete event
,09-15 08:05:33.551  5669  5692 I         : BTE_InitTraceLevels -- TRC_HCI
09-15 08:05:33.551  5669  5692 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_A2D
,09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 08:05:33.552  5669  5692 I         : BTE_InitTraceLevels -- TRC_PAN
,09-15 08:05:33.553  5669  5692 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 08:05:33.553  5669  5692 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 08:05:33.553  5669  5692 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 08:05:33.553  5669  5692 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 08:05:33.553  5669  5692 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 08:05:33.637  5669  5692 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c69549
09-15 08:05:33.637  5669  5692 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c69549 
,09-15 08:05:33.657  5669  5685 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 08:05:33.658  5669  5685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 08:05:33.659  5669  5685 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 08:05:33.661  5669  5685 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:05:33.663  5669  5685 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:05:33.664  5669  5685 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 08:05:33.664  5669  5685 D bt_hci  : do_postload posting postload work item
,09-15 08:05:33.664  5669  5689 I bt_hci  : event_postload
09-15 08:05:33.664  5669  5689 I bt_vendor: sco_config_cb
09-15 08:05:33.664  5669  5689 I bt_hci  : sco_config_callback postload finished.
09-15 08:05:33.668  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:33.671  5669  5685 D bt_bte_conf: Device ID record 1 : primary
09-15 08:05:33.672  5669  5689 I bt_vendor: low_power_mode_cb
09-15 08:05:33.672  5669  5685 D bt_bte_conf:   vendorId            = 000f
09-15 08:05:33.672  5669  5685 D bt_bte_conf:   vendorIdSource      = 0001
,09-15 08:05:33.672  5669  5685 D bt_bte_conf:   product             = 1200
09-15 08:05:33.672  5669  5685 D bt_bte_conf:   version             = 1436
09-15 08:05:33.672  5669  5685 D bt_bte_conf:   clientExecutableURL = 
09-15 08:05:33.672  5669  5685 D bt_bte_conf:   serviceDescription  = 
09-15 08:05:33.672  5669  5685 D bt_bte_conf:   documentationURL    = 
09-15 08:05:33.672  5669  5685 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 08:05:33.673  5669  5682 D bt_stack_manager: event_start_up_stack finished
,09-15 08:05:33.673  5669  5681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 08:05:33.674  5669  5681 D BluetoothAdapterProperties: Setting state to 15
09-15 08:05:33.674  5669  5681 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 08:05:33.675  5669  5681 I BluetoothAdapterState: Entering BleOnState
,09-15 08:05:33.679  5669  5681 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 08:05:33.679  5669  5681 D BluetoothAdapterProperties: Setting state to 11
09-15 08:05:33.679  5669  5681 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 08:05:33.684  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:33.685  5669  5669 D HeadsetService: Received start request. Starting profile...
09-15 08:05:33.689  5669  5669 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 08:05:33.689  5669  5669 D HeadsetStateMachine: make
09-15 08:05:33.689  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:33.704  5669  5681 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:05:33.704  5669  5669 D HeadsetStateMachine: max_hf_connections = 1
09-15 08:05:33.704  5669  5669 I bt_bluedroid: get_profile_interface handsfree
09-15 08:05:33.705  5669  5685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 08:05:33.705  5669  5685 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-15 08:05:33.709  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:33.710  5669  5669 D A2dpService: Received start request. Starting profile...
09-15 08:05:33.710  5669  5669 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-15 08:05:33.711  5669  5669 I bt_bluedroid: get_profile_interface avrcp
,09-15 08:05:33.718  5669  5669 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 08:05:33.718  5669  5669 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 08:05:33.718  5669  5669 D A2dpStateMachine: make
,09-15 08:05:33.719  5669  5669 I bt_bluedroid: get_profile_interface a2dp
09-15 08:05:33.720  5669  5685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 08:05:33.722  5669  5700 D A2dpStateMachine: Enter Disconnected: -2
,09-15 08:05:33.722  5669  5669 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 08:05:33.723  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:33.724  5669  5669 D HidService: Received start request. Starting profile...
,09-15 08:05:33.724  5669  5669 I bt_bluedroid: get_profile_interface hidhost
09-15 08:05:33.725  5669  5669 D HidService: setHidService(): set to: null
09-15 08:05:33.725  5669  5685 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c4a56d
09-15 08:05:33.725  5669  5685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-15 08:05:33.726  5669  5669 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 08:05:33.727  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:33.728  5669  5669 D HealthService: Received start request. Starting profile...
09-15 08:05:33.728  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:05:33.730  5669  5669 I bt_bluedroid: get_profile_interface health
09-15 08:05:33.731  5669  5669 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 08:05:33.732  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:33.732  5669  5669 D PanService: Received start request. Starting profile...
09-15 08:05:33.732  5669  5669 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-15 08:05:33.733  5669  5669 I bt_bluedroid: get_profile_interface pan
09-15 08:05:33.733  5669  5685 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 08:05:33.737  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:33.738  5669  5669 D BluetoothMapService: Received start request. Starting profile...
,09-15 08:05:33.738  5669  5669 D BluetoothMapService: start()
,09-15 08:05:33.741  5669  5669 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 08:05:33.742  5669  5669 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 08:05:33.742  5669  5669 D BluetoothMapAppObserver: createReceiver()
09-15 08:05:33.744  5669  5669 D BluetoothMapAppObserver: initObservers()
09-15 08:05:33.744  5669  5669 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 08:05:33.750  5669  5669 V SapService: SapBinder()
,09-15 08:05:33.750  5669  5669 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
,09-15 08:05:33.752  5669  5669 D SapService: Received start request. Starting profile...
,09-15 08:05:33.752  5669  5669 V SapService: start()
,09-15 08:05:33.754  5669  5669 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:05:33.754  5669  5669 V BluetoothAdapterState: isTurningOn()=true
,09-15 08:05:33.754  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:33.754  5669  5698 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 08:05:33.754  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:33.755  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:05:33.756  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.757  5669  5669 V BluetoothAdapterState: isTurningOff()=false
09-15 08:05:33.757  5669  5669 V BluetoothAdapterState: isTurningOn()=true
09-15 08:05:33.757  5669  5669 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:05:33.757  5669  5669 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:05:33.757  5669  5681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 08:05:33.757  5669  5681 D BluetoothAdapterProperties: ScanMode =  20
09-15 08:05:33.757  5669  5681 D BluetoothAdapterProperties: State =  11
,09-15 08:05:33.758  5669  5681 D BluetoothAdapterProperties: Setting state to 12
09-15 08:05:33.758  5669  5681 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 08:05:33.759  5669  5681 I BluetoothAdapterState: Entering OnState
09-15 08:05:33.759  3072  3084 D BluetoothPan: onBluetoothStateChange on: true
,09-15 08:05:33.760  5669  5685 D BluetoothAdapterProperties: Scan Mode:21
09-15 08:05:33.761  5669  5685 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 08:05:33.762  3457  3479 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:33.763  3072  3085 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 08:05:33.763  3072  3072 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:05:33.763  3072  3072 D PanProfile: Bluetooth service connected
,09-15 08:05:33.765  5484  5664 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:33.767  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:33.768  5484  5501 D BluetoothPan: onBluetoothStateChange on: true
,09-15 08:05:33.769  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:33.769  5669  5669 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 08:05:33.770   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 08:05:33.770  5669  5669 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-15 08:05:33.771  3072  3655 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 08:05:33.772  5669  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:05:33.773  5484  5664 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 08:05:33.774  5669  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:05:33.775  3072  3084 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:05:33.776  5669  5669 D ObexServerSockets: Succeed to create listening sockets 
09-15 08:05:33.776  5669  5669 D ObexServerSockets0: startAccept()
09-15 08:05:33.776  5669  5669 D ObexServerSockets0: prepareForNewConnect()
09-15 08:05:33.777   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:33.777   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:33.778  3072  3085 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 08:05:33.778  5669  5669 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 08:05:33.778  5669  5669 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 08:05:33.779  5669  5705 D ObexServerSockets0: Accepting socket connection...
09-15 08:05:33.779   929   929 D BluetoothA2dp: Proxy object connected
09-15 08:05:33.780   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:33.780  3072  3655 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:05:33.780  3072  3072 D BluetoothA2dp: Proxy object connected
09-15 08:05:33.780  5669  5706 D ObexServerSockets0: Accepting socket connection...
09-15 08:05:33.781  5484  5501 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:05:33.782  3072  3072 D BluetoothInputDevice: Proxy object connected
09-15 08:05:33.782  3072  3072 D HidProfile: Bluetooth service connected
09-15 08:05:33.783  5484  5500 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:05:33.779  5484  5484 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:05:33.784  5484  5484 D PanProfile: Bluetooth service connected
09-15 08:05:33.784  5484  5484 D BluetoothA2dp: Proxy object connected
09-15 08:05:33.786  3072  3072 D BluetoothMap: Proxy object connected
09-15 08:05:33.786  3072  3072 D MapProfile: Bluetooth service connected
09-15 08:05:33.786  3072  3072 D BluetoothMap: getConnectedDevices()
,09-15 08:05:33.786  5484  5501 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 08:05:33.789  5484  5484 D BluetoothInputDevice: Proxy object connected
,09-15 08:05:33.792  5484  5484 D HidProfile: Bluetooth service connected
,09-15 08:05:33.792   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 08:05:33.792  5669  5669 D BluetoothMapService: onReceive
09-15 08:05:33.792  5669  5669 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 08:05:33.793  5669  5669 D BluetoothMapService: STATE_ON
,09-15 08:05:33.793  5484  5484 D BluetoothMap: Proxy object connected
,09-15 08:05:33.793  5484  5484 D MapProfile: Bluetooth service connected
09-15 08:05:33.794  5484  5484 D BluetoothMap: getConnectedDevices()
09-15 08:05:33.795  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:33.797  5669  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:05:33.798  5669  5707 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 08:05:33.798  5669  5707 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 08:05:33.799  5484  5484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 08:05:33.806  3542  3542 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:05:33.809  5484  5484 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:05:33.813  5484  5484 D BluetoothPbap: Proxy object connected
,09-15 08:05:33.813  5484  5484 D PbapServerProfile: Bluetooth service connected
,09-15 08:05:33.819  5669  5669 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 08:05:33.819  5669  5669 D ObexServerSockets0: prepareForNewConnect()
,09-15 08:05:33.821  5669  5713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:05:33.825  3072  3072 D BluetoothPbap: Proxy object connected
09-15 08:05:33.825  3072  3072 D PbapServerProfile: Bluetooth service connected
,09-15 08:05:33.831  5669  5717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:05:33.833  5669  5717 I BtOppRfcommListener: Accept thread started.
,09-15 08:05:33.864  5484  5501 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.864   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:05:33.864  3457  3671 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.865   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:05:33.865   929   929 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.865  3072  3655 D BluetoothHeadset: Proxy object connected
09-15 08:05:33.865  3072  3072 D HeadsetProfile: Bluetooth service connected
09-15 08:05:33.866  5484  5664 D BluetoothHeadset: Proxy object connected
09-15 08:05:33.868  5484  5484 D HeadsetProfile: Bluetooth service connected
09-15 08:05:33.869  5484  5484 D HeadsetProfile: Bluetooth service connected
,09-15 08:05:33.877   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.877   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.880   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.880  3072  3084 D BluetoothHeadset: Proxy object connected
,09-15 08:05:33.881  3072  3072 D HeadsetProfile: Bluetooth service connected
,09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:34.710  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:34.718  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:34.720  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:34.720  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc5b133 added. We now have 8 listener(s)
,09-15 08:05:34.720  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:05:34.725   929  3111 D WifiService: setWifiEnabled: false pid=5432, uid=10077
,09-15 08:05:34.725   929  3111 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:05:34.732  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:34.733   929  3714 D WifiService: setWifiEnabled: true pid=5432, uid=10077
09-15 08:05:34.733   929  3714 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:05:34.741   510   927 D SoftapController: Softap fwReload - Ok
,09-15 08:05:34.743   510   927 D CommandListener: Setting iface cfg
,09-15 08:05:34.743   510   927 D CommandListener: Trying to bring down wlan0
,09-15 08:05:34.745   510   927 D CommandListener: Clearing all IP addresses on wlan0
,09-15 08:05:34.748   929  2939 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 08:05:35.358   929  2939 D wifi    : set interface wlan0 flags (UP)
,09-15 08:05:35.363   929  2939 I WifiHAL : Initializing wifi
,09-15 08:05:35.363   929  2939 I WifiHAL : Creating socket
,09-15 08:05:35.368   929  2939 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-15 08:05:35.368   929  2939 D wifi    : Did set static halHandle = 0x7f79b4e4c0
09-15 08:05:35.369   929  2939 D wifi    : halHandle = 0x7f79b4e4c0, mVM = 0x7f95c8d140, mCls = 0x20198a
,09-15 08:05:35.369   929  2939 D wifi    : array field set
09-15 08:05:35.369   929  2939 I WifiNative-HAL: interface[0] = wlan0
09-15 08:05:35.372   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-15 08:05:35.372   929  5722 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547502744768
09-15 08:05:35.373   929  5722 D wifi    : waitForHalEvents called, vm = 0x7f95c8d140, obj = 0x20198a, env = 0x7f7a461e40
,09-15 08:05:35.433  5723  5723 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 08:05:35.456  5723  5723 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:05:35.465  5723  5723 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:05:35.465  5723  5723 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 08:05:35.473   929  2939 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 08:05:35.481  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:35.486   929  2939 D WifiConfigStore: Loading config and enabling all networks 
,09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:35.491  5432  5432 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:35.493  5432  5432 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:35.497   929  2939 D WifiConfigStore: loaded 0 passpoint configs
,09-15 08:05:35.497   929  2939 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:05:35.497   929  2939 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 08:05:35.498   929  2939 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 08:05:35.499   929  2939 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:05:35.499   929  2939 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 08:05:35.499   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 08:05:35.499   929  2939 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 08:05:35.502  4243  4243 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:05:35.502   929  2939 D WifiNative-HAL: Setting external_sim to 1
09-15 08:05:35.503   929  2939 D wifi    : setting dfs flag to true, 0x7f79f58ca0
09-15 08:05:35.504   929  2939 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 08:05:35.504   929  2939 D wifi    : setting scan oui 0x7f79f58ca0
,09-15 08:05:35.504   929  2939 D WifiHAL : Sending mac address OUI
,09-15 08:05:35.518   929  2939 E native  : do suspend true
,09-15 08:05:35.524   929  2939 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 08:05:35.523   929   929 D RttService: SCAN_AVAILABLE : 3
09-15 08:05:35.524   510   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 08:05:35.524   929  3007 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 08:05:35.525   510   927 D CommandListener: Setting iface cfg
,09-15 08:05:35.528   929  2933 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,09-15 08:05:35.529   929  2933 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 08:05:35.535   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=249267 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
09-15 08:05:35.535   929  2933 D WifiNative-HAL: p2pGetDeviceAddress
09-15 08:05:35.535   929  2933 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:35.750  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:35.758  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:35.764  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 08:05:35.765  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-15 08:05:35.769  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f74a256 Bundle[{}]
,09-15 08:05:35.769  5432  5478 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 08:05:35.770  5432  5478 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-15 08:05:35.771  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 08:05:35.772  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 08:05:35.773  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-15 08:05:35.774  5432  5478 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 08:05:35.781  5432  5478 I System.out: Running OutgoingSocketThread
,09-15 08:05:35.783  5432  5725 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-15 08:05:35.787  5432  5725 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47718
,09-15 08:05:35.787  5432  5725 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 08:05:36.785  5432  5478 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-15 08:05:36.785  5432  5478 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-15 08:05:36.791  5432  5478 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-15 08:05:36.792  5432  5478 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-15 08:05:36.793  5432  5478 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-15 08:05:36.798  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.798  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9c2cf0 added. We now have 2 listener(s)
,09-15 08:05:36.802  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:05:36.802  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.802  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 08:05:36.803  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 08:05:36.803  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd07269 added. We now have 9 listener(s)
09-15 08:05:36.803  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.803  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:05:36.807  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:36.811  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:36.813  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:36.813  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:36.814  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.814  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a02d8f added. We now have 3 listener(s)
,09-15 08:05:36.815  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:36.816  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:05:36.816  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.816  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.816  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.816  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7af281c added. We now have 10 listener(s)
09-15 08:05:36.817  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.817  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:36.817  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:36.817  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:36.817  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:36.817  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:05:36.817  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.817  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:36.817  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.817  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9c2cf0 removed from the list
09-15 08:05:36.818  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.818  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd07269 removed from the list
09-15 08:05:36.818  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:05:36.818  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.819  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.819  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.820  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:36.821  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.821  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.821  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd07269 not in the list
,09-15 08:05:36.821  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.821  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.822  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.822  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:36.822  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.822  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7af281c removed from the list
09-15 08:05:36.822  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.822  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.822  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.822  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.823  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a02d8f removed from the list
09-15 08:05:36.823  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.823  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@574cc25 added. We now have 2 listener(s)
09-15 08:05:36.825  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:05:36.825  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.825  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.825  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.825  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c61fa added. We now have 9 listener(s)
09-15 08:05:36.825  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.826  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:05:36.829  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:36.831  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:36.832  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:36.833  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:36.833  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.833  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@694aa08 added. We now have 3 listener(s)
09-15 08:05:36.834  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:36.835  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.835  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 08:05:36.835  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.835  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.835  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b05a1 added. We now have 10 listener(s)
09-15 08:05:36.835  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.836  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:36.836  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:05:36.836  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:05:36.836  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:36.836  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:05:36.836  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:36.839  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:05:36.839  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 08:05:36.842  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 08:05:36.842  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 08:05:36.842  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:05:36.845  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 08:05:36.845  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:05:36.845  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:05:36.846  5432  5478 D BluetoothAdapter: STATE_ON
,09-15 08:05:36.848  5669  5709 D BtGatt.GattService: registerClient() - UUID=4dfe5317-4dc0-4f72-801c-0af41f8de3a5
,09-15 08:05:36.849  5669  5685 D BtGatt.GattService: onClientRegistered() - UUID=4dfe5317-4dc0-4f72-801c-0af41f8de3a5, clientIf=5
,09-15 08:05:36.849  5432  5442 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:05:36.850  5669  5697 D BtGatt.GattService: start scan with filters
,09-15 08:05:36.853  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 08:05:36.854  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:05:36.854  5669  5688 D BtGatt.ScanManager: handling starting scan
09-15 08:05:36.854  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:05:36.854  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 08:05:36.855  5669  5688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cd4c1fb
09-15 08:05:36.857  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:36.857  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:05:36.857  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:36.858  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:05:36.860  5669  5685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 08:05:36.860  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.861  5669  5688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 08:05:36.861  5432  5478 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-15 08:05:36.861  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:36.861  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:05:36.861  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.861  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:05:36.861  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:05:36.861  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:05:36.861  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:05:36.862  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:36.862  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:05:36.862  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 08:05:36.862  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:36.863  5669  5679 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:05:36.863  5669  5680 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:05:36.863  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:05:36.864  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:05:36.864  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:05:36.864  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:05:36.864  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:05:36.865  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:36.865  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:05:36.865  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 08:05:36.865  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:05:36.865  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:36.866  5669  5685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:05:36.866  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.866  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:36.866  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:36.866  5669  5688 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:05:36.866  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:36.866  5669  5688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:05:36.868  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:05:36.868  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:36.868  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:36.868  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.868  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.868  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:36.868  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.868  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@574cc25 removed from the list
09-15 08:05:36.868  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.868  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c61fa removed from the list
09-15 08:05:36.868  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:05:36.868  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.869  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.869  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.870  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:36.870  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.870  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.870  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c61fa not in the list
09-15 08:05:36.870  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.870  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.871  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.871  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:36.871  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.871  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b05a1 removed from the list
09-15 08:05:36.871  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.871  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.871  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.871  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.872  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@694aa08 removed from the list
09-15 08:05:36.872  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.872  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f15add added. We now have 2 listener(s)
09-15 08:05:36.874  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.874  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.874  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.874  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.875  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5613652 added. We now have 9 listener(s)
09-15 08:05:36.875  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:05:36.875  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 08:05:36.876  5669  5685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:05:36.876  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:36.878  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:36.881  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:36.881  5669  5685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:05:36.881  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:36.883  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:36.883  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:36.883  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.883  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74cb220 added. We now have 3 listener(s)
09-15 08:05:36.884  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.884  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.884  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.884  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.884  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eadc7d9 added. We now have 10 listener(s)
09-15 08:05:36.885  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.885  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:36.885  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:36.885  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:36.885  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:05:36.886  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:05:36.886  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:36.886  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:05:36.886  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:36.888  5669  5685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:05:36.888  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.889  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 08:05:36.889  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 08:05:36.889  5669  5688 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:05:36.894  5669  5685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 08:05:36.894  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.894  5669  5688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:05:36.894  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:05:36.895  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:05:36.895  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:05:36.898  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 08:05:36.898  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:05:36.898  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:05:36.898  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:36.898  5669  5685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 08:05:36.898  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:36.900  5669  5679 D BtGatt.GattService: registerClient() - UUID=860f1ca6-3c57-4095-ba73-394757940150
,09-15 08:05:36.900  5669  5685 D BtGatt.GattService: onClientRegistered() - UUID=860f1ca6-3c57-4095-ba73-394757940150, clientIf=5
,09-15 08:05:36.900  5432  5443 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:05:36.901  5669  5709 D BtGatt.GattService: start scan with filters
09-15 08:05:36.902  5669  5688 D BtGatt.ScanManager: handling starting scan
,09-15 08:05:36.902  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:05:36.903  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:05:36.903  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:05:36.903  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:05:36.905  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:05:36.905  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:05:36.905  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:05:36.907  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:05:36.907  5669  5685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 08:05:36.907  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.908  5669  5688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 08:05:36.909  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:36.909  5432  5478 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 08:05:36.909  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:05:36.909  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:36.909  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:36.909  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.909  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.910  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:05:36.910  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.910  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f15add removed from the list
09-15 08:05:36.910  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.910  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5613652 removed from the list
09-15 08:05:36.910  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:36.910  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:05:36.911  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.911  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 08:05:36.911  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.911  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:36.912  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:36.912  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.912  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.912  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5613652 not in the list
09-15 08:05:36.912  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 08:05:36.912  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:05:36.912  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:36.912  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:05:36.912  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 08:05:36.912  5432  5478 D BluetoothAdapter: STATE_ON
09-15 08:05:36.913  5669  5685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:05:36.913  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.913  5669  5680 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:05:36.913  5669  5688 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:05:36.913  5669  5688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 08:05:36.914  5669  5708 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 08:05:36.914  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:05:36.914  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:05:36.914  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:05:36.914  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:05:36.914  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:05:36.915  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:36.915  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:05:36.915  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:05:36.915  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:05:36.915  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.916  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.916  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:36.916  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.916  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:36.916  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eadc7d9 removed from the list
09-15 08:05:36.916  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.916  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:36.916  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.916  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:36.916  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.916  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.917  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74cb220 removed from the list
09-15 08:05:36.917  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.917  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a0895 added. We now have 2 listener(s)
09-15 08:05:36.919  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.919  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.919  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.919  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.919  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc13daa added. We now have 9 listener(s)
09-15 08:05:36.919  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.920  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 08:05:36.922  5669  5685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:05:36.922  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.922  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:36.925  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:05:36.926  5669  5685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:05:36.926  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.927  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:05:36.927  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:36.928  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.928  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2caa538 added. We now have 3 listener(s)
09-15 08:05:36.929  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:36.929  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.929  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.929  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.929  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.930  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef9911 added. We now have 10 listener(s)
09-15 08:05:36.930  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.930  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:36.930  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:05:36.930  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:05:36.930  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:05:36.930  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:05:36.930  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:05:36.932  5669  5685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:05:36.932  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.932  5669  5688 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:05:36.934  5432  5478 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:05:36.934  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 08:05:36.938  5669  5685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 08:05:36.938  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.938  5669  5688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:05:36.938  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:05:36.941  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 08:05:36.941  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:05:36.943  5669  5685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 08:05:36.943  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:36.945  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 08:05:36.945  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:05:36.945  5432  5478 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 08:05:36.946  5432  5478 D BluetoothAdapter: STATE_ON
,09-15 08:05:36.948  5669  5708 D BtGatt.GattService: registerClient() - UUID=f3a21393-8833-464b-b1d0-c07a4b3c3826
,09-15 08:05:36.948  5669  5685 D BtGatt.GattService: onClientRegistered() - UUID=f3a21393-8833-464b-b1d0-c07a4b3c3826, clientIf=5
,09-15 08:05:36.948  5432  5442 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:05:36.948  5669  5679 D BtGatt.GattService: start scan with filters
09-15 08:05:36.950  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:05:36.950  5669  5688 D BtGatt.ScanManager: handling starting scan
09-15 08:05:36.950  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:05:36.950  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:05:36.950  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:05:36.952  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:05:36.952  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:05:36.952  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:05:36.953  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 08:05:36.954  5669  5685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:05:36.955  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.955  5669  5688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 08:05:36.958  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:05:36.958  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:05:36.958  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:36.958  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.958  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.958  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:05:36.958  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.958  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a0895 removed from the list
09-15 08:05:36.958  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.958  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc13daa removed from the list
09-15 08:05:36.958  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:05:36.958  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:36.958  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.959  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-15 08:05:36.959  5669  5685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:05:36.959  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.959  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:05:36.959  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.959  5669  5688 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:05:36.959  5669  5688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:05:36.959  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:36.959  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.959  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:05:36.960  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc13daa not in the list
09-15 08:05:36.960  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:05:36.960  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:05:36.960  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:05:36.960  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:05:36.960  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 08:05:36.960  5432  5478 D BluetoothAdapter: STATE_ON
,09-15 08:05:36.961  5669  5708 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:05:36.964  5669  5679 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:05:36.965  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 08:05:36.965  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:05:36.965  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:05:36.965  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:05:36.965  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 08:05:36.966  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:05:36.966  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:05:36.966  5432  5478 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:05:36.966  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:05:36.967  5669  5685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:05:36.967  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.967  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:36.969  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:05:36.969  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:36.969  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.969  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:36.969  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef9911 removed from the list
09-15 08:05:36.969  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.969  5432  5432 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:05:36.969  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.969  5432  5432 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:05:36.969  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.969  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.969  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2caa538 removed from the list
09-15 08:05:36.970  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.970  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a3b54d added. We now have 2 listener(s)
09-15 08:05:36.971  5669  5685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:05:36.971  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.971  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.971  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:05:36.972  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 08:05:36.972  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.972  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7fd802 added. We now have 9 listener(s)
09-15 08:05:36.972  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.972  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:05:36.974  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:05:36.976  5669  5685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 08:05:36.976  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.977  5669  5688 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:05:36.978  5432  5478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:05:36.979  5432  5478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:05:36.979  5432  5478 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:05:36.979  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:05:36.979  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@880e350 added. We now have 3 listener(s)
09-15 08:05:36.980  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:05:36.981  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 08:05:36.981  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:05:36.981  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:05:36.981  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4035949 added. We now have 10 listener(s)
09-15 08:05:36.981  5432  5478 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:05:36.981  5432  5478 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:05:36.981  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:05:36.981  5669  5685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:05:36.981  5432  5478 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:05:36.981  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:05:36.981  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.981  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.981  5669  5688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:05:36.981  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:05:36.981  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.981  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a3b54d removed from the list
09-15 08:05:36.981  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.981  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7fd802 removed from the list
09-15 08:05:36.982  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:36.982  5432  5478 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:05:36.982  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.983  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.983  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.984  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:05:36.984  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.984  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.985  5432  5478 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7fd802 not in the list
09-15 08:05:36.985  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.985  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-15 08:05:36.985  5432  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:05:36.986  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:05:36.986  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:05:36.986  5432  5478 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:05:36.986  5432  5478 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4035949 removed from the list
,09-15 08:05:36.986  5432  5478 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:05:36.986  5432  5478 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:05:36.986  5432  5478 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-15 08:05:36.986  5432  5478 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:05:36.986  5432  5478 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@880e350 removed from the list
09-15 08:05:36.986  5669  5685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 08:05:36.986  5669  5685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:05:36.987  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-15 08:05:36.987  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 08:05:36.987  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 08:05:36.987  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:05:36.987  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 08:05:36.987  5432  5478 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:05:36.991  5432  5726 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
09-15 08:05:36.991  5432  5726 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-15 08:05:36.991  5432  5726 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 08:05:36.993  5432  5727 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
,09-15 08:05:36.993  5432  5727 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-15 08:05:36.993  5432  5727 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-15 08:05:36.995  5432  5478 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-15 08:05:36.995  5432  5478 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-15 08:05:36.995  5432  5478 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-15 08:05:36.995  5432  5478 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-15 08:05:36.995  5432  5478 D com.test.thalitest.ThaliTestRunner: Total duration: 22590 ms
09-15 08:05:36.996  5432  5478 I jxcore-log: *Native tests were executed*
09-15 08:05:36.996  5432  5478 I jxcore-log: 
09-15 08:05:36.996  5432  5478 I jxcore-log: Total number of executed tests:  80
09-15 08:05:36.996  5432  5478 I jxcore-log: 
09-15 08:05:36.997  5432  5478 I jxcore-log: Number of passed tests:  80
09-15 08:05:36.997  5432  5478 I jxcore-log: 
09-15 08:05:36.997  5432  5478 I jxcore-log: Number of failed tests:  0
09-15 08:05:36.997  5432  5478 I jxcore-log: 
09-15 08:05:36.997  5432  5478 I jxcore-log: Number of ignored tests:  0
09-15 08:05:36.997  5432  5478 I jxcore-log: 
,09-15 08:05:36.997  5432  5478 I jxcore-log: Total duration:  22590
09-15 08:05:36.997  5432  5478 I jxcore-log: 
,09-15 08:05:36.998  5432  5478 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 08:05:36.998  5432  5478 I jxcore-log: 
09-15 08:05:37.000  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.000  5432  5478 I jxcore-log: 
09-15 08:05:37.003  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.003  5432  5478 I jxcore-log: 
09-15 08:05:37.004  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.004  5432  5478 I jxcore-log: 
,09-15 08:05:37.005  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.005  5432  5478 I jxcore-log: 
09-15 08:05:37.006  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.006  5432  5478 I jxcore-log: 
09-15 08:05:37.008  5432  5432 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-15 08:05:37.008  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.008  5432  5478 I jxcore-log: 
09-15 08:05:37.011  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:05:37.011  5432  5478 I jxcore-log: 
09-15 08:05:37.013  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.013  5432  5478 I jxcore-log: 
09-15 08:05:37.014  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.014  5432  5478 I jxcore-log: 
09-15 08:05:37.014  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.014  5432  5478 I jxcore-log: 
09-15 08:05:37.015  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.015  5432  5478 I jxcore-log: 
09-15 08:05:37.016  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:05:37.016  5432  5478 I jxcore-log: 
09-15 08:05:37.017  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.017  5432  5478 I jxcore-log: 
09-15 08:05:37.018  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.018  5432  5478 I jxcore-log: 
09-15 08:05:37.019  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.019  5432  5478 I jxcore-log: 
09-15 08:05:37.019  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.019  5432  5478 I jxcore-log: 
09-15 08:05:37.020  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.020  5432  5478 I jxcore-log: 
09-15 08:05:37.021  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.021  5432  5478 I jxcore-log: 
09-15 08:05:37.021  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.021  5432  5478 I jxcore-log: 
09-15 08:05:37.022  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.022  5432  5478 I jxcore-log: 
09-15 08:05:37.022  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.022  5432  5478 I jxcore-log: 
,09-15 08:05:37.023  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:05:37.023  5432  5478 I jxcore-log: 
09-15 08:05:37.024  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.024  5432  5478 I jxcore-log: 
,09-15 08:05:37.024  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.024  5432  5478 I jxcore-log: 
,09-15 08:05:37.025  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.025  5432  5478 I jxcore-log: 
,09-15 08:05:37.026  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.026  5432  5478 I jxcore-log: 
09-15 08:05:37.026  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.026  5432  5478 I jxcore-log: 
,09-15 08:05:37.027  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.027  5432  5478 I jxcore-log: 
,09-15 08:05:37.028  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:05:37.028  5432  5478 I jxcore-log: 
,09-15 08:05:37.368  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:05:37.371  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:05:37.371  5432  5478 I jxcore-log: 
,09-15 08:05:37.417  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:05:37.420  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:05:37.420  5432  5478 I jxcore-log: 
,09-15 08:05:37.470  5432  5432 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:05:37.476  5432  5478 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:05:37.476  5432  5478 I jxcore-log: 
,09-15 08:05:37.504  5728  5728 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 08:05:37.509  5728  5728 D AndroidRuntime: CheckJNI is OFF
,09-15 08:05:37.538  5728  5728 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 08:05:37.571  5728  5728 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 08:05:37.589  5728  5728 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 08:05:37.599   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-15 08:05:37.599   929   942 I ActivityManager: Killing 5432:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 08:05:37.687   929  2946 D WifiService: Client connection lost with reason: 4
,09-15 08:05:37.687   929  3105 D GraphicsStats: Buffer count: 2
,09-15 08:05:37.688   929  3360 I WindowState: WIN DEATH: Window{ab2c97d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-15 08:05:37.740   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-15 08:05:37.740   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-15 08:05:37.741   929   952 I art     : Starting a blocking GC Explicit
,09-15 08:05:37.741   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-15 08:05:37.741   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 08:05:37.741   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:37.741   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:37.741   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 08:05:37.741   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 08:05:37.743   929   942 I ActivityManager:   Force finishing activity ActivityRecord{3e7bc5e u0 com.test.thalitest/.MainActivity t2}
,09-15 08:05:37.753   929  3715 W ActivityManager: Spurious death for ProcessRecord{f9cedc2 0:com.test.thalitest/u0a77}, curProc for 5432: null
,09-15 08:05:37.817   929   952 I art     : Explicit concurrent mark sweep GC freed 23876(1495KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.592ms total 76.289ms
,09-15 08:05:37.836   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-15 08:05:37.838  5728  5728 I art     : System.exit called, status: 0
,09-15 08:05:37.838  5728  5728 I AndroidRuntime: VM exiting with result code 0.
,09-15 08:05:37.854   929   952 I ActivityManager: Start proc 5738:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-15 08:05:37.854   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 08:05:37.861   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-15 08:05:37.867  5669  5669 D BluetoothMapAppObserver: onReceive
,09-15 08:05:37.867  5669  5669 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-15 08:05:37.870  3374  3374 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-15 08:05:37.871  3566  3917 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-15 08:05:37.882   929  2921 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-15 08:05:37.902  3361  5751 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 08:05:37.903  3374  5750 I Keyboard.Facilitator.DecoderInitializer: run()
,09-15 08:05:37.908  4709  4718 W art     : Suspending all threads took: 11.232ms
,09-15 08:05:37.914  3457  3457 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 08:05:37.931  3542  3542 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-15 08:05:37.931  3542  3542 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-15 08:05:37.928    27    27 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 08:05:37.931    27    27 W kworker/2:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 08:05:37.937  3374  5750 I Decoder : createOrResetDecoder
,09-15 08:05:37.940   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 08:05:37.947   929   941 E PackageManager: Failed to write settings, restoring backup
09-15 08:05:37.947   929   941 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
09-15 08:05:37.947   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-15 08:05:37.947   929   941 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-15 08:05:37.947   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
09-15 08:05:37.947   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
09-15 08:05:37.947   929   941 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
09-15 08:05:37.947   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
09-15 08:05:37.947   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
09-15 08:05:37.947   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
09-15 08:05:37.947   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-15 08:05:37.947   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-15 08:05:37.947   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:05:37.947   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:37.947   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 08:05:37.947   929   941 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-15 08:05:37.947   929   941 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
09-15 08:05:37.947   929   941 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
09-15 08:05:37.947   929   941 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-15 08:05:37.947   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-15 08:05:37.947   929   941 E PackageManager: 	... 12 more
,09-15 08:05:37.958    27    27 W kworker/2:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 08:05:37.963   929  3359 I ActivityManager: Start proc 5758:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-15 08:05:37.964  3483  3623 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 08:05:37.964  3483  3623 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3483
09-15 08:05:37.964  3483  3623 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:05:37.964  3483  3623 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 08:05:37.967   929  3715 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-15 08:05:37.973  3483  3623 I Process : Sending signal. PID: 3483 SIG: 9
09-15 08:05:37.975   929  5765 E DropBoxManagerService: Can't write: system_app_crash
09-15 08:05:37.975   929  5765 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-15 08:05:37.975   929  5765 E DropBoxManagerService: 	... 8 more
,09-15 08:05:37.988  3361  3391 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjE627F190B) - 
,09-15 08:05:37.996  3869  5757 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-15 08:05:37.996  3869  5757 D AccountUtils: Clearing selected account for com.test.thalitest
,09-15 08:05:38.016  3542  3542 I ConfigService: onCreate

```
