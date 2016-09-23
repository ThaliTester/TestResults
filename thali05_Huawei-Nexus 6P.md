#### Test 863332464e64f14_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 09:23:06.018   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-23 09:23:06.018   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 09:23:06.537  5344  5344 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 09:23:06.542  5344  5344 D AndroidRuntime: CheckJNI is OFF
09-23 09:23:06.570  5344  5344 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 09:23:06.607  5344  5344 I Radio-JNI: register_android_hardware_Radio DONE
09-23 09:23:06.624  5344  5344 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 09:23:06.630   930  3073 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 09:23:06.680   930  3073 I ActivityManager: Start proc 5353:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 09:23:06.696  5344  5344 D AndroidRuntime: Shutting down VM
,09-23 09:23:07.026   930  3423 I WindowManager: Screenshot max retries 4 of Token{155d23 ActivityRecord{9af8652 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{5898daa u0 Starting com.test.thalitest} drawState=2
,09-23 09:23:07.092  5353  5353 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 09:23:07.125  5353  5353 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 09:23:07.150  5353  5353 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 645-665)
,09-23 09:23:07.151  5353  5353 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 09:23:07.170  5353  5353 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e82348}
,09-23 09:23:07.171  5353  5353 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 09:23:07.171  5353  5353 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-23 09:23:07.177  5353  5353 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 09:23:07.179  5353  5353 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 09:23:07.213  5353  5353 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 09:23:07.229  5353  5353 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 09:23:07.229  5353  5353 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 09:23:07.229  5353  5353 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 09:23:07.229  5353  5353 I Adreno  : Build Date                       : 12/06/15
09-23 09:23:07.229  5353  5353 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 09:23:07.229  5353  5353 I Adreno  : Local Branch                     : mybranch17112971
09-23 09:23:07.229  5353  5353 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 09:23:07.229  5353  5353 I Adreno  : Remote Branch                    : NONE
09-23 09:23:07.229  5353  5353 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 09:23:07.282   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee5e949:true
,09-23 09:23:07.308  3871  3871 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14282]" dev="sockfs" ino=14282 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 09:23:07.308  3871  3871 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[14282]" dev="sockfs" ino=14282 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 09:23:07.325  5353  5353 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 09:23:07.334  5353  5353 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 09:23:07.365  5353  5390 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-23 09:23:07.358  3871  3871 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31606]" dev="sockfs" ino=31606 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 09:23:07.358  3871  3871 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31606]" dev="sockfs" ino=31606 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 09:23:07.365  3335  3335 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14287]" dev="sockfs" ino=14287 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 09:23:07.365  3335  3335 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14287]" dev="sockfs" ino=14287 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 09:23:07.372  5353  5377 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 09:23:07.394  5353  5390 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 09:23:07.469   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +441ms (total +822ms)
,09-23 09:23:07.516  5353  5353 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5353
,09-23 09:23:07.606  5353  5353 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 09:23:07.741  5353  5392 D jxcore_app_log: JniHelper::setJavaVM(0xf4ffc000), pthread_self() = -565446352
,09-23 09:23:07.745  5353  5392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 09:23:07.745  5353  5392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 09:23:07.745  5353  5392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 09:23:07.745  5353  5392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 09:23:07.745  5353  5392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 09:23:07.745  5353  5392 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f59dd9 added. We now have 1 listener(s)
,09-23 09:23:07.747  5353  5392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 09:23:07.748  5353  5392 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:23:07.748  5353  5392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:23:07.748  5353  5392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 09:23:07.750  5353  5392 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d1e4c added. We now have 1 listener(s)
,09-23 09:23:07.750  5353  5392 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:07.759   930  2891 D WifiService: New client listening to asynchronous messages
,09-23 09:23:07.760  5353  5392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:23:07.760  5353  5392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 09:23:07.760  5353  5392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 09:23:07.760  5353  5392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 09:23:07.760  5353  5392 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 09:23:07.763  5353  5392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:07.763  5353  5392 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 09:23:07.767  5353  5392 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:07.767  5353  5392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:23:07.767  5353  5392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 09:23:07.767  5353  5392 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:23:07.768  5353  5392 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 09:23:07.772  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:07.776  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:07.784  5353  5353 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 09:23:08.091  5353  5399 W jxcore-log: Initializing JXcore engine
09-23 09:23:08.091  5353  5399 W jxcore-log: JXcore engine is ready
,09-23 09:23:08.112  5399  5399 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12739 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-23 09:23:08.112  5399  5399 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14387]" dev="sockfs" ino=14387 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 09:23:08.112  5399  5399 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-23 09:23:08.112  5399  5399 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30318]" dev="sockfs" ino=30318 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 09:23:08.124  5353  5399 W jxcore-log: Starting JXcore engine
,09-23 09:23:08.186  5353  5399 W jxcore-log: Platform android
09-23 09:23:08.186  5353  5399 W jxcore-log: 
,09-23 09:23:08.186  5353  5399 W jxcore-log: Process ARCH arm
09-23 09:23:08.186  5353  5399 W jxcore-log: 
,09-23 09:23:08.282  5353  5399 I jxcore-log: JXcore Cordova bridge is ready!
09-23 09:23:08.282  5353  5399 I jxcore-log: 
09-23 09:23:08.283  5353  5399 W jxcore-log: JXcore engine is started
,09-23 09:23:08.285   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:23:08.295  5353  5392 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 09:23:08.300  5353  5353 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 09:23:16.020   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:17.021   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:17.999  5353  5399 I jxcore-log: 2016-09-23 13:23:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 09:23:17.999  5353  5399 I jxcore-log: 
,09-23 09:23:18.001  5353  5399 I jxcore-log: 2016-09-23 13:23:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 09:23:18.001  5353  5399 I jxcore-log: 
,09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:18.004  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:23:18.006  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:23:18.008  5353  5399 I jxcore-log: 2016-09-23 13:23:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 09:23:18.008  5353  5399 I jxcore-log: 
,09-23 09:23:18.010  5353  5399 I jxcore-log: 2016-09-23 13:23:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 09:23:18.010  5353  5399 I jxcore-log: 
,09-23 09:23:18.022   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:18.258  5353  5399 I jxcore-log: Running unit tests
09-23 09:23:18.258  5353  5399 I jxcore-log: 
,09-23 09:23:18.259  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:23:18.259  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddf2906 added. We now have 2 listener(s)
09-23 09:23:18.260  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:23:18.260  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:23:18.260  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:23:18.260  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:23:18.260  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7287bc7 added. We now have 2 listener(s)
09-23 09:23:18.260  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:18.261  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:23:18.262  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:18.265  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:23:18.266  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:23:18.266  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:23:18.267  5353  5399 D executeNativeTests: Running unit tests
,09-23 09:23:18.273  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:18.280  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:18.305  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:23:18.305  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d added. We now have 3 listener(s)
,09-23 09:23:18.306  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 09:23:18.306  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:23:18.306  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:23:18.306  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:23:18.306  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 added. We now have 3 listener(s)
09-23 09:23:18.306  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:18.306  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:23:18.308  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:18.310  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:18.311  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:18.311  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:23:18.312  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 09:23:18.312  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 09:23:18.312  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:23:18.312  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:23:18.313  5353  5399 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 09:23:18.313  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 09:23:18.313  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-23 09:23:18.313  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:23:18.313  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:23:18.313  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:23:18.313  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:18.313  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:23:18.314  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-23 09:23:18.314  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:23:18.314  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.314  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:18.314  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:23:18.314  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d removed from the list
,09-23 09:23:18.314  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:18.314  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 removed from the list
,09-23 09:23:18.316  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:18.322  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:18.322  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:18.322  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.323  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.323  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.323  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:18.323  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:18.323  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:18.323  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
,09-23 09:23:18.324  5353  5399 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 09:23:18.324  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:18.324  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:18.324  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:18.324  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:18.324  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:18.325  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.325  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:18.325  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:18.325  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:18.325  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:18.325  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.325  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:18.325  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.325  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.325  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:18.325  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:18.325  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:18.325  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-23 09:23:18.328  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 09:23:18.329  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:18.329  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:18.329  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:18.329  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:18.329  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.329  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.329  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:18.329  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:18.329  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:18.329  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:18.329  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.329  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.329  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:18.329  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:18.330  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:18.330  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:18.330  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:18.330  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:18.330  5353  5399 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 09:23:18.331  5353  5399 I org.thaliproject.p2p.btconnect,orlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:18.333  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:18.334  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:18.334  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:23:18.334  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:23:18.334  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:23:18.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:23:18.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:18.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:18.338  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:18.340  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:23:18.340  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:23:18.341  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:18.342  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:23:18.343  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:23:18.343  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:23:18.344  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 09:23:18.347  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 09:23:18.347  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 09:23:18.348  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:23:18.348  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:23:18.349  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:18.351  4400  4610 D BtGatt.GattService: registerClient() - UUID=2678055b-7463-4636-bece-bc10e3b0b2a6
09-23 09:23:18.352  4400  4461 D BtGatt.GattService: onClientRegistered() - UUID=2678055b-7463-4636-bece-bc10e3b0b2a6, clientIf=5
09-23 09:23:18.352  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 09:23:18.353  4400  4412 D BtGatt.GattService: start scan with filters
09-23 09:23:18.357  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:23:18.358  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 09:23:18.358  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:23:18.358  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 09:23:18.359  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:23:18.359  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:23:18.359  4400  4464 D BtGatt.ScanManager: handling starting scan
09-23 09:23:18.360  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:23:18.360  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:23:18.361  5353  5399 I io.jxcore.node.ConnectionHelper: start: OK
09-23 09:23:18.361  4400  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:23:18.369  4400  4461 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:23:18.369  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:18.370  4400  4464 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:23:18.377  4400  4461 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 09:23:18.377  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:18.378  4400  4464 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:23:18.378  4400  4464 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 09:23:18.390  4400  4461 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 09:23:18.390  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:18.397  4400  4461 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 09:23:18.397  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:23:18.861  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 09:23:18.862  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:23:18.862  5353  5353 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:23:18.943   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:23:18.952   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-23 09:23:19.022   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:20.023   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:21.024   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 09:23:21.966   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:23:21.973   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-23 09:23:23.365  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:23.365  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:23.365  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:23:23.365  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:23.365  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:23:23.365  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:23:23.365  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 09:23:23.365  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:23:23.366  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 09:23:23.366  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:23:23.367  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:23:23.367  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:23.368  4400  4610 D BtGatt.GattService: stopScan() - queue size =1
,09-23 09:23:23.370  4400  4412 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:23:23.371  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:23:23.372  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:23:23.372  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:23:23.372  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:23:23.372  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:23:23.374  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:23:23.374  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:23.374  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:23:23.374  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:23.375  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:23:23.379  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:23:23.379  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:23.379  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:23.377  4400  4400 D BtGatt.ScanManager: awakened up at time 236892
09-23 09:23:23.379  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:23.379  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:23.379  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:23.379  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:23.379  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:23.379  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:23:23.379  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:23.379  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:23.387  4400  4461 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:23:23.387  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:23.387  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:23:23.388  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:23:23.392  4400  4464 D BtGatt.ScanManager: stopping BLe Batch
,09-23 09:23:23.395  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:23:23.397  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:23:23.397  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:23:23.397  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:23:23.398  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:23.401  4400  4461 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:23:23.401  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:23.401  4400  4464 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 09:23:23.401  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:23.402  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:23.402  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:23.405  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:23:23.406  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:23.406  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:23.410  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:23:23.424  4400  4461 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-23 09:23:23.424  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:23.424  4400  4461 D BtGatt.GattService: current time is 236939278380
09-23 09:23:23.425  4400  4461 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -72, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -75, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -52, 11, 57, -70, 107, -17, 1, 0, -102, 68, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0]
,09-23 09:23:23.426  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-23 09:23:23.427  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 09:23:23.427  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 09:23:23.428  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 09:23:23.428  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 09:23:23.428  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 09:23:23.428  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
,09-23 09:23:23.910  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:23:24.999   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:23:25.004   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-23 09:23:26.025   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:27.027   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:28.028   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:28.287   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:23:28.388  5353  5399 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-23 09:23:28.395  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:28.407  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:23:28.413  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:23:28.413  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 09:23:28.413  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 09:23:28.414  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-23 09:23:28.414  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:23:28.414  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:28.414  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:23:28.419  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:28.421  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:23:28.426  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:28.430  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:23:28.430  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:23:28.431  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 09:23:28.432  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:23:28.436  4400  4630 D BtGatt.GattService: registerClient() - UUID=2e32d081-0200-4733-860b-3fc31a907719
,09-23 09:23:28.437  4400  4461 D BtGatt.GattService: onClientRegistered() - UUID=2e32d081-0200-4733-860b-3fc31a907719, clientIf=5
,09-23 09:23:28.437  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 09:23:28.438  4400  4610 D BtGatt.GattService: start scan with filters
,09-23 09:23:28.442  4400  4464 D BtGatt.ScanManager: handling starting scan
09-23 09:23:28.443  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 09:23:28.443  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 09:23:28.443  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-23 09:23:28.444  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 09:23:28.448  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:23:28.449  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:23:28.449  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:23:28.452  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:23:28.453  4400  4461 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:23:28.453  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:28.453  4400  4464 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:23:28.456  5353  5399 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 09:23:28.460  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:28.460  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 09:23:28.460  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:28.460  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:23:28.461  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:28.461  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:23:28.461  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:23:28.461  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:23:28.461  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:23:28.461  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:23:28.461  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 09:23:28.461  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:23:28.462  4400  4461 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 09:23:28.462  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:28.462  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:28.462  4400  4464 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 09:23:28.463  4400  4464 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 09:23:28.463  4400  4414 D BtGatt.GattService: stopScan() - queue size =1
,09-23 09:23:28.465  4400  4610 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 09:23:28.466  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:28.466  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:23:28.466  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:23:28.466  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:23:28.466  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:23:28.468  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:23:28.468  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:28.468  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 09:23:28.468  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:28.469  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:28.470  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:28.470  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:28.470  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:28.470  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:28.470  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:28.470  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:23:28.470  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
,09-23 09:23:28.470  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:28.471  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:28.471  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:28.471  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:28.475  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:23:28.475  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:23:28.481  4400  4461 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 09:23:28.482  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:23:28.482  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:23:28.483  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:23:28.483  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:23:28.483  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:28.484  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:28.487  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:28.487  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:28.487  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:23:28.489  4400  4461 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 09:23:28.489  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:23:28.491  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:23:28.491  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:28.491  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:28.494  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:23:28.494  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:28.494  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:28.496  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:28.496  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:28.496  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:28.497  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:28.497  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:28.497  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:28.497  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:28.497  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:28.498  5353  5399 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 09:23:28.498  4400  4461 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:23:28.498  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:28.498  4400  4464 D BtGatt.ScanManager: stopping BLe Batch
,09-23 09:23:28.501  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:28.507  4400  4461 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-23 09:23:28.507  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:23:28.507  4400  4464 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:28.509  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:28.511  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:28.511  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:23:28.511  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:23:28.511  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:23:28.511  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:23:28.512  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:28.512  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:28.513  4400  4461 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-23 09:23:28.513  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:28.514  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:28.516  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:23:28.516  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:28.519  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 09:23:28.519  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:23:28.519  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:23:28.520  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:28.522  4400  4610 D BtGatt.GattService: registerClient() - UUID=d8db9bf8-4e30-47b8-8222-6699acd4681b
,09-23 09:23:28.523  4400  4461 D BtGatt.GattService: onClientRegistered() - UUID=d8db9bf8-4e30-47b8-8222-6699acd4681b, clientIf=5
,09-23 09:23:28.523  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 09:23:28.523  4400  4412 D BtGatt.GattService: start scan with filters
,09-23 09:23:28.526  4400  4464 D BtGatt.ScanManager: handling starting scan
,09-23 09:23:28.527  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:23:28.527  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 09:23:28.527  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:23:28.527  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 09:23:28.530  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:23:28.531  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:23:28.531  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:23:28.532  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 09:23:28.533  4400  4461 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:23:28.533  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:28.533  4400  4464 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:23:28.534  5353  5399 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 09:23:28.538  4400  4461 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 09:23:28.538  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:28.538  4400  4464 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 09:23:28.538  4400  4464 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 09:23:28.547  4400  4461 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 09:23:28.547  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:23:28.552  4400  4461 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 09:23:28.552  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:23:29.030   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:29.032  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 09:23:29.032  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:23:29.032  5353  5353 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:23:30.031   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:31.031   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-23 09:23:31.056   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:23:31.060   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-23 09:23:33.534  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:33.535  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:23:33.535  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:23:33.535  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:33.536  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:23:33.536  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:23:33.536  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:23:33.536  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 09:23:33.536  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:23:33.536  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:23:33.536  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:23:33.541  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:23:33.543  4400  4630 D BtGatt.GattService: stopScan() - queue size =1
,09-23 09:23:33.544  4400  4414 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:23:33.545  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:33.545  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:23:33.546  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-23 09:23:33.546  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:23:33.546  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:23:33.549  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:23:33.549  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:33.549  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:23:33.549  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:33.550  4400  4400 D BtGatt.ScanManager: awakened up at time 247065
09-23 09:23:33.550  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:23:33.555  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:33.555  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:33.555  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:33.556  4400  4461 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:23:33.557  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:33.557  4400  4464 D BtGatt.ScanManager: stopping BLe Batch
09-23 09:23:33.560  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:23:33.560  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:23:33.567  4400  4461 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:23:33.567  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:23:33.567  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:33.568  4400  4464 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 09:23:33.569  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:23:33.569  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:23:33.569  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:23:33.570  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:33.574  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:33.574  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:33.574  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:23:33.579  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:23:33.579  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:23:33.580  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:23:33.583  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:23:33.596  4400  4461 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-23 09:23:33.596  4400  4461 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:23:33.596  4400  4461 D BtGatt.GattService: current time is 247111028033
,09-23 09:23:33.596  4400  4461 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -75, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -75, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -52, 11, 57, -70, 107, -17, 1, 0, -94, 76, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 35, 97, 126, -92, 22, -56, 1, -128, -78, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -72, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-23 09:23:33.596  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 09:23:33.597  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 09:23:33.597  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 09:23:33.597  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 09:23:33.597  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 09:23:33.597  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-23 09:23:33.597  4400  4461 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-23 09:23:34.082   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 09:23:34.084  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:23:34.084  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:23:34.085  5353  5353 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 09:23:34.091   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-23 09:23:38.555  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:38.556  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.556  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.556  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.556  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:38.556  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:38.557  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
,09-23 09:23:38.557  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.557  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.557  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.557  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:38.560  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.561  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:38.564  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:23:38.565  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:23:38.565  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:23:38.567  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.567  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.568  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.568  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:38.568  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
,09-23 09:23:38.570  5353  5399 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-23 09:23:38.573  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:38.573  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.573  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-23 09:23:38.574  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.574  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.574  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.574  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
,09-23 09:23:38.575  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.576  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.576  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:23:38.576  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.577  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.577  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.577  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:38.580  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:23:38.581  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.581  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.582  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.582  5353  5399 D BluetoothLeScanner: could not find callback wrapper
,09-23 09:23:38.582  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.583  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:38.583  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
,09-23 09:23:38.585  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-23 09:23:38.586  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.586  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.586  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.586  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.586  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.586  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:38.587  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.587  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.587  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.587  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.587  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.587  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.587  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:38.587  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.589  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.589  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.589  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.590  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:23:38.590  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.591  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.591  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.591  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.592  5353  5399 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 09:23:38.592  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:23:38.593  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.593  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.593  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.593  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.593  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:38.593  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.593  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.593  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.593  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.593  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:38.594  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.594  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.594  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:38.596  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.596  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.596  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:23:38.597  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.598  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.598  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-23 09:23:38.598  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.598  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
,09-23 09:23:38.600  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-23 09:23:38.600  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.600  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.600  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.600  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.600  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.600  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.600  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.600  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.601  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.601  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.601  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:38.601  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.601  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.601  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.602  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.602  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.603  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:23:38.603  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.603  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.603  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.604  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.604  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
,09-23 09:23:38.605  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 09:23:38.605  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:23:38.605  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 09:23:38.605  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 09:23:38.605  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:23:38.605  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:23:38.605  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 09:23:38.606  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:23:38.606  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 09:23:38.606  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.606  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.606  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.606  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.606  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:38.606  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.606  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.606  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.607  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.607  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.607  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.607  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.607  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.607  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.610  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.610  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.611  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.612  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:23:38.612  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.612  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.612  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.612  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.613  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:23:38.613  5353  5399 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 09:23:38.614  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 09:23:38.617  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-23 09:23:38.618  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-23 09:23:38.618  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-23 09:23:38.619  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 09:23:38.620  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 09:23:38.620  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 09:23:38.620  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-23 09:23:38.620  5353  5399 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 09:23:38.620  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 09:23:38.620  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:23:38.620  5353  5399 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 09:23:38.620  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 09:23:38.621  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:23:38.621  5353  5399 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 09:23:38.621  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-23 09:23:38.624  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-23 09:23:38.625  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-23 09:23:38.626  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-23 09:23:38.626  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 09:23:38.626  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-23 09:23:38.626  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-23 09:23:38.627  5353  5399 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 09:23:38.627  5353  5399 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 09:23:38.627  5353  5401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-23 09:23:38.628  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.628  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.628  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.628  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.628  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.628  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.629  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 09:23:38.630  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.630  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.630  5353  5401 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:23:38.630  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.630  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.630  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.630  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.631  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.631  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.631  5353  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-23 09:23:38.632  5353  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-23 09:23:38.633  5353  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-23 09:23:38.633  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.633  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.633  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.634  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.634  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.634  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.634  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.634  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.635  5353  5401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-23 09:23:38.628  4610  4610 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29310]" dev="sockfs" ino=29310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:23:38.632  4610  4610 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29310]" dev="sockfs" ino=29310 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:23:38.635  5353  5399 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 09:23:38.640  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.640  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.640  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.640  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.641  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.641  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.641  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.641  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.641  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.641  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.641  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.641  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.641  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.641  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.643  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.643  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.643  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.644  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.644  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.644  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.644  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.644  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.645  5353  5399 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-23 09:23:38.645  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.645  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.645  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.645  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.645  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.645  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.645  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.645  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.646  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.646  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.646  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.646  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.646  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.646  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.647  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.647  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.647  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.648  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.648  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.648  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.648  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.648  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.649  5353  5399 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 09:23:38.649  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 09:23:38.649  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 09:23:38.649  5353  5399 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 09:23:38.649  5353  5399 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 09:23:38.649  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 09:23:38.649  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 09:23:38.649  5353  5399 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 09:23:38.649  5353  5399 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 09:23:38.649  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 09:23:38.649  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 09:23:38.649  5353  5399 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 09:23:38.649  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:38.650  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:38.650  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:38.650  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.650  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.650  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.650  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.650  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.650  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.650  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.650  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.650  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.650  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.650  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.651  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:38.651  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:38.651  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:38.652  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:38.652  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:38.652  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:38.652  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.652  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.653  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:38.653  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.653  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:38.653  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:38.653  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:38.653  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:38.653  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:38.653  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:38.653  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:41.032   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:42.033   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:43.034   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:43.654  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:43.654  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.654  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:23:43.654  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.655  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.655  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.655  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:43.655  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:23:43.656  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:43.656  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:43.656  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.656  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.656  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.656  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:43.657  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.657  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:43.657  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.657  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.657  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.657  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.660  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:43.661  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:23:43.661  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:43.663  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:43.663  5353  5399 D BluetoothLeScanner: could not find callback wrapper
,09-23 09:23:43.663  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:43.663  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:43.663  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.667  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 09:23:43.668  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:43.670  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 09:23:43.672  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 09:23:43.672  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 09:23:43.673  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 09:23:43.673  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:23:43.673  5353  5353 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 09:23:43.673  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:43.674  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 09:23:43.674  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 09:23:43.674  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 09:23:43.674  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.674  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 09:23:43.674  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.674  5353  5403 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:23:43.674  5353  5353 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-23 09:23:43.674  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.675  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:23:43.675  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:23:43.675  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:23:43.675  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 09:23:43.677  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:43.677  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:43.677  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:43.677  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:43.677  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:23:43.677  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.678  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.680  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:23:43.680  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.680  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:23:43.680  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:23:43.680  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:43.680  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:23:43.680  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:43.680  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:43.680  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:43.681  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.681  5353  5403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 09:23:43.681  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:43.681  5353  5403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 09:23:43.681  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.681  5353  5403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 09:23:43.681  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.681  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.681  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:43.681  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.682  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:43.675  4610  4610 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28528]" dev="sockfs" ino=28528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:23:43.675  4610  4610 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28528]" dev="sockfs" ino=28528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:23:43.687  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:23:43.687  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:23:43.695  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:23:43.696  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:23:43.696  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:23:43.696  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:43.697  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:43.700  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.701  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:43.702  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:43.702  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:43.703  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:23:43.704  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:43.704  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:43.704  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:43.704  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.704  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 09:23:43.704  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.704  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:43.704  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:23:43.706  5353  5399 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-23 09:23:43.706  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 09:23:43.706  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 09:23:43.706  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-23 09:23:43.707  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 09:23:43.707  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:43.707  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:43.707  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:43.707  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:43.707  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.707  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:23:43.707  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.707  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.707  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.708  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:43.708  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.708  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:23:43.713  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:23:43.713  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:23:43.714  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:43.720  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:43.720  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:23:43.720  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:23:43.721  5353  5353 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 09:23:43.722  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:43.722  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:43.722  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:23:43.723  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:23:43.723  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:43.723  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:43.723  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.723  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.727  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:43.727  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:43.727  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:43.727  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:43.728  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:43.728  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.728  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.728  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.728  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.728  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:43.728  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.728  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.728  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.728  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.729  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-23 09:23:43.729  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:43.729  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:23:43.730  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:23:43.730  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:43.730  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:43.730  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.730  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.731  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:23:43.732  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:23:43.732  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:23:43.732  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:23:43.732  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:43.732  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.732  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d66fb8d not in the list
09-23 09:23:43.732  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.732  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.732  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:43.732  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.732  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.732  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:23:43.732  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:43.734  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:23:43.734  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:23:43.734  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:23:43.736  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:23:43.736  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:23:43.736  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:23:43.736  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:23:43.736  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c4142 not in the list
09-23 09:23:43.737  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-23 09:23:43.737  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 09:23:43.737  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 09:23:43.737  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 09:23:43.737  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-23 09:23:43.737  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 09:23:43.739  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 09:23:43.739  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-23 09:23:43.740  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-23 09:23:43.740  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 09:23:43.740  5353  5399 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-23 09:23:43.740  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 09:23:43.740  5353  5399 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-23 09:23:43.740  5353  5399 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-23 09:23:43.741  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-23 09:23:43.741  5353  5399 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 09:23:43.741  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 09:23:43.741  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-23 09:23:43.741  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 09:23:43.741  5353  5399 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-23 09:23:43.743  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:23:43.743  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4642d8 added. We now have 3 listener(s)
09-23 09:23:43.743  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:43.745  5353  5399 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 09:23:43.746   930  3423 D WifiService: setWifiEnabled: true pid=5353, uid=10077
09-23 09:23:43.746   930  3423 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:23:43.761  4400  4603 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-23 09:23:43.762  4400  4608 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-23 09:23:44.036   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:44.221  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:23:45.037   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:23:46.037   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-23 09:23:48.751  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:23:48.752  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1587631 added. We now have 4 listener(s)
09-23 09:23:48.752  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:48.765  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:48.766  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1587631 removed from the list
09-23 09:23:48.766  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:48.766  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:48.766  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:48.767  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:23:48.767  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1937116 added. We now have 4 listener(s)
09-23 09:23:48.767  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:48.770  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:23:48.770  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1937116 removed from the list
09-23 09:23:48.770  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:23:48.770  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:23:48.770  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:23:48.772  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:23:48.772  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5400a97 added. We now have 4 listener(s)
09-23 09:23:48.772  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:23:48.776   930  3336 D WifiService: setWifiEnabled: false pid=5353, uid=10077
,09-23 09:23:48.777   930  3336 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:23:48.781   930  2890 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-23 09:23:48.781   930  2890 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-23 09:23:48.782   930  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:23:48.782   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:23:48.792  4400  4457 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 09:23:48.792  4400  4457 D BluetoothAdapterProperties: Setting state to 13
,09-23 09:23:48.792  4400  4457 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-23 09:23:48.793  4400  4457 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 09:23:48.794  4400  4457 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:23:48.796  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:23:48.797  4400  4400 D BluetoothMapService: onReceive
09-23 09:23:48.797  4400  4400 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:23:48.797  4400  4400 D BluetoothMapService: STATE_TURNING_OFF
09-23 09:23:48.798  4400  4400 D BluetoothMapService: MAP Service closeService in
09-23 09:23:48.798  4400  4400 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 09:23:48.798  4400  4400 D ObexServerSockets0: shutdown(block = true)
09-23 09:23:48.800  4400  4632 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-23 09:23:48.801  4400  4400 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 09:23:48.801  4400  4400 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 09:23:48.801  4400  4608 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 09:23:48.802  4400  4633 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 09:23:48.804  4400  4400 I BtOppRfcommListener: stopping Accept Thread
09-23 09:23:48.805  4400  5057 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 09:23:48.805  4400  5057 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 09:23:48.807  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:48.808  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:48.808   507   925 D CommandListener: Clearing all IP addresses on wlan0
09-23 09:23:48.809  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.809   930  5107 D DhcpClient: Clearing IP address
09-23 09:23:48.809  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:48.809  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 09:23:48.812   507   925 D CommandListener: Setting iface cfg
,09-23 09:23:48.817  3545  5161 V NativeCrypto: Read error: ssl=0x7f7226d380: I/O error during system call, Connection timed out
09-23 09:23:48.819   930  5108 D DhcpClient: Receive thread stopped
09-23 09:23:48.820  3545  5161 V NativeCrypto: SSL shutdown failed: ssl=0x7f7226d380: I/O error during system call, Broken pipe
09-23 09:23:48.821  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:48.821  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:48.822  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:48.822  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:48.823   930  3457 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-23 09:23:48.824   930  5105 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-23 09:23:48.826   930   943 I ActivityManager: Start proc 5407:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-23 09:23:48.826  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:48.829  4400  4461 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:23:48.829  4400  4457 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 09:23:48.830   930  5105 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-23 09:23:48.831  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:48.831  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:48.832   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-23 09:23:48.832   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-23 09:23:48.832  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:48.832  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:48.833   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-23 09:23:48.833   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-23 09:23:48.834   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-23 09:23:48.834   533   533 E Parcel  : Reading a NULL string not supported here.
09-23 09:23:48.837  4400  4400 D HeadsetService: Received stop request...Stopping profile...
,09-23 09:23:48.843  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.843  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:48.844   930   930 D BluetoothHeadset: Proxy object disconnected
09-23 09:23:48.844   930   930 D BluetoothHeadset: Proxy object disconnected
09-23 09:23:48.845  3047  3060 D BluetoothHeadset: Proxy object disconnected
09-23 09:23:48.845   930  2892 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 09:23:48.845  4400  4400 D A2dpService: Received stop request...Stopping profile...
,09-23 09:23:48.845  3437  3682 D BluetoothHeadset: Proxy object disconnected
,09-23 09:23:48.846  4400  4613 D A2dpStateMachine: Exit Disconnected: -1
09-23 09:23:48.846   930   930 D BluetoothHeadset: Proxy object disconnected
09-23 09:23:48.847  3407  3575 W QCNEJ   : |CORE| network lost: 100
09-23 09:23:48.847   930   930 D BluetoothA2dp: Proxy object disconnected
09-23 09:23:48.848  3407  3575 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-23 09:23:48.848  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.848  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:48.850  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.851  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:48.851   930   930 D RttService: SCAN_AVAILABLE : 1
09-23 09:23:48.851  4400  4400 D HidService: Received stop request...Stopping profile...
09-23 09:23:48.851   930  2999 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 09:23:48.851  4400  4400 D HidService: Stopping Bluetooth HidService
09-23 09:23:48.853  4400  4400 D HealthService: Received stop request...Stopping profile...
09-23 09:23:48.853  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.853  3047  3047 D HeadsetProfile: Bluetooth service disconnected
09-23 09:23:48.854  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.854  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:48.854  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:23:48.854  3047  3047 D BluetoothA2dp: Proxy object disconnected
,09-23 09:23:48.854  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.854  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:23:48.855  4400  4400 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 09:23:48.855  4400  4400 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 09:23:48.855  4400  4461 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 09:23:48.855  4400  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:23:48.855  4400  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:23:48.855  4400  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:23:48.855  4400  4461 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 09:23:48.856  4400  4400 D PanService: Received stop request...Stopping profile...
09-23 09:23:48.856  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.856  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:48.857   930  2890 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-23 09:23:48.857  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:48.860  3047  3047 D BluetoothInputDevice: Proxy object disconnected
09-23 09:23:48.860  3047  3047 D HidProfile: Bluetooth service disconnected
09-23 09:23:48.861   930  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:23:48.862  4400  4400 D BluetoothMapService: Received stop request...Stopping profile...
09-23 09:23:48.862  4400  4400 D BluetoothMapService: stop()
09-23 09:23:48.863  4400  4400 D BluetoothMapAppObserver: deinitObservers()
09-23 09:23:48.863  4400  4400 D BluetoothMapAppObserver: removeReceiver()
09-23 09:23:48.864  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.864  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.864  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:48.864  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:23:48.866  4400  4461 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-23 09:23:48.866  4400  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:23:48.866  4400  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:23:48.866  4400  4603 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:23:48.866  4400  4603 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:23:48.866  4400  4603 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:23:48.866  4400  4603 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:23:48.866  4400  4400 D SapService: Received stop request...Stopping profile...
09-23 09:23:48.866  4400  4400 V SapService: stop()
09-23 09:23:48.872  3047  3047 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 09:23:48.872  3047  3047 D PanProfile: Bluetooth service disconnected
09-23 09:23:48.872  3047  3047 D BluetoothMap: Proxy object disconnected
,09-23 09:23:48.872  3047  3047 D MapProfile: Bluetooth service disconnected
,09-23 09:23:48.878  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.878  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.878  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:48.878  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:23:48.878  4400  4400 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 09:23:48.878  4400  4400 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-23 09:23:48.879  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.879  4400  4461 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 09:23:48.879  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.879  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:48.879  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:23:48.879  4400  4400 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 09:23:48.879  4400  4461 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-23 09:23:48.885  4400  4400 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-23 09:23:48.885  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.885  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.885  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:48.885  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:23:48.886  4400  4400 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 09:23:48.886  4400  4400 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 09:23:48.886  4400  4400 D BluetoothMapService: MAP Service closeService in
09-23 09:23:48.886  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.886  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.887  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 09:23:48.887  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:23:48.887   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-23 09:23:48.887  4400  4400 D BluetoothMapService: cleanup()
09-23 09:23:48.887  4400  4400 D BluetoothMapService: MAP Service closeService in
09-23 09:23:48.887  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 09:23:48.887  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:48.887  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:48.887  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:23:48.888  4400  4457 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 09:23:48.888  4400  4457 D BluetoothAdapterProperties: Setting state to 15
09-23 09:23:48.888  4400  4457 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-23 09:23:48.888   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:23:48.889  3047  3586 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-23 09:23:48.889   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:23:48.889   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:23:48.890  3047  3058 D BluetoothMap: onBluetoothStateChange: up=false
09-23 09:23:48.890  4400  4457 I BluetoothAdapterState: Entering BleOnState
09-23 09:23:48.890  3437  3464 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:23:48.891  3047  3060 D BluetoothPan: onBluetoothStateChange on: false
09-23 09:23:48.891  3047  3640 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:23:48.891  3047  3586 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-23 09:23:48.892   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:23:48.892  3047  3058 D BluetoothPbap: onBluetoothStateChange: up=false
,09-23 09:23:48.893  4400  4457 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-23 09:23:48.893  4400  4457 D BluetoothAdapterProperties: Setting state to 16
09-23 09:23:48.893  4400  4457 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-23 09:23:48.894  4400  4457 D BluetoothAdapterProperties: onBleDisable
09-23 09:23:48.894  4400  4457 I BluetoothAdapterState: Entering PendingCommandState
09-23 09:23:48.894  4400  4458 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 09:23:48.895  4400  4461 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:23:48.895  4400  4603 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 09:23:48.895  4400  4603 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:23:48.895  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:48.896  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:48.897  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:48.899  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:48.900  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:48.901  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:48.911  5407  5407 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-23 09:23:48.915   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:23:48.915   507   925 D CommandListener: Clearing all IP addresses on wlan0
,09-23 09:23:48.916   507   925 D TetherController: Setting IP forward enable = 0
09-23 09:23:48.917   930  2892 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-23 09:23:48.917   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 09:23:48.918   930  2890 D DhcpClient: doQuit
09-23 09:23:48.919   930  2890 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 09:23:48.919  3573  3573 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 09:23:48.920   930   947 D Tethering: MasterInitialState.processMessage what=3
09-23 09:23:48.921   930  5107 D DhcpClient: onQuitting
,09-23 09:23:48.922  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.923  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:23:48.924  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.924  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:48.927  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.927  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:48.928  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.928  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:48.930  3573  3573 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 09:23:48.930  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:48.930  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:48.931  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:48.931  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:48.932  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:48.934  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:48.935  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:48.935  3573  3573 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-23 09:23:48.935  4169  4169 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@63cecb4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-23 09:23:48.938  4735  4735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-23 09:23:48.940  4801  4826 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-23 09:23:48.940  4801  4826 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:23:48.940  4801  4826 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 09:23:48.940  4801  4826 E SarControlService: no key has been found,reset the power
09-23 09:23:48.940  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-23 09:23:48.941  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:23:48.941  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 09:23:48.941  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:23:48.941  4830  4830 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 09:23:48.943  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 09:23:48.943  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:23:48.943  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-23 09:23:48.944  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:23:48.944  4830  4830 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:23:48.947  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000ea03000000000000ffffffff]
09-23 09:23:48.947  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:23:48.947  4830  4844 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-23 09:23:48.947  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-23 09:23:48.947  4801  4811 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:23:48.948  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000eb03000000000000ffffffff]
09-23 09:23:48.948  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:23:48.948  4830  4844 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-23 09:23:48.949  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:23:48.949  4801  4812 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 09:23:48.953  5407  5407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 09:23:48.958   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2264479:true
,09-23 09:23:48.960  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:23:48.967  3573  3573 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 09:23:48.970   507   925 E Netd    : netlink response contains error (No such file or directory)
09-23 09:23:48.971   507   925 D TetherController: Setting IP forward enable = 0
09-23 09:23:48.972   930  2892 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-23 09:23:48.972   930  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 09:23:48.974   930  3335 I ActivityManager: Start proc 5437:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 09:23:48.978  3573  3573 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 09:23:48.998  5407  5407 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 09:23:49.000  5407  5407 D BluetoothMap: Create BluetoothMap proxy object
,09-23 09:23:49.014  5407  5407 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 09:23:49.020  5437  5437 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 09:23:49.029  5407  5407 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:23:49.035   930   940 I ActivityManager: Killing 4776:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 09:23:49.084  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 09:23:49.084   930  2890 D wifi    : In wifi stop Hal
09-23 09:23:49.084   930  2890 D wifi    : halHandle = 0x7f60fe3360, mVM = 0x7f7cdcd140, mCls = 0x100b62
,09-23 09:23:49.084   930  3571 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 09:23:49.084   930  3571 D WifiHAL : Got a signal to exit!!!
09-23 09:23:49.084   930  3571 I WifiHAL : Exit wifi_event_loop
09-23 09:23:49.085   930  2890 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 09:23:49.085   930  2890 E WifiHAL : Event processing terminated
09-23 09:23:49.085   930  2890 D wifi    : In wifi cleaned up handler
09-23 09:23:49.085   930  2890 I WifiHAL : Internal cleanup completed
09-23 09:23:49.086  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:49.087  3382  3960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 09:23:49.088  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:49.089  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:49.100  4400  4461 I bt_hci  : shut_down
,09-23 09:23:49.102  4400  4465 D bt_hwcfg: hw_epilog_process
,09-23 09:23:49.102  4400  4465 I bt_vendor: low_power_mode_cb
,09-23 09:23:49.105  4400  4465 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 09:23:49.105  4400  4465 I bt_vendor: epilog_cb
09-23 09:23:49.105  4400  4465 I bt_hci  : epilog_finished_callback
,09-23 09:23:49.108  4400  4461 I bt_hci_h4: hal_close
,09-23 09:23:49.108   930  3571 D wifi    : set interface wlan0 flags (DOWN)
09-23 09:23:49.109  4400  4461 I bt_userial_vendor: device fd = 54 close
09-23 09:23:49.109   930  2890 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 09:23:49.216  4400  4458 D bt_stack_manager: event_shut_down_stack finished.
,09-23 09:23:49.217  4400  4457 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-23 09:23:49.218  4400  4457 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 09:23:49.218  4400  4400 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 09:23:49.219  4400  4400 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 09:23:49.219  4400  4400 D BtGatt.GattService: stop()
09-23 09:23:49.219  4400  4400 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 09:23:49.221  4400  4400 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:23:49.221  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 09:23:49.221  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:23:49.221  4400  4400 V BluetoothAdapterState: isBleTurningOff()=true
,09-23 09:23:49.222  4400  4457 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-23 09:23:49.222  4400  4457 D BluetoothAdapterProperties: Setting state to 10
09-23 09:23:49.222  4400  4457 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 09:23:49.222  4400  4457 I BluetoothAdapterState: Entering OffState
09-23 09:23:49.223   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-23 09:23:49.229  4400  4400 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-23 09:23:49.229  4400  4400 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 09:23:49.229  4400  4400 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 09:23:49.231  4400  4458 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 09:23:49.239  4400  4400 I art     : System.exit called, status: 0
,09-23 09:23:49.239  4400  4400 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 09:23:49.244  5437  5437 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.244  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 09:23:49.245  5437  5437 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 09:23:49.245  5437  5437 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.245  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 09:23:49.265  5437  5437 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:23:49.265  5437  5437 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:23:49.265  5437  5437 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
0,9-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.265  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:23:49.266  5437  5437 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:23:49.266  5437  5437 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 09:23:49.266  5437  5437 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 09:23:49.270  5407  5407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:23:49.287  5407  5407 D DockEventReceiver: finishStartingService: stopping service
09-23 09:23:49.288   930  3457 I ActivityManager: Killing 4169:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-23 09:23:49.311   930   947 D Tethering: InitialState.processMessage what=4
09-23 09:23:49.312   930  3335 I ActivityManager: Process com.android.bluetooth (pid 4400) has died
09-23 09:23:49.314   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-23 09:23:49.314  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:23:49.328   930  3475 I ActivityManager: Start proc 5471:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-23 09:23:49.389  5471  5471 D AdapterServiceConfig: Adding HeadsetService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding A2dpService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding HidService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding HealthService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding PanService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding GattService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding BluetoothMapService
09-23 09:23:49.390  5471  5471 D AdapterServiceConfig: Adding SapService
,09-23 09:23:49.399   930  3475 I ActivityManager: Killing 5135:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-23 09:23:49.423  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-23 09:23:49.426  3834  3834 D SystemUpdateService: onCreate
,09-23 09:23:49.432  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 09:23:49.440  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 09:23:49.446  3834  5133 I iu.UploadsManager: num queued entries: 0
,09-23 09:23:49.446  3834  5133 I iu.UploadsManager: num updated entries: 0
09-23 09:23:49.446  3834  5133 I iu.SyncManager: NEXT; no task
,09-23 09:23:49.454  3834  5483 I SystemUpdateService: active receiver: enabled
,09-23 09:23:49.456  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 09:23:49.458  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:23:49.460  3834  5483 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:23:49.469   930   940 I ActivityManager: Start proc 5485:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-23 09:23:49.469  3834  5483 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-23 09:23:49.469  3834  5483 I SystemUpdateService: now status is 0 (complete)
09-23 09:23:49.470  3834  5483 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 09:23:49.470  3834  5483 I SystemUpdateService: file has been verified
,09-23 09:23:49.472  3834  5483 I SystemUpdateService: OTA package size = 21989297
,09-23 09:23:49.485  3834  5483 I SystemUpdateService: showing system update notification
,09-23 09:23:49.504  5485  5485 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-23 09:23:49.507  5485  5485 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:23:49.517  5485  5485 D SprintDMHelper: simOperator: 
09-23 09:23:49.517  5485  5485 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:23:49.542  3834  3834 D SystemUpdateService: onDestroy
,09-23 09:23:49.548  4216  5497 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 09:23:49.563   930  3423 I ActivityManager: Start proc 5498:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 09:23:49.565   930  3423 I ActivityManager: Killing 4471:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 09:23:49.621  5498  5498 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 09:23:49.631   930  3423 I ActivityManager: Killing 5216:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-23 09:23:49.682  5437  5459 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 09:23:49.690   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2afdba0:true
,09-23 09:23:53.813   930   940 D WifiService: setWifiEnabled: true pid=5353, uid=10077
,09-23 09:23:53.813   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:23:53.825   507   925 D SoftapController: Softap fwReload - Ok
,09-23 09:23:53.830   507   925 D CommandListener: Setting iface cfg
,09-23 09:23:53.830   507   925 D CommandListener: Trying to bring down wlan0
09-23 09:23:53.831   507   925 D CommandListener: Clearing all IP addresses on wlan0
09-23 09:23:53.834   930  2890 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 09:23:54.408   930  2890 D wifi    : set interface wlan0 flags (UP)
,09-23 09:23:54.410   930  2890 I WifiHAL : Initializing wifi
09-23 09:23:54.410   930  2890 I WifiHAL : Creating socket
,09-23 09:23:54.413   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 09:23:54.414   930  2890 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 09:23:54.414   930  2890 D wifi    : Did set static halHandle = 0x7f60fe3360
09-23 09:23:54.414   930  2890 D wifi    : halHandle = 0x7f60fe3360, mVM = 0x7f7cdcd140, mCls = 0x10196a
09-23 09:23:54.415   930  2890 D wifi    : array field set
,09-23 09:23:54.415   930  2890 I WifiNative-HAL: interface[0] = wlan0
,09-23 09:23:54.417   930  5517 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547088118624
09-23 09:23:54.417   930  5517 D wifi    : waitForHalEvents called, vm = 0x7f7cdcd140, obj = 0x10196a, env = 0x7f635e9640
,09-23 09:23:54.482  5518  5518 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 09:23:54.503  5518  5518 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:23:54.519   930  2890 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 09:23:54.523  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:54.524  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:54.524  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:54.538  5518  5518 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:23:54.538  5518  5518 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 09:23:54.553   930  2890 D WifiConfigStore: Loading config and enabling all networks 
,09-23 09:23:54.554  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:54.555  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:54.555  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:54.555  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:54.556  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:54.557  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:54.557  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:54.557  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:54.558  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:54.558  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:54.558  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:54.558  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:23:54.563   930  2890 D WifiConfigStore: loaded 0 passpoint configs
,09-23 09:23:54.564   930  2890 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 09:23:54.564   930  2890 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 09:23:54.565   930  2890 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 09:23:54.566   930  2890 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 09:23:54.566   930  2890 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 09:23:54.566   930  2890 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 09:23:54.566   930  2890 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 09:23:54.570   930  2890 D WifiNative-HAL: Setting external_sim to 1
,09-23 09:23:54.570  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 09:23:54.571   930  2890 D wifi    : setting dfs flag to true, 0x7f61368860
,09-23 09:23:54.571   930  2890 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 09:23:54.571   930  2890 D wifi    : setting scan oui 0x7f61368860
09-23 09:23:54.571   930  2890 D WifiHAL : Sending mac address OUI
,09-23 09:23:54.576   930  2890 E native  : do suspend false
,09-23 09:23:54.582   930  2890 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 09:23:54.582   507   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-23 09:23:54.583   930   930 D RttService: SCAN_AVAILABLE : 3
09-23 09:23:54.583   930  2999 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 09:23:54.585   507   925 D CommandListener: Setting iface cfg
,09-23 09:23:54.586   930  2889 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-23 09:23:54.587   930  2889 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 09:23:54.594   930  2889 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 09:23:54.599   930  2889 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-23 09:23:54.599   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268113 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-23 09:23:57.727  5518  5518 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:23:57.731  5518  5518 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:23:57.737  5518  5518 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:23:57.788   930  2890 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 09:23:57.789   930  2890 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 09:23:57.789   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:23:57.800   930  2890 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 09:23:57.837   930  2890 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 09:23:57.839  5518  5518 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 09:23:58.261  5518  5518 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 09:23:58.296  5518  5518 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 09:23:58.297  5518  5518 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 09:23:58.307   930  2890 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:23:58.307   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 09:23:58.307   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 09:23:58.325   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:23:58.336   507   925 D CommandListener: Setting iface cfg
,09-23 09:23:58.341   930  2890 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 09:23:58.347   930  5524 D DhcpClient: Receive thread started
,09-23 09:23:58.351   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 09:23:58.351   930  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 09:23:58.351   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 09:23:58.432   930  2890 E native  : do suspend false
,09-23 09:23:58.446   930  5523 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 09:23:58.459   930  5524 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-23 09:23:58.460   930  5523 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-23 09:23:58.462   930  5523 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 09:23:58.474   930  5524 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 09:23:58.475   930  5523 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 09:23:58.477   507   925 D CommandListener: Setting iface cfg
,09-23 09:23:58.483   930  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 09:23:58.488   930  5523 D DhcpClient: Scheduling renewal in 86399s
,09-23 09:23:58.503   930  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 09:23:58.503   930  2890 D WifiConfigStore: No blacklist allowed without epno enabled
09-23 09:23:58.504   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-23 09:23:58.507   930  2892 D ConnectivityService: Adding iface wlan0 to network 101
09-23 09:23:58.507   930  2890 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 09:23:58.568   930  2892 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 09:23:58.570   930  2892 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 09:23:58.573   930  2892 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 09:23:58.575   930  2892 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-23 09:23:58.576   930  2892 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 09:23:58.583   930  2892 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 09:23:58.588   930  2892 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-23 09:23:58.588   930  2892 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-23 09:23:58.588   930  2892 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-23 09:23:58.588   930  2890 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 09:23:58.588   930  2892 D ConnectivityService:    accepting network in place of null
09-23 09:23:58.588   930  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:23:58.589   930  2892 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:23:58.604   930  5522 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272119, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 09:23:58.613   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:23:58.636   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:23:58.640   930  2892 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-23 09:23:58.640   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 09:23:58.640  3407  3575 W QCNEJ   : |CORE| network available: 101
09-23 09:23:58.641   930  2892 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-23 09:23:58.642   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-23 09:23:58.643  3407  3575 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-23 09:23:58.644  3407  3575 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-23 09:23:58.646  3407  3575 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-23 09:23:58.647  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:58.647  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:58.647  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.648  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:58.650  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:58.650  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:58.650  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:58.650  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:58.653  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:23:58.653  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:23:58.653  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.653  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:23:58.657  4801  4826 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:23:58.657  4801  4826 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:23:58.657  4801  4826 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 09:23:58.657  4801  4826 E SarControlService: no key has been found,reset the power
09-23 09:23:58.657  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:23:58.657  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-23 09:23:58.657  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 09:23:58.658  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:23:58.658  4830  4830 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-23 09:23:58.659  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-23 09:23:58.659  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:23:58.659  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:23:58.659  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:23:58.659  4830  4830 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:23:58.661  4735  4735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-23 09:23:58.663  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-23 09:23:58.665  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000ec03000000000000ffffffff]
,09-23 09:23:58.665  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:23:58.665  4830  4844 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 09:23:58.666  3834  3834 D SystemUpdateService: onCreate
09-23 09:23:58.666  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:23:58.667  4801  4811 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:23:58.670  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 09:23:58.673  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000ed03000000000000ffffffff]
09-23 09:23:58.673  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:23:58.673  4830  4844 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 09:23:58.673  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-23 09:23:58.674  4801  4812 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 09:23:58.676   930  5521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-23 09:23:58.679  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 09:23:58.686  3834  5133 I iu.UploadsManager: num queued entries: 0
,09-23 09:23:58.687  3834  5133 I iu.UploadsManager: num updated entries: 0
09-23 09:23:58.687  3834  5133 I iu.SyncManager: NEXT; no task
,09-23 09:23:58.690  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 09:23:58.691  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:23:58.693  5485  5485 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-23 09:23:58.696  5485  5485 D SprintDMHelper: simOperator: 
09-23 09:23:58.696  5485  5485 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:23:58.702  3834  5534 I SystemUpdateService: active receiver: enabled
,09-23 09:23:58.722   930  5521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 13:23:58 GMT], X-Android-Received-Millis=[1474637038721], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474637038699]}
,09-23 09:23:58.723   930  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 09:23:58.723   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-23 09:23:58.723   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 09:23:58.724   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 09:23:58.726  3834  5534 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:23:58.733  3834  5534 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 09:23:58.733  3834  5534 I SystemUpdateService: now status is 0 (complete)
09-23 09:23:58.733  3834  5534 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 09:23:58.733  3834  5534 I SystemUpdateService: file has been verified
09-23 09:23:58.733  3834  5534 I SystemUpdateService: OTA package size = 21989297
,09-23 09:23:58.739  3834  5534 I SystemUpdateService: showing system update notification
,09-23 09:23:58.751  3834  3834 D SystemUpdateService: onDestroy
,09-23 09:23:58.803  4216  5539 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 09:23:58.824   930   941 D WifiService: setWifiEnabled: false pid=5353, uid=10077
09-23 09:23:58.824   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:23:58.826   930  2890 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-23 09:23:58.826   930  2890 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-23 09:23:58.826   930  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:23:58.826   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:23:58.837   930  5523 D DhcpClient: Clearing IP address
,09-23 09:23:58.837   507   925 D CommandListener: Clearing all IP addresses on wlan0
,09-23 09:23:58.839   507   925 D CommandListener: Setting iface cfg
,09-23 09:23:58.842  3545  5546 V NativeCrypto: Read error: ssl=0x7f72f4bd80: I/O error during system call, Connection timed out
,09-23 09:23:58.842  3545  5546 V NativeCrypto: SSL shutdown failed: ssl=0x7f72f4bd80: I/O error during system call, Broken pipe
,09-23 09:23:58.848   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-23 09:23:58.848   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-23 09:23:58.852   533   533 E Parcel  : Reading a NULL string not supported here.
,09-23 09:23:58.856   930  2892 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-23 09:23:58.857   930   930 D RttService: SCAN_AVAILABLE : 1
09-23 09:23:58.858   930  2999 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 09:23:58.858  3407  3575 W QCNEJ   : |CORE| network lost: 101
09-23 09:23:58.859  3407  3575 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-23 09:23:58.862   930  2890 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 09:23:58.863   930  5524 D DhcpClient: Receive thread stopped
,09-23 09:23:58.865   930  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 09:23:58.880   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:23:58.899   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:23:58.900   930  2892 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-23 09:23:58.900   507   925 D CommandListener: Clearing all IP addresses on wlan0
09-23 09:23:58.900   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:23:58.901   930   947 D Tethering: MasterInitialState.processMessage what=3
09-23 09:23:58.904  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.904  4735  4735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:58.904  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:58.904  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:58.904  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:58.905  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:58.906  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:58.906  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.906  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:58.907  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:58.907  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:58.907  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.907  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:23:58.909  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-23 09:23:58.912  4801  4826 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:23:58.913  4801  4826 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:23:58.913  4801  4826 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 09:23:58.913  4801  4826 E SarControlService: no key has been found,reset the power
09-23 09:23:58.913  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:23:58.913  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:23:58.914  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-23 09:23:58.914  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:23:58.914  4830  4830 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 09:23:58.916  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 09:23:58.916  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:23:58.916  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:23:58.916  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-23 09:23:58.917  4830  4830 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:23:58.921  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000ee03000000000000ffffffff]
09-23 09:23:58.921  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:23:58.921  4830  4844 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-23 09:23:58.921  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:23:58.921  4801  4812 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:23:58.922  3834  3834 D SystemUpdateService: onCreate
09-23 09:23:58.923  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000ef03000000000000ffffffff]
,09-23 09:23:58.923  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:23:58.923  4830  4844 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-23 09:23:58.923  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:23:58.924  4801  4811 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 09:23:58.926  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 09:23:58.930  3834  5554 I SystemUpdateService: active receiver: enabled
,09-23 09:23:58.934  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 09:23:58.939  3834  5133 I iu.UploadsManager: num queued entries: 0
,09-23 09:23:58.939  3834  5133 I iu.UploadsManager: num updated entries: 0
09-23 09:23:58.940  3834  5133 I iu.SyncManager: NEXT; no task
,09-23 09:23:58.942  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 09:23:58.944  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:23:58.945  5485  5485 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:23:58.949  5485  5485 D SprintDMHelper: simOperator: 
09-23 09:23:58.949  5485  5485 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:23:58.953   507   925 E Netd    : netlink response contains error (No such file or directory)
09-23 09:23:58.954   930  2890 D DhcpClient: doQuit
,09-23 09:23:58.954   930  2890 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 09:23:58.954   930  5523 D DhcpClient: onQuitting
09-23 09:23:58.955  5518  5518 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-23 09:23:58.957  3834  5554 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:23:58.959  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:58.959  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:23:58.960  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.960  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:58.960  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:58.961  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:58.961  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:23:58.961  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:23:58.961  4216  5558 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 09:23:58.962  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:23:58.962  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:23:58.962  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:23:58.962  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:23:58.967  5518  5518 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-23 09:23:58.968  3834  5554 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-23 09:23:58.968  3834  5554 I SystemUpdateService: now status is 0 (complete)
09-23 09:23:58.968  3834  5554 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 09:23:58.968  3834  5554 I SystemUpdateService: file has been verified
09-23 09:23:58.968  3834  5554 I SystemUpdateService: OTA package size = 21989297
,09-23 09:23:58.971  5518  5518 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-23 09:23:58.983  3834  5554 I SystemUpdateService: showing system update notification
,09-23 09:23:58.990  3834  3834 D SystemUpdateService: onDestroy
,09-23 09:23:59.001  5518  5518 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 09:23:59.012  5518  5518 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 09:23:59.114   930  2890 D wifi    : In wifi stop Hal
09-23 09:23:59.114   930  2890 D wifi    : halHandle = 0x7f60fe3360, mVM = 0x7f7cdcd140, mCls = 0x10196a
09-23 09:23:59.115   930  5517 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 09:23:59.115   930  5517 D WifiHAL : Got a signal to exit!!!
09-23 09:23:59.115   930  5517 I WifiHAL : Exit wifi_event_loop
09-23 09:23:59.116  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 09:23:59.117   930  2890 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 09:23:59.117   930  2890 E WifiHAL : Event processing terminated
09-23 09:23:59.118   930  2890 D wifi    : In wifi cleaned up handler
09-23 09:23:59.118   930  2890 I WifiHAL : Internal cleanup completed
09-23 09:23:59.119  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:23:59.122  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:59.125  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:23:59.127  3382  3960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 09:23:59.149   930  5517 D wifi    : set interface wlan0 flags (DOWN)
,09-23 09:23:59.149   930  2890 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 09:23:59.356   930   947 D Tethering: InitialState.processMessage what=4
09-23 09:23:59.362   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 09:23:59.641   930  2892 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 09:24:01.038   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:02.039   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:03.040   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:03.864   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba3dbb7:true
,09-23 09:24:03.865  5471  5471 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 09:24:03.870  5471  5471 I bt_bluedroid: init
,09-23 09:24:03.870  5471  5560 I BluetoothAdapterState: Entering OffState
,09-23 09:24:03.873  5471  5561 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 09:24:03.874  5471  5561 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 09:24:03.874  5471  5561 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 09:24:03.874  5471  5561 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 09:24:03.875  5471  5471 I bt_bluedroid: get_profile_interface socket
,09-23 09:24:03.877  5471  5564 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 09:24:03.877  5471  5471 I bt_bluedroid: get_profile_interface sdp
,09-23 09:24:03.881  5471  5564 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 09:24:03.885  5471  5482 I bt_bluedroid: config_hci_snoop_log
,09-23 09:24:03.886   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 09:24:03.892  5471  5560 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 09:24:03.892  5471  5560 D BluetoothAdapterProperties: Setting state to 14
09-23 09:24:03.892  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 09:24:03.894  5471  5560 D BluetoothBondStateMachine: make
,09-23 09:24:03.896  5471  5565 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 09:24:03.900  5471  5560 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:24:03.901  5471  5471 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 09:24:03.904  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:03.905  5471  5471 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 09:24:03.905  5471  5471 D BtGatt.GattService: Received start request. Starting profile...
,09-23 09:24:03.906  5471  5471 D BtGatt.GattService: start()
09-23 09:24:03.906  5471  5471 I bt_bluedroid: get_profile_interface gatt
,09-23 09:24:03.907  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:03.907  5471  5471 D BtGatt.AdvertiseManager: advertise manager created
,09-23 09:24:03.914  5471  5471 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:24:03.914  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:03.915  5471  5471 V BluetoothAdapterState: isBleTurningOn()=true
09-23 09:24:03.915  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:03.915  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 09:24:03.917  5471  5560 I bt_bluedroid: bt_bluedroid
,09-23 09:24:03.917  5471  5561 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 09:24:03.918  5471  5561 I bt_hci  : start_up
,09-23 09:24:03.924  5471  5561 I bt_vendor: alloc value 0xf3c38871
,09-23 09:24:03.924  5471  5561 I bt_vendor: init
09-23 09:24:03.924  5471  5561 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 09:24:03.925  5471  5561 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 09:24:04.035  5471  5561 D bt_hci  : start_up starting async portion
,09-23 09:24:04.035  5471  5568 I bt_hci  : event_finish_startup
09-23 09:24:04.036  5471  5568 I bt_hci_h4: hal_open
,09-23 09:24:04.036  5471  5568 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 09:24:04.032  5569  5569 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-23 09:24:04.039  5471  5568 I bt_userial_vendor: device fd = 54 open
,09-23 09:24:04.041   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:04.054  5471  5568 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 09:24:04.056  5471  5568 D bt_hwcfg: Chipset BCM4358A3
,09-23 09:24:04.056  5471  5568 D bt_hwcfg: Target name = [BCM4358A3]
09-23 09:24:04.056  5471  5568 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 09:24:04.436  5471  5568 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-23 09:24:04.436  5471  5568 D bt_hwcfg: Settlement delay -- 100 ms
09-23 09:24:04.436  5471  5568 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 09:24:04.570  5471  5568 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 09:24:04.571  5471  5568 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 09:24:04.572  5471  5568 I bt_hwcfg: vendor lib fwcfg completed
09-23 09:24:04.572  5471  5568 I bt_vendor: firmware callback
09-23 09:24:04.572  5471  5568 I bt_hci  : firmware_config_callback
,09-23 09:24:04.582  5471  5571 I bt_btu  : btu_task pending for preload complete event
,09-23 09:24:04.583  5471  5571 I bt_btu_task: Bluetooth chip preload is complete
09-23 09:24:04.583  5471  5571 I bt_btu  : btu_task received preload complete event
,09-23 09:24:04.589  5471  5571 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 09:24:04.590  5471  5571 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 09:24:04.591  5471  5571 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 09:24:04.591  5471  5571 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 09:24:04.591  5471  5571 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 09:24:04.591  5471  5571 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 09:24:04.591  5471  5571 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 09:24:04.591  5471  5571 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 09:24:04.672  5471  5571 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bb6549
,09-23 09:24:04.672  5471  5571 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bb6549 
,09-23 09:24:04.694  5471  5564 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 09:24:04.696  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 09:24:04.697  5471  5564 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 09:24:04.699  5471  5564 D BluetoothAdapterProperties: Name is: Nexus 6P
09-23 09:24:04.701  5471  5564 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:24:04.702  5471  5564 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-23 09:24:04.702  5471  5564 D bt_hci  : do_postload posting postload work item
,09-23 09:24:04.702  5471  5568 I bt_hci  : event_postload
09-23 09:24:04.702  5471  5568 I bt_vendor: sco_config_cb
09-23 09:24:04.702  5471  5568 I bt_hci  : sco_config_callback postload finished.
09-23 09:24:04.706  5471  5564 D bt_bte_conf: Device ID record 1 : primary
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   vendorId            = 000f
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   vendorIdSource      = 0001
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   product             = 1200
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   version             = 1436
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   clientExecutableURL = 
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   serviceDescription  = 
09-23 09:24:04.707  5471  5564 D bt_bte_conf:   documentationURL    = 
09-23 09:24:04.707  5471  5564 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 09:24:04.708  5471  5561 D bt_stack_manager: event_start_up_stack finished
,09-23 09:24:04.709  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 09:24:04.709  5471  5560 D BluetoothAdapterProperties: Setting state to 15
09-23 09:24:04.709  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 09:24:04.711  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:04.715  5471  5560 I BluetoothAdapterState: Entering BleOnState
,09-23 09:24:04.715  5471  5568 I bt_vendor: low_power_mode_cb
,09-23 09:24:04.717  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:04.717  5471  5560 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 09:24:04.718  5471  5560 D BluetoothAdapterProperties: Setting state to 11
09-23 09:24:04.718  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-23 09:24:04.718  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:04.722  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:04.723  5471  5471 D HeadsetService: Received start request. Starting profile...
,09-23 09:24:04.725  5471  5471 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 09:24:04.725  5471  5471 D HeadsetStateMachine: make
,09-23 09:24:04.731  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:04.733  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:04.734  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:04.737  5471  5560 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:24:04.739  5471  5471 D HeadsetStateMachine: max_hf_connections = 1
09-23 09:24:04.740  5471  5471 I bt_bluedroid: get_profile_interface handsfree
09-23 09:24:04.740  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 09:24:04.740  5471  5564 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-23 09:24:04.743  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:04.744  5471  5471 D A2dpService: Received start request. Starting profile...
,09-23 09:24:04.744  5471  5471 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 09:24:04.745  5471  5471 I bt_bluedroid: get_profile_interface avrcp
,09-23 09:24:04.750  5471  5471 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 09:24:04.750  5471  5471 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 09:24:04.750  5471  5471 D A2dpStateMachine: make
09-23 09:24:04.751  5471  5471 I bt_bluedroid: get_profile_interface a2dp
,09-23 09:24:04.752  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 09:24:04.753  5471  5580 D A2dpStateMachine: Enter Disconnected: -2
,09-23 09:24:04.754  5471  5471 I BluetoothHidServiceJni: classInitNative: succeeds
09-23 09:24:04.754  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:04.756  5407  5407 D BluetoothInputDevice: Proxy object connected
09-23 09:24:04.756  5471  5471 D HidService: Received start request. Starting profile...
09-23 09:24:04.756  5471  5471 I bt_bluedroid: get_profile_interface hidhost
09-23 09:24:04.756  5471  5471 D HidService: setHidService(): set to: null
09-23 09:24:04.756  5471  5564 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9756d
09-23 09:24:04.756  5407  5407 D HidProfile: Bluetooth service connected
09-23 09:24:04.757  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 09:24:04.758  5471  5471 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-23 09:24:04.759  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:04.759  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:24:04.760  5471  5471 D HealthService: Received start request. Starting profile...
,09-23 09:24:04.762  5471  5471 I bt_bluedroid: get_profile_interface health
,09-23 09:24:04.762  5471  5471 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 09:24:04.763  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:04.764  5407  5407 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:24:04.764  5407  5407 D PanProfile: Bluetooth service connected
,09-23 09:24:04.765  5471  5471 D PanService: Received start request. Starting profile...
,09-23 09:24:04.765  5471  5471 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-23 09:24:04.765  5471  5471 I bt_bluedroid: get_profile_interface pan
09-23 09:24:04.766  5471  5564 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 09:24:04.767  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:04.769  5407  5407 D BluetoothMap: Proxy object connected
09-23 09:24:04.769  5471  5471 D BluetoothMapService: Received start request. Starting profile...
09-23 09:24:04.769  5471  5471 D BluetoothMapService: start()
09-23 09:24:04.769  5407  5407 D MapProfile: Bluetooth service connected
09-23 09:24:04.769  5407  5407 D BluetoothMap: getConnectedDevices()
,09-23 09:24:04.770  5407  5407 D BluetoothMap: Bluetooth is Not enabled
09-23 09:24:04.771  5471  5471 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 09:24:04.772  5471  5471 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-23 09:24:04.772  5471  5471 D BluetoothMapAppObserver: createReceiver()
09-23 09:24:04.773  5471  5471 D BluetoothMapAppObserver: initObservers()
09-23 09:24:04.773  5471  5471 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 09:24:04.779  5471  5471 V SapService: SapBinder()
,09-23 09:24:04.779  5471  5471 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:04.779  5471  5471 D SapService: Received start request. Starting profile...
09-23 09:24:04.779  5471  5471 V SapService: start()
,09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:04.782  5471  5577 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:04.782  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isTurningOn()=true
,09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isTurningOn()=true
,09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:04.783  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.784  5471  5471 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:04.784  5471  5471 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:04.784  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:04.784  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.786  5471  5471 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:04.786  5471  5471 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:04.786  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 09:24:04.786  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:04.786  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 09:24:04.786  5471  5560 D BluetoothAdapterProperties: ScanMode =  20
09-23 09:24:04.786  5471  5560 D BluetoothAdapterProperties: State =  11
09-23 09:24:04.787  5471  5560 D BluetoothAdapterProperties: Setting state to 12
09-23 09:24:04.787  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 09:24:04.787   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:04.787  5471  5560 I BluetoothAdapterState: Entering OnState
09-23 09:24:04.787  3047  3060 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:24:04.789  5471  5564 D BluetoothAdapterProperties: Scan Mode:21
09-23 09:24:04.790  5471  5564 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 09:24:04.790  3047  3047 D BluetoothInputDevice: Proxy object connected
,09-23 09:24:04.790  3047  3047 D HidProfile: Bluetooth service connected
09-23 09:24:04.790   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 09:24:04.790   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:24:04.791  3047  3586 D BluetoothMap: onBluetoothStateChange: up=true
09-23 09:24:04.792   930   930 D BluetoothA2dp: Proxy object connected
,09-23 09:24:04.793  3437  3459 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 09:24:04.794  3047  3047 D BluetoothMap: Proxy object connected
09-23 09:24:04.794  3047  3047 D MapProfile: Bluetooth service connected
09-23 09:24:04.794  3047  3047 D BluetoothMap: getConnectedDevices()
09-23 09:24:04.794  3047  3060 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:24:04.796  3047  3047 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:24:04.796  3047  3586 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:04.796  3047  3047 D PanProfile: Bluetooth service connected
,09-23 09:24:04.797  5407  5419 D BluetoothPbap: onBluetoothStateChange: up=true
,09-23 09:24:04.798  5471  5471 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 09:24:04.798  5407  5418 D BluetoothMap: onBluetoothStateChange: up=true
09-23 09:24:04.798  3047  3058 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:24:04.798  5471  5471 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 09:24:04.799  5471  5471 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:04.799  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:24:04.800   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:04.800  3047  3047 D BluetoothA2dp: Proxy object connected
,09-23 09:24:04.801  3047  3640 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 09:24:04.801  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:04.802  5407  5419 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:24:04.802  5471  5471 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:24:04.802  5407  5418 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:24:04.804   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:04.805  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:04.807  5407  5407 D LocalBluetoothProfileManager: Adding local A2DP profile
09-23 09:24:04.807  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:04.807  5471  5471 D ObexServerSockets: Succeed to create listening sockets 
09-23 09:24:04.807  5471  5471 D ObexServerSockets0: startAccept()
09-23 09:24:04.807  5471  5471 D ObexServerSockets0: prepareForNewConnect()
09-23 09:24:04.810  5471  5471 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 09:24:04.810  5471  5471 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 09:24:04.811  5407  5407 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:04.811  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:04.811  5471  5471 D BluetoothMapService: onReceive
09-23 09:24:04.811  5471  5471 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:24:04.812  5471  5471 D BluetoothMapService: STATE_ON
09-23 09:24:04.812  5471  5588 D ObexServerSockets0: Accepting socket connection...
09-23 09:24:04.812  5471  5587 D ObexServerSockets0: Accepting socket connection...
,09-23 09:24:04.814  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:04.815  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:04.815  5471  5589 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:04.816  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:04.817  5471  5589 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 09:24:04.817  5471  5589 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 09:24:04.817  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:04.820  5407  5407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 09:24:04.823  5407  5407 D BluetoothA2dp: Proxy object connected
,09-23 09:24:04.830  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:24:04.832  5407  5407 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:24:04.836  3047  3047 D BluetoothPbap: Proxy object connected
,09-23 09:24:04.836  5407  5407 D BluetoothPbap: Proxy object connected
09-23 09:24:04.836  3047  3047 D PbapServerProfile: Bluetooth service connected
09-23 09:24:04.836  5471  5471 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 09:24:04.836  5471  5471 D ObexServerSockets0: prepareForNewConnect()
09-23 09:24:04.837  5407  5407 D PbapServerProfile: Bluetooth service connected
,09-23 09:24:04.842  5471  5593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:04.858  5471  5597 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:04.859  5471  5597 I BtOppRfcommListener: Accept thread started.
,09-23 09:24:04.889   930   930 D BluetoothHeadset: Proxy object connected
,09-23 09:24:04.889   930   930 D BluetoothHeadset: Proxy object connected
09-23 09:24:04.889  3047  3060 D BluetoothHeadset: Proxy object connected
09-23 09:24:04.889  3047  3047 D HeadsetProfile: Bluetooth service connected
09-23 09:24:04.890  3437  3464 D BluetoothHeadset: Proxy object connected
09-23 09:24:04.890   930   947 D BluetoothHeadset: Proxy object connected
,09-23 09:24:04.890   930   930 D BluetoothHeadset: Proxy object connected
,09-23 09:24:04.895  3437  3747 D BluetoothHeadset: Proxy object connected
,09-23 09:24:04.896  3047  3058 D BluetoothHeadset: Proxy object connected
09-23 09:24:04.897  3047  3047 D HeadsetProfile: Bluetooth service connected
,09-23 09:24:04.901   930   947 D BluetoothHeadset: Proxy object connected
,09-23 09:24:04.914  5407  5418 D BluetoothHeadset: Proxy object connected
,09-23 09:24:04.915  5407  5407 D HeadsetProfile: Bluetooth service connected
,09-23 09:24:05.042   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:06.043   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 09:24:06.595   930  2892 D ConnectivityService: handlePromptUnvalidated 101
,09-23 09:24:08.842  5471  5560 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 09:24:08.842  5471  5560 D BluetoothAdapterProperties: Setting state to 13
09-23 09:24:08.842  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-23 09:24:08.843  5471  5560 D BluetoothAdapterProperties: onBluetoothDisable()
,09-23 09:24:08.845  5471  5560 I BluetoothAdapterState: Entering PendingCommandState
09-23 09:24:08.850  5471  5471 D BluetoothMapService: onReceive
,09-23 09:24:08.850  5471  5471 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:24:08.850  5471  5471 D BluetoothMapService: STATE_TURNING_OFF
09-23 09:24:08.850  5471  5471 D BluetoothMapService: MAP Service closeService in
09-23 09:24:08.850  5471  5471 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 09:24:08.850  5471  5471 D ObexServerSockets0: shutdown(block = true)
09-23 09:24:08.851  5471  5471 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 09:24:08.851  5471  5587 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 09:24:08.852  5471  5471 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-23 09:24:08.852  5471  5588 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 09:24:08.853  5471  5573 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 09:24:08.854  5471  5471 I BtOppRfcommListener: stopping Accept Thread
09-23 09:24:08.854  5471  5564 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:24:08.854  5471  5597 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 09:24:08.854  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 09:24:08.855  5471  5597 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 09:24:08.855  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:08.855  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:08.856  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 09:24:08.857  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:24:08.857  5471  5471 D HeadsetService: Received stop request...Stopping profile...
09-23 09:24:08.860   930   930 D BluetoothHeadset: Proxy object disconnected
09-23 09:24:08.860   930   930 D BluetoothHeadset: Proxy object disconnected
09-23 09:24:08.861  3047  3058 D BluetoothHeadset: Proxy object disconnected
09-23 09:24:08.861  5407  5407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:24:08.861  3437  3682 D BluetoothHeadset: Proxy object disconnected
09-23 09:24:08.862   930   930 D BluetoothHeadset: Proxy object disconnected
09-23 09:24:08.863  5407  5419 D BluetoothHeadset: Proxy object disconnected
09-23 09:24:08.863  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:08.863  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:08.864  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:24:08.864  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:24:08.866  5407  5407 D HeadsetProfile: Bluetooth service disconnected
09-23 09:24:08.869  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:08.869  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:08.870  5353  5353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 09:24:08.870  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:08.871  5407  5407 D DockEventReceiver: finishStartingService: stopping service
09-23 09:24:08.871  5471  5471 V BluetoothAdapterState: isTurningOff()=true
09-23 09:24:08.871  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.872  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:08.872  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:24:08.872  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.872  5471  5471 D A2dpService: Received stop request...Stopping profile...
09-23 09:24:08.873  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.874  3047  3047 D HeadsetProfile: Bluetooth service disconnected
09-23 09:24:08.874  3047  3047 D BluetoothA2dp: Proxy object disconnected
09-23 09:24:08.874   930   930 D BluetoothA2dp: Proxy object disconnected
09-23 09:24:08.875  5471  5580 D A2dpStateMachine: Exit Disconnected: -1
09-23 09:24:08.875  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.875  5407  5407 D BluetoothA2dp: Proxy object disconnected
09-23 09:24:08.876  5471  5471 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 09:24:08.876  5471  5471 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 09:24:08.876  5471  5571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:24:08.876  5471  5571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:24:08.876  5471  5571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:24:08.877  5471  5471 D HidService: Received stop request...Stopping profile...
09-23 09:24:08.877  5471  5471 D HidService: Stopping Bluetooth HidService
09-23 09:24:08.878  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 09:24:08.878  5471  5564 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 09:24:08.879  3047  3047 D BluetoothInputDevice: Proxy object disconnected
09-23 09:24:08.879  3047  3047 D HidProfile: Bluetooth service disconnected
09-23 09:24:08.879  5407  5407 D BluetoothInputDevice: Proxy object disconnected
09-23 09:24:08.879  5407  5407 D HidProfile: Bluetooth service disconnected
09-23 09:24:08.879  5471  5471 D HealthService: Received stop request...Stopping profile...
09-23 09:24:08.881  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:24:08.882  5471  5471 D PanService: Received stop request...Stopping profile...
09-23 09:24:08.883  3047  3047 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 09:24:08.883  3047  3047 D PanProfile: Bluetooth service disconnected
09-23 09:24:08.883  5471  5471 D BluetoothMapService: Received stop request...Stopping profile...
09-23 09:24:08.883  5471  5471 D BluetoothMapService: stop()
09-23 09:24:08.884  5471  5471 D BluetoothMapAppObserver: deinitObservers()
09-23 09:24:08.884  5471  5471 D BluetoothMapAppObserver: removeReceiver()
,09-23 09:24:08.885  3047  3047 D BluetoothMap: Proxy object disconnected
09-23 09:24:08.885  3047  3047 D MapProfile: Bluetooth service disconnected
,09-23 09:24:08.888  5471  5471 D SapService: Received stop request...Stopping profile...
09-23 09:24:08.888  5471  5471 V SapService: stop()
,09-23 09:24:08.889  5407  5407 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 09:24:08.889  5407  5407 D PanProfile: Bluetooth service disconnected
09-23 09:24:08.889  5407  5407 D BluetoothMap: Proxy object disconnected
09-23 09:24:08.889  5407  5407 D MapProfile: Bluetooth service disconnected
09-23 09:24:08.890  5471  5471 V BluetoothAdapterState: isTurningOff()=true
09-23 09:24:08.890  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.890  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:08.890  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:24:08.891  5471  5571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:24:08.891  5471  5571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 09:24:08.891  5471  5471 V BluetoothAdapterState: isTurningOff()=true
09-23 09:24:08.891  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.891  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 09:24:08.891  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 09:24:08.891  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:08.891  5471  5571 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:24:08.891  5471  5571 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:24:08.891  5471  5571 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 09:24:08.891  5471  5571 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 09:24:08.892  5471  5471 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 09:24:08.892  5471  5471 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 09:24:08.892  5471  5564 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 09:24:08.894  3047  3047 D BluetoothPbap: Proxy object disconnected
09-23 09:24:08.894  3047  3047 D PbapServerProfile: Bluetooth service disconnected
09-23 09:24:08.894  5471  5471 V BluetoothAdapterState: isTurningOff()=true
09-23 09:24:08.894  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.894  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:08.894  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:08.895  5471  5471 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-23 09:24:08.896  5407  5407 D BluetoothPbap: Proxy object disconnected
09-23 09:24:08.896  5407  5407 D PbapServerProfile: Bluetooth service disconnected
,09-23 09:24:08.897  5471  5564 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-23 09:24:08.897  5471  5471 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 09:24:08.897  5471  5471 V BluetoothAdapterState: isTurningOff()=true
,09-23 09:24:08.897  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.897  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:08.898  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:08.898  5471  5471 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 09:24:08.899  5471  5471 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-23 09:24:08.902  5471  5471 D BluetoothMapService: MAP Service closeService in
,09-23 09:24:08.902  5471  5471 V BluetoothAdapterState: isTurningOff()=true
09-23 09:24:08.902  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.902  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:08.902  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:08.902  5471  5471 D BluetoothMapService: cleanup()
09-23 09:24:08.903  5471  5471 D BluetoothMapService: MAP Service closeService in
09-23 09:24:08.903  5471  5471 V BluetoothAdapterState: isTurningOff()=true
09-23 09:24:08.903  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:08.903  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:08.903  5471  5471 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:24:08.903  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 09:24:08.903  5471  5560 D BluetoothAdapterProperties: Setting state to 15
09-23 09:24:08.903  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 09:24:08.904  5471  5560 I BluetoothAdapterState: Entering BleOnState
09-23 09:24:08.904   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:24:08.904  3047  3058 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 09:24:08.905   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 09:24:08.905  5407  5419 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:24:08.906   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:24:08.906  3047  3586 D BluetoothMap: onBluetoothStateChange: up=false
09-23 09:24:08.906  3437  3459 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:24:08.906  3047  3640 D BluetoothPan: onBluetoothStateChange on: false
09-23 09:24:08.907  3047  3060 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 09:24:08.907  5407  5418 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 09:24:08.908  5407  5419 D BluetoothMap: onBluetoothStateChange: up=false
09-23 09:24:08.908  3047  3058 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 09:24:08.909   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 09:24:08.909  3047  3586 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 09:24:08.909  5407  5418 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 09:24:08.909  5407  5419 D BluetoothPan: onBluetoothStateChange on: false
09-23 09:24:08.910  5407  5418 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 09:24:08.911  5471  5560 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 09:24:08.911  5471  5560 D BluetoothAdapterProperties: Setting state to 16
09-23 09:24:08.911  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 09:24:08.912  5471  5560 D BluetoothAdapterProperties: onBleDisable
09-23 09:24:08.912  5471  5560 I BluetoothAdapterState: Entering PendingCommandState
09-23 09:24:08.913  5471  5561 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 09:24:08.914  5471  5564 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:24:08.914  5471  5571 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 09:24:08.914  5471  5571 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 09:24:08.918  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:08.918  5407  5407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 09:24:08.919  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.921  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.922  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.923  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.925  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:08.925  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:24:08.927  5407  5407 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:24:09.125  5471  5564 I bt_hci  : shut_down
,09-23 09:24:09.133  5471  5568 D bt_hwcfg: hw_epilog_process
,09-23 09:24:09.133  5471  5568 I bt_vendor: low_power_mode_cb
,09-23 09:24:09.136  5471  5568 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 09:24:09.136  5471  5568 I bt_vendor: epilog_cb
09-23 09:24:09.136  5471  5568 I bt_hci  : epilog_finished_callback
,09-23 09:24:09.141  5471  5564 I bt_hci_h4: hal_close
,09-23 09:24:09.142  5471  5564 I bt_userial_vendor: device fd = 54 close
,09-23 09:24:09.256  5471  5561 D bt_stack_manager: event_shut_down_stack finished.
,09-23 09:24:09.256  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 09:24:09.260  5471  5560 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-23 09:24:09.260  5471  5471 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 09:24:09.261  5471  5471 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 09:24:09.262  5471  5471 D BtGatt.GattService: stop()
09-23 09:24:09.262  5471  5471 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 09:24:09.265  5471  5471 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:24:09.265  5471  5471 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:09.265  5471  5471 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:09.265  5471  5471 V BluetoothAdapterState: isBleTurningOff()=true
09-23 09:24:09.266  5471  5560 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 09:24:09.266  5471  5560 D BluetoothAdapterProperties: Setting state to 10
09-23 09:24:09.266  5471  5560 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-23 09:24:09.268  5471  5560 I BluetoothAdapterState: Entering OffState
,09-23 09:24:09.268   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-23 09:24:09.282  5471  5471 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 09:24:09.282  5471  5471 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-23 09:24:09.282  5471  5471 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 09:24:09.284  5471  5561 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 09:24:09.289  5471  5471 I art     : System.exit called, status: 0
09-23 09:24:09.290  5471  5471 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 09:24:09.317   930   940 I ActivityManager: Process com.android.bluetooth (pid 5471) has died
,09-23 09:24:13.841  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:24:13.841  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:13.846  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:24:13.847  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5400a97 removed from the list
09-23 09:24:13.847  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:13.847  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:13.847  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:13.849  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:13.850  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30d446d added. We now have 4 listener(s)
09-23 09:24:13.850  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:24:13.851  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:13.852  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30d446d removed from the list
09-23 09:24:13.852  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:13.852  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:13.852  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:13.854  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:13.854  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd88a2 added. We now have 4 listener(s)
09-23 09:24:13.854  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:24:18.866  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:18.903   930   947 I ActivityManager: Start proc 5605:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 09:24:18.989  5605  5605 D AdapterServiceConfig: Adding HeadsetService
,09-23 09:24:18.989  5605  5605 D AdapterServiceConfig: Adding A2dpService
09-23 09:24:18.989  5605  5605 D AdapterServiceConfig: Adding HidService
09-23 09:24:18.989  5605  5605 D AdapterServiceConfig: Adding HealthService
09-23 09:24:18.990  5605  5605 D AdapterServiceConfig: Adding PanService
09-23 09:24:18.990  5605  5605 D AdapterServiceConfig: Adding GattService
09-23 09:24:18.990  5605  5605 D AdapterServiceConfig: Adding BluetoothMapService
09-23 09:24:18.990  5605  5605 D AdapterServiceConfig: Adding SapService
,09-23 09:24:19.001   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9befe4:true
,09-23 09:24:19.001  5605  5605 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 09:24:19.003  5605  5605 I bt_bluedroid: init
,09-23 09:24:19.004  5605  5617 I BluetoothAdapterState: Entering OffState
,09-23 09:24:19.007  5605  5618 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-23 09:24:19.007  5605  5618 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 09:24:19.007  5605  5618 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 09:24:19.007  5605  5618 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-23 09:24:19.008  5605  5605 I bt_bluedroid: get_profile_interface socket
,09-23 09:24:19.009  5605  5605 I bt_bluedroid: get_profile_interface sdp
09-23 09:24:19.009  5605  5621 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 09:24:19.011  5605  5621 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 09:24:19.015  5605  5616 I bt_bluedroid: config_hci_snoop_log
,09-23 09:24:19.016   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-23 09:24:19.020  5605  5617 D BluetoothAdapterState: Current state: OFF, message: 0
,09-23 09:24:19.020  5605  5617 D BluetoothAdapterProperties: Setting state to 14
09-23 09:24:19.020  5605  5617 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 09:24:19.022  5605  5617 D BluetoothBondStateMachine: make
,09-23 09:24:19.024  5605  5622 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 09:24:19.027  5605  5617 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:24:19.028  5605  5605 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 09:24:19.030  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:19.031  5605  5605 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 09:24:19.031  5605  5605 D BtGatt.GattService: Received start request. Starting profile...
09-23 09:24:19.032  5605  5605 D BtGatt.GattService: start()
09-23 09:24:19.032  5605  5605 I bt_bluedroid: get_profile_interface gatt
,09-23 09:24:19.033  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:19.033  5605  5605 D BtGatt.AdvertiseManager: advertise manager created
,09-23 09:24:19.039  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:19.039  5605  5605 V BluetoothAdapterState: isTurningOn()=false
09-23 09:24:19.039  5605  5605 V BluetoothAdapterState: isBleTurningOn()=true
,09-23 09:24:19.039  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:19.039  5605  5617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 09:24:19.040  5605  5617 I bt_bluedroid: bt_bluedroid
,09-23 09:24:19.041  5605  5618 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-23 09:24:19.041  5605  5618 I bt_hci  : start_up
,09-23 09:24:19.046  5605  5618 I bt_vendor: alloc value 0xf3cab871
,09-23 09:24:19.046  5605  5618 I bt_vendor: init
09-23 09:24:19.046  5605  5618 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 09:24:19.046  5605  5618 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 09:24:19.156  5605  5618 D bt_hci  : start_up starting async portion
09-23 09:24:19.156  5605  5625 I bt_hci  : event_finish_startup
,09-23 09:24:19.156  5605  5625 I bt_hci_h4: hal_open
09-23 09:24:19.156  5605  5625 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 09:24:19.155  5626  5626 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-23 09:24:19.159  5605  5625 I bt_userial_vendor: device fd = 54 open
,09-23 09:24:19.174  5605  5625 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 09:24:19.177  5605  5625 D bt_hwcfg: Chipset BCM4358A3
09-23 09:24:19.177  5605  5625 D bt_hwcfg: Target name = [BCM4358A3]
,09-23 09:24:19.177  5605  5625 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 09:24:19.670  5605  5625 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 09:24:19.670  5605  5625 D bt_hwcfg: Settlement delay -- 100 ms
09-23 09:24:19.670  5605  5625 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 09:24:19.804  5605  5625 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 09:24:19.804  5605  5625 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 09:24:19.806  5605  5625 I bt_hwcfg: vendor lib fwcfg completed
,09-23 09:24:19.806  5605  5625 I bt_vendor: firmware callback
,09-23 09:24:19.807  5605  5625 I bt_hci  : firmware_config_callback
09-23 09:24:19.816  5605  5628 I bt_btu  : btu_task pending for preload complete event
,09-23 09:24:19.816  5605  5628 I bt_btu_task: Bluetooth chip preload is complete
09-23 09:24:19.816  5605  5628 I bt_btu  : btu_task received preload complete event
,09-23 09:24:19.824  5605  5628 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 09:24:19.825  5605  5628 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 09:24:19.825  5605  5628 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-23 09:24:19.825  5605  5628 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 09:24:19.825  5605  5628 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-23 09:24:19.825  5605  5628 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 09:24:19.825  5605  5628 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_BTM
,09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 09:24:19.826  5605  5628 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 09:24:19.923  5605  5628 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c29549
09-23 09:24:19.923  5605  5628 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c29549 
,09-23 09:24:19.939  5605  5621 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 09:24:19.942  5605  5621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 09:24:19.942  5605  5621 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 09:24:19.945  5605  5621 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 09:24:19.949  5605  5621 D BluetoothAdapterProperties: Scan Mode:20
09-23 09:24:19.949  5605  5621 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 09:24:19.949  5605  5621 D bt_hci  : do_postload posting postload work item
,09-23 09:24:19.950  5605  5625 I bt_hci  : event_postload
,09-23 09:24:19.950  5605  5625 I bt_vendor: sco_config_cb
09-23 09:24:19.950  5605  5625 I bt_hci  : sco_config_callback postload finished.
,09-23 09:24:19.953  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:19.957  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:19.960  5605  5621 D bt_bte_conf: Device ID record 1 : primary
09-23 09:24:19.960  5605  5621 D bt_bte_conf:   vendorId            = 000f
09-23 09:24:19.960  5605  5621 D bt_bte_conf:   vendorIdSource      = 0001
09-23 09:24:19.960  5605  5625 I bt_vendor: low_power_mode_cb
09-23 09:24:19.960  5605  5621 D bt_bte_conf:   product             = 1200
09-23 09:24:19.960  5605  5621 D bt_bte_conf:   version             = 1436
09-23 09:24:19.960  5605  5621 D bt_bte_conf:   clientExecutableURL = 
09-23 09:24:19.960  5605  5621 D bt_bte_conf:   serviceDescription  = 
,09-23 09:24:19.960  5605  5621 D bt_bte_conf:   documentationURL    = 
09-23 09:24:19.961  5605  5621 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-23 09:24:19.961  5605  5618 D bt_stack_manager: event_start_up_stack finished
09-23 09:24:19.961  5605  5617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 09:24:19.962  5605  5617 D BluetoothAdapterProperties: Setting state to 15
,09-23 09:24:19.962  5605  5617 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 09:24:19.963  5605  5617 I BluetoothAdapterState: Entering BleOnState
,09-23 09:24:19.968  5605  5617 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 09:24:19.968  5605  5617 D BluetoothAdapterProperties: Setting state to 11
,09-23 09:24:19.968  5605  5617 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 09:24:19.973  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:19.973  5605  5605 D HeadsetService: Received start request. Starting profile...
,09-23 09:24:19.976  5605  5605 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 09:24:19.979  5605  5605 D HeadsetStateMachine: make
,09-23 09:24:19.980  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:19.982  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:19.991  5605  5605 D HeadsetStateMachine: max_hf_connections = 1
,09-23 09:24:19.991  5605  5605 I bt_bluedroid: get_profile_interface handsfree
09-23 09:24:19.992  5605  5621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-23 09:24:19.992  5605  5621 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-23 09:24:19.995  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:19.996  5605  5605 D A2dpService: Received start request. Starting profile...
09-23 09:24:19.997  5605  5605 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 09:24:19.997  5605  5605 I bt_bluedroid: get_profile_interface avrcp
09-23 09:24:19.998  5605  5617 I BluetoothAdapterState: Entering PendingCommandState
,09-23 09:24:20.003  5605  5605 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-23 09:24:20.003  5605  5605 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 09:24:20.003  5605  5605 D A2dpStateMachine: make
,09-23 09:24:20.005  5605  5605 I bt_bluedroid: get_profile_interface a2dp
,09-23 09:24:20.005  5605  5621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 09:24:20.007  5605  5636 D A2dpStateMachine: Enter Disconnected: -2
,09-23 09:24:20.008  5605  5605 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 09:24:20.009  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:20.010  5605  5605 D HidService: Received start request. Starting profile...
09-23 09:24:20.010  5605  5605 I bt_bluedroid: get_profile_interface hidhost
09-23 09:24:20.010  5605  5605 D HidService: setHidService(): set to: null
09-23 09:24:20.011  5605  5621 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c0a56d
09-23 09:24:20.011  5605  5621 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-23 09:24:20.014  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 09:24:20.014  5605  5605 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-23 09:24:20.015  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:20.016  5605  5605 D HealthService: Received start request. Starting profile...
09-23 09:24:20.018  5605  5605 I bt_bluedroid: get_profile_interface health
,09-23 09:24:20.019  5605  5605 V BluetoothAdapterState: isTurningOff()=false
,09-23 09:24:20.019  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.019  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.019  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:20.019  5605  5605 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 09:24:20.020  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:20.020  5605  5605 D PanService: Received start request. Starting profile...
09-23 09:24:20.021  5605  5605 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 09:24:20.021  5605  5605 I bt_bluedroid: get_profile_interface pan
09-23 09:24:20.023  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:20.024  5605  5605 D BluetoothMapService: Received start request. Starting profile...
09-23 09:24:20.024  5605  5605 D BluetoothMapService: start()
09-23 09:24:20.025  5605  5621 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 09:24:20.027  5605  5605 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 09:24:20.027  5605  5605 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 09:24:20.028  5605  5605 D BluetoothMapAppObserver: createReceiver()
09-23 09:24:20.029  5605  5605 D BluetoothMapAppObserver: initObservers()
09-23 09:24:20.029  5605  5605 D BluetoothMapAppObserver: getEnabledAccountItems()
09-23 09:24:20.035  5605  5634 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 09:24:20.036  5605  5605 V SapService: SapBinder()
09-23 09:24:20.036  5605  5605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
,09-23 09:24:20.036  5605  5605 D SapService: Received start request. Starting profile...
09-23 09:24:20.036  5605  5605 V SapService: start()
,09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.037  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.038  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 09:24:20.039  5605  5605 V BluetoothAdapterState: isTurningOff()=false
09-23 09:24:20.039  5605  5605 V BluetoothAdapterState: isTurningOn()=true
09-23 09:24:20.039  5605  5605 V BluetoothAdapterState: isBleTurningOn()=false
09-23 09:24:20.039  5605  5605 V BluetoothAdapterState: isBleTurningOff()=false
09-23 09:24:20.039  5605  5617 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-23 09:24:20.039  5605  5617 D BluetoothAdapterProperties: ScanMode =  20
09-23 09:24:20.039  5605  5617 D BluetoothAdapterProperties: State =  11
09-23 09:24:20.040  5605  5617 D BluetoothAdapterProperties: Setting state to 12
09-23 09:24:20.040  5605  5617 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 09:24:20.040  5605  5617 I BluetoothAdapterState: Entering OnState
09-23 09:24:20.040   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:20.041  3047  3058 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:24:20.042  5605  5621 D BluetoothAdapterProperties: Scan Mode:21
09-23 09:24:20.042  5605  5621 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 09:24:20.044   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 09:24:20.044  5407  5419 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:20.045  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:20.045  3047  3047 D BluetoothInputDevice: Proxy object connected
09-23 09:24:20.045  3047  3047 D HidProfile: Bluetooth service connected
09-23 09:24:20.046   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 09:24:20.047  3047  3060 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 09:24:20.048  5407  5407 D BluetoothA2dp: Proxy object connected
,09-23 09:24:20.048   930   930 D BluetoothA2dp: Proxy object connected
,09-23 09:24:20.053  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:24:20.053  3437  3459 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:20.054  3047  3058 D BluetoothPan: onBluetoothStateChange on: true
09-23 09:24:20.054  3047  3047 D BluetoothMap: Proxy object connected
09-23 09:24:20.054  3047  3047 D MapProfile: Bluetooth service connected
,09-23 09:24:20.054  3047  3047 D BluetoothMap: getConnectedDevices()
09-23 09:24:20.056  5605  5605 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:20.056  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 09:24:20.057  5605  5605 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 09:24:20.059  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:20.059  3047  3640 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:20.060  5605  5605 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:20.060  5407  5419 D BluetoothPbap: onBluetoothStateChange: up=true
,09-23 09:24:20.062  5605  5605 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:20.062  5407  5418 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 09:24:20.063  5605  5605 D ObexServerSockets: Succeed to create listening sockets 
,09-23 09:24:20.063  5605  5605 D ObexServerSockets0: startAccept()
09-23 09:24:20.063  5605  5605 D ObexServerSockets0: prepareForNewConnect()
09-23 09:24:20.065  3047  3060 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 09:24:20.066  5605  5605 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-23 09:24:20.066  5605  5605 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 09:24:20.066  5605  5644 D ObexServerSockets0: Accepting socket connection...
09-23 09:24:20.067  3047  3047 D BluetoothA2dp: Proxy object connected
09-23 09:24:20.067   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:20.067  5605  5645 D ObexServerSockets0: Accepting socket connection...
09-23 09:24:20.068  3047  3060 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 09:24:20.069  3047  3047 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:24:20.069  3047  3047 D PanProfile: Bluetooth service connected
,09-23 09:24:20.070  5407  5419 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 09:24:20.070  5407  5418 D BluetoothPan: onBluetoothStateChange on: true
,09-23 09:24:20.072  5407  5419 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 09:24:20.074  5407  5407 D BluetoothMap: Proxy object connected
09-23 09:24:20.074  5407  5407 D MapProfile: Bluetooth service connected
,09-23 09:24:20.074  5407  5407 D BluetoothMap: getConnectedDevices()
09-23 09:24:20.075   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 09:24:20.076  5605  5605 D BluetoothMapService: onReceive
09-23 09:24:20.076  5605  5605 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 09:24:20.076  5605  5605 D BluetoothMapService: STATE_ON
09-23 09:24:20.076  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:20.077  5605  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:24:20.077  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:20.077  5407  5407 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 09:24:20.077  5407  5407 D PanProfile: Bluetooth service connected
09-23 09:24:20.077  5407  5407 D BluetoothInputDevice: Proxy object connected
,09-23 09:24:20.077  5407  5407 D HidProfile: Bluetooth service connected
09-23 09:24:20.078  5605  5646 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 09:24:20.078  5605  5646 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-23 09:24:20.082  5407  5407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 09:24:20.088  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 09:24:20.090  5407  5407 D DockEventReceiver: finishStartingService: stopping service
,09-23 09:24:20.094  5407  5407 D BluetoothPbap: Proxy object connected
09-23 09:24:20.094  5407  5407 D PbapServerProfile: Bluetooth service connected
,09-23 09:24:20.100  5605  5605 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 09:24:20.100  5605  5605 D ObexServerSockets0: prepareForNewConnect()
,09-23 09:24:20.105  5605  5650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:20.109  3047  3047 D BluetoothPbap: Proxy object connected
09-23 09:24:20.109  3047  3047 D PbapServerProfile: Bluetooth service connected
,09-23 09:24:20.117  5605  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 09:24:20.120  5605  5654 I BtOppRfcommListener: Accept thread started.
,09-23 09:24:20.142   930   930 D BluetoothHeadset: Proxy object connected
,09-23 09:24:20.142   930   930 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.143  3047  3058 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.143  3047  3047 D HeadsetProfile: Bluetooth service connected
09-23 09:24:20.143  3437  3464 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.143   930   930 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.143  5407  5418 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.144   930   947 D BluetoothHeadset: Proxy object connected
,09-23 09:24:20.145  5407  5407 D HeadsetProfile: Bluetooth service connected
,09-23 09:24:20.154  3437  3747 D BluetoothHeadset: Proxy object connected
,09-23 09:24:20.159  3047  3586 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.160  3047  3047 D HeadsetProfile: Bluetooth service connected
,09-23 09:24:20.168   930   947 D BluetoothHeadset: Proxy object connected
,09-23 09:24:20.171  5407  5419 D BluetoothHeadset: Proxy object connected
09-23 09:24:20.171  5407  5407 D HeadsetProfile: Bluetooth service connected
,09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:23.884  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:24:23.889  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 09:24:23.890  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:23.890  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd88a2 removed from the list
09-23 09:24:23.890  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:23.891  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:24:23.891  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:23.892  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:23.893  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@670b933 added. We now have 4 listener(s)
09-23 09:24:23.893  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:24:23.896   930  3447 D WifiService: setWifiEnabled: false pid=5353, uid=10077
09-23 09:24:23.897   930  3447 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:24:26.044   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:27.045   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:28.046   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:28.906  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:28.907   930  3335 D WifiService: setWifiEnabled: true pid=5353, uid=10077
09-23 09:24:28.908   930  3335 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 09:24:28.919   507   925 D SoftapController: Softap fwReload - Ok
,09-23 09:24:28.923   507   925 D CommandListener: Setting iface cfg
,09-23 09:24:28.924   507   925 D CommandListener: Trying to bring down wlan0
09-23 09:24:28.926   507   925 D CommandListener: Clearing all IP addresses on wlan0
,09-23 09:24:28.931   930  2890 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 09:24:29.048   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:29.612   930  2890 D wifi    : set interface wlan0 flags (UP)
09-23 09:24:29.614   930  2890 I WifiHAL : Initializing wifi
09-23 09:24:29.614   930  2890 I WifiHAL : Creating socket
09-23 09:24:29.620   930  2890 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-23 09:24:29.620   930  2890 D wifi    : Did set static halHandle = 0x7f60fe3360
09-23 09:24:29.621   930  2890 D wifi    : halHandle = 0x7f60fe3360, mVM = 0x7f7cdcd140, mCls = 0x1692
09-23 09:24:29.621   930  2890 D wifi    : array field set
,09-23 09:24:29.621   930  2890 I WifiNative-HAL: interface[0] = wlan0
09-23 09:24:29.626   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-23 09:24:29.629   930  5661 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547088118624
09-23 09:24:29.629   930  5661 D wifi    : waitForHalEvents called, vm = 0x7f7cdcd140, obj = 0x1692, env = 0x7f635e9ac0
,09-23 09:24:29.689  5662  5662 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 09:24:29.711  5662  5662 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:24:29.722  5662  5662 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 09:24:29.722  5662  5662 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 09:24:29.725   930  2890 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 09:24:29.736  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:29.739  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:29.745   930  2890 D WifiConfigStore: Loading config and enabling all networks 
,09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:29.747  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:24:29.749  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 09:24:29.753  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 09:24:29.756  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 09:24:29.756   930  2890 D WifiConfigStore: loaded 0 passpoint configs
,09-23 09:24:29.757   930  2890 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 09:24:29.757   930  2890 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 09:24:29.758   930  2890 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-23 09:24:29.759   930  2890 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 09:24:29.760   930  2890 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 09:24:29.760   930  2890 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 09:24:29.760   930  2890 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 09:24:29.764   930  2890 D WifiNative-HAL: Setting external_sim to 1
,09-23 09:24:29.764  4216  4216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 09:24:29.764   930  2890 D wifi    : setting dfs flag to true, 0x7f61348e00
09-23 09:24:29.765   930  2890 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 09:24:29.765   930  2890 D wifi    : setting scan oui 0x7f61348e00
09-23 09:24:29.765   930  2890 D WifiHAL : Sending mac address OUI
,09-23 09:24:29.769   930  2890 E native  : do suspend false
,09-23 09:24:29.778   930  2890 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 09:24:29.778   930   930 D RttService: SCAN_AVAILABLE : 3
09-23 09:24:29.778   507   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 09:24:29.779   930  2999 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 09:24:29.780   507   925 D CommandListener: Setting iface cfg
,09-23 09:24:29.784   930  2889 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '97 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 97 Failed to set address (No such device)'
,09-23 09:24:29.784   930  2889 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 09:24:29.796   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303311 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-23 09:24:29.797   930  2889 D WifiNative-HAL: p2pGetDeviceAddress
09-23 09:24:29.798   930  2889 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 09:24:30.049   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:24:31.050   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 09:24:32.927  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:24:32.932  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:24:32.940  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 09:24:32.998   930  2890 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 09:24:32.999   930  2890 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 09:24:32.999   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:24:33.013   930  2890 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 09:24:33.050   930  2890 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 09:24:33.052  5662  5662 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 09:24:33.486  5662  5662 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 09:24:33.524  5662  5662 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 09:24:33.526  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 09:24:33.534   930  2890 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:24:33.534   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 09:24:33.535   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 09:24:33.552   930  2890 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 09:24:33.566   507   925 D CommandListener: Setting iface cfg
,09-23 09:24:33.572   930  2890 D WifiStateMachine: Start Dhcp Watchdog 3
,09-23 09:24:33.581   930  5667 D DhcpClient: Receive thread started
,09-23 09:24:33.586   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-23 09:24:33.587   930  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 09:24:33.587   930  2892 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-23 09:24:33.676   930  2890 E native  : do suspend false
,09-23 09:24:33.696   930  5666 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 09:24:33.713   930  5667 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-23 09:24:33.714   930  5666 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-23 09:24:33.716   930  5666 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 09:24:33.734   930  5667 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 09:24:33.735   930  5666 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 09:24:33.737   507   925 D CommandListener: Setting iface cfg
,09-23 09:24:33.742   930  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 09:24:33.747   930  5666 D DhcpClient: Scheduling renewal in 86399s
,09-23 09:24:33.760   930  2890 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 09:24:33.762   930  2890 D WifiConfigStore: No blacklist allowed without epno enabled
09-23 09:24:33.763   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-23 09:24:33.765   930  2892 D ConnectivityService: Adding iface wlan0 to network 102
,09-23 09:24:33.777   930  2890 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 09:24:33.812   930  2892 E ConnectivityService: Unexpected mtu value: 0, wlan0,
09-23 09:24:33.812   930  2892 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-23 09:24:33.815   930  2892 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-23 09:24:33.816   930  2892 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-23 09:24:33.818   930  2892 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-23 09:24:33.827   930  2892 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-23 09:24:33.833   930  2892 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-23 09:24:33.833   930  2892 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-23 09:24:33.833   930  2892 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-23 09:24:33.833   930  2890 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 09:24:33.833   930  2892 D ConnectivityService:    accepting network in place of null
09-23 09:24:33.833   930  2890 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 09:24:33.834   930  2892 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 09:24:33.846   930  5665 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307360, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 09:24:33.859   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:24:33.880   507   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 09:24:33.884   930  2892 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-23 09:24:33.884   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:24:33.884  3407  3575 W QCNEJ   : |CORE| network available: 102
09-23 09:24:33.885   930  2892 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-23 09:24:33.889   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-23 09:24:33.891  3407  3575 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-23 09:24:33.892  3407  3575 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-23 09:24:33.892  3407  3575 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:33.895  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:24:33.897  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:33.901  5353  5353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:24:33.903  5353  5353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:33.903  4801  4826 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 09:24:33.903  4801  4826 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 09:24:33.903  4801  4826 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 09:24:33.903  4801  4826 E SarControlService: no key has been found,reset the power
09-23 09:24:33.904  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 09:24:33.904  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 09:24:33.904  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-23 09:24:33.904  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:24:33.904  4830  4830 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-23 09:24:33.908  4735  4735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-23 09:24:33.909  4801  4839 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-23 09:24:33.909  4801  4839 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 09:24:33.909  4801  4839 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 09:24:33.910  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 09:24:33.910  4830  4830 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 09:24:33.911  3834  3834 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 09:24:33.914   930  5664 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-23 09:24:33.914  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000f003000000000000ffffffff]
,09-23 09:24:33.914  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:24:33.915  4830  4844 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,09-23 09:24:33.916  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:24:33.916  4801  4812 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 09:24:33.917  3834  3834 D SystemUpdateService: onCreate
09-23 09:24:33.921  3834  3834 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 09:24:33.922  4830  4844 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@fe0693a HexData = [00000000f103000000000000ffffffff]
09-23 09:24:33.922  4830  4844 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 09:24:33.922  4830  4844 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-23 09:24:33.923  4830  4830 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 09:24:33.923  4801  4811 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:33.925  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:24:33.930  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:24:33.931  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:24:33.931  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@670b933 removed from the list
09-23 09:24:33.931  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:33.931  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:33.931  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:33.933  3834  3834 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-23 09:24:33.934  5353  5680 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-23 09:24:33.934  5353  5680 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 09:24:33.939  3834  5677 I SystemUpdateService: active receiver: enabled
,09-23 09:24:33.941  3834  5133 I iu.UploadsManager: num queued entries: 0
09-23 09:24:33.941  3834  5133 I iu.UploadsManager: num updated entries: 0
,09-23 09:24:33.944  3834  3834 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-23 09:24:33.945  3834  3834 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 09:24:33.947  5485  5485 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 09:24:33.950  5485  5485 D SprintDMHelper: simOperator: 
09-23 09:24:33.951  5485  5485 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 09:24:33.974  3834  5133 I iu.SyncManager: NEXT; no task
,09-23 09:24:33.975  3834  5677 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 09:24:33.979   930  5664 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 13:24:33 GMT], X-Android-Received-Millis=[1474637073978], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474637073948]}
,09-23 09:24:33.979   930  2892 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 09:24:33.979   930  2892 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-23 09:24:33.980   930  2892 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-23 09:24:33.981   930  2892 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 09:24:33.988  3834  5677 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-23 09:24:33.988  3834  5677 I SystemUpdateService: now status is 0 (complete)
09-23 09:24:33.988  3834  5677 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-23 09:24:33.989  3834  5677 I SystemUpdateService: file has been verified
09-23 09:24:33.989  3834  5677 I SystemUpdateService: OTA package size = 21989297
,09-23 09:24:33.994  3834  5677 I SystemUpdateService: showing system update notification
,09-23 09:24:34.005  3834  3834 D SystemUpdateService: onDestroy
,09-23 09:24:34.054  4216  5682 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 09:24:36.966  5353  5680 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-23 09:24:36.966  5353  5690 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-23 09:24:36.967  5353  5680 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:24:36.967  5353  5690 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-23 09:24:36.968  5353  5690 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:24:36.968  5353  5680 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:24:36.969  5353  5690 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:24:36.970  5353  5680 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:24:36.971  5353  5690 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 09:24:36.972  5353  5692 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,09-23 09:24:36.974  5353  5680 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 09:24:36.975  5353  5693 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender)
,09-23 09:24:36.977  5353  5695 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
09-23 09:24:36.977  5353  5694 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Receiver)
09-23 09:24:36.979  5353  5694 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: IncomingSocketThread/Receiver)
09-23 09:24:36.979  5353  5695 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
,09-23 09:24:36.979  5353  5694 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-23 09:24:36.979  5353  5694 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 09:24:36.979  5353  5695 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 09:24:36.980  5353  5695 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 09:24:39.943  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-23 09:24:39.944  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-23 09:24:39.952  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@de9c8de Bundle[{}]
,09-23 09:24:39.953  5353  5399 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 09:24:39.953  5353  5399 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-23 09:24:39.954  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-23 09:24:39.955  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-23 09:24:39.956  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-23 09:24:39.957  5353  5399 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-23 09:24:39.964  5353  5399 I System.out: Running OutgoingSocketThread
,09-23 09:24:39.966  5353  5696 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-23 09:24:39.966  5353  5696 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 09:24:41.839   930  2892 D ConnectivityService: handlePromptUnvalidated 102
,09-23 09:24:42.979  5353  5697 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-23 09:24:42.979  5353  5697 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:24:42.979  5353  5696 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-23 09:24:42.979  5353  5696 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 09:24:42.979  5353  5697 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:24:42.979  5353  5696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:24:42.981  5353  5696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:24:42.981  5353  5697 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 09:24:42.983  5353  5699 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: IncomingSocketThread/Sender)
,09-23 09:24:42.984  5353  5697 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-23 09:24:42.986  5353  5696 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 09:24:42.988  5353  5700 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender)
,09-23 09:24:42.991  5353  5701 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,09-23 09:24:42.991  5353  5702 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
09-23 09:24:42.992  5353  5701 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
09-23 09:24:42.992  5353  5701 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 09:24:42.992  5353  5701 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 09:24:42.992  5353  5702 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
09-23 09:24:42.993  5353  5702 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 09:24:42.993  5353  5702 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-23 09:24:44.799   930  2890 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-23 09:24:45.976  5353  5399 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-23 09:24:45.977  5353  5399 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-23 09:24:45.977  5353  5399 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-23 09:24:45.983  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 09:24:45.983  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de94f0 added. We now have 3 listener(s)
09-23 09:24:45.987  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:24:45.987  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:24:45.987  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:24:45.988  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:45.988  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc6ba69 added. We now have 4 listener(s)
09-23 09:24:45.988  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 09:24:45.989  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:24:45.994  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:46.002  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:24:46.006  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:46.006  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 09:24:46.007  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:24:46.007  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:24:46.007  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:24:46.007  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:46.007  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:46.007  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:24:46.007  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:24:46.007  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de94f0 removed from the list
09-23 09:24:46.007  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:46.007  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc6ba69 removed from the list
,09-23 09:24:46.010  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:46.010  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:24:46.010  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:46.011  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:46.011  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:46.012  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:46.012  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:24:46.012  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:46.012  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc6ba69 not in the list
09-23 09:24:46.012  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:46.013  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:46.014  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:46.014  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:46.014  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:46.014  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc6ba69 not in the list
09-23 09:24:46.014  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:46.015  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:24:46.015  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:46.015  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6de94f0 not in the list
09-23 09:24:46.015  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:46.015  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:24:46.016  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3b58f added. We now have 3 listener(s)
09-23 09:24:46.017  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:24:46.018  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:24:46.018  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:24:46.018  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:46.018  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b0101c added. We now have 4 listener(s)
09-23 09:24:46.018  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:24:46.019  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:24:46.023  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:46.027  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:24:46.030  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:46.030  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 09:24:46.031  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:24:46.031  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:24:46.031  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:24:46.031  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:46.031  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:46.034  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:24:46.034  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:24:46.034  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:46.038  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:46.038  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:24:46.039  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:24:46.039  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:24:46.043  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:24:46.043  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:24:46.043  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 09:24:46.044  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:46.046  5605  5615 D BtGatt.GattService: registerClient() - UUID=96ac4f29-e8a3-4aa7-b7db-3c9aa36dcb57
,09-23 09:24:46.048  5605  5621 D BtGatt.GattService: onClientRegistered() - UUID=96ac4f29-e8a3-4aa7-b7db-3c9aa36dcb57, clientIf=5
09-23 09:24:46.049  5353  5363 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 09:24:46.050  5605  5642 D BtGatt.GattService: start scan with filters
,09-23 09:24:46.053  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:24:46.053  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 09:24:46.053  5605  5624 D BtGatt.ScanManager: handling starting scan
09-23 09:24:46.053  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:24:46.053  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 09:24:46.055  5605  5624 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c8e6b63
09-23 09:24:46.055  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:24:46.055  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:24:46.056  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:24:46.056  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 09:24:46.059  5353  5399 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 09:24:46.059  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 09:24:46.059  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 09:24:46.059  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:46.059  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:24:46.059  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:24:46.060  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:24:46.060  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:24:46.060  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:24:46.060  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:24:46.060  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:24:46.060  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:46.061  5605  5615 D BtGatt.GattService: stopScan() - queue size =1
09-23 09:24:46.062  5605  5642 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 09:24:46.062  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:46.062  5605  5621 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:24:46.062  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:24:46.062  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:46.063  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:24:46.063  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:24:46.063  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:24:46.063  5605  5624 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-23 09:24:46.064  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:24:46.064  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:46.064  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 09:24:46.064  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:24:46.065  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:24:46.069  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:24:46.069  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:46.069  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:46.070  5605  5621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 09:24:46.070  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:46.071  5605  5624 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:24:46.071  5605  5624 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 09:24:46.072  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:24:46.072  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 09:24:46.076  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 09:24:46.077  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:24:46.077  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:24:46.077  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:24:46.078  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:24:46.080  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:24:46.080  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:24:46.080  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:46.082  5605  5621 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 09:24:46.082  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:46.082  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:24:46.082  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:24:46.083  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:24:46.084  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:24:46.086  5605  5621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 09:24:46.086  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:24:46.092  5605  5621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:24:46.092  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:46.092  5605  5624 D BtGatt.ScanManager: stopping BLe Batch
,09-23 09:24:46.097  5605  5621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:24:46.097  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:46.098  5605  5624 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 09:24:46.102  5605  5621 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-23 09:24:46.102  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:24:46.586  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-23 09:24:46.586  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 09:24:46.586  5353  5353 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:24:49.070  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:24:49.070  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:24:49.070  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:24:49.070  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:49.071  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:49.071  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:24:49.071  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 09:24:49.071  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3b58f removed from the list
09-23 09:24:49.071  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:49.072  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b0101c removed from the list
09-23 09:24:49.072  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:49.072  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:49.073  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:24:49.074  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:49.077  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:49.077  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:49.078  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:24:49.080  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:24:49.080  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:49.081  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:49.081  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:24:49.081  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b0101c not in the list
09-23 09:24:49.081  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:49.081  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:49.084  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:49.085  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:49.086  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:49.086  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:49.086  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:49.086  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:49.086  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:24:49.086  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b0101c not in the list
09-23 09:24:49.086  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:49.087  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:49.087  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:49.087  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3b58f not in the list
09-23 09:24:49.090  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:24:49.090  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9522dd added. We now have 3 listener(s)
09-23 09:24:49.092  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:24:49.092  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:24:49.092  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:24:49.092  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 09:24:49.092  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5e52 added. We now have 4 listener(s)
09-23 09:24:49.092  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:24:49.093  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:24:49.096  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:49.102  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 09:24:49.104  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:49.105  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:24:49.105  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 09:24:49.106  5353  5399 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-23 09:24:49.106  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 09:24:49.107  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 09:24:49.107  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 09:24:49.107  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 09:24:49.107  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:49.108  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 09:24:49.109  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:49.110  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 09:24:49.110  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 09:24:49.110  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 09:24:49.110  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 09:24:49.110  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:49.110  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:49.114  5353  5703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 09:24:49.114  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:49.114  5353  5353 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-23 09:24:49.112  5642  5642 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 09:24:49.118  5353  5703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 09:24:49.115  5642  5642 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33805]" dev="sockfs" ino=33805 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 09:24:49.119  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:24:49.119  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:24:49.123  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:24:49.123  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:24:49.123  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:24:49.125  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 09:24:49.126  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:24:49.126  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-23 09:24:49.127  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 09:24:49.127  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 09:24:49.127  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 09:24:49.128  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:24:49.133  5605  5641 D BtGatt.GattService: registerClient() - UUID=bf5890e8-d8d4-4e48-bce3-a526a01dff60
09-23 09:24:49.133  5605  5621 D BtGatt.GattService: onClientRegistered() - UUID=bf5890e8-d8d4-4e48-bce3-a526a01dff60, clientIf=5
,09-23 09:24:49.133  5353  5363 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 09:24:49.135  5605  5623 D BtGatt.AdvertiseManager: message : 0
,09-23 09:24:49.137  5605  5623 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 09:24:49.147  5605  5621 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 09:24:49.151  5605  5621 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 09:24:49.152  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 09:24:49.153  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 09:24:49.154  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 09:24:49.156  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 09:24:49.156  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 09:24:49.156  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 09:24:49.156  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 09:24:49.156  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 09:24:49.156  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 09:24:49.158  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 09:24:49.159  5353  5353 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 09:24:49.159  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 09:24:49.660  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 09:24:49.660  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 09:24:49.660  5353  5353 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:24:52.159  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:24:52.160  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 09:24:52.160  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 09:24:52.160  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 09:24:52.160  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 09:24:52.160  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 09:24:52.161  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:24:52.161  5353  5703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 09:24:52.161  5353  5399 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-23 09:24:52.161  5353  5703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 09:24:52.161  5353  5703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 09:24:52.161  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:24:52.161  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:24:52.161  5353  5353 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 09:24:52.162  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 09:24:52.162  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:24:52.162  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:24:52.164  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:52.165  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:52.165  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:52.165  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 09:24:52.167  5605  5623 D BtGatt.AdvertiseManager: message : 1
,09-23 09:24:52.169  5605  5623 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 09:24:52.181  5605  5621 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 09:24:52.181  5605  5621 D BtGatt.GattService: Client app is not null!
,09-23 09:24:52.183  5605  5615 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:24:52.183  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 09:24:52.184  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 09:24:52.184  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 09:24:52.184  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 09:24:52.184  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 09:24:52.187  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 09:24:52.187  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 09:24:52.187  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:24:52.188  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:24:52.190  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:52.190  5353  5353 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 09:24:52.190  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:52.190  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:24:52.190  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:24:52.190  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:24:52.190  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9522dd removed from the list
09-23 09:24:52.191  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:52.191  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:24:52.191  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:52.191  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5e52 removed from the list
09-23 09:24:52.191  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:52.191  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 09:24:52.198  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:24:52.198  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:24:52.203  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:24:52.204  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 09:24:52.204  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:24:52.204  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:24:52.204  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:52.207  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:52.207  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:52.208  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:52.208  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:52.208  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:52.209  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:24:52.209  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:52.209  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:52.209  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:52.210  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:24:52.210  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5e52 not in the list
09-23 09:24:52.210  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:52.210  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:24:52.213  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:24:52.213  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:24:52.214  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:52.216  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:52.216  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:24:52.216  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:52.218  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-23 09:24:52.219  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:52.219  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:52.219  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:52.219  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:52.219  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:52.219  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:52.219  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5e52 not in the list
09-23 09:24:52.219  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 09:24:52.219  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:52.219  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:52.219  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9522dd not in the list
09-23 09:24:52.220  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:24:52.220  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a3459b added. We now have 3 listener(s)
09-23 09:24:52.222  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:24:52.222  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:24:52.222  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 09:24:52.223  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:52.223  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9c0d38 added. We now have 4 listener(s)
09-23 09:24:52.223  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:24:52.223  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 09:24:52.226  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:52.231  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:24:52.233  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 09:24:52.233  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:24:52.233  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:24:52.234  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 09:24:52.234  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 09:24:52.234  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:52.234  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:52.237  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:52.238  5353  5399 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:24:52.238  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:24:52.241  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:52.243  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:24:52.244  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:24:52.244  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 09:24:52.247  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 09:24:52.247  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 09:24:52.247  5353  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 09:24:52.248  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:24:52.251  5605  5641 D BtGatt.GattService: registerClient() - UUID=0a34821b-3d56-4989-8414-3a629f46c523
09-23 09:24:52.251  5605  5621 D BtGatt.GattService: onClientRegistered() - UUID=0a34821b-3d56-4989-8414-3a629f46c523, clientIf=5
,09-23 09:24:52.252  5353  5364 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 09:24:52.252  5605  5616 D BtGatt.GattService: start scan with filters
,09-23 09:24:52.255  5605  5624 D BtGatt.ScanManager: handling starting scan
,09-23 09:24:52.256  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 09:24:52.256  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 09:24:52.256  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 09:24:52.256  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 09:24:52.259  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 09:24:52.259  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 09:24:52.259  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 09:24:52.260  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 09:24:52.260  5605  5621 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 09:24:52.260  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:52.261  5605  5624 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 09:24:52.266  5605  5621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 09:24:52.266  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:52.266  5605  5624 D BtGatt.ScanManager: Starting BLE batch scan
09-23 09:24:52.266  5605  5624 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 09:24:52.275  5605  5621 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 09:24:52.275  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:24:52.280  5605  5621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 09:24:52.280  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:24:52.717  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:24:52.760  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-23 09:24:52.760  5353  5353 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:24:52.760  5353  5353 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 09:24:55.270  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 09:24:55.270  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:24:55.271  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 09:24:55.271  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 09:24:55.271  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:24:55.271  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 09:24:55.271  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 09:24:55.272  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 09:24:55.272  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 09:24:55.272  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 09:24:55.272  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 09:24:55.274  5353  5399 D BluetoothAdapter: STATE_ON
,09-23 09:24:55.276  5605  5633 D BtGatt.GattService: stopScan() - queue size =1
09-23 09:24:55.278  5605  5615 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 09:24:55.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:55.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 09:24:55.279  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 09:24:55.279  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 09:24:55.280  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 09:24:55.282  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:24:55.282  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:55.283  5353  5399 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 09:24:55.283  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 09:24:55.284  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:24:55.286  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:24:55.286  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:55.287  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:55.287  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 09:24:55.287  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.287  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 09:24:55.287  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:24:55.287  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a3459b removed from the list
09-23 09:24:55.287  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:55.287  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9c0d38 removed from the list
09-23 09:24:55.287  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
09-23 09:24:55.287  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:24:55.287  5605  5605 D BtGatt.ScanManager: awakened up at time 328802
09-23 09:24:55.293  5605  5621 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 09:24:55.293  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:55.293  5605  5624 D BtGatt.ScanManager: stopping BLe Batch
09-23 09:24:55.293  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 09:24:55.294  5353  5353 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 09:24:55.299  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 09:24:55.300  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 09:24:55.300  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 09:24:55.300  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:24:55.300  5605  5621 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 09:24:55.300  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 09:24:55.300  5605  5624 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 09:24:55.300  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:55.304  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.304  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:55.305  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:55.305  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:55.305  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:55.306  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:55.306  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:55.306  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:55.306  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:55.306  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9c0d38 not in the list
09-23 09:24:55.306  5353  5353 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 09:24:55.306  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:55.306  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 09:24:55.310  5353  5353 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 09:24:55.310  5353  5353 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 09:24:55.310  5353  5353 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:55.313  5353  5353 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 09:24:55.313  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.313  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 09:24:55.314  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:55.315  5353  5399 D BluetoothAdapter: STATE_ON
09-23 09:24:55.315  5353  5399 D BluetoothLeScanner: could not find callback wrapper
09-23 09:24:55.315  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 09:24:55.315  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:55.315  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 09:24:55.315  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:55.315  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9c0d38 not in the list
,09-23 09:24:55.315  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:55.315  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.315  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:55.315  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a3459b not in the list
,09-23 09:24:55.316  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 09:24:55.316  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbda149 added. We now have 3 listener(s)
09-23 09:24:55.317  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 09:24:55.317  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 09:24:55.318  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 09:24:55.318  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 09:24:55.318  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2581a4e added. We now have 4 listener(s)
,09-23 09:24:55.318  5353  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 09:24:55.318  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 09:24:55.320  5605  5621 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-23 09:24:55.320  5605  5621 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 09:24:55.320  5605  5621 D BtGatt.GattService: current time is 328835311176
09-23 09:24:55.320  5605  5621 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -75, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -77, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -75, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-23 09:24:55.322  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 09:24:55.322  5605  5621 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 09:24:55.323  5605  5621 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 09:24:55.323  5605  5621 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 09:24:55.323  5605  5621 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 09:24:55.324  5605  5621 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 09:24:55.326  5353  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 09:24:55.328  5353  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 09:24:55.328  5353  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 09:24:55.328  5353  5399 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 09:24:55.328  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:24:55.328  5353  5399 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 09:24:55.328  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:55.328  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.328  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 09:24:55.328  5353  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 09:24:55.328  5353  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbda149 removed from the list
09-23 09:24:55.328  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:55.329  5353  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2581a4e removed from the list
09-23 09:24:55.330  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 09:24:55.330  5353  5399 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 09:24:55.330  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:55.330  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.330  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:55.332  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:55.333  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:55.333  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 09:24:55.333  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2581a4e not in the list
09-23 09:24:55.333  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.333  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:55.333  5353  5353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 09:24:55.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 09:24:55.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 09:24:55.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 09:24:55.334  5353  5399 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2581a4e not in the list
09-23 09:24:55.334  5353  5399 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 09:24:55.334  5353  5399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 09:24:55.334  5353  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 09:24:55.334  5353  5399 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbda149 not in the list
,09-23 09:24:55.336  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-23 09:24:55.336  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 09:24:55.336  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 09:24:55.336  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 09:24:55.336  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 09:24:55.336  5353  5399 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-23 09:24:55.814  5353  5353 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 09:24:56.051   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-23 09:24:56.051   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 09:24:57.347  5353  5706 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-23 09:24:59.346  5353  5399 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,09-23 09:24:59.346  5353  5399 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-23 09:24:59.350  5353  5707 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,09-23 09:24:59.351  5353  5707 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
09-23 09:24:59.351  5353  5707 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-23 09:24:59.355  5353  5399 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 09:24:59.360  5353  5708 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-23 09:24:59.361  5353  5708 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-23 09:24:59.361  5353  5708 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-23 09:24:59.372  5353  5399 I jxcore-log: Total number of executed tests:  82
09-23 09:24:59.372  5353  5399 I jxcore-log: 
09-23 09:24:59.372  5353  5399 I jxcore-log: Number of passed tests:  82
09-23 09:24:59.372  5353  5399 I jxcore-log: 
,09-23 09:24:59.373  5353  5399 I jxcore-log: Number of failed tests:  0
09-23 09:24:59.373  5353  5399 I jxcore-log: 
09-23 09:24:59.373  5353  5399 I jxcore-log: Number of ignored tests:  0
09-23 09:24:59.373  5353  5399 I jxcore-log: 
09-23 09:24:59.373  5353  5399 I jxcore-log: Total duration:  101063
09-23 09:24:59.373  5353  5399 I jxcore-log: 
,09-23 09:24:59.379  5353  5399 I jxcore-log: Unit Test app is loaded
09-23 09:24:59.379  5353  5399 I jxcore-log: 
,09-23 09:24:59.393  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.393  5353  5399 I jxcore-log: 
,09-23 09:24:59.399  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.399  5353  5399 I jxcore-log: 
,09-23 09:24:59.401  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.401  5353  5399 I jxcore-log: 
,09-23 09:24:59.402  5353  5353 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-23 09:24:59.403  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.403  5353  5399 I jxcore-log: 
,09-23 09:24:59.405  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-23 09:24:59.405  5353  5399 I jxcore-log: 
,09-23 09:24:59.407  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:24:59.407  5353  5399 I jxcore-log: 
,09-23 09:24:59.411  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.411  5353  5399 I jxcore-log: 
,09-23 09:24:59.413  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.413  5353  5399 I jxcore-log: 
,09-23 09:24:59.415  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-23 09:24:59.415  5353  5399 I jxcore-log: 
09-23 09:24:59.416  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:24:59.416  5353  5399 I jxcore-log: 
,09-23 09:24:59.417  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:24:59.417  5353  5399 I jxcore-log: 
,09-23 09:24:59.418  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.418  5353  5399 I jxcore-log: 
,09-23 09:24:59.419  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.419  5353  5399 I jxcore-log: 
,09-23 09:24:59.420  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.420  5353  5399 I jxcore-log: 
,09-23 09:24:59.421  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.421  5353  5399 I jxcore-log: 
,09-23 09:24:59.423  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.423  5353  5399 I jxcore-log: 
,09-23 09:24:59.424  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.424  5353  5399 I jxcore-log: 
,09-23 09:24:59.425  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.425  5353  5399 I jxcore-log: 
,09-23 09:24:59.426  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.426  5353  5399 I jxcore-log: 
,09-23 09:24:59.427  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.427  5353  5399 I jxcore-log: 
,09-23 09:24:59.428  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.428  5353  5399 I jxcore-log: 
,09-23 09:24:59.429  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.429  5353  5399 I jxcore-log: 
,09-23 09:24:59.430  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.430  5353  5399 I jxcore-log: 
,09-23 09:24:59.431  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.431  5353  5399 I jxcore-log: 
09-23 09:24:59.432  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.432  5353  5399 I jxcore-log: 
,09-23 09:24:59.433  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.433  5353  5399 I jxcore-log: 
,09-23 09:24:59.434  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.434  5353  5399 I jxcore-log: 
,09-23 09:24:59.447  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.447  5353  5399 I jxcore-log: 
,09-23 09:24:59.448  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.448  5353  5399 I jxcore-log: 
,09-23 09:24:59.451  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.451  5353  5399 I jxcore-log: 
,09-23 09:24:59.452  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.452  5353  5399 I jxcore-log: 
,09-23 09:24:59.453  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.453  5353  5399 I jxcore-log: 
,09-23 09:24:59.454  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.454  5353  5399 I jxcore-log: 
,09-23 09:24:59.454  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.454  5353  5399 I jxcore-log: 
,09-23 09:24:59.455  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.455  5353  5399 I jxcore-log: 
,09-23 09:24:59.456  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.456  5353  5399 I jxcore-log: 
,09-23 09:24:59.456  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.456  5353  5399 I jxcore-log: 
09-23 09:24:59.457  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.457  5353  5399 I jxcore-log: 
,09-23 09:24:59.457  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-23 09:24:59.457  5353  5399 I jxcore-log: 
,09-23 09:24:59.458  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.458  5353  5399 I jxcore-log: 
,09-23 09:24:59.459  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-23 09:24:59.459  5353  5399 I jxcore-log: 
,09-23 09:24:59.459  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.459  5353  5399 I jxcore-log: 
09-23 09:24:59.460  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.460  5353  5399 I jxcore-log: 
,09-23 09:24:59.461  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.461  5353  5399 I jxcore-log: 
09-23 09:24:59.462  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.462  5353  5399 I jxcore-log: 
,09-23 09:24:59.462  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.462  5353  5399 I jxcore-log: 
09-23 09:24:59.463  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:24:59.463  5353  5399 I jxcore-log: 
09-23 09:24:59.463  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.463  5353  5399 I jxcore-log: 
09-23 09:24:59.464  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-23 09:24:59.464  5353  5399 I jxcore-log: 
09-23 09:24:59.465  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.465  5353  5399 I jxcore-log: 
09-23 09:24:59.466  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:24:59.466  5353  5399 I jxcore-log: 
09-23 09:24:59.466  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-23 09:24:59.466  5353  5399 I jxcore-log: 
09-23 09:24:59.466  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-23 09:24:59.466  5353  5399 I jxcore-log: 
09-23 09:24:59.466  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-23 09:24:59.466  5353  5399 I jxcore-log: 
09-23 09:24:59.468  5353  5399 I jxcore-log: My device name is: Huawei-Nexus 6P
09-23 09:24:59.468  5353  5399 I jxcore-log: 
09-23 09:24:59.469  5353  5399 I jxcore-log: 2016-09-23 13:24:59 - WARN testUtils: 'myNameCallback not set!'
09-23 09:24:59.469  5353  5399 I jxcore-log: 
09-23 09:24:59.469  5353  5399 I jxcore-log: Running for WIFI network type
09-23 09:24:59.469  5353  5399 I jxcore-log: 
,09-23 09:24:59.508  5353  5706 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-23 09:24:59.823  5353  5399 I jxcore-log: { [Error: Cannot find module './CoordinatedClient'] code: 'MODULE_NOT_FOUND' }
09-23 09:24:59.823  5353  5399 I jxcore-log: 
,09-23 09:24:59.826  5353  5399 E jxcore  : Error!: JXcore: Method Doesn't Exist [
09-23 09:24:59.826  5353  5399 E jxcore  : Stack: [{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"309","_columnNumber":"11","_msg":"    at JXMobile.executeJSON@main.js:309:11"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"main.js","_functionName":"unknown","_lineNumber":"309","_columnNumber":"11","_msg":""}]
,09-23 09:25:11.052   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:12.054   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:13.056   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:13.812   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:25:14.057   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:14.236   930  5665 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347750, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 09:25:15.059   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:16.059   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 09:25:21.061   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:22.062   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:23.064   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:24.066   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:25.067   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:26.068   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-23 09:25:32.163   930  5665 D NetlinkSocketObserver: NeighborEvent{elapsedMs=365677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-23 09:25:36.069   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:37.070   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:38.071   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:39.073   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:40.074   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:41.075   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-23 09:25:53.818   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:25:56.076   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:57.077   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:58.079   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:25:59.080   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:00.081   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:01.082   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 09:26:12.084   930  5665 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405598, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 09:26:13.819   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:26:21.083   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:22.084   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:23.086   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:24.088   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:25.089   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:26:26.090   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 09:26:51.091   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 09:26:51.092   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 09:26:53.824   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:27:11.093   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:12.094   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:13.096   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:13.829   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:27:14.097   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:15.099   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:16.100   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 09:27:21.101   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:22.102   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:23.104   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:24.105   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:25.107   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:26.108   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-23 09:27:33.829   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 09:27:36.109   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:37.111   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:38.112   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:39.114   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:40.115   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:41.115   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-23 09:27:56.117   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:57.119   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:58.121   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:27:59.122   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:28:00.123   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 09:28:01.124   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-23 09:28:04.763   930  5665 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-23 09:28:13.834   930  2890 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437

```
