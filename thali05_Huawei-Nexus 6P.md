#### Test 890133743ddb6d0_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-14 10:32:56.202   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-14 10:32:56.202   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-14 10:32:56.725  5555  5555 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-14 10:32:56.730  5555  5555 D AndroidRuntime: CheckJNI is OFF
10-14 10:32:56.763  5555  5555 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-14 10:32:56.800  5555  5555 I Radio-JNI: register_android_hardware_Radio DONE
10-14 10:32:56.817  5555  5555 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-14 10:32:56.820   928  3754 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-14 10:32:56.867   928  3754 I ActivityManager: Start proc 5564:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-14 10:32:56.880  5555  5555 D AndroidRuntime: Shutting down VM
,10-14 10:32:57.212   928  3362 I WindowManager: Screenshot max retries 4 of Token{d4e6205 ActivityRecord{bfbe97c u0 com.test.thalitest/.MainActivity t2}} appWin=Window{d05ec14 u0 Starting com.test.thalitest} drawState=2
,10-14 10:32:57.298  5564  5564 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 10:32:57.331  5564  5564 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 10:32:57.361  5564  5564 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 9475-9497)
,10-14 10:32:57.361  5564  5564 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 10:32:57.381  5564  5564 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6003ee7}
,10-14 10:32:57.382  5564  5564 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 10:32:57.382  5564  5564 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-14 10:32:57.387  5564  5564 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 10:32:57.389  5564  5564 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 10:32:57.427  5564  5564 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 10:32:57.440  5564  5564 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 10:32:57.440  5564  5564 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 10:32:57.440  5564  5564 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 10:32:57.440  5564  5564 I Adreno  : Build Date                       : 12/06/15
10-14 10:32:57.440  5564  5564 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 10:32:57.440  5564  5564 I Adreno  : Local Branch                     : mybranch17112971
10-14 10:32:57.440  5564  5564 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 10:32:57.440  5564  5564 I Adreno  : Remote Branch                    : NONE
10-14 10:32:57.440  5564  5564 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 10:32:57.494   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccaa9ac:true
,10-14 10:32:57.521  2901  2901 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33841]" dev="sockfs" ino=33841 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 10:32:57.521  2901  2901 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33841]" dev="sockfs" ino=33841 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 10:32:57.535  5564  5564 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-14 10:32:57.544  5564  5564 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-14 10:32:57.565  2901  2901 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33365]" dev="sockfs" ino=33365 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 10:32:57.565  2901  2901 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33365]" dev="sockfs" ino=33365 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-14 10:32:57.570  5564  5601 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-14 10:32:57.571   938   938 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28798]" dev="sockfs" ino=28798 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-14 10:32:57.571   938   938 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28798]" dev="sockfs" ino=28798 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 10:32:57.578  5564  5588 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-14 10:32:57.605  5564  5601 I OpenGLRenderer: Initialized EGL, version 1.4
,10-14 10:32:57.686   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +470ms (total +845ms)
,10-14 10:32:57.713  5564  5564 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5564
,10-14 10:32:57.800  5564  5564 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-14 10:32:57.925  5564  5604 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -565180112
,10-14 10:32:57.929  5564  5604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-14 10:32:57.929  5564  5604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-14 10:32:57.929  5564  5604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-14 10:32:57.929  5564  5604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-14 10:32:57.929  5564  5604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-14 10:32:57.930  5564  5604 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9320ec added. We now have 1 listener(s)
,10-14 10:32:57.932  5564  5604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-14 10:32:57.932  5564  5604 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:32:57.933  5564  5604 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:32:57.933  5564  5604 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-14 10:32:57.934  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-14 10:32:57.935  5564  5604 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@473bebb added. We now have 1 listener(s)
10-14 10:32:57.935  5564  5604 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:32:57.939   928  2918 D WifiService: New client listening to asynchronous messages
10-14 10:32:57.940  5564  5604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 10:32:57.940  5564  5604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-14 10:32:57.940  5564  5604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-14 10:32:57.940  5564  5604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-14 10:32:57.940  5564  5604 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-14 10:32:57.942  5564  5604 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:32:57.942  5564  5604 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
10-14 10:32:57.946  5564  5604 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:32:57.946  5564  5604 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:32:57.946  5564  5604 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-14 10:32:57.946  5564  5604 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:32:57.947  5564  5604 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-14 10:32:57.950  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:32:57.955  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:32:57.964  5564  5564 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-14 10:32:58.243  5564  5610 W jxcore-log: Initializing JXcore engine
10-14 10:32:58.243  5564  5610 W jxcore-log: JXcore engine is ready
,10-14 10:32:58.265  5610  5610 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12359 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-14 10:32:58.265  5610  5610 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15437]" dev="sockfs" ino=15437 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-14 10:32:58.265  5610  5610 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,10-14 10:32:58.265  5610  5610 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33341]" dev="sockfs" ino=33341 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-14 10:32:58.274  5564  5610 W jxcore-log: Starting JXcore engine
,10-14 10:32:58.281  5564  5573 I art     : Background sticky concurrent mark sweep GC freed 86533(8MB) AllocSpace objects, 18(1556KB) LOS objects, 22% free, 25MB/32MB, paused 1.397ms total 102.300ms
,10-14 10:32:58.327  5564  5610 W jxcore-log: Platform android
10-14 10:32:58.327  5564  5610 W jxcore-log: 
10-14 10:32:58.327  5564  5610 W jxcore-log: Process ARCH arm
10-14 10:32:58.327  5564  5610 W jxcore-log: 
,10-14 10:32:58.437  5564  5610 I jxcore-log: JXcore Cordova bridge is ready!
10-14 10:32:58.437  5564  5610 I jxcore-log: 
,10-14 10:32:58.438  5564  5610 W jxcore-log: JXcore engine is started
,10-14 10:32:58.448  5564  5604 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-14 10:32:58.453  5564  5564 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-14 10:32:59.377   928  2917 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 10:33:06.203   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:07.204   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:08.206   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:08.292  5564  5610 I jxcore-log: 2016-10-14 14:33:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-14 10:33:08.292  5564  5610 I jxcore-log: 
,10-14 10:33:08.294  5564  5610 I jxcore-log: 2016-10-14 14:33:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-14 10:33:08.294  5564  5610 I jxcore-log: 
,10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:08.299  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:33:08.300  5564  5610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:33:08.301  5564  5610 I jxcore-log: 2016-10-14 14:33:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-14 10:33:08.301  5564  5610 I jxcore-log: 
10-14 10:33:08.302  5564  5610 I jxcore-log: 2016-10-14 14:33:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-14 10:33:08.302  5564  5610 I jxcore-log: 
,10-14 10:33:08.560  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:33:08.560  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b4d19 added. We now have 2 listener(s)
10-14 10:33:08.561  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 10:33:08.561  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:33:08.561  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:33:08.561  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:33:08.561  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53a1de added. We now have 2 listener(s)
10-14 10:33:08.561  5564  5610 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:33:08.562  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:33:08.564  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:08.567  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:33:08.568  5564  5610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:33:08.568  5564  5610 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:33:08.569  5564  5610 D ExecuteNativeTests: Running unit tests
,10-14 10:33:08.569  5564  5610 D BluetoothAdapter: enable(): BT is already enabled..!
10-14 10:33:08.569   928  3754 D WifiService: setWifiEnabled: true pid=5564, uid=10077
10-14 10:33:08.569   928  3754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:08.574  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:08.579  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:09.207   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:10.209   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:11.209   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 10:33:16.211   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:17.212   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:18.214   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:18.574  5564  5610 I com.test.thalitest.ThaliTestRunner: Running UT
,10-14 10:33:18.639  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 10:33:18.639  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b932c0 added. We now have 3 listener(s)
,10-14 10:33:18.640  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 10:33:18.640  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:33:18.640  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:33:18.640  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:33:18.641  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14bf9 added. We now have 3 listener(s)
10-14 10:33:18.641  5564  5610 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:33:18.642  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 10:33:18.645  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:18.650  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:33:18.657  5564  5610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:33:18.658  5564  5610 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:33:18.661  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-14 10:33:18.661  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 10:33:18.661  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:18.661  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:18.661  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:18.662  5564  5610 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-14 10:33:18.662  5564  5610 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 10:33:18.662  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 10:33:18.662  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:18.662  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:18.662  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:18.662  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:18.663  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-14 10:33:18.664  5564  5610 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-14 10:33:18.665  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
10-14 10:33:18.667  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-14 10:33:18.667  5564  5610 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-14 10:33:18.669  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:18.669  5564  5610 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-14 10:33:18.670  5564  5610 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,10-14 10:33:18.670  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-14 10:33:18.670  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-14 10:33:18.670  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-14 10:33:18.670  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 10:33:18.670  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:18.671  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-14 10:33:18.671  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-14 10:33:18.672  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 10:33:18.672  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-14 10:33:18.672  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 10:33:18.672  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-14 10:33:18.672  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:18.672  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-14 10:33:18.672  5564  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 10:33:18.672  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 10:33:18.674  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:33:18.674  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 10:33:18.675  5564  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:33:18.675  4561  4561 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31538]" dev="sockfs" ino=31538 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 10:33:18.681  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 10:33:18.675  4561  4561 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31538]" dev="sockfs" ino=31538 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:18.681  5564  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-14 10:33:18.683  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:33:18.683  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:33:18.685  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-14 10:33:18.685  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:18.686  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
10-14 10:33:18.686  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-14 10:33:18.686  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-14 10:33:18.686  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-14 10:33:18.686  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:18.687  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:18.691  4549  4768 D BtGatt.GattService: registerClient() - UUID=9b8f224b-2119-4428-b22a-123dc1332fd8
,10-14 10:33:18.691  4549  4611 D BtGatt.GattService: onClientRegistered() - UUID=9b8f224b-2119-4428-b22a-123dc1332fd8, clientIf=5
,10-14 10:33:18.692  5564  5575 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-14 10:33:18.695  4549  4614 D BtGatt.AdvertiseManager: message : 0
,10-14 10:33:18.697  4549  4614 D BtGatt.AdvertiseManager: starting multi advertising
,10-14 10:33:18.713  4549  4611 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-14 10:33:18.721  4549  4611 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-14 10:33:18.722  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-14 10:33:18.722  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-14 10:33:18.722  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-14 10:33:18.723  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-14 10:33:18.723  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:33:18.724  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:33:18.725  5564  5610 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 10:33:18.725  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:18.726  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-14 10:33:18.726  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-14 10:33:18.726  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-14 10:33:18.726  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,10-14 10:33:18.726  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-14 10:33:18.726  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,10-14 10:33:18.726  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:33:18.726  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-14 10:33:18.726  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-14 10:33:18.730  5564  5564 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-14 10:33:18.731  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-14 10:33:19.215   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:19.228  5564  5610 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:33:19.228  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-14 10:33:19.228  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 10:33:19.229  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 10:33:19.230  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,10-14 10:33:19.231  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 10:33:19.231  5564  5610 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-14 10:33:19.231  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-14 10:33:19.232  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 10:33:19.232  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-14 10:33:19.232  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 10:33:19.232  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 10:33:19.232  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:33:19.232  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-14 10:33:19.233  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 10:33:19.233  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:33:19.233  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-14 10:33:19.233  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:33:19.233  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:33:19.233  5564  5612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-14 10:33:19.233  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-14 10:33:19.233  5564  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 10:33:19.234  5564  5612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 10:33:19.234  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:33:19.235  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:19.236  5564  5610 D BluetoothLeScanner: could not find callback wrapper
10-14 10:33:19.236  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:33:19.236  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-14 10:33:19.237  4549  4614 D BtGatt.AdvertiseManager: message : 1
10-14 10:33:19.239  4549  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
10-14 10:33:19.255  4549  4611 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-14 10:33:19.255  4549  4611 D BtGatt.GattService: Client app is not null!
,10-14 10:33:19.257  4549  4769 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:33:19.258  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:33:19.258  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-14 10:33:19.258  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:19.258  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-14 10:33:19.258  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:19.258  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:33:19.259  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-14 10:33:19.259  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,10-14 10:33:19.259  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-14 10:33:19.261  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:19.261  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:33:19.262  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:33:19.262  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:33:19.263  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:33:19.264  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:33:19.265  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 10:33:19.265  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:19.265  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:19.265  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 10:33:19.265  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:33:19.265  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:19.266  5564  5610 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-14 10:33:19.266  5564  5610 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-14 10:33:19.266  5564  5610 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-14 10:33:19.267  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-14 10:33:19.267  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-14 10:33:19.267  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-14 10:33:19.267  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 10:33:19.267  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:19.268  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-14 10:33:19.269  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 10:33:19.269  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 10:33:19.269  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-14 10:33:19.270  5564  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 10:33:19.270  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 10:33:19.271  5564  5615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:19.271  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 10:33:19.268  4769  4769 W Binder_5: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28317]" dev="sockfs" ino=28317 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:19.268  4769  4769 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28317]" dev="sockfs" ino=28317 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:19.272  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-14 10:33:19.273  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:19.274  5564  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-14 10:33:19.273  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:33:19.282  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:33:19.282  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 10:33:19.285  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 10:33:19.286  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:33:19.286  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 10:33:19.288  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-14 10:33:19.288  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:19.288  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
10-14 10:33:19.288  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:19.289  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-14 10:33:19.289  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-14 10:33:19.289  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:19.289  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:19.292  4549  4759 D BtGatt.GattService: registerClient() - UUID=1dbd09a1-b29f-4245-ab0e-33355f513a95
10-14 10:33:19.292  4549  4611 D BtGatt.GattService: onClientRegistered() - UUID=1dbd09a1-b29f-4245-ab0e-33355f513a95, clientIf=5
10-14 10:33:19.293  5564  5574 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-14 10:33:19.294  4549  4614 D BtGatt.AdvertiseManager: message : 0
10-14 10:33:19.296  4549  4614 D BtGatt.AdvertiseManager: starting multi advertising
,10-14 10:33:19.316  4549  4611 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
10-14 10:33:19.322  4549  4611 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-14 10:33:19.323  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-14 10:33:19.323  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-14 10:33:19.323  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-14 10:33:19.323  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-14 10:33:19.323  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:33:19.325  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 10:33:19.326  5564  5610 I io.jxcore.node.ConnectionHelper: start: OK
10-14 10:33:19.326  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:19.326  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-14 10:33:19.327  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-14 10:33:19.327  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-14 10:33:19.327  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-14 10:33:19.327  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:19.327  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-14 10:33:19.327  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:33:19.327  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-14 10:33:19.327  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-14 10:33:19.329  5564  5564 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-14 10:33:19.329  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-14 10:33:19.830  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
10-14 10:33:19.831  5564  5610 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-14 10:33:19.831  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-14 10:33:19.831  5564  5610 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-14 10:33:19.831  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-14 10:33:19.831  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-14 10:33:19.832  5564  5610 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-14 10:33:19.832  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-14 10:33:19.833  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,10-14 10:33:19.836  4549  4614 D BtGatt.AdvertiseManager: message : 1
10-14 10:33:19.838  4549  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-14 10:33:19.852  4549  4611 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-14 10:33:19.852  4549  4611 D BtGatt.GattService: Client app is not null!
,10-14 10:33:19.853  4549  4759 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-14 10:33:19.854  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:33:19.854  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-14 10:33:19.855  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:19.855  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 10:33:19.855  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-14 10:33:19.855  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 10:33:19.855  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
10-14 10:33:19.856  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:19.856  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-14 10:33:19.856  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-14 10:33:19.856  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:19.858  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:19.862  4549  4769 D BtGatt.GattService: registerClient() - UUID=485a680b-f977-4cbe-9b88-2824c7a2e408
,10-14 10:33:19.863  4549  4611 D BtGatt.GattService: onClientRegistered() - UUID=485a680b-f977-4cbe-9b88-2824c7a2e408, clientIf=5
10-14 10:33:19.864  5564  5575 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-14 10:33:19.868  4549  4614 D BtGatt.AdvertiseManager: message : 0
,10-14 10:33:19.871  4549  4614 D BtGatt.AdvertiseManager: starting multi advertising
,10-14 10:33:19.888  4549  4611 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-14 10:33:19.896  4549  4611 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-14 10:33:19.897  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-14 10:33:19.897  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-14 10:33:19.897  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-14 10:33:19.897  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-14 10:33:19.897  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-14 10:33:19.897  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 10:33:19.897  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 10:33:19.897  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-14 10:33:19.898  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,10-14 10:33:19.898  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-14 10:33:19.898  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,10-14 10:33:19.898  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:33:19.898  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:19.898  5564  5610 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 10:33:19.898  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-14 10:33:19.898  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-14 10:33:19.899  5564  5610 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:33:19.899  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-14 10:33:19.899  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 10:33:19.899  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-14 10:33:19.900  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 10:33:19.900  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 10:33:19.900  5564  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-14 10:33:19.900  5564  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 10:33:19.900  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:33:19.900  5564  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 10:33:19.900  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-14 10:33:19.900  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 10:33:19.900  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 10:33:19.900  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:33:19.900  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:33:19.900  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:33:19.900  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:33:19.901  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-14 10:33:19.901  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:33:19.901  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 10:33:19.902  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:19.902  5564  5610 D BluetoothLeScanner: could not find callback wrapper
10-14 10:33:19.902  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:33:19.902  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-14 10:33:19.903  4549  4614 D BtGatt.AdvertiseManager: message : 1
10-14 10:33:19.904  4549  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
10-14 10:33:19.912  4549  4611 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-14 10:33:19.912  4549  4611 D BtGatt.GattService: Client app is not null!
10-14 10:33:19.913  4549  4768 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:33:19.913  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-14 10:33:19.913  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-14 10:33:19.913  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:19.913  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-14 10:33:19.913  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-14 10:33:19.914  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:33:19.914  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-14 10:33:19.914  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-14 10:33:19.914  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-14 10:33:19.915  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:33:19.915  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:33:19.915  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:33:19.916  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:33:19.917  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:33:19.917  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-14 10:33:19.917  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:33:19.917  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:19.917  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:33:19.919  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,10-14 10:33:19.919  5564  5610 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-14 10:33:19.920  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
10-14 10:33:19.920  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-14 10:33:19.921  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-14 10:33:19.921  5564  5610 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-14 10:33:19.922  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-14 10:33:19.922  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-14 10:33:19.922  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-14 10:33:19.922  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 10:33:19.922  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-14 10:33:19.922  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:19.922  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:19.922  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 10:33:19.923  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:19.923  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:19.923  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:19.923  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 10:33:19.923  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:19.923  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:33:19.923  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-14 10:33:19.923  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-14 10:33:19.924  5564  5610 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 10:33:19.924  5564  5610 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-14 10:33:19.934  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-14 10:33:19.934  5564  5610 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-14 10:33:19.936  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,10-14 10:33:19.936  5564  5610 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-14 10:33:19.937  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,10-14 10:33:19.938  5564  5610 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
10-14 10:33:19.938  5564  5610 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-14 10:33:19.938  5564  5610 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-14 10:33:19.938  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 10:33:19.938  5564  5610 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-14 10:33:19.938  5564  5610 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-14 10:33:19.938  5564  5610 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-14 10:33:19.938  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 10:33:19.938  5564  5610 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-14 10:33:19.938  5564  5610 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-14 10:33:19.938  5564  5610 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 10:33:19.938  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 10:33:19.939  5564  5610 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-14 10:33:19.940  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-14 10:33:19.940  5564  5610 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-14 10:33:19.940  5564  5610 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-14 10:33:19.940  5564  5610 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-14 10:33:19.940  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-14 10:33:19.940  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:19.940  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-14 10:33:19.940  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 10:33:19.940  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:33:19.942  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-14 10:33:19.941  4759  4759 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31557]" dev="sockfs" ino=31557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 10:33:19.941  4759  4759 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31557]" dev="sockfs" ino=31557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:19.942  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 10:33:19.942  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-14 10:33:19.943  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-14 10:33:19.943  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-14 10:33:19.943  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-14 10:33:19.943  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:19.943  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 10:33:19.943  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:33:19.943  5564  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 10:33:19.943  5564  5619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:19.945  5564  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-14 10:33:19.947  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:33:19.947  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 10:33:19.951  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:33:19.952  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:33:19.952  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:33:19.955  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-14 10:33:19.955  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:19.955  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
10-14 10:33:19.955  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:19.955  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-14 10:33:19.956  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-14 10:33:19.956  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-14 10:33:19.956  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:19.959  4549  4769 D BtGatt.GattService: registerClient() - UUID=add8d4e1-5a21-4857-b287-34487920a59b
,10-14 10:33:19.960  4549  4611 D BtGatt.GattService: onClientRegistered() - UUID=add8d4e1-5a21-4857-b287-34487920a59b, clientIf=5
10-14 10:33:19.960  5564  5575 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-14 10:33:19.961  4549  4614 D BtGatt.AdvertiseManager: message : 0
,10-14 10:33:19.963  4549  4614 D BtGatt.AdvertiseManager: starting multi advertising
,10-14 10:33:19.973  4549  4611 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-14 10:33:19.978  4549  4611 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-14 10:33:19.979  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-14 10:33:19.979  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-14 10:33:19.979  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-14 10:33:19.979  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-14 10:33:19.979  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:33:19.980  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 10:33:19.981  5564  5610 I io.jxcore.node.ConnectionHelper: start: OK
10-14 10:33:19.981  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:19.981  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-14 10:33:19.981  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-14 10:33:19.981  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-14 10:33:19.981  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-14 10:33:19.981  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:19.981  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-14 10:33:19.981  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-14 10:33:19.981  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-14 10:33:19.981  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-14 10:33:19.983  5564  5564 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-14 10:33:19.984  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-14 10:33:20.216   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:20.483  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:33:20.483  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-14 10:33:20.483  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 10:33:20.483  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 10:33:20.484  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-14 10:33:20.484  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-14 10:33:20.484  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 10:33:20.484  5564  5619 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-14 10:33:20.484  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:33:20.484  5564  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-14 10:33:20.484  5564  5619 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 10:33:20.484  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b932c0 removed from the list
10-14 10:33:20.485  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-14 10:33:20.485  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:33:20.485  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:33:20.485  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:33:20.485  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-14 10:33:20.485  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 10:33:20.485  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:33:20.485  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 10:33:20.485  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:33:20.487  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:20.488  5564  5610 D BluetoothLeScanner: could not find callback wrapper
10-14 10:33:20.488  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:33:20.488  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-14 10:33:20.490  4549  4614 D BtGatt.AdvertiseManager: message : 1
,10-14 10:33:20.492  4549  4614 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-14 10:33:20.505  4549  4611 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-14 10:33:20.505  4549  4611 D BtGatt.GattService: Client app is not null!
10-14 10:33:20.506  4549  4563 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:33:20.507  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:33:20.507  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-14 10:33:20.507  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-14 10:33:20.507  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-14 10:33:20.508  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:20.508  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:33:20.508  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-14 10:33:20.508  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-14 10:33:20.508  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-14 10:33:20.510  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:20.510  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:33:20.510  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-14 10:33:20.511  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 10:33:20.513  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14bf9 removed from the list
,10-14 10:33:20.513  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:33:20.513  5564  5610 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:33:20.513  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:20.513  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:33:20.513  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:33:21.014  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:33:21.217   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 10:33:25.517  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-14 10:33:25.519  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-14 10:33:25.519  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:33:25.523  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-14 10:33:25.524  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-14 10:33:25.524  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 10:33:25.525  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-14 10:33:25.525  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 10:33:25.525  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:33:25.525  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-14 10:33:25.525  5564  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 10:33:25.526  5564  5620 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:25.527  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
10-14 10:33:25.525  4759  4759 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31562]" dev="sockfs" ino=31562 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:25.525  4759  4759 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31562]" dev="sockfs" ino=31562 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:25.528  5564  5610 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-14 10:33:25.529  5564  5610 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 10:33:25.529  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 10:33:25.529  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:33:25.529  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-14 10:33:25.531  5564  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-14 10:33:25.532  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,10-14 10:33:25.538  5564  5610 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-14 10:33:25.538  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:33:25.539  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-14 10:33:25.539  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 10:33:25.539  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 10:33:25.539  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:25.539  5564  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-14 10:33:25.539  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-14 10:33:25.539  5564  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 10:33:25.539  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 10:33:25.539  5564  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 10:33:25.539  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-14 10:33:25.539  5564  5610 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b932c0 not in the list
10-14 10:33:25.539  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:33:25.539  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 10:33:25.539  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:33:25.539  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-14 10:33:25.539  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:33:25.539  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:33:25.540  5564  5610 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:33:25.540  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:25.541  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:33:25.541  5564  5610 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14bf9 not in the list
10-14 10:33:25.541  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:25.541  5564  5610 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:33:25.541  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:25.541  5564  5610 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:33:25.541  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:25.541  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:25.543  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-14 10:33:25.543  5564  5610 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-14 10:33:25.543  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 10:33:25.543  5564  5610 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-14 10:33:25.543  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 10:33:25.543  5564  5610 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-14 10:33:25.544  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-14 10:33:25.544  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
10-14 10:33:25.545  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
10-14 10:33:25.547  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
10-14 10:33:25.547  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-14 10:33:25.547  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-14 10:33:25.548  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,10-14 10:33:25.548  5564  5610 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-14 10:33:25.548  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-14 10:33:25.549  5564  5610 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-14 10:33:25.549  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-14 10:33:25.549  5564  5610 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-14 10:33:25.549  5564  5610 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-14 10:33:25.550  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
10-14 10:33:25.550  5564  5610 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,10-14 10:33:25.550  5564  5610 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-14 10:33:25.551  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
10-14 10:33:25.551  5564  5610 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-14 10:33:25.551  5564  5610 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-14 10:33:25.551  5564  5610 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-14 10:33:25.551  5564  5610 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-14 10:33:25.552  5564  5610 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,10-14 10:33:25.553  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:33:25.553  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a02569 added. We now have 3 listener(s)
10-14 10:33:25.555  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:25.555  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:33:25.555  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:33:25.555  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 10:33:25.555  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1bee added. We now have 3 listener(s)
10-14 10:33:25.555  5564  5610 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:33:25.556  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:33:25.558  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:25.563  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:33:25.565  5564  5610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:33:25.566  5564  5610 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:33:25.567  5564  5610 D BluetoothAdapter: enable(): BT is already enabled..!
10-14 10:33:25.568   928  3767 D WifiService: setWifiEnabled: true pid=5564, uid=10077
10-14 10:33:25.568   928  3767 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-14 10:33:25.568  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:25.570  5564  5610 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,10-14 10:33:25.571  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:25.572  5564  5610 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-14 10:33:25.573  5564  5610 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-14 10:33:25.576   928  3754 D WifiService: setWifiEnabled: false pid=5564, uid=10077
,10-14 10:33:25.576   928  3754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:25.581   928  2917 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-14 10:33:25.581   928  2917 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-14 10:33:25.581   928  2917 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:33:25.581   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:33:25.588   928  5315 D DhcpClient: Clearing IP address
10-14 10:33:25.589   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:33:25.597  3516  5372 V NativeCrypto: Read error: ssl=0x7f9d057580: I/O error during system call, Connection timed out
10-14 10:33:25.597   508   922 D CommandListener: Setting iface cfg
10-14 10:33:25.599  3516  5372 V NativeCrypto: SSL shutdown failed: ssl=0x7f9d057580: I/O error during system call, Broken pipe
10-14 10:33:25.600   928  3767 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-14 10:33:25.601   928  5313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-14 10:33:25.603   928  5313 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-14 10:33:25.603   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-14 10:33:25.604   928  2919 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 10:33:25.605   928  2919 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-14 10:33:25.609   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-14 10:33:25.609   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-14 10:33:25.614   537   537 E Parcel  : Reading a NULL string not supported here.
,10-14 10:33:25.616   928   928 D RttService: SCAN_AVAILABLE : 1
,10-14 10:33:25.617   928  3025 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 10:33:25.617   928  2919 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-14 10:33:25.619  3719  3833 W QCNEJ   : |CORE| network lost: 100
10-14 10:33:25.620  3719  3833 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-14 10:33:25.621   928  5316 D DhcpClient: Receive thread stopped
,10-14 10:33:25.638   928  2917 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-14 10:33:25.649   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:33:25.653   928  2917 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:33:25.673   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 10:33:25.673   508   922 D CommandListener: Clearing all IP addresses on wlan0
10-14 10:33:25.673   508   922 D TetherController: Setting IP forward enable = 0
10-14 10:33:25.674   928  2919 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-14 10:33:25.674   928  2919 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 10:33:25.675   928  2917 D DhcpClient: doQuit
,10-14 10:33:25.675   928  2917 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 10:33:25.676   928  5315 D DhcpClient: onQuitting
,10-14 10:33:25.678  3421  3421 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-14 10:33:25.679   928   945 D Tethering: MasterInitialState.processMessage what=3
10-14 10:33:25.682  5228  5228 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dd0f1f2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:25.686  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:25.687  3883  3883 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 10:33:25.688  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:25.690  4982  5003 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 10:33:25.690  4982  5003 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 10:33:25.690  4982  5003 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-14 10:33:25.690  4982  5003 E SarControlService: no key has been found,reset the power
10-14 10:33:25.690  4982  5017 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 10:33:25.690  4982  5017 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 10:33:25.690  4982  5017 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 10:33:25.691  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:33:25.691  5007  5007 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:25.693  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:25.695  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:25.695  4982  5017 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 10:33:25.695  4982  5017 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 10:33:25.695  4982  5017 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 10:33:25.696  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:33:25.696  5007  5007 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 10:33:25.699  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@51195e8 HexData = [00000000ea03000000000000ffffffff]
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:25.699  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:25.699  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:33:25.699  5007  5021 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-14 10:33:25.700  3421  3421 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-14 10:33:25.700  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:33:2,5.701  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 10:33:25.701  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:25.703  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:25.704  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:25.705  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:25.706  3883  3883 D SystemUpdateService: onCreate
10-14 10:33:25.707  3421  3421 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-14 10:33:25.707  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@51195e8 HexData = [00000000eb03000000000000ffffffff]
10-14 10:33:25.708  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:33:25.708  5007  5021 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-14 10:33:25.708  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-14 10:33:25.708  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 10:33:25.710   508   915 W SocketClient: write error (Broken pipe)
10-14 10:33:25.710   508   915 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-14 10:33:25.710   508   915 W SocketListener: Error sending broadcast (Broken pipe)
10-14 10:33:25.712  3883  3883 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 10:33:25.721  3883  3883 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 10:33:25.725  3883  5639 I SystemUpdateService: active receiver: enabled
,10-14 10:33:25.727  3883  5339 I iu.UploadsManager: num queued entries: 0
,10-14 10:33:25.729  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 10:33:25.731  3883  3883 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 10:33:25.733  3421  3421 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 10:33:25.733  5344  5344 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:33:25.738  5344  5344 D SprintDMHelper: simOperator: 
10-14 10:33:25.738  5344  5344 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 10:33:25.744   508   922 E Netd    : netlink response contains error (No such file or directory)
10-14 10:33:25.745   508   922 D TetherController: Setting IP forward enable = 0
10-14 10:33:25.746   928  2919 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-14 10:33:25.746   928  2919 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-14 10:33:25.751  4957  5643 I Babel   : connection state changed from CONNECTED to DISCONNECTED
10-14 10:33:25.727  3883  5339 I iu.UploadsManager: num updated entries: 0
10-14 10:33:25.755  3421  3421 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-14 10:33:25.755  3883  5339 I iu.SyncManager: NEXT; no task
10-14 10:33:25.756  3883  5639 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 10:33:25.758  3883  5639 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-14 10:33:25.758  3883  5639 I SystemUpdateService: now status is 0 (complete)
10-14 10:33:25.758  3883  5639 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 10:33:25.758  3883  5639 I SystemUpdateService: file has been verified
10-14 10:33:25.758  3883  5639 I SystemUpdateService: OTA package size = 21989297
,10-14 10:33:25.765  3883  5639 I SystemUpdateService: showing system update notification
,10-14 10:33:25.766   928   939 I ActivityManager: Start proc 5646:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-14 10:33:25.784  3883  3883 D SystemUpdateService: onDestroy
,10-14 10:33:25.799  5646  5646 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-14 10:33:25.810   928  5327 I ActivityManager: Killing 4922:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-14 10:33:25.859   928  2917 D wifi    : In wifi stop Hal
,10-14 10:33:25.859   928  2917 D wifi    : halHandle = 0x7f809a7400, mVM = 0x7f9cfcd140, mCls = 0x100a02
10-14 10:33:25.860  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:33:25.861   928  3420 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-14 10:33:25.861   928  3420 D WifiHAL : Got a signal to exit!!!
10-14 10:33:25.861   928  3420 I WifiHAL : Exit wifi_event_loop
10-14 10:33:25.861  4067  4158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:33:25.862   928  2917 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-14 10:33:25.862   928  2917 E WifiHAL : Event processing terminated
10-14 10:33:25.862   928  2917 D wifi    : In wifi cleaned up handler
10-14 10:33:25.862   928  2917 I WifiHAL : Internal cleanup completed
10-14 10:33:25.863  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:25.865  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:25.866  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:25.885   928  3420 D wifi    : set interface wlan0 flags (DOWN)
,10-14 10:33:25.886   928  2917 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 10:33:26.042  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:33:26.086  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:26.092   928  3363 D WifiService: setWifiEnabled: true pid=5564, uid=10077
10-14 10:33:26.092   928   945 D Tethering: InitialState.processMessage what=4
,10-14 10:33:26.092   928  3363 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:26.101   508   922 D SoftapController: Softap fwReload - Ok
,10-14 10:33:26.103   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 10:33:26.105   508   922 D CommandListener: Setting iface cfg
,10-14 10:33:26.106   508   922 D CommandListener: Trying to bring down wlan0
,10-14 10:33:26.108   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:33:26.113   928  2917 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 10:33:26.601   928  3754 D WifiService: setWifiEnabled: true pid=5564, uid=10077
,10-14 10:33:26.603   928  3754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:26.727   928  2917 D wifi    : set interface wlan0 flags (UP)
,10-14 10:33:26.731   928  2917 I WifiHAL : Initializing wifi
10-14 10:33:26.731   928  2917 I WifiHAL : Creating socket
,10-14 10:33:26.737   928  2917 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-14 10:33:26.737   928  2917 D wifi    : Did set static halHandle = 0x7f809a7400
10-14 10:33:26.737   928  2917 D wifi    : halHandle = 0x7f809a7400, mVM = 0x7f9cfcd140, mCls = 0x14d2
10-14 10:33:26.738   928  2917 D wifi    : array field set
,10-14 10:33:26.738   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-14 10:33:26.738   928  2917 I WifiNative-HAL: interface[0] = wlan0
10-14 10:33:26.740   928  5661 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547618452480
,10-14 10:33:26.741   928  5661 D wifi    : waitForHalEvents called, vm = 0x7f9cfcd140, obj = 0x14d2, env = 0x7f7e67d440
,10-14 10:33:26.831  5662  5662 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 10:33:26.843   928  2917 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-14 10:33:26.847  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:26.849  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:26.850  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:26.854  5662  5662 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:33:26.863  5662  5662 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:33:26.863  5662  5662 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 10:33:26.877   928  2917 D WifiConfigStore: Loading config and enabling all networks 
,10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:26.883  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:26.886  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:26.886   928  2917 D WifiConfigStore: loaded 0 passpoint configs
10-14 10:33:26.887   928  2917 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:33:26.887   928  2917 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-14 10:33:26.888   928  2917 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-14 10:33:26.888   928  2917 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-14 10:33:26.888   928  2917 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 10:33:26.889   928  2917 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 10:33:26.889   928  2917 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:26.890  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:26.891   928  2917 D WifiNative-HAL: Setting external_sim to 1
10-14 10:33:26.892   928  2917 D wifi    : setting dfs flag to true, 0x7f7d407be0
,10-14 10:33:26.892   928  2917 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 10:33:26.892   928  2917 D wifi    : setting scan oui 0x7f7d407be0
10-14 10:33:26.892   928  2917 D WifiHAL : Sending mac address OUI
,10-14 10:33:26.892  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:33:26.893  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:26.896  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:26.897  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:26.899   928  2917 E native  : do suspend false
,10-14 10:33:26.906   928  2917 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-14 10:33:26.906   928   928 D RttService: SCAN_AVAILABLE : 3
10-14 10:33:26.906   928  3025 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-14 10:33:26.906   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-14 10:33:26.907   508   922 D CommandListener: Setting iface cfg
,10-14 10:33:26.910   928  2916 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-14 10:33:26.910   928  2916 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 10:33:26.920   928  2916 D WifiNative-HAL: p2pGetDeviceAddress
,10-14 10:33:26.924   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=249059 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-14 10:33:26.924   928  2916 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 10:33:27.111  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.126  4549  4607 D BluetoothAdapterState: Current state: ON, message: 23
,10-14 10:33:27.126  4549  4607 D BluetoothAdapterProperties: Setting state to 13
10-14 10:33:27.126  4549  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-14 10:33:27.129  4549  4607 D BluetoothAdapterProperties: onBluetoothDisable()
,10-14 10:33:27.131  4549  4607 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:33:27.132  4549  4549 D BluetoothMapService: onReceive
10-14 10:33:27.132  4549  4549 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-14 10:33:27.132  4549  4549 D BluetoothMapService: STATE_TURNING_OFF
10-14 10:33:27.133  4549  4549 D BluetoothMapService: MAP Service closeService in
10-14 10:33:27.134  4549  4549 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 10:33:27.134  4549  4549 D ObexServerSockets0: shutdown(block = true)
,10-14 10:33:27.136  4549  4549 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:33:27.136  4549  4757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-14 10:33:27.136  4549  4549 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:33:27.138  4549  4772 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 10:33:27.135  4549  4771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-14 10:33:27.148  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:27.148  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:27.148  4549  4549 I BtOppRfcommListener: stopping Accept Thread
10-14 10:33:27.149  4549  5244 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 10:33:27.149  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:27.149  4549  5244 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-14 10:33:27.149  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:27.153  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:27.154  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:27.155  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:27.155  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:27.159  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:27.159  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:27.161  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:27.162  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:27.169   928   941 I ActivityManager: Start proc 5668:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-14 10:33:27.170  4549  4611 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:33:27.170  4549  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-14 10:33:27.174  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:27.175  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.176  4549  4549 D HeadsetService: Received stop request...Stopping profile...
,10-14 10:33:27.177  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.181   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 10:33:27.181   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 10:33:27.181   928   928 D BluetoothHeadset: Proxy object disconnected
,10-14 10:33:27.182  3084  3096 D BluetoothHeadset: Proxy object disconnected
,10-14 10:33:27.182  3084  3084 D HeadsetProfile: Bluetooth service disconnected
10-14 10:33:27.183  4549  4549 D A2dpService: Received stop request...Stopping profile...
10-14 10:33:27.183  3755  3769 D BluetoothHeadset: Proxy object disconnected
10-14 10:33:27.183  4549  4763 D A2dpStateMachine: Exit Disconnected: -1
10-14 10:33:27.184   928   928 D BluetoothA2dp: Proxy object disconnected
10-14 10:33:27.185  3084  3084 D BluetoothA2dp: Proxy object disconnected
10-14 10:33:27.185  4549  4549 D HidService: Received stop request...Stopping profile...
10-14 10:33:27.185  4549  4549 D HidService: Stopping Bluetooth HidService
,10-14 10:33:27.186  3084  3084 D BluetoothInputDevice: Proxy object disconnected
10-14 10:33:27.186  3084  3084 D HidProfile: Bluetooth service disconnected
,10-14 10:33:27.187  4549  4549 D HealthService: Received stop request...Stopping profile...
,10-14 10:33:27.190  4549  4549 D PanService: Received stop request...Stopping profile...
10-14 10:33:27.191  3084  3084 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 10:33:27.191  3084  3084 D PanProfile: Bluetooth service disconnected
,10-14 10:33:27.191  4549  4549 D BluetoothMapService: Received stop request...Stopping profile...
10-14 10:33:27.191  4549  4549 D BluetoothMapService: stop()
10-14 10:33:27.192  4549  4549 D BluetoothMapAppObserver: deinitObservers()
10-14 10:33:27.192  4549  4549 D BluetoothMapAppObserver: removeReceiver()
,10-14 10:33:27.195  4549  4549 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:33:27.195  4549  4549 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:27.195  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.195  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:27.195  3084  3084 D BluetoothMap: Proxy object disconnected
10-14 10:33:27.196  3084  3084 D MapProfile: Bluetooth service disconnected
10-14 10:33:27.196  4549  4549 D SapService: Received stop request...Stopping profile...
10-14 10:33:27.196  4549  4549 V SapService: stop()
10-14 10:33:27.199  4549  4549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 10:33:27.199  4549  4549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-14 10:33:27.199  4549  4739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-14 10:33:27.199  4549  4739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:27.199  4549  4549 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:27.199  4549  4739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:27.199  4549  4549 V BluetoothAdapterState: isTurningOn()=false
,10-14 10:33:27.199  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.199  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:27.200  4549  4549 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:27.200  4549  4549 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:27.200  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 10:33:27.201  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:27.201  4549  4549 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-14 10:33:27.201  4549  4549 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-14 10:33:27.201  4549  4549 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:33:27.201  4549  4549 V BluetoothAdapterState: isTurningOn()=false
,10-14 10:33:27.201  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.201  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:27.202  4549  4549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-14 10:33:27.202  4549  4611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 10:33:27.202  4549  4549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 10:33:27.202  4549  4611 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-14 10:33:27.202  4549  4611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 10:33:27.202  4549  4611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 10:33:27.202  4549  4739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:27.202  4549  4611 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-14 10:33:27.202  4549  4549 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:27.202  4549  4549 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:27.202  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.203  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:27.203  4549  4739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:27.203  4549  4739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-14 10:33:27.203  4549  4739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 10:33:27.203  4549  4739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:33:27.203  4549  4739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 10:33:27.203  4549  4549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 10:33:27.203  4549  4549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 10:33:27.204  4549  4549 D BluetoothMapService: MAP Service closeService in
10-14 10:33:27.204  4549  4549 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:27.204  4549  4549 V BluetoothAdapterState: isTurningOn()=false
,10-14 10:33:27.204  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.204  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:27.205  4549  4549 D BluetoothMapService: cleanup()
,10-14 10:33:27.205  4549  4549 D BluetoothMapService: MAP Service closeService in
10-14 10:33:27.205  4549  4549 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:27.205  4549  4549 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:27.205  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.205  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:27.205  4549  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 10:33:27.205  4549  4607 D BluetoothAdapterProperties: Setting state to 15
10-14 10:33:27.205  4549  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 10:33:27.206  4549  4607 I BluetoothAdapterState: Entering BleOnState
10-14 10:33:27.210  3084  3096 D BluetoothPbap: onBluetoothStateChange: up=false
,10-14 10:33:27.211  3084  3284 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:27.211  3084  3098 D BluetoothMap: onBluetoothStateChange: up=false
10-14 10:33:27.211   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:27.212   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:27.212  3084  3917 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 10:33:27.212   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:27.212  3084  3096 D BluetoothPan: onBluetoothStateChange on: false
10-14 10:33:27.213   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 10:33:27.213  3084  3284 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 10:33:27.214  3755  3768 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:27.215  4549  4607 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 10:33:27.215  4549  4607 D BluetoothAdapterProperties: Setting state to 16
10-14 10:33:27.215  4549  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 10:33:27.215  4549  4607 D BluetoothAdapterProperties: onBleDisable
10-14 10:33:27.215  4549  4607 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:33:27.215  4549  4608 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 10:33:27.216  4549  4739 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 10:33:27.216  4549  4739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:27.221  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:27.222  4549  4611 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:33:27.223  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:27.224  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:27.226  5668  5668 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-14 10:33:27.229  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.230  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.233  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.245  5668  5668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 10:33:27.250   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e491f1f:true
,10-14 10:33:27.251  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:33:27.264   928   938 I ActivityManager: Start proc 5680:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-14 10:33:27.285  5668  5668 D LocalBluetoothProfileManager: Adding local MAP profile
,10-14 10:33:27.291  5668  5668 D BluetoothMap: Create BluetoothMap proxy object
,10-14 10:33:27.300  5668  5668 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-14 10:33:27.307  5680  5680 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-14 10:33:27.318  5668  5668 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:33:27.321   928  3068 I ActivityManager: Killing 5228:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-14 10:33:27.430  4549  4611 I bt_hci  : shut_down
,10-14 10:33:27.435  4549  4617 D bt_hwcfg: hw_epilog_process
,10-14 10:33:27.435  4549  4617 I bt_vendor: low_power_mode_cb
,10-14 10:33:27.437  4549  4617 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-14 10:33:27.438  4549  4617 I bt_vendor: epilog_cb
10-14 10:33:27.438  4549  4617 I bt_hci  : epilog_finished_callback
,10-14 10:33:27.441  4549  4611 I bt_hci_h4: hal_close
,10-14 10:33:27.442  4549  4611 I bt_userial_vendor: device fd = 54 close
,10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.k.d(PG:583)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.506  5680  5680 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:33:27.506  5680  5680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:33:27.510  5668  5668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:33:27.516  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:33:27.519  5668  5668 D DockEventReceiver: finishStartingService: stopping service
10-14 10:33:27.523   928  3068 I ActivityManager: Killing 4621:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-14 10:33:27.548  4549  4608 D bt_stack_manager: event_shut_down_stack finished.
10-14 10:33:27.548  4549  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-14 10:33:27.550  4549  4607 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-14 10:33:27.550  4549  4549 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 10:33:27.550  4549  4549 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 10:33:27.550  4549  4549 D BtGatt.GattService: stop()
10-14 10:33:27.550  4549  4549 D BtGatt.AdvertiseManager: advertise clients cleared
10-14 10:33:27.552  4549  4549 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:27.552  4549  4549 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:27.552  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:27.552  4549  4549 V BluetoothAdapterState: isBleTurningOff()=true
10-14 10:33:27.552  4549  4607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 10:33:27.553  4549  4607 D BluetoothAdapterProperties: Setting state to 10
10-14 10:33:27.553  4549  4607 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 10:33:27.553  4549  4607 I BluetoothAdapterState: Entering OffState
10-14 10:33:27.554   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-14 10:33:27.560  4549  4549 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-14 10:33:27.560  4549  4549 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 10:33:27.560  4549  4549 I BluetoothServiceJni: cleanupNative: return from cleanup
10-14 10:33:27.562  4549  4608 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-14 10:33:27.566  4549  4549 I art     : System.exit called, status: 0
10-14 10:33:27.566  4549  4549 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 10:33:27.609   928  3632 I ActivityManager: Process com.android.bluetooth (pid 4549) has died
,10-14 10:33:27.624  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:27.637   928   945 I ActivityManager: Start proc 5713:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-14 10:33:27.698  5713  5713 D AdapterServiceConfig: Adding HeadsetService
,10-14 10:33:27.698  5713  5713 D AdapterServiceConfig: Adding A2dpService
10-14 10:33:27.699  5713  5713 D AdapterServiceConfig: Adding HidService
10-14 10:33:27.699  5713  5713 D AdapterServiceConfig: Adding HealthService
10-14 10:33:27.699  5713  5713 D AdapterServiceConfig: Adding PanService
10-14 10:33:27.699  5713  5713 D AdapterServiceConfig: Adding GattService
10-14 10:33:27.699  5713  5713 D AdapterServiceConfig: Adding BluetoothMapService
10-14 10:33:27.699  5713  5713 D AdapterServiceConfig: Adding SapService
,10-14 10:33:27.710   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3a4534:true
,10-14 10:33:27.711  5713  5713 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 10:33:27.713  5713  5713 I bt_bluedroid: init
,10-14 10:33:27.713  5713  5725 I BluetoothAdapterState: Entering OffState
,10-14 10:33:27.715  5713  5726 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 10:33:27.715  5713  5726 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 10:33:27.715  5713  5726 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-14 10:33:27.715  5713  5726 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 10:33:27.716  5713  5713 I bt_bluedroid: get_profile_interface socket
,10-14 10:33:27.717  5713  5729 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 10:33:27.718  5713  5713 I bt_bluedroid: get_profile_interface sdp
,10-14 10:33:27.719  5713  5729 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:33:27.722  5713  5724 I bt_bluedroid: config_hci_snoop_log
,10-14 10:33:27.723   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,10-14 10:33:27.726  5713  5725 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 10:33:27.726  5713  5725 D BluetoothAdapterProperties: Setting state to 14
10-14 10:33:27.726  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-14 10:33:27.728  5713  5725 D BluetoothBondStateMachine: make
10-14 10:33:27.729  5713  5730 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 10:33:27.732  5713  5725 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:33:27.733  5713  5713 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 10:33:27.735  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:27.736  5713  5713 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 10:33:27.736  5713  5713 D BtGatt.GattService: Received start request. Starting profile...
10-14 10:33:27.736  5713  5713 D BtGatt.GattService: start()
,10-14 10:33:27.737  5713  5713 I bt_bluedroid: get_profile_interface gatt
,10-14 10:33:27.737  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:27.738  5713  5713 D BtGatt.AdvertiseManager: advertise manager created
,10-14 10:33:27.742  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:27.742  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:27.742  5713  5713 V BluetoothAdapterState: isBleTurningOn()=true
10-14 10:33:27.742  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:27.742  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 10:33:27.743  5713  5725 I bt_bluedroid: bt_bluedroid
10-14 10:33:27.743  5713  5726 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-14 10:33:27.744  5713  5726 I bt_hci  : start_up
,10-14 10:33:27.748  5713  5726 I bt_vendor: alloc value 0xf40f3871
,10-14 10:33:27.748  5713  5726 I bt_vendor: init
10-14 10:33:27.748  5713  5726 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 10:33:27.748  5713  5726 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 10:33:27.773  5680  5701 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-14 10:33:27.785   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3263d15:true
,10-14 10:33:27.859  5713  5726 D bt_hci  : start_up starting async portion
,10-14 10:33:27.859  5713  5733 I bt_hci  : event_finish_startup
10-14 10:33:27.859  5713  5733 I bt_hci_h4: hal_open
10-14 10:33:27.859  5713  5733 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-14 10:33:27.855  5736  5736 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-14 10:33:27.860  5713  5733 I bt_userial_vendor: device fd = 54 open
,10-14 10:33:27.871  5713  5733 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:33:27.873  5713  5733 D bt_hwcfg: Chipset BCM4358A3
,10-14 10:33:27.873  5713  5733 D bt_hwcfg: Target name = [BCM4358A3]
10-14 10:33:27.873  5713  5733 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 10:33:28.133  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-14 10:33:28.265  5713  5733 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-14 10:33:28.265  5713  5733 D bt_hwcfg: Settlement delay -- 100 ms
10-14 10:33:28.266  5713  5733 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 10:33:28.391  5713  5733 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:33:28.391  5713  5733 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-14 10:33:28.392  5713  5733 I bt_hwcfg: vendor lib fwcfg completed
,10-14 10:33:28.393  5713  5733 I bt_vendor: firmware callback
,10-14 10:33:28.393  5713  5733 I bt_hci  : firmware_config_callback
,10-14 10:33:28.401  5713  5738 I bt_btu  : btu_task pending for preload complete event
,10-14 10:33:28.402  5713  5738 I bt_btu_task: Bluetooth chip preload is complete
10-14 10:33:28.402  5713  5738 I bt_btu  : btu_task received preload complete event
,10-14 10:33:28.407  5713  5738 I         : BTE_InitTraceLevels -- TRC_HCI
10-14 10:33:28.407  5713  5738 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-14 10:33:28.407  5713  5738 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_AVDT
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_AVRC
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_A2D
,10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_BNEP
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_BTM
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_PAN
10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_SDP
,10-14 10:33:28.408  5713  5738 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 10:33:28.409  5713  5738 I         : BTE_InitTraceLevels -- TRC_SMP
10-14 10:33:28.409  5713  5738 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-14 10:33:28.409  5713  5738 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 10:33:28.492  5713  5738 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4071549
,10-14 10:33:28.492  5713  5738 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4071549 
,10-14 10:33:28.509  5713  5729 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 10:33:28.511  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 10:33:28.512  5713  5729 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 10:33:28.514  5713  5729 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:33:28.519  5713  5729 D BluetoothAdapterProperties: Scan Mode:20
,10-14 10:33:28.519  5713  5729 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-14 10:33:28.519  5713  5729 D bt_hci  : do_postload posting postload work item
10-14 10:33:28.519  5713  5733 I bt_hci  : event_postload
10-14 10:33:28.519  5713  5733 I bt_vendor: sco_config_cb
10-14 10:33:28.519  5713  5733 I bt_hci  : sco_config_callback postload finished.
10-14 10:33:28.521  5713  5729 D bt_bte_conf: Device ID record 1 : primary
10-14 10:33:28.522  5713  5729 D bt_bte_conf:   vendorId            = 000f
,10-14 10:33:28.522  5713  5729 D bt_bte_conf:   vendorIdSource      = 0001
10-14 10:33:28.522  5713  5729 D bt_bte_conf:   product             = 1200
10-14 10:33:28.522  5713  5729 D bt_bte_conf:   version             = 1436
10-14 10:33:28.522  5713  5729 D bt_bte_conf:   clientExecutableURL = 
10-14 10:33:28.522  5713  5729 D bt_bte_conf:   serviceDescription  = 
,10-14 10:33:28.522  5713  5729 D bt_bte_conf:   documentationURL    = 
10-14 10:33:28.522  5713  5729 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 10:33:28.523  5713  5726 D bt_stack_manager: event_start_up_stack finished
10-14 10:33:28.524  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.528  5713  5733 I bt_vendor: low_power_mode_cb
,10-14 10:33:28.528  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.531  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.532  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 10:33:28.533  5713  5725 D BluetoothAdapterProperties: Setting state to 15
10-14 10:33:28.533  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-14 10:33:28.534  5713  5725 I BluetoothAdapterState: Entering BleOnState
,10-14 10:33:28.537  5713  5725 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-14 10:33:28.537  5713  5725 D BluetoothAdapterProperties: Setting state to 11
,10-14 10:33:28.537  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-14 10:33:28.543  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:28.544  5713  5713 D HeadsetService: Received start request. Starting profile...
,10-14 10:33:28.547  5713  5713 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 10:33:28.547  5713  5713 D HeadsetStateMachine: make
10-14 10:33:28.548  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.551  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.553  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.561  5713  5725 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:33:28.562  5713  5713 D HeadsetStateMachine: max_hf_connections = 1
10-14 10:33:28.562  5713  5713 I bt_bluedroid: get_profile_interface handsfree
10-14 10:33:28.562  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 10:33:28.562  5713  5729 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-14 10:33:28.566  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:28.567  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:33:28.567  5713  5713 D A2dpService: Received start request. Starting profile...
10-14 10:33:28.568  5713  5713 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-14 10:33:28.568  5713  5713 I bt_bluedroid: get_profile_interface avrcp
,10-14 10:33:28.574  5713  5713 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 10:33:28.575  5713  5713 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 10:33:28.575  5713  5713 D A2dpStateMachine: make
10-14 10:33:28.576  5713  5713 I bt_bluedroid: get_profile_interface a2dp
,10-14 10:33:28.576  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-14 10:33:28.579  5713  5747 D A2dpStateMachine: Enter Disconnected: -2
,10-14 10:33:28.579  5713  5713 I BluetoothHidServiceJni: classInitNative: succeeds
,10-14 10:33:28.580  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:28.582  5713  5713 D HidService: Received start request. Starting profile...
,10-14 10:33:28.582  5713  5713 I bt_bluedroid: get_profile_interface hidhost
10-14 10:33:28.582  5713  5713 D HidService: setHidService(): set to: null
10-14 10:33:28.582  5713  5729 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf405256d
10-14 10:33:28.582  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-14 10:33:28.583  5713  5713 I BluetoothHealthServiceJni: classInitNative: succeeds
10-14 10:33:28.583  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:28.584  5713  5713 D HealthService: Received start request. Starting profile...
,10-14 10:33:28.585  5713  5713 I bt_bluedroid: get_profile_interface health
,10-14 10:33:28.586  5713  5713 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-14 10:33:28.587  5668  5668 D BluetoothInputDevice: Proxy object connected
10-14 10:33:28.587  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:28.587  5668  5668 D HidProfile: Bluetooth service connected
,10-14 10:33:28.588  5713  5713 D PanService: Received start request. Starting profile...
10-14 10:33:28.588  5713  5713 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 10:33:28.588  5713  5713 I bt_bluedroid: get_profile_interface pan
10-14 10:33:28.588  5713  5729 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-14 10:33:28.590  5668  5668 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:33:28.590  5668  5668 D PanProfile: Bluetooth service connected
,10-14 10:33:28.592  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:28.593  5668  5668 D BluetoothMap: Proxy object connected
,10-14 10:33:28.594  5713  5713 D BluetoothMapService: Received start request. Starting profile...
10-14 10:33:28.594  5713  5713 D BluetoothMapService: start()
10-14 10:33:28.596  5713  5713 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-14 10:33:28.597  5713  5713 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 10:33:28.597  5713  5713 D BluetoothMapAppObserver: createReceiver()
,10-14 10:33:28.598  5713  5713 D BluetoothMapAppObserver: initObservers()
,10-14 10:33:28.599  5713  5713 D BluetoothMapAppObserver: getEnabledAccountItems()
10-14 10:33:28.604  5668  5668 D MapProfile: Bluetooth service connected
,10-14 10:33:28.604  5713  5713 V SapService: SapBinder()
10-14 10:33:28.604  5713  5713 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:28.604  5668  5668 D BluetoothMap: getConnectedDevices()
10-14 10:33:28.605  5713  5713 D SapService: Received start request. Starting profile...
10-14 10:33:28.605  5668  5668 D BluetoothMap: Bluetooth is Not enabled
10-14 10:33:28.605  5713  5713 V SapService: start()
,10-14 10:33:28.607  5713  5713 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:33:28.607  5713  5713 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:28.607  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.607  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.607  5713  5744 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.608  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isTurningOn()=true
,10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:28.609  5713  5713 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:28.610  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.610  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:28.610  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:28.610  5713  5713 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:28.611  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.611  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:28.611  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 10:33:28.611  5713  5725 D BluetoothAdapterProperties: ScanMode =  20
10-14 10:33:28.611  5713  5725 D BluetoothAdapterProperties: State =  11
,10-14 10:33:28.613  5713  5729 D BluetoothAdapterProperties: Scan Mode:21
,10-14 10:33:28.613  5713  5729 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:33:28.613  5713  5725 D BluetoothAdapterProperties: Setting state to 12
10-14 10:33:28.613  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 10:33:28.613  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 10:33:28.614  5713  5725 I BluetoothAdapterState: Entering OnState
10-14 10:33:28.614  3084  3096 D BluetoothPbap: onBluetoothStateChange: up=true
,10-14 10:33:28.616  3084  3917 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:28.617  5564  5564 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-14 10:33:28.617  3084  3284 D BluetoothMap: onBluetoothStateChange: up=true
10-14 10:33:28.619  3084  3084 D BluetoothMap: Proxy object connected
10-14 10:33:28.619  3084  3084 D MapProfile: Bluetooth service connected
10-14 10:33:28.619  3084  3084 D BluetoothMap: getConnectedDevices()
10-14 10:33:28.620  5564  5564 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-14 10:33:28.621   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:28.621   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:33:28.621  5668  5678 D BluetoothMap: onBluetoothStateChange: up=true
10-14 10:33:28.622  3084  3096 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:33:28.622  5713  5713 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:28.623  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:28.623  5713  5713 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-14 10:33:28.625  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:28.625  3084  3084 D BluetoothInputDevice: Proxy object connected
10-14 10:33:28.625  3084  3084 D HidProfile: Bluetooth service connected
10-14 10:33:28.625  5668  5679 D BluetoothPan: onBluetoothStateChange on: true
,10-14 10:33:28.625   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:33:28.626  3084  3098 D BluetoothPan: onBluetoothStateChange on: true
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:28.628  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:28.629  3084  3084 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:33:28.629  3084  3084 D PanProfile: Bluetooth service connected
10-14 10:33:28.629   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:33:28.629  5713  5713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:28.630  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:28.631  3084  3096 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:33:28.631  5713  5713 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:28.632  5668  5678 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:28.632  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:28.633  5668  5679 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:33:28.634  3755  3938 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:28.634  5713  5713 D ObexServerSockets: Succeed to create listening sockets 
10-14 10:33:28.634  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:28.634  5713  5713 D ObexServerSockets0: startAccept()
10-14 10:33:28.634  5713  5713 D ObexServerSockets0: prepareForNewConnect()
10-14 10:33:28.636  5713  5713 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-14 10:33:28.636  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 10:33:28.636   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 10:33:28.636  5713  5713 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 10:33:28.638  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.639   928   928 D BluetoothA2dp: Proxy object connected
10-14 10:33:28.639  3084  3084 D BluetoothA2dp: Proxy object connected
10-14 10:33:28.639  5668  5668 D LocalBluetoothProfileManager: Adding local A2DP profile
10-14 10:33:28.639  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.640  5713  5713 D BluetoothMapService: onReceive
10-14 10:33:28.640  5713  5713 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 10:33:28.640  5713  5713 D BluetoothMapService: STATE_ON
10-14 10:33:28.641  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.643  5713  5752 D ObexServerSockets0: Accepting socket connection...
,10-14 10:33:28.643  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.643  5564  5610 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:33:28.643  5713  5753 D ObexServerSockets0: Accepting socket connection...
10-14 10:33:28.643  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:28.646  5564  5610 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
10-14 10:33:28.647  5564  5610 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
10-14 10:33:28.646  5713  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:33:28.647  5668  5668 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-14 10:33:28.649  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.649  5713  5755 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-14 10:33:28.650  5713  5755 D BluetoothSdpJni: SDP Create record success - handle: 1
10-14 10:33:28.650  5713  5725 D BluetoothAdapterState: Current state: ON, message: 23
10-14 10:33:28.650  5713  5725 D BluetoothAdapterProperties: Setting state to 13
10-14 10:33:28.650  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-14 10:33:28.650  5713  5725 D BluetoothAdapterProperties: onBluetoothDisable()
,10-14 10:33:28.652  5713  5725 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:33:28.653  5713  5713 D BluetoothMapService: onReceive
10-14 10:33:28.653  5713  5713 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 10:33:28.653  5713  5713 D BluetoothMapService: STATE_TURNING_OFF
10-14 10:33:28.654  5713  5713 D BluetoothMapService: MAP Service closeService in
10-14 10:33:28.654  5713  5713 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 10:33:28.654  5713  5713 D ObexServerSockets0: shutdown(block = true)
10-14 10:33:28.654  5713  5729 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:33:28.654  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-14 10:33:28.654  5713  5713 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:33:28.654  5713  5713 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:33:28.654  5713  5752 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-14 10:33:28.655  5713  5753 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 10:33:28.655  5713  5740 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-14 10:33:28.656  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:28.656  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:28.657  5713  5713 D HeadsetService: Received stop request...Stopping profile...
10-14 10:33:28.657  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:28.657  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:28.659  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:28.659  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:28.659  5668  5668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:33:28.660  5564  5564 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:28.660  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:28.661  5668  5668 D BluetoothA2dp: Proxy object connected
10-14 10:33:28.662  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.663  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.664  5713  5713 D A2dpService: Received stop request...Stopping profile...
,10-14 10:33:28.664  5713  5747 D A2dpStateMachine: Exit Disconnected: -1
10-14 10:33:28.665   928   928 D BluetoothA2dp: Proxy object disconnected
10-14 10:33:28.665  3084  3084 D BluetoothA2dp: Proxy object disconnected
10-14 10:33:28.666  5713  5713 D HidService: Received stop request...Stopping profile...
10-14 10:33:28.666  5713  5713 D HidService: Stopping Bluetooth HidService
,10-14 10:33:28.666  5668  5668 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:33:28.667  3084  3084 D BluetoothInputDevice: Proxy object disconnected
10-14 10:33:28.667  3084  3084 D HidProfile: Bluetooth service disconnected
10-14 10:33:28.667  5713  5713 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:28.667  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.667  5668  5668 D BluetoothA2dp: Proxy object disconnected
10-14 10:33:28.667  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.667  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.668  5668  5668 D BluetoothInputDevice: Proxy object disconnected
10-14 10:33:28.668  5668  5668 D HidProfile: Bluetooth service disconnected
,10-14 10:33:28.668  5713  5713 D HealthService: Received stop request...Stopping profile...
10-14 10:33:28.669  5713  5713 D PanService: Received stop request...Stopping profile...
10-14 10:33:28.670  3084  3084 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-14 10:33:28.670  3084  3084 D PanProfile: Bluetooth service disconnected
10-14 10:33:28.670  5668  5668 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 10:33:28.670  5668  5668 D PanProfile: Bluetooth service disconnected
10-14 10:33:28.670  5713  5713 D BluetoothMapService: Received stop request...Stopping profile...
10-14 10:33:28.670  5713  5713 D BluetoothMapService: stop()
,10-14 10:33:28.671  5713  5713 D BluetoothMapAppObserver: deinitObservers()
,10-14 10:33:28.671  5713  5713 D BluetoothMapAppObserver: removeReceiver()
10-14 10:33:28.672  3084  3084 D BluetoothMap: Proxy object disconnected
10-14 10:33:28.672  3084  3084 D MapProfile: Bluetooth service disconnected
10-14 10:33:28.672  5668  5668 D BluetoothMap: Proxy object disconnected
10-14 10:33:28.672  5668  5668 D MapProfile: Bluetooth service disconnected
10-14 10:33:28.673  5713  5713 D SapService: Received stop request...Stopping profile...
10-14 10:33:28.673  5713  5713 V SapService: stop()
,10-14 10:33:28.675  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:33:28.676  5713  5713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 10:33:28.676  5713  5713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 10:33:28.676  5713  5738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:28.676  5713  5738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:28.676  5713  5713 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:28.676  5713  5738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:28.676  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.676  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.676  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:28.677  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-14 10:33:28.677  5713  5729 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
10-14 10:33:28.677  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 10:33:28.677  5713  5713 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:33:28.677  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.677  5713  5738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:28.677  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.677  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.678  5713  5738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:28.678  5713  5713 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 10:33:28.678  5713  5713 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 10:33:28.678  5713  5738 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:33:28.678  5713  5738 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 10:33:28.678  5713  5738 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:33:28.678  5713  5713 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:33:28.678  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.678  5713  5738 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 10:33:28.678  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.678  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.678  5713  5713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-14 10:33:28.678  5713  5729 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 10:33:28.678  5713  5729 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-14 10:33:28.678  5713  5713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 10:33:28.679  5713  5713 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:28.679  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.679  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.679  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.679  5713  5713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-14 10:33:28.679  5713  5713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-14 10:33:28.680  5713  5713 D BluetoothMapService: MAP Service closeService in
10-14 10:33:28.680  5713  5713 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:33:28.680  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.680  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.680  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:28.680  5713  5713 D BluetoothMapService: cleanup()
10-14 10:33:28.680  5713  5713 D BluetoothMapService: MAP Service closeService in
10-14 10:33:28.688  3084  3084 D BluetoothPbap: Proxy object connected
10-14 10:33:28.688  3084  3084 D PbapServerProfile: Bluetooth service connected
,10-14 10:33:28.688  5668  5668 D BluetoothPbap: Proxy object connected
10-14 10:33:28.689  5713  5713 V BluetoothAdapterState: isTurningOff()=true
10-14 10:33:28.689  5713  5713 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:28.689  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:28.689  5713  5713 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:28.689  5668  5668 D PbapServerProfile: Bluetooth service connected
10-14 10:33:28.689  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 10:33:28.689  5713  5725 D BluetoothAdapterProperties: Setting state to 15
10-14 10:33:28.689  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 10:33:28.690  5713  5725 I BluetoothAdapterState: Entering BleOnState
,10-14 10:33:28.690  3084  3098 D BluetoothPbap: onBluetoothStateChange: up=false
,10-14 10:33:28.691  3084  3917 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:28.692  3084  3096 D BluetoothMap: onBluetoothStateChange: up=false
10-14 10:33:28.692   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:28.692   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:28.692  5668  5678 D BluetoothMap: onBluetoothStateChange: up=false
10-14 10:33:28.693  3084  3284 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-14 10:33:28.693  5668  5679 D BluetoothPan: onBluetoothStateChange on: false
10-14 10:33:28.694  5668  5678 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 10:33:28.695  5668  5679 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:28.695   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:28.696  3084  3098 D BluetoothPan: onBluetoothStateChange on: false
10-14 10:33:28.696   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-14 10:33:28.697  3084  3917 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-14 10:33:28.698  5668  5678 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 10:33:28.699  5668  5679 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 10:33:28.700  3755  3769 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:33:28.700  5713  5725 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-14 10:33:28.700  5713  5725 D BluetoothAdapterProperties: Setting state to 16
10-14 10:33:28.700  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 10:33:28.702  5713  5725 D BluetoothAdapterProperties: onBleDisable
10-14 10:33:28.702  5713  5725 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:33:28.702  5713  5726 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 10:33:28.703  5713  5738 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 10:33:28.703  5713  5738 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:33:28.705  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.705  5713  5729 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:33:28.706  5668  5668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:33:28.706  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.708  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:28.709  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:28.713  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:33:28.719  5668  5668 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:33:28.723  5668  5668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 10:33:28.727  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:33:28.729  5668  5668 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:33:28.903  5713  5729 I bt_hci  : shut_down
,10-14 10:33:28.903  5713  5733 D bt_hwcfg: hw_epilog_process
10-14 10:33:28.904  5713  5733 I bt_vendor: low_power_mode_cb
,10-14 10:33:28.906  5713  5733 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-14 10:33:28.907  5713  5733 I bt_vendor: epilog_cb
,10-14 10:33:28.907  5713  5733 I bt_hci  : epilog_finished_callback
10-14 10:33:28.907  5713  5729 I bt_hci_h4: hal_close
10-14 10:33:28.907  5713  5729 I bt_userial_vendor: device fd = 54 close
,10-14 10:33:29.027  5713  5726 D bt_stack_manager: event_shut_down_stack finished.
,10-14 10:33:29.028  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-14 10:33:29.031  5713  5725 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-14 10:33:29.032  5713  5713 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-14 10:33:29.032  5713  5713 D BtGatt.GattService: Received stop request...Stopping profile...
,10-14 10:33:29.032  5713  5713 D BtGatt.GattService: stop()
10-14 10:33:29.032  5713  5713 D BtGatt.AdvertiseManager: advertise clients cleared
10-14 10:33:29.034  5713  5713 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:29.035  5713  5713 V BluetoothAdapterState: isTurningOn()=false
,10-14 10:33:29.035  5713  5713 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:29.035  5713  5713 V BluetoothAdapterState: isBleTurningOff()=true
10-14 10:33:29.035  5713  5725 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 10:33:29.035  5713  5725 D BluetoothAdapterProperties: Setting state to 10
10-14 10:33:29.035  5713  5725 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-14 10:33:29.036  5713  5725 I BluetoothAdapterState: Entering OffState
10-14 10:33:29.037   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-14 10:33:29.046  5713  5713 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-14 10:33:29.046  5713  5713 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 10:33:29.046  5713  5713 I BluetoothServiceJni: cleanupNative: return from cleanup
10-14 10:33:29.048  5713  5726 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-14 10:33:29.053  5713  5713 I art     : System.exit called, status: 0
,10-14 10:33:29.053  5713  5713 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 10:33:29.077   928   938 I ActivityManager: Process com.android.bluetooth (pid 5713) has died
,10-14 10:33:29.150  5564  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:29.151  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:29.151  5564  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:33:29.151  5564  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:29.155  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:29.185   928   945 I ActivityManager: Start proc 5766:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-14 10:33:29.276  5766  5766 D AdapterServiceConfig: Adding HeadsetService
,10-14 10:33:29.277  5766  5766 D AdapterServiceConfig: Adding A2dpService
10-14 10:33:29.277  5766  5766 D AdapterServiceConfig: Adding HidService
10-14 10:33:29.277  5766  5766 D AdapterServiceConfig: Adding HealthService
10-14 10:33:29.277  5766  5766 D AdapterServiceConfig: Adding PanService
,10-14 10:33:29.277  5766  5766 D AdapterServiceConfig: Adding GattService
10-14 10:33:29.278  5766  5766 D AdapterServiceConfig: Adding BluetoothMapService
,10-14 10:33:29.278  5766  5766 D AdapterServiceConfig: Adding SapService
,10-14 10:33:29.288   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7cc5f8c:true
,10-14 10:33:29.289  5766  5766 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 10:33:29.291  5766  5766 I bt_bluedroid: init
10-14 10:33:29.292  5766  5778 I BluetoothAdapterState: Entering OffState
,10-14 10:33:29.293  5766  5779 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 10:33:29.294  5766  5779 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 10:33:29.294  5766  5779 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-14 10:33:29.294  5766  5779 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 10:33:29.294  5766  5766 I bt_bluedroid: get_profile_interface socket
,10-14 10:33:29.296  5766  5766 I bt_bluedroid: get_profile_interface sdp
10-14 10:33:29.297  5766  5782 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 10:33:29.300  5766  5782 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:33:29.301  5766  5777 I bt_bluedroid: config_hci_snoop_log
10-14 10:33:29.302   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-14 10:33:29.306  5766  5778 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 10:33:29.306  5766  5778 D BluetoothAdapterProperties: Setting state to 14
10-14 10:33:29.306  5766  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 10:33:29.308  5766  5778 D BluetoothBondStateMachine: make
,10-14 10:33:29.309  5766  5783 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 10:33:29.312  5766  5778 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:33:29.313  5766  5766 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-14 10:33:29.315  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:29.316  5766  5766 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 10:33:29.316  5766  5766 D BtGatt.GattService: Received start request. Starting profile...
10-14 10:33:29.316  5766  5766 D BtGatt.GattService: start()
10-14 10:33:29.316  5766  5766 I bt_bluedroid: get_profile_interface gatt
10-14 10:33:29.317  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:29.317  5766  5766 D BtGatt.AdvertiseManager: advertise manager created
,10-14 10:33:29.326  5766  5766 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:33:29.326  5766  5766 V BluetoothAdapterState: isTurningOn()=false
10-14 10:33:29.326  5766  5766 V BluetoothAdapterState: isBleTurningOn()=true
10-14 10:33:29.326  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:29.326  5766  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 10:33:29.328  5766  5778 I bt_bluedroid: bt_bluedroid
10-14 10:33:29.328  5766  5779 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-14 10:33:29.328  5766  5779 I bt_hci  : start_up
,10-14 10:33:29.333  5766  5779 I bt_vendor: alloc value 0xf40f3871
,10-14 10:33:29.333  5766  5779 I bt_vendor: init
10-14 10:33:29.333  5766  5779 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 10:33:29.333  5766  5779 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 10:33:29.444  5766  5779 D bt_hci  : start_up starting async portion
,10-14 10:33:29.445  5766  5786 I bt_hci  : event_finish_startup
10-14 10:33:29.445  5766  5786 I bt_hci_h4: hal_open
,10-14 10:33:29.445  5766  5786 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-14 10:33:29.441  5787  5787 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:33:29.447  5766  5786 I bt_userial_vendor: device fd = 54 open
,10-14 10:33:29.461  5766  5786 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:33:29.464  5766  5786 D bt_hwcfg: Chipset BCM4358A3
,10-14 10:33:29.464  5766  5786 D bt_hwcfg: Target name = [BCM4358A3]
10-14 10:33:29.465  5766  5786 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 10:33:29.661  5766  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-14 10:33:29.875  5766  5786 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-14 10:33:29.875  5766  5786 D bt_hwcfg: Settlement delay -- 100 ms
10-14 10:33:29.875  5766  5786 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 10:33:29.998  5766  5786 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:33:29.999  5766  5786 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-14 10:33:30.001  5766  5786 I bt_hwcfg: vendor lib fwcfg completed
10-14 10:33:30.001  5766  5786 I bt_vendor: firmware callback
10-14 10:33:30.001  5766  5786 I bt_hci  : firmware_config_callback
,10-14 10:33:30.009  5766  5789 I bt_btu  : btu_task pending for preload complete event
,10-14 10:33:30.009  5766  5789 I bt_btu_task: Bluetooth chip preload is complete
10-14 10:33:30.009  5766  5789 I bt_btu  : btu_task received preload complete event
,10-14 10:33:30.018  5766  5789 I         : BTE_InitTraceLevels -- TRC_HCI
,10-14 10:33:30.018  5766  5789 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-14 10:33:30.018  5766  5789 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 10:33:30.018  5766  5789 I         : BTE_InitTraceLevels -- TRC_AVDT
10-14 10:33:30.018  5766  5789 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-14 10:33:30.018  5766  5789 I         : BTE_InitTraceLevels -- TRC_A2D
10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_BNEP
10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_BTM
,10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_PAN
,10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_SDP
10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_SMP
,10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-14 10:33:30.019  5766  5789 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 10:33:30.076  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:30.081  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:30.086  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:30.091  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:30.102  5766  5789 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4071549
10-14 10:33:30.102  5766  5789 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4071549 
,10-14 10:33:30.125  5766  5782 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 10:33:30.127  5766  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 10:33:30.127  5766  5782 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 10:33:30.129  5766  5782 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:33:30.131  5766  5782 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:33:30.132  5766  5782 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:33:30.132  5766  5782 D bt_hci  : do_postload posting postload work item
10-14 10:33:30.132  5766  5786 I bt_hci  : event_postload
10-14 10:33:30.132  5766  5786 I bt_vendor: sco_config_cb
10-14 10:33:30.132  5766  5786 I bt_hci  : sco_config_callback postload finished.
,10-14 10:33:30.135  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:30.138  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:30.140  5766  5782 D bt_bte_conf: Device ID record 1 : primary
,10-14 10:33:30.140  5766  5782 D bt_bte_conf:   vendorId            = 000f
10-14 10:33:30.140  5766  5782 D bt_bte_conf:   vendorIdSource      = 0001
10-14 10:33:30.140  5766  5782 D bt_bte_conf:   product             = 1200
10-14 10:33:30.140  5766  5782 D bt_bte_conf:   version             = 1436
10-14 10:33:30.140  5766  5782 D bt_bte_conf:   clientExecutableURL = 
10-14 10:33:30.140  5766  5782 D bt_bte_conf:   serviceDescription  = 
10-14 10:33:30.140  5766  5782 D bt_bte_conf:   documentationURL    = 
10-14 10:33:30.141  5766  5782 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 10:33:30.141  5766  5779 D bt_stack_manager: event_start_up_stack finished
10-14 10:33:30.141  5766  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 10:33:30.142  5766  5778 D BluetoothAdapterProperties: Setting state to 15
10-14 10:33:30.142  5766  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-14 10:33:30.143  5766  5786 I bt_vendor: low_power_mode_cb
10-14 10:33:30.143  5766  5778 I BluetoothAdapterState: Entering BleOnState
,10-14 10:33:30.148  5766  5778 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-14 10:33:30.148  5766  5778 D BluetoothAdapterProperties: Setting state to 11
10-14 10:33:30.148  5766  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-14 10:33:30.154  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:30.161   928   928 D BluetoothHeadset: Proxy object connected
,10-14 10:33:30.161   928   928 D BluetoothHeadset: Proxy object connected
,10-14 10:33:30.161   928   928 D BluetoothHeadset: Proxy object connected
,10-14 10:33:30.162  5766  5766 D HeadsetService: Received start request. Starting profile...
,10-14 10:33:30.162  3084  3284 D BluetoothHeadset: Proxy object connected
10-14 10:33:30.162  3084  3084 D HeadsetProfile: Bluetooth service connected
10-14 10:33:30.163  3755  3769 D BluetoothHeadset: Proxy object connected
10-14 10:33:30.167  5766  5766 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 10:33:30.168  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:30.168  5766  5766 D HeadsetStateMachine: make
10-14 10:33:30.171  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:30.171  5766  5778 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:33:30.171  5766  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-14 10:33:30.172   928  2917 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 10:33:30.173   928  2917 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-14 10:33:30.173   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:33:30.181  5766  5766 D HeadsetStateMachine: max_hf_connections = 1
,10-14 10:33:30.181  5766  5766 I bt_bluedroid: get_profile_interface handsfree
10-14 10:33:30.181  5766  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 10:33:30.182  5766  5782 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-14 10:33:30.184   928  2917 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-14 10:33:30.185  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:30.185  5766  5766 D A2dpService: Received start request. Starting profile...
10-14 10:33:30.186  5766  5766 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-14 10:33:30.186  5766  5766 I bt_bluedroid: get_profile_interface avrcp
,10-14 10:33:30.191  5766  5766 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 10:33:30.192  5766  5766 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 10:33:30.192  5766  5766 D A2dpStateMachine: make
,10-14 10:33:30.193  5766  5766 I bt_bluedroid: get_profile_interface a2dp
,10-14 10:33:30.193  5766  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-14 10:33:30.194  5766  5798 D A2dpStateMachine: Enter Disconnected: -2
10-14 10:33:30.195  5766  5766 I BluetoothHidServiceJni: classInitNative: succeeds
10-14 10:33:30.195  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:30.196  5766  5766 D HidService: Received start request. Starting profile...
10-14 10:33:30.196  5766  5766 I bt_bluedroid: get_profile_interface hidhost
10-14 10:33:30.196  5766  5766 D HidService: setHidService(): set to: null
10-14 10:33:30.196  5766  5782 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf405256d
10-14 10:33:30.196  5766  5782 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-14 10:33:30.197  5766  5766 I BluetoothHealthServiceJni: classInitNative: succeeds
10-14 10:33:30.197  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:30.198  5766  5766 D HealthService: Received start request. Starting profile...
,10-14 10:33:30.200  5766  5766 I bt_bluedroid: get_profile_interface health
,10-14 10:33:30.200  5766  5766 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-14 10:33:30.202  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
,10-14 10:33:30.202  5766  5766 D PanService: Received start request. Starting profile...
,10-14 10:33:30.202  5766  5766 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 10:33:30.202  5766  5766 I bt_bluedroid: get_profile_interface pan
10-14 10:33:30.203  5766  5782 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-14 10:33:30.205  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:30.205  5766  5766 D BluetoothMapService: Received start request. Starting profile...
10-14 10:33:30.205  5766  5766 D BluetoothMapService: start()
10-14 10:33:30.208  5766  5766 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-14 10:33:30.210  5766  5766 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 10:33:30.210  5766  5766 D BluetoothMapAppObserver: createReceiver()
,10-14 10:33:30.212  5766  5766 D BluetoothMapAppObserver: initObservers()
10-14 10:33:30.212  5766  5766 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-14 10:33:30.220   928  2917 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 10:33:30.223  5662  5662 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 10:33:30.223  5766  5766 V SapService: SapBinder()
10-14 10:33:30.223  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:33:30.223  5766  5766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:30.224  5766  5766 D SapService: Received start request. Starting profile...
10-14 10:33:30.224  5766  5766 V SapService: start()
,10-14 10:33:30.227  5766  5766 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:33:30.227  5766  5766 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:30.227  5766  5795 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 10:33:30.227  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:30.227  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:30.228  5766  5766 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isTurningOn()=true
,10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:33:30.229  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:30.231  5766  5766 V BluetoothAdapterState: isTurningOff()=false
10-14 10:33:30.231  5766  5766 V BluetoothAdapterState: isTurningOn()=true
10-14 10:33:30.231  5766  5766 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 10:33:30.231  5766  5766 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:33:30.232  5766  5778 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-14 10:33:30.232  5766  5778 D BluetoothAdapterProperties: ScanMode =  20
10-14 10:33:30.232  5766  5778 D BluetoothAdapterProperties: State =  11
10-14 10:33:30.232  5766  5778 D BluetoothAdapterProperties: Setting state to 12
,10-14 10:33:30.232  5766  5778 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 10:33:30.233  5766  5778 I BluetoothAdapterState: Entering OnState
10-14 10:33:30.233  3084  3917 D BluetoothPbap: onBluetoothStateChange: up=true
,10-14 10:33:30.236  5766  5782 D BluetoothAdapterProperties: Scan Mode:21
10-14 10:33:30.236  5766  5782 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:33:30.236  3084  3096 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:30.236  3084  3284 D BluetoothMap: onBluetoothStateChange: up=true
10-14 10:33:30.237  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-14 10:33:30.240   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:33:30.240   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:33:30.240  5668  5678 D BluetoothMap: onBluetoothStateChange: up=true
10-14 10:33:30.240  3084  3084 D BluetoothMap: Proxy object connected
10-14 10:33:30.240  3084  3084 D MapProfile: Bluetooth service connected
10-14 10:33:30.240  3084  3084 D BluetoothMap: getConnectedDevices()
,10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:30.240  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:30.242  3084  3096 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:33:30.242  5766  5766 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:33:30.242  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:30.243  5766  5766 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-14 10:33:30.244  5668  5679 D BluetoothPan: onBluetoothStateChange on: true
10-14 10:33:30.245  5668  5678 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:33:30.246  5766  5766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:30.246  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:30.247  5668  5679 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:30.248   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:30.248  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:30.248  3084  3098 D BluetoothPan: onBluetoothStateChange on: true
10-14 10:33:30.248  5766  5766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:30.249   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:33:30.249  5766  5766 D ObexServerSockets: Succeed to create listening sockets 
10-14 10:33:30.249  5766  5766 D ObexServerSockets0: startAccept()
10-14 10:33:30.249  5766  5766 D ObexServerSockets0: prepareForNewConnect()
10-14 10:33:30.250  3084  3284 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:33:30.251  5668  5668 D BluetoothMap: Proxy object connected
10-14 10:33:30.251  5668  5668 D MapProfile: Bluetooth service connected
10-14 10:33:30.251  5668  5668 D BluetoothMap: getConnectedDevices()
10-14 10:33:30.251  5766  5766 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-14 10:33:30.251  5766  5766 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 10:33:30.251  5766  5805 D ObexServerSockets0: Accepting socket connection...
10-14 10:33:30.252  5668  5678 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 10:33:30.252  5766  5806 D ObexServerSockets0: Accepting socket connection...
10-14 10:33:30.252  3084  3084 D BluetoothInputDevice: Proxy object connected
10-14 10:33:30.252  3084  3084 D HidProfile: Bluetooth service connected
10-14 10:33:30.254   928   928 D BluetoothA2dp: Proxy object connected
10-14 10:33:30.254  5668  5678 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:33:30.255  3084  3084 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:33:30.255  3084  3084 D PanProfile: Bluetooth service connected
10-14 10:33:30.255  3084  3084 D BluetoothA2dp: Proxy object connected
10-14 10:33:30.256  3755  3769 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:33:30.257  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 10:33:30.257  5766  5766 D BluetoothMapService: onReceive
10-14 10:33:30.258  5766  5766 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 10:33:30.258  5766  5766 D BluetoothMapService: STATE_ON
,10-14 10:33:30.259  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:30.260  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:30.260   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 10:33:30.260   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
10-14 10:33:30.261  5766  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:30.262  5766  5807 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-14 10:33:30.262  5766  5807 D BluetoothSdpJni: SDP Create record success - handle: 1
10-14 10:33:30.263  5668  5668 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:33:30.263  5668  5668 D PanProfile: Bluetooth service connected
10-14 10:33:30.263  5668  5668 D BluetoothA2dp: Proxy object connected
10-14 10:33:30.265  5668  5668 D BluetoothInputDevice: Proxy object connected
,10-14 10:33:30.265  5668  5668 D HidProfile: Bluetooth service connected
,10-14 10:33:30.272  5668  5668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 10:33:30.277  3516  3516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:33:30.279  5668  5668 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:33:30.284  3084  3084 D BluetoothPbap: Proxy object connected
,10-14 10:33:30.284  3084  3084 D PbapServerProfile: Bluetooth service connected
,10-14 10:33:30.285  5668  5668 D BluetoothPbap: Proxy object connected
,10-14 10:33:30.285  5668  5668 D PbapServerProfile: Bluetooth service connected
10-14 10:33:30.285  5766  5766 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:33:30.285  5766  5766 D ObexServerSockets0: prepareForNewConnect()
,10-14 10:33:30.297  5766  5811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:33:30.306  5766  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:33:30.307  5766  5815 I BtOppRfcommListener: Accept thread started.
,10-14 10:33:30.348  5668  5678 D BluetoothHeadset: Proxy object connected
,10-14 10:33:30.349  5668  5668 D HeadsetProfile: Bluetooth service connected
,10-14 10:33:30.643  5662  5662 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 10:33:30.675  5662  5662 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:30.676  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:30.676  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
10-14 10:33:30.684  5564  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:30.686  5564  5610 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
10-14 10:33:30.686   928  2917 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-14 10:33:30.687   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 10:33:30.687   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
10-14 10:33:30.689   928  3754 D WifiService: setWifiEnabled: false pid=5564, uid=10077
,10-14 10:33:30.689   928  3754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:30.696  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:30.704   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:33:30.714   508   922 D CommandListener: Setting iface cfg
,10-14 10:33:30.719   928  2917 D WifiStateMachine: Start Dhcp Watchdog 2
,10-14 10:33:30.730   928  2917 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,10-14 10:33:30.730   928  2919 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-14 10:33:30.730   928  2919 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
10-14 10:33:30.730   928  2917 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:33:30.730   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:33:30.736   928  5820 D DhcpClient: Receive thread started
,10-14 10:33:30.740   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:33:30.745   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,10-14 10:33:30.745   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,10-14 10:33:30.751   928  5820 D DhcpClient: Receive thread stopped
,10-14 10:33:30.751   928  2919 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-14 10:33:30.752   928  2919 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-14 10:33:30.754   928   928 D RttService: SCAN_AVAILABLE : 1
10-14 10:33:30.754   928  3025 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-14 10:33:30.757   928  2917 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-14 10:33:30.760   928  2917 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:33:30.762   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:33:30.765   928  2917 D DhcpClient: doQuit
,10-14 10:33:30.765   928  2917 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 10:33:30.765   928  5819 D DhcpClient: onQuitting
10-14 10:33:30.766  5662  5662 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:30.773  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:30.777  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:30.777  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:30.781  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:30.781  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-14 10:33:30.783  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:30.829  5662  5662 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 10:33:30.832  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 10:33:30.935   928  2917 D wifi    : In wifi stop Hal
,10-14 10:33:30.935   928  2917 D wifi    : halHandle = 0x7f809a7400, mVM = 0x7f9cfcd140, mCls = 0x14d2
10-14 10:33:30.935   928  5661 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-14 10:33:30.935   928  5661 D WifiHAL : Got a signal to exit!!!
10-14 10:33:30.935   928  5661 I WifiHAL : Exit wifi_event_loop
10-14 10:33:30.937   928  2917 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-14 10:33:30.937   928  2917 E WifiHAL : Event processing terminated
10-14 10:33:30.937   928  2917 D wifi    : In wifi cleaned up handler
10-14 10:33:30.937   928  2917 I WifiHAL : Internal cleanup completed
10-14 10:33:30.941  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:30.935  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:33:30.942  4067  4158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:33:30.944  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:30.968   928  5661 D wifi    : set interface wlan0 flags (DOWN)
,10-14 10:33:30.968   928  2917 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 10:33:31.174   928   945 D Tethering: InitialState.processMessage what=4
,10-14 10:33:31.181   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:31.203  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:31.209  5564  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:31.212   928   938 D WifiService: setWifiEnabled: true pid=5564, uid=10077
,10-14 10:33:31.212   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-14 10:33:31.218   508   922 D SoftapController: Softap fwReload - Ok
,10-14 10:33:31.219   540   540 I ServiceManager: Waiting for service AtCmdFwd...
10-14 10:33:31.219  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:31.224   508   922 D CommandListener: Setting iface cfg
10-14 10:33:31.224   508   922 D CommandListener: Trying to bring down wlan0
,10-14 10:33:31.225   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:33:31.229   928  2917 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 10:33:31.719   928  3362 D WifiService: setWifiEnabled: true pid=5564, uid=10077
,10-14 10:33:31.723   928  3362 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:31.827   928  2917 D wifi    : set interface wlan0 flags (UP)
,10-14 10:33:31.827   928  2917 I WifiHAL : Initializing wifi
,10-14 10:33:31.828   928  2917 I WifiHAL : Creating socket
,10-14 10:33:31.833   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-14 10:33:31.837   928  2917 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-14 10:33:31.837   928  2917 D wifi    : Did set static halHandle = 0x7f809a7400
10-14 10:33:31.837   928  2917 D wifi    : halHandle = 0x7f809a7400, mVM = 0x7f9cfcd140, mCls = 0x100f36
,10-14 10:33:31.837   928  2917 D wifi    : array field set
10-14 10:33:31.837   928  2917 I WifiNative-HAL: interface[0] = wlan0
10-14 10:33:31.839   928  5823 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547618452480
10-14 10:33:31.839   928  5823 D wifi    : waitForHalEvents called, vm = 0x7f9cfcd140, obj = 0x100f36, env = 0x7f92495840
,10-14 10:33:31.897  5824  5824 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 10:33:31.919  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:33:31.928  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:33:31.928  5824  5824 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 10:33:31.940   928  2917 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-14 10:33:31.952   928  2917 D WifiConfigStore: Loading config and enabling all networks 
,10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:31.955  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:31.957  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:31.961  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:33:31.962   928  2917 D WifiConfigStore: loaded 0 passpoint configs
10-14 10:33:31.963   928  2917 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:33:31.963  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:31.963   928  2917 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-14 10:33:31.964   928  2917 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-14 10:33:31.964  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:31.965   928  2917 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:33:31.965   928  2917 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 10:33:31.965  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:33:31.965   928  2917 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 10:33:31.966   928  2917 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 10:33:31.980  4957  4957 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-14 10:33:31.981   928  2917 D WifiNative-HAL: Setting external_sim to 1
,10-14 10:33:31.981   928  2917 D wifi    : setting dfs flag to true, 0x7f84ab9820
10-14 10:33:31.982   928  2917 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 10:33:31.982   928  2917 D wifi    : setting scan oui 0x7f84ab9820
10-14 10:33:31.982   928  2917 D WifiHAL : Sending mac address OUI
,10-14 10:33:31.986   928  2917 E native  : do suspend false
,10-14 10:33:31.993   928  2917 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-14 10:33:31.993   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-14 10:33:31.993   928   928 D RttService: SCAN_AVAILABLE : 3
10-14 10:33:31.993   928  3025 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-14 10:33:31.994   508   922 D CommandListener: Setting iface cfg
,10-14 10:33:31.997   928  2916 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '141 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 141 Failed to set address (No such device)'
10-14 10:33:31.998   928  2916 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 10:33:32.002   928  2916 D WifiNative-HAL: p2pGetDeviceAddress
,10-14 10:33:32.006   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=254142 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,10-14 10:33:32.006   928  2916 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 10:33:32.220   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:32.234  5564  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:32.236  5564  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:33:32.238  5564  5610 D BluetoothAdapter: enable(): BT is already enabled..!
10-14 10:33:32.239   928  3097 D WifiService: setWifiEnabled: true pid=5564, uid=10077
10-14 10:33:32.239   928  3097 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:33:32.240  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:33:32.240  5564  5610 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:33:32.240  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:32.240  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:33:32.240  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-14 10:33:32.241  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a02569 removed from the list
10-14 10:33:32.241  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:33:32.241  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc1bee removed from the list
,10-14 10:33:32.241  5564  5610 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:33:32.241  5564  5610 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:33:32.241  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:32.243  5564  5610 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
10-14 10:33:32.245  5564  5610 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
10-14 10:33:32.246  5564  5610 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
10-14 10:33:32.247  5564  5610 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,10-14 10:33:32.250  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-14 10:33:32.251  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-14 10:33:32.253  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,10-14 10:33:32.253  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-14 10:33:32.254  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
10-14 10:33:32.256  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
10-14 10:33:32.256  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@858f2f5 Bundle[{}]
10-14 10:33:32.256  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-14 10:33:32.256  5564  5610 I io.jxcore.node.LifeCycleMonitor: start: OK
10-14 10:33:32.257  5564  5610 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-14 10:33:32.257  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
10-14 10:33:32.257  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-14 10:33:32.258  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,10-14 10:33:32.258  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-14 10:33:32.259  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-14 10:33:32.259  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-14 10:33:32.259  5564  5610 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
10-14 10:33:32.260  5564  5610 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-14 10:33:32.261  5564  5610 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
10-14 10:33:32.263  5564  5610 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
10-14 10:33:32.263  5564  5610 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
10-14 10:33:32.264  5564  5610 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-14 10:33:32.265  5564  5610 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,10-14 10:33:32.266  5564  5610 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-14 10:33:32.267  5564  5610 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
10-14 10:33:32.268  5564  5610 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
10-14 10:33:32.269  5564  5610 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
10-14 10:33:32.270  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
10-14 10:33:32.270  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
10-14 10:33:32.271  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-14 10:33:32.271  5564  5610 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
10-14 10:33:32.271  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,10-14 10:33:32.272  5564  5610 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-14 10:33:32.272  5564  5610 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
10-14 10:33:32.272  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
10-14 10:33:32.272  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
10-14 10:33:32.273  5564  5610 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
10-14 10:33:32.273  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:33:32.273  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90caf25 added. We now have 3 listener(s)
10-14 10:33:32.274  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:32.274  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:33:32.274  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:33:32.274  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:33:32.274  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36208fa added. We now have 3 listener(s)
,10-14 10:33:32.274  5564  5610 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:33:32.275  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:33:32.277  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:33:32.282  5564  5610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:33:32.284  5564  5610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:33:32.284  5564  5610 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:33:32.286  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:32.288  5564  5610 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
10-14 10:33:32.288  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:33:32.289  5564  5610 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,10-14 10:33:32.289  5564  5610 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-14 10:33:32.289  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,10-14 10:33:32.289  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:32.289  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-14 10:33:32.289  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 10:33:32.289  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:32.290  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-14 10:33:32.291  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 10:33:32.291  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 10:33:32.291  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-14 10:33:32.291  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 10:33:32.291  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 10:33:32.291  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,10-14 10:33:32.291  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:32.291  5564  5826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 10:33:32.291  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:33:32.292  5564  5826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:33:32.291  5803  5803 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35051]" dev="sockfs" ino=35051 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:32.296  5564  5826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-14 10:33:32.291  5803  5803 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35051]" dev="sockfs" ino=35051 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 10:33:32.297  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-14 10:33:32.297  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 10:33:32.302  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:33:32.303  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 10:33:32.303  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:33:32.305  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-14 10:33:32.305  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:32.305  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
10-14 10:33:32.305  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:32.305  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-14 10:33:32.305  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-14 10:33:32.306  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:32.306  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:32.309  5766  5794 D BtGatt.GattService: registerClient() - UUID=341e9456-bc0d-4c2e-b171-0bbbbe9969e2
,10-14 10:33:32.310  5766  5782 D BtGatt.GattService: onClientRegistered() - UUID=341e9456-bc0d-4c2e-b171-0bbbbe9969e2, clientIf=5
10-14 10:33:32.311  5564  5574 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-14 10:33:32.313  5766  5784 D BtGatt.AdvertiseManager: message : 0
,10-14 10:33:32.315  5766  5784 D BtGatt.AdvertiseManager: starting multi advertising
,10-14 10:33:32.326  5766  5782 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-14 10:33:32.334  5766  5782 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-14 10:33:32.335  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-14 10:33:32.335  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-14 10:33:32.335  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-14 10:33:32.335  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-14 10:33:32.335  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-14 10:33:32.336  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 10:33:32.337  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-14 10:33:32.338  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-14 10:33:32.338  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-14 10:33:32.338  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-14 10:33:32.338  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-14 10:33:32.338  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:32.338  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-14 10:33:32.338  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:33:32.338  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-14 10:33:32.338  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-14 10:33:32.340  5564  5564 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-14 10:33:32.340  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-14 10:33:32.841  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-14 10:33:32.842  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-14 10:33:32.842  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:33:33.221   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:34.222   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:35.126  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:35.130  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:35.134  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:35.140  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:33:35.156  5824  5824 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 10:33:35.206   928  2917 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 10:33:35.208   928  2917 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-14 10:33:35.208   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:33:35.222   928  2917 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
10-14 10:33:35.223   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:35.255   928  2917 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 10:33:35.587  5824  5824 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 10:33:35.621  5824  5824 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 10:33:35.623  5824  5824 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 10:33:35.631   928  2917 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 10:33:35.631   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 10:33:35.632   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-14 10:33:35.650   928  2917 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:33:35.665   508   922 D CommandListener: Setting iface cfg
,10-14 10:33:35.672   928  2917 D WifiStateMachine: Start Dhcp Watchdog 3
,10-14 10:33:35.678   928  5831 D DhcpClient: Receive thread started
,10-14 10:33:35.682   928  2919 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-14 10:33:35.683   928  2917 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-14 10:33:35.683   928  2919 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-14 10:33:35.763   928  2917 E native  : do suspend false
,10-14 10:33:35.778   928  5830 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 10:33:35.796   928  5831 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172583, domain null,
,10-14 10:33:35.797   928  5830 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172583 seconds
,10-14 10:33:35.800   928  5830 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 10:33:35.824   928  5831 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 10:33:35.825   928  5830 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 10:33:35.828   508   922 D CommandListener: Setting iface cfg
,10-14 10:33:35.834   928  2917 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 10:33:35.839   928  5830 D DhcpClient: Scheduling renewal in 86399s
,10-14 10:33:35.840  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-14 10:33:35.841  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 10:33:35.841  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-14 10:33:35.841  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-14 10:33:35.841  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-14 10:33:35.842  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-14 10:33:35.842  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-14 10:33:35.842  5564  5826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-14 10:33:35.842  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 10:33:35.842  5564  5826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 10:33:35.842  5564  5826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-14 10:33:35.842  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:33:35.843  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-14 10:33:35.843  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 10:33:35.843  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:33:35.843  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:33:35.843  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:33:35.848   928  2917 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-14 10:33:35.848  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:35.848  5564  5610 D BluetoothLeScanner: could not find callback wrapper
10-14 10:33:35.848  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:33:35.848  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-14 10:33:35.849   928  2917 D WifiConfigStore: No blacklist allowed without epno enabled
,10-14 10:33:35.850   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-14 10:33:35.850  5766  5784 D BtGatt.AdvertiseManager: message : 1
10-14 10:33:35.853  5766  5784 D BtGatt.AdvertiseManager: stop advertise for client 5
10-14 10:33:35.862   928  2919 D ConnectivityService: Adding iface wlan0 to network 102
10-14 10:33:35.868   928  2917 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-14 10:33:35.873  5766  5782 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-14 10:33:35.874  5766  5782 D BtGatt.GattService: Client app is not null!
10-14 10:33:35.875  5766  5803 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:33:35.875  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:33:35.875  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-14 10:33:35.875  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:35.875  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-14 10:33:35.875  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:35.875  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:33:35.876  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-14 10:33:35.876  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-14 10:33:35.876  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-14 10:33:35.878  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:35.878  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:33:35.878  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:33:35.878  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:33:35.880  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:33:35.880  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-14 10:33:35.880  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-14 10:33:35.880  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 10:33:35.882  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:35.882  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:35.882  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:35.888  5564  5610 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
10-14 10:33:35.889  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:33:35.889  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:33:35.890  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 10:33:35.890  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 10:33:35.890  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:35.890  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:33:35.893  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:33:35.893  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 10:33:35.898  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 10:33:35.899  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:33:35.899  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:33:35.904  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 10:33:35.904  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 10:33:35.904  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:33:35.904   928  2919 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-14 10:33:35.904   928  2919 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-14 10:33:35.905  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:33:35.905  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:33:35.906  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:35.908  5766  5777 D BtGatt.GattService: registerClient() - UUID=8a2e9295-5965-47a1-b55b-26b1a48f1a63
10-14 10:33:35.909  5766  5782 D BtGatt.GattService: onClientRegistered() - UUID=8a2e9295-5965-47a1-b55b-26b1a48f1a63, clientIf=5
10-14 10:33:35.909  5564  5575 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 10:33:35.910  5766  5794 D BtGatt.GattService: start scan with filters
10-14 10:33:35.911   928  2919 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-14 10:33:35.913   928  2919 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-14 10:33:35.914   928  2919 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-14 10:33:35.916  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-14 10:33:35.916  5766  5785 D BtGatt.ScanManager: handling starting scan
10-14 10:33:35.916  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:33:35.916  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:35.916  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:33:35.916  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:33:35.916  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:33:35.916  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 10:33:35.918  5766  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e6827e
10-14 10:33:35.919  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:33:35.919  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:33:35.919  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:33:35.920  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 10:33:35.925   928  2919 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 10:33:35.927  5766  5782 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 10:33:35.927  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:35.927  5766  5785 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 10:33:35.929   928  2919 D ConnectivityService: scheduleUnvalidatedPrompt 102
10-14 10:33:35.930   928  2919 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,10-14 10:33:35.930   928  2919 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-14 10:33:35.930   928  2917 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-14 10:33:35.930   928  2919 D ConnectivityService:    accepting network in place of null
10-14 10:33:35.930   928  2917 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 10:33:35.930   928  2919 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-14 10:33:35.933  5766  5782 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 10:33:35.933  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:35.933  5766  5785 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:33:35.933  5766  5785 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-14 10:33:35.942  5766  5782 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-14 10:33:35.942  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:33:35.944   928  5829 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258080, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 10:33:35.946  5766  5782 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 10:33:35.947  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:33:35.952   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:33:35.970   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:33:35.973   928  2919 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-14 10:33:35.973  3719  3833 W QCNEJ   : |CORE| network available: 102
10-14 10:33:35.973   928  2919 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 10:33:35.974   928  2919 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-14 10:33:35.975   928   945 D Tethering: MasterInitialState.processMessage what=3
10-14 10:33:35.979  3719  3833 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-14 10:33:35.981  3719  3833 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-14 10:33:35.982  3719  3833 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:35.983  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:33:35.985  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:35.988  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:33:35.988  4982  5003 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 10:33:35.989  4982  5003 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 10:33:35.989  4982  5003 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,10-14 10:33:35.989  4982  5003 E SarControlService: no key has been found,reset the power
10-14 10:33:35.989  4982  5017 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 10:33:35.989  4982  5017 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 10:33:35.989  4982  5017 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 10:33:35.990  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:33:35.990  5007  5007 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 10:33:35.990  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:35.991  4982  5017 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 10:33:35.991  4982  5017 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-14 10:33:35.991  4982  5017 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 10:33:35.992  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:33:35.992  5007  5007 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:33:35.993  5564  5564 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:33:35.995  5564  5564 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:33:35.997  3883  3883 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 10:33:35.998  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@51195e8 HexData = [00000000ec03000000000000ffffffff]
,10-14 10:33:35.998  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:33:35.998  5007  5021 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-14 10:33:35.999  5007  5021 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@51195e8 HexData = [00000000ed03000000000000ffffffff]
10-14 10:33:36.000  5007  5021 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:33:36.000  5007  5021 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-14 10:33:36.002  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:33:36.002  4982  4992 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 10:33:36.003  3883  3883 D SystemUpdateService: onCreate
10-14 10:33:36.003  5007  5007 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:33:36.004  4982  4993 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 10:33:36.006  3883  3883 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 10:33:36.017  3883  3883 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-14 10:33:36.023  3883  5339 I iu.UploadsManager: num queued entries: 0
,10-14 10:33:36.023  3883  5339 I iu.UploadsManager: num updated entries: 0
,10-14 10:33:36.024  3883  5339 I iu.SyncManager: NEXT; no task
,10-14 10:33:36.026  3883  5843 I SystemUpdateService: active receiver: enabled
,10-14 10:33:36.029  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-14 10:33:36.030  3883  3883 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 10:33:36.032  5344  5344 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:33:36.035  5344  5344 D SprintDMHelper: simOperator: 
10-14 10:33:36.035  5344  5344 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 10:33:36.056  3883  5843 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 10:33:36.068  3883  5843 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-14 10:33:36.068  3883  5843 I SystemUpdateService: now status is 0 (complete)
10-14 10:33:36.068  3883  5843 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 10:33:36.068  3883  5843 I SystemUpdateService: file has been verified
10-14 10:33:36.068  3883  5843 I SystemUpdateService: OTA package size = 21989297
,10-14 10:33:36.075  3883  5843 I SystemUpdateService: showing system update notification
,10-14 10:33:36.084  3883  3883 D SystemUpdateService: onDestroy
,10-14 10:33:36.093   928  5828 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.100,2a00:1450:400c:c0c::8a
,10-14 10:33:36.223   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 10:33:36.224  4957  5848 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-14 10:33:36.227   928  5828 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 14:33:36 GMT], X-Android-Received-Millis=[1476455616225], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476455616178]}
,10-14 10:33:36.229   928  2919 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-14 10:33:36.230   928  2919 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-14 10:33:36.230   928  2919 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-14 10:33:36.234   928  2919 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-14 10:33:36.420  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 10:33:36.420  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:33:36.420  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:33:36.448  5766  5766 D BtGatt.ScanManager: awakened up at time 258584
,10-14 10:33:36.449  5766  5785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 10:33:36.464  5766  5782 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,10-14 10:33:36.464  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:36.464  5766  5782 D BtGatt.GattService: current time is 258600580025
10-14 10:33:36.465  5766  5782 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 85, -113, -37, 31, -33, 8, 0, -128, -86, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0]
10-14 10:33:36.466  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 10:33:36.467  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
10-14 10:33:36.467  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
,10-14 10:33:36.472  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
,10-14 10:33:36.472  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-14 10:33:36.472  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=08:DF:1F:DB:8F:55, mScanRecord=ScanRecord [mAdvertiseFlags=2, mServiceUuids=[0000febe-0000-1000-8000-00805f9b34fb], mManufacturerSpecificData={272=[64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=258551058462}
10-14 10:33:36.473  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-14 10:33:36.473  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=258101058462}
10-14 10:33:36.473  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-14 10:33:36.474  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=258201058462}
,10-14 10:33:36.974   928  2919 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-14 10:33:38.925  5564  5610 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,10-14 10:33:38.925  5564  5610 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-14 10:33:38.926  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 10:33:38.926  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:33:38.929  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:38.932  5766  5796 D BtGatt.GattService: stopScan() - queue size =1
10-14 10:33:38.934  5766  5777 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-14 10:33:38.935  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:33:38.935  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:38.935  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 10:33:38.935  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 10:33:38.936  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 10:33:38.936  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:33:38.936  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:33:38.936  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:33:38.939  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:38.940  5766  5766 D BtGatt.ScanManager: awakened up at time 261076
10-14 10:33:38.944  5766  5776 D BtGatt.GattService: registerClient() - UUID=b159a5b7-6310-45fc-8b22-a091031f32d5
10-14 10:33:38.945  5766  5782 D BtGatt.GattService: onClientRegistered() - UUID=b159a5b7-6310-45fc-8b22-a091031f32d5, clientIf=5
10-14 10:33:38.945  5766  5782 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:33:38.945  5564  5575 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 10:33:38.945  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:33:38.945  5766  5803 D BtGatt.GattService: start scan with filters
,10-14 10:33:38.946  5766  5785 D BtGatt.ScanManager: stopping BLe Batch
10-14 10:33:38.948  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 10:33:38.948  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-14 10:33:38.948  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:38.949  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:33:38.949  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:33:38.949  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:38.949  5564  5610 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-14 10:33:38.949  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 10:33:38.949  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:33:38.950  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-14 10:33:38.950  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 10:33:38.950  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 10:33:38.951  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-14 10:33:38.951  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 10:33:38.951  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-14 10:33:38.951  5564  5855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 10:33:38.951  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 10:33:38.952  5564  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:33:38.952  5766  5782 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 10:33:38.952  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:38.952  5564  5610 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:33:38.953  5766  5785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 10:33:38.955  5564  5855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-14 10:33:38.951  5776  5776 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35893]" dev="sockfs" ino=35893 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:33:38.951  5776  5776 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35893]" dev="sockfs" ino=35893 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 10:33:38.961  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,10-14 10:33:38.961  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-14 10:33:38.961  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:33:38.961  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
10-14 10:33:38.962  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:38.962  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-14 10:33:38.962  5564  5610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-14 10:33:38.962  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-14 10:33:38.962  5564  5610 D BluetoothAdapter: STATE_ON
,10-14 10:33:38.965  5766  5776 D BtGatt.GattService: registerClient() - UUID=d61943f0-24ab-4bcf-a0a6-117accd84946
10-14 10:33:38.966  5766  5782 D BtGatt.GattService: onClientRegistered() - UUID=d61943f0-24ab-4bcf-a0a6-117accd84946, clientIf=6
,10-14 10:33:38.966  5564  5692 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
10-14 10:33:38.967  5766  5784 D BtGatt.AdvertiseManager: message : 0
,10-14 10:33:38.969  5766  5784 D BtGatt.AdvertiseManager: starting multi advertising
,10-14 10:33:38.971  5766  5782 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-14 10:33:38.971  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:38.971  5766  5782 D BtGatt.GattService: current time is 261107542167
10-14 10:33:38.972  5766  5782 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -81, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -87, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -75, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -83, 40, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -78, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-14 10:33:38.972  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 10:33:38.972  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
10-14 10:33:38.972  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
10-14 10:33:38.972  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
10-14 10:33:38.973  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 10:33:38.973  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
10-14 10:33:38.973  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 10:33:38.973  5766  5785 D BtGatt.ScanManager: handling starting scan
,10-14 10:33:38.981  5766  5782 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-14 10:33:38.985  5766  5782 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 10:33:38.985  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:33:38.985  5766  5785 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 10:33:38.990  5766  5782 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,10-14 10:33:38.990  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-14 10:33:38.990  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-14 10:33:38.990  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-14 10:33:38.990  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
,10-14 10:33:38.990  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:33:38.990  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-14 10:33:38.991  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser, adv = true, disc = true
10-14 10:33:38.991  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:33:38.992  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:33:38.994  5766  5782 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 10:33:38.995  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:38.995  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-14 10:33:38.995  5766  5785 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:33:38.995  5766  5785 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 10:33:38.995  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-14 10:33:38.995  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-14 10:33:38.995  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-14 10:33:38.995  5564  5564 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-14 10:33:38.995  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:38.995  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-14 10:33:38.996  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:33:38.996  5564  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
10-14 10:33:38.996  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,10-14 10:33:38.998  5564  5564 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-14 10:33:38.998  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-14 10:33:39.005  5766  5782 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-14 10:33:39.005  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:33:39.010  5766  5782 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-14 10:33:39.010  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:33:39.379   928  2917 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 17 -> obsolete
,10-14 10:33:39.499  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-14 10:33:39.500  5564  5564 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-14 10:33:39.500  5564  5564 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:33:41.721   928  2919 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 10:33:41.918   928  2917 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 17 -> obsolete
,10-14 10:33:41.999  5564  5610 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-14 10:33:42.000  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:33:42.000  5564  5610 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-14 10:33:42.000  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 10:33:42.000  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 10:33:42.001  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:33:42.001  5564  5855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-14 10:33:42.001  5564  5855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 10:33:42.001  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-14 10:33:42.001  5564  5610 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-14 10:33:42.001  5564  5855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 10:33:42.002  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-14 10:33:42.002  5564  5564 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 10:33:42.002  5564  5610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90caf25 removed from the list
10-14 10:33:42.002  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 10:33:42.002  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:33:42.002  5564  5564 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:33:42.002  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:33:42.002  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:33:42.003  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:33:42.003  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:33:42.003  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 10:33:42.005  5564  5610 D BluetoothAdapter: STATE_ON
10-14 10:33:42.007  5766  5777 D BtGatt.GattService: stopScan() - queue size =1
10-14 10:33:42.008  5766  5796 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:33:42.009  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:33:42.009  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:42.010  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 10:33:42.010  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:33:42.010  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,10-14 10:33:42.010  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-14 10:33:42.010  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
10-14 10:33:42.010  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
10-14 10:33:42.016  5766  5766 D BtGatt.ScanManager: awakened up at time 264151
10-14 10:33:42.018  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-14 10:33:42.019  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-14 10:33:42.020  5766  5784 D BtGatt.AdvertiseManager: message : 1
10-14 10:33:42.020  5766  5784 D BtGatt.AdvertiseManager: stop advertise for client 6
,10-14 10:33:42.022  5766  5782 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:33:42.022  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:42.023  5766  5785 D BtGatt.ScanManager: stopping BLe Batch
,10-14 10:33:42.030  5766  5782 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,10-14 10:33:42.030  5766  5782 D BtGatt.GattService: Client app is not null!
,10-14 10:33:42.031  5766  5794 D BtGatt.GattService: unregisterClient() - clientIf=6
10-14 10:33:42.031  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:33:42.031  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-14 10:33:42.031  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-14 10:33:42.031  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-14 10:33:42.032  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-14 10:33:42.032  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-14 10:33:42.032  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-14 10:33:42.032  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-14 10:33:42.032  5564  5610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-14 10:33:42.033  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:33:42.033  5564  5610 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:33:42.033  5564  5610 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:33:42.034  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:33:42.036  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:33:42.036  5564  5610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36208fa removed from the list
10-14 10:33:42.037  5564  5610 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:33:42.037  5564  5564 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:33:42.037  5564  5610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:33:42.037  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-14 10:33:42.037  5564  5564 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:33:42.039  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,10-14 10:33:42.039  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-14 10:33:42.039  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-14 10:33:42.039  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-14 10:33:42.039  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:33:42.039  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,10-14 10:33:42.040  5564  5610 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 10:33:42.040  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,10-14 10:33:42.041  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,10-14 10:33:42.042  5766  5782 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 10:33:42.042  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:42.042  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
10-14 10:33:42.042  5766  5785 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 10:33:42.043  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-14 10:33:42.044  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-14 10:33:42.044  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,10-14 10:33:42.045  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,10-14 10:33:42.046  5564  5610 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-14 10:33:42.065  5766  5782 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,10-14 10:33:42.065  5766  5782 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:33:42.065  5766  5782 D BtGatt.GattService: current time is 264201142093
10-14 10:33:42.065  5766  5782 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -89, 13, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -83, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -90, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 50, -35, 86, -77, -92, -11, 1, -128, -98, 27, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -60, 3, 42, 3, 1, -37, 18, -106, 119, 4, 114, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
10-14 10:33:42.066  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
10-14 10:33:42.066  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-14 10:33:42.066  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-14 10:33:42.066  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 10:33:42.066  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 10:33:42.066  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -60, 3, 42, 3, 1, -37, 18, -106, 119, 4, 114]
10-14 10:33:42.067  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-14 10:33:42.067  5766  5782 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,10-14 10:33:42.536  5564  5564 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:33:43.932   928  2919 D ConnectivityService: handlePromptUnvalidated 102
,10-14 10:33:44.051  5564  5610 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-14 10:33:44.196  5564  5857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 10:33:44.196  5564  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:33:44.737   928  2919 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 10:33:45.039  5564  5857 W !!      : call onHalfStreamCopied
,10-14 10:33:45.039  5564  5857 I testCopyDataAndClose: closing input stream
,10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 10:33:45.816  5564  5857 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 10:33:47.009   928  2917 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,10-14 10:33:49.601  5564  5610 I StreamCopyingThreadTest: Starting test: testRun
,10-14 10:33:49.605  5564  5858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:33:49.605  5564  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:33:51.225   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:52.226   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:53.228   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:54.229   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:54.612  5564  5859 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-14 10:33:54.614  5564  5610 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-14 10:33:54.764  5564  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 10:33:54.764  5564  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:33:55.231   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:33:56.231   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 10:33:56.387  5564  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 10:34:00.130  5564  5610 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:34:00.131  5564  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-14 10:34:00.132  5564  5610 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-14 10:34:00.132  5564  5610 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-14 10:34:00.133  5564  5610 I StreamCopyingThreadTest: Starting test: testRunWithException
,10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:34:00.134  5564  5862 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:34:00.134  5564  5862 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-14 10:34:00.135  5564  5610 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
10-14 10:34:00.135  5564  5610 E com.test.thalitest.ThaliTestRunner: 
10-14 10:34:00.135  5564  5610 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-14 10:34:00.135  5564  5610 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.ParentRunner.run(ParentRunner.java:363)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-14 1,0:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-14 10:34:00.136  5564  5610 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runne,rs.ParentRunner.runChildren(ParentRunner.java:288)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:00.137  5564  5610 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-14 10:34:00.138  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG UnitTest_app: 'Running unit tests'
10-14 10:34:00.138  5564  5610 I jxcore-log: 
10-14 10:34:00.138  5564  5610 I jxcore-log: *Native tests were executed*
10-14 10:34:00.138  5564  5610 I jxcore-log: 
10-14 10:34:00.138  5564  5610 I jxcore-log: Total number of executed tests:  82
10-14 10:34:00.138  5564  5610 I jxcore-log: 
10-14 10:34:00.138  5564  5610 I jxcore-log: Number of passed tests:  80
10-14 10:34:00.138  5564  5610 I jxcore-log: 
10-14 10:34:00.138  5564  5610 I jxcore-log: Number of failed tests:  2
10-14 10:34:00.138  5564  5610 I jxcore-log: 
10-14 10:34:00.139  5564  5610 I jxcore-log: Number of ignored tests:  0
10-14 10:34:00.139  5564  5610 I jxcore-log: 
10-14 10:34:00.1,39  5564  5610 I jxcore-log: Total duration:  41498
10-14 10:34:00.139  5564  5610 I jxcore-log: 
10-14 10:34:00.139  5564  5610 I jxcore-log: Failed to execute UT.
10-14 10:34:00.139  5564  5610 I jxcore-log: 
10-14 10:34:00.140  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-14 10:34:00.140  5564  5610 I jxcore-log: 
10-14 10:34:00.141  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-14 10:34:00.141  5564  5610 I jxcore-log: 
10-14 10:34:00.144  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.144  5564  5610 I jxcore-log: 
10-14 10:34:00.145  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.145  5564  5610 I jxcore-log: 
10-14 10:34:00.145  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.145  5564  5610 I jxcore-log: 
,10-14 10:34:00.146  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-14 10:34:00.146  5564  5610 I jxcore-log: 
10-14 10:34:00.146  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-14 10:34:00.146  5564  5610 I jxcore-log: 
10-14 10:34:00.147  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-14 10:34:00.147  5564  5610 I jxcore-log: 
10-14 10:34:00.147  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:34:00.147  5564  5610 I jxcore-log: 
10-14 10:34:00.147  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.147  5564  5610 I jxcore-log: 
10-14 10:34:00.148  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:34:00.148  5564  5610 I jxcore-log: 
10-14 10:34:00.148  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:34:00.148  5564  5610 I jxcore-log: 
10-14 10:34:00.148  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:34:00.148  5564  5610 I jxcore-log: 
,10-14 10:34:00.149  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:34:00.149  5564  5610 I jxcore-log: 
10-14 10:34:00.149  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.149  5564  5610 I jxcore-log: 
10-14 10:34:00.149  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.149  5564  5610 I jxcore-log: 
10-14 10:34:00.149  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.149  5564  5610 I jxcore-log: 
10-14 10:34:00.150  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.150  5564  5610 I jxcore-log: 
,10-14 10:34:00.150  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.150  5564  5610 I jxcore-log: 
10-14 10:34:00.150  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.150  5564  5610 I jxcore-log: 
10-14 10:34:00.150  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.150  5564  5610 I jxcore-log: 
10-14 10:34:00.151  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.151  5564  5610 I jxcore-log: 
10-14 10:34:00.151  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.151  5564  5610 I jxcore-log: 
10-14 10:34:00.151  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.151  5564  5610 I jxcore-log: 
10-14 10:34:00.151  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.151  5564  5610 I jxcore-log: 
10-14 10:34:00.152  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.152  5564  5610 I jxcore-log: 
10-14 10:34:00.152  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.152  5564  5610 I jxcore-log: 
,10-14 10:34:00.152  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.152  5564  5610 I jxcore-log: 
,10-14 10:34:00.153  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.153  5564  5610 I jxcore-log: 
10-14 10:34:00.154  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:34:00.154  5564  5610 I jxcore-log: 
10-14 10:34:00.154  5564  5564 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-14 10:34:00.154  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:34:00.154  5564  5610 I jxcore-log: 
10-14 10:34:00.154  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:34:00.154  5564  5610 I jxcore-log: 
10-14 10:34:00.155  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.155  5564  5610 I jxcore-log: 
10-14 10:34:00.155  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.155  5564  5610 I jxcore-log: 
10-14 10:34:00.155  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.155  5564  5610 I jxcore-log: 
10-14 10:34:00.155  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:34:00.155  5564  5610 I jxcore-log: 
,10-14 10:34:00.155  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-14 10:34:00.155  5564  5610 I jxcore-log: 
10-14 10:34:00.156  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.156  5564  5610 I jxcore-log: 
10-14 10:34:00.156  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.156  5564  5610 I jxcore-log: 
10-14 10:34:00.156  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:34:00.156  5564  5610 I jxcore-log: 
10-14 10:34:00.156  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 10:34:00.156  5564  5610 I jxcore-log: 
10-14 10:34:00.157  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
10-14 10:34:00.157  5564  5610 I jxcore-log: 
10-14 10:34:00.157  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:34:00.157  5564  5610 I jxcore-log: 
,10-14 10:34:00.162  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-14 10:34:00.162  5564  5610 I jxcore-log: 
10-14 10:34:00.162  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - WARN testUtils: 'myNameCallback not set!'
10-14 10:34:00.162  5564  5610 I jxcore-log: 
,10-14 10:34:00.163  5564  5610 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-14 10:34:00.164  5564  5610 I jxcore-log: 2016-10-14 14:34:00 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-14 10:34:00.164  5564  5610 I jxcore-log: 
,10-14 10:34:02.189  5564  5610 I jxcore-log: 2016-10-14 14:34:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-14 10:34:02.189  5564  5610 I jxcore-log: 
,10-14 10:34:02.532  5564  5610 I jxcore-log: 2016-10-14 14:34:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-14 10:34:02.532  5564  5610 I jxcore-log: 
,10-14 10:34:02.545  5564  5610 I jxcore-log: 2016-10-14 14:34:02 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-14 10:34:02.545  5564  5610 I jxcore-log: 
,10-14 10:34:03.654  5564  5610 I jxcore-log: 2016-10-14 14:34:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-14 10:34:03.654  5564  5610 I jxcore-log: 
,10-14 10:34:03.801  5564  5610 I jxcore-log: 2016-10-14 14:34:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-14 10:34:03.801  5564  5610 I jxcore-log: 
,10-14 10:34:03.806  5564  5610 I jxcore-log: 2016-10-14 14:34:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-14 10:34:03.806  5564  5610 I jxcore-log: 
,10-14 10:34:03.811  5564  5610 I jxcore-log: 2016-10-14 14:34:03 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-14 10:34:03.811  5564  5610 I jxcore-log: 
,10-14 10:34:04.372  5564  5610 I jxcore-log: 2016-10-14 14:34:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-14 10:34:04.372  5564  5610 I jxcore-log: 
,10-14 10:34:04.425  5564  5610 I jxcore-log: 2016-10-14 14:34:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-14 10:34:04.425  5564  5610 I jxcore-log: 
,10-14 10:34:04.437  5564  5610 I jxcore-log: 2016-10-14 14:34:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-14 10:34:04.437  5564  5610 I jxcore-log: 
,10-14 10:34:04.442  5564  5610 I jxcore-log: 2016-10-14 14:34:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-14 10:34:04.442  5564  5610 I jxcore-log: 
,10-14 10:34:04.721  5564  5610 I jxcore-log: 2016-10-14 14:34:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-14 10:34:04.721  5564  5610 I jxcore-log: 
,10-14 10:34:04.846  5564  5610 I jxcore-log: 2016-10-14 14:34:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-14 10:34:04.846  5564  5610 I jxcore-log: 
,10-14 10:34:05.077  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-14 10:34:05.077  5564  5610 I jxcore-log: 
,10-14 10:34:05.087  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-14 10:34:05.087  5564  5610 I jxcore-log: 
,10-14 10:34:05.091  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-14 10:34:05.091  5564  5610 I jxcore-log: 
,10-14 10:34:05.225  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-14 10:34:05.225  5564  5610 I jxcore-log: 
,10-14 10:34:05.233  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-14 10:34:05.233  5564  5610 I jxcore-log: 
,10-14 10:34:05.260  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-14 10:34:05.260  5564  5610 I jxcore-log: 
,10-14 10:34:05.293  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-14 10:34:05.293  5564  5610 I jxcore-log: 
,10-14 10:34:05.300  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-14 10:34:05.300  5564  5610 I jxcore-log: 
,10-14 10:34:05.306  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-14 10:34:05.306  5564  5610 I jxcore-log: 
,10-14 10:34:05.319  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-14 10:34:05.319  5564  5610 I jxcore-log: 
,10-14 10:34:05.323  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-14 10:34:05.323  5564  5610 I jxcore-log: 
,10-14 10:34:05.328  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-14 10:34:05.328  5564  5610 I jxcore-log: 
,10-14 10:34:05.333  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-14 10:34:05.333  5564  5610 I jxcore-log: 
,10-14 10:34:05.345  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-14 10:34:05.345  5564  5610 I jxcore-log: 
,10-14 10:34:05.364  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-14 10:34:05.364  5564  5610 I jxcore-log: 
,10-14 10:34:05.372  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-14 10:34:05.372  5564  5610 I jxcore-log: 
,10-14 10:34:05.383  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-14 10:34:05.383  5564  5610 I jxcore-log: 
,10-14 10:34:05.392  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-14 10:34:05.392  5564  5610 I jxcore-log: 
,10-14 10:34:05.404  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-14 10:34:05.404  5564  5610 I jxcore-log: 
,10-14 10:34:05.415  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-14 10:34:05.415  5564  5610 I jxcore-log: 
,10-14 10:34:05.420  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-14 10:34:05.420  5564  5610 I jxcore-log: 
,10-14 10:34:05.440  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-14 10:34:05.440  5564  5610 I jxcore-log: 
,10-14 10:34:05.446  5564  5610 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-14 10:34:05.447  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - INFO testUtils: 'BLE multiple advertisement supported'
10-14 10:34:05.447  5564  5610 I jxcore-log: 
,10-14 10:34:05.541  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - DEBUG CoordinatedClient: 'connected to the test server'
10-14 10:34:05.541  5564  5610 I jxcore-log: 
,10-14 10:34:05.632  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-14 10:34:05.632  5564  5610 I jxcore-log: 
,10-14 10:34:05.632  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - DEBUG CoordinatedClient: 'test client failed'
10-14 10:34:05.632  5564  5610 I jxcore-log: 
,10-14 10:34:05.633  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-14 10:34:05.633  5564  5610 I jxcore-log: 
10-14 10:34:05.635  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-14 10:34:05.635  5564  5610 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-14 10:34:05.635  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-14 10:34:05.635  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-14 10:34:05.635  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-14 10:34:05.635  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-14 10:34:05.635  5564  5610 I jxcore-log: 
10-14 10:34:05.635  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-14 10:34:05.635  5564  5610 I jxcore-log: 
,10-14 10:34:05.636  5564  5610 I jxcore-log: 2016-10-14 14:34:05 - ERROR runTests: 'Test client failed: Native unit tests failed
10-14 10:34:05.636  5564  5610 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-14 10:34:05.636  5564  5610 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-14 10:34:05.636  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-14 10:34:05.636  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-14 10:34:05.636  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-14 10:34:05.636  5564  5610 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
10-14 10:34:05.636  5564  5610 I jxcore-log: 
,10-14 10:34:06.192  5871  5871 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-14 10:34:06.215  5871  5871 D AndroidRuntime: CheckJNI is OFF
,10-14 10:34:06.245  5871  5871 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-14 10:34:06.275  5871  5871 I Radio-JNI: register_android_hardware_Radio DONE
,10-14 10:34:06.290  5871  5871 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-14 10:34:06.297   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-14 10:34:06.297   928   941 I ActivityManager: Killing 5564:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-14 10:34:06.406   928  3363 I WindowState: WIN DEATH: Window{2e9ec6b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-14 10:34:06.406   928  2918 D WifiService: Client connection lost with reason: 4
10-14 10:34:06.407   928  3068 D GraphicsStats: Buffer count: 2
,10-14 10:34:06.431   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-14 10:34:06.432   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-14 10:34:06.433   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-14 10:34:06.433   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-14 10:34:06.433   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:34:06.433   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:06.433   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:34:06.433   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-14 10:34:06.434   928   941 I ActivityManager:   Force finishing activity ActivityRecord{bfbe97c u0 com.test.thalitest/.MainActivity t2}
10-14 10:34:06.435   928   951 I art     : Starting a blocking GC Explicit
,10-14 10:34:06.444   928   939 W ActivityManager: Spurious death for ProcessRecord{c6c7a5 0:com.test.thalitest/u0a77}, curProc for 5564: null
,10-14 10:34:06.470   382   408 E BufferQueueProducer: [Starting com.test.thalitest] connect(P): BufferQueue has been abandoned
10-14 10:34:06.471   928   946 E ViewRootImpl: Could not lock surface
10-14 10:34:06.471   928   946 E ViewRootImpl: java.lang.IllegalArgumentException
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.Surface.nativeLockCanvas(Native Method)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.Surface.lockCanvas(Surface.java:264)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.ViewRootImpl.drawSoftware(ViewRootImpl.java:2676)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.ViewRootImpl.draw(ViewRootImpl.java:2650)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.ViewRootImpl.performDraw(ViewRootImpl.java:2442)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2075)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1115)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6023)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.Choreographer.doFrame(Choreographer.java:606)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:34:06.471   928   946 E ViewRootImpl: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-14 10:34:06.471   928   946 W WindowManager: Failed looking up window
10-14 10:34:06.471   928   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@c7fdd0f does not exist
10-14 10:34:06.471   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-14 10:34:06.471   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-14 10:34:06.471   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.finishDrawingWindow(WindowManagerService.java:3449)
10-14 10:34:06.471   928   946 W WindowManager: 	at com.android.server.wm.Session.finishDrawing(Session.java:232)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.ViewRootImpl.performDraw(ViewRootImpl.java:2480)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2075)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1115)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6023)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:606)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.j,ava:148)
10-14 10:34:06.471   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:34:06.471   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-14 10:34:06.472   928   946 W WindowManager: Failed looking up window
10-14 10:34:06.472   928   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@c7fdd0f does not exist
10-14 10:34:06.472   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-14 10:34:06.472   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-14 10:34:06.472   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-14 10:34:06.472   928   946 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-14 10:34:06.472   928   946 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-14 10:34:06.472   928   946 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-14 10:34:06.472   928   946 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-14 10:34:06.472   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:34:06.472   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:06.472   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:34:06.472   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-14 10:34:06.514   928   951 I art     : Explicit concurrent mark sweep GC freed 49577(3MB) AllocSpace objects, 20(644KB) LOS objects, 33% free, 28MB/43MB, paused 1.476ms total 79.165ms
,10-14 10:34:06.533   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-14 10:34:06.536  5871  5871 I art     : System.exit called, status: 0
,10-14 10:34:06.536  5871  5871 I AndroidRuntime: VM exiting with result code 0.
,10-14 10:34:06.543   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-14 10:34:06.551   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-14 10:34:06.558  5766  5766 D BluetoothMapAppObserver: onReceive
10-14 10:34:06.558   928  2881 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-14 10:34:06.558  5766  5766 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-14 10:34:06.561  4067  4129 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-14 10:34:06.562  3628  3628 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-14 10:34:06.588  3628  5883 I Keyboard.Facilitator.DecoderInitializer: run()
,10-14 10:34:06.599  3755  3755 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-14 10:34:06.614  3346  5884 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-14 10:34:06.617  3516  3516 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-14 10:34:06.618  3516  3516 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-14 10:34:06.625   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-14 10:34:06.630  3628  5883 I Decoder : createOrResetDecoder
,10-14 10:34:06.636  3883  5888 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-14 10:34:06.637  3883  5888 D AccountUtils: Clearing selected account for com.test.thalitest
,10-14 10:34:06.672  3516  3516 I ConfigService: onCreate
,10-14 10:34:06.671    13    13 W kworker/1:0: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:34:06.675    13    13 W kworker/1:0: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:34:06.685    13    13 W kworker/1:0: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:34:06.698  3883  5888 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-14 10:34:06.706  3628  5883 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-14 10:34:06.715  3346  3373 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj5E0156984) - 
,10-14 10:34:06.735  3883  5888 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:06.735  3883  5888 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:06.736  3883  5888 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:34:06.737  3883  5888 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-14 10:34:06.774  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,10-14 10:34:06.774  3883  3883 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,10-14 10:34:06.782  3883  3883 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,10-14 10:34:06.782  3883  3883 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,--------- beginning of crash
10-14 10:34:06.798  3346  3373 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-14 10:34:06.798  3346  3373 E AndroidRuntime: Process: android.process.acore, PID: 3346
10-14 10:34:06.798  3346  3373 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:34:06.798  3346  3373 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 10:34:06.815  4883  5897 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,10-14 10:34:06.828   928  5327 I ActivityManager: Start proc 5901:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,10-14 10:34:06.855  4883  5897 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,10-14 10:34:06.867  3346  3373 I Process : Sending signal. PID: 3346 SIG: 9
,10-14 10:34:06.875   928  3767 I ActivityManager: Start proc 5907:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-14 10:34:06.883  3883  5896 W BaseAppContext: Using Auth Proxy for data requests.
,10-14 10:34:06.889  3883  5896 W BaseAppContext: Using Auth Proxy for data requests.
,10-14 10:34:06.907  3883  3883 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,10-14 10:34:06.919  3883  5913 I GMPM-SVC: App measurement is starting up
,10-14 10:34:06.923  3883  5913 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-14 10:34:06.924  3883  5913 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-14 10:34:07.087   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
