#### Test 87119404f514987_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-28 10:19:08.224   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 10:19:08.225   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 10:19:08.743  5717  5717 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 10:19:08.749  5717  5717 D AndroidRuntime: CheckJNI is OFF
09-28 10:19:08.781  5717  5717 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 10:19:08.820  5717  5717 I Radio-JNI: register_android_hardware_Radio DONE
09-28 10:19:08.836  5717  5717 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-28 10:19:08.841   927  3477 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 10:19:08.880   927  3477 I ActivityManager: Start proc 5726:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 10:19:08.885  5717  5717 D AndroidRuntime: Shutting down VM
,09-28 10:19:09.227   927   938 I WindowManager: Screenshot max retries 4 of Token{a0e8517 ActivityRecord{7fd4596 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{df716e u0 Starting com.test.thalitest} drawState=2
,09-28 10:19:09.300  5726  5726 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 10:19:09.332  5726  5726 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 10:19:09.360  5726  5726 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 466-486)
,09-28 10:19:09.360  5726  5726 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 10:19:09.380  5726  5726 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {969c4ab}
,09-28 10:19:09.380  5726  5726 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 10:19:09.380  5726  5726 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 10:19:09.385  5726  5726 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-28 10:19:09.387  5726  5726 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 10:19:09.421  5726  5726 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 10:19:09.436  5726  5726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 10:19:09.436  5726  5726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 10:19:09.436  5726  5726 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 10:19:09.436  5726  5726 I Adreno  : Build Date                       : 12/06/15
09-28 10:19:09.436  5726  5726 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 10:19:09.436  5726  5726 I Adreno  : Local Branch                     : mybranch17112971
09-28 10:19:09.436  5726  5726 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 10:19:09.436  5726  5726 I Adreno  : Remote Branch                    : NONE
09-28 10:19:09.436  5726  5726 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 10:19:09.491   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c03015d:true
,09-28 10:19:09.522   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14314]" dev="sockfs" ino=14314 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:19:09.522   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[14314]" dev="sockfs" ino=14314 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:19:09.535  5726  5726 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 10:19:09.545  5726  5726 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 10:19:09.573  5726  5763 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-28 10:19:09.568  3031  3031 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33064]" dev="sockfs" ino=33064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:19:09.568  3031  3031 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33064]" dev="sockfs" ino=33064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:19:09.575  3895  3895 W Binder_C: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14318]" dev="sockfs" ino=14318 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 10:19:09.575  3895  3895 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14318]" dev="sockfs" ino=14318 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 10:19:09.581  5726  5750 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 10:19:09.609  5726  5763 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 10:19:09.687   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +458ms (total +831ms)
,09-28 10:19:09.713  5726  5726 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5726
,09-28 10:19:09.808  5726  5726 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 10:19:09.933  5726  5766 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -586675920
,09-28 10:19:09.936  5726  5766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 10:19:09.936  5726  5766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 10:19:09.936  5726  5766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 10:19:09.936  5726  5766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 10:19:09.936  5726  5766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-28 10:19:09.936  5726  5766 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6477be0 added. We now have 1 listener(s)
,09-28 10:19:09.939  5726  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-28 10:19:09.939  5726  5766 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:19:09.940  5726  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:19:09.940  5726  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-28 10:19:09.943  5726  5766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e73d3f added. We now have 1 listener(s)
09-28 10:19:09.943  5726  5766 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:19:09.947   927  3040 D WifiService: New client listening to asynchronous messages
,09-28 10:19:09.947  5726  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:19:09.947  5726  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 10:19:09.947  5726  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 10:19:09.947  5726  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-28 10:19:09.948  5726  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-28 10:19:09.949  5726  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:19:09.949  5726  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 10:19:09.953  5726  5766 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:09.953  5726  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:09.953  5726  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-28 10:19:09.953  5726  5766 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:19:09.954  5726  5766 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 10:19:09.957  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:09.959  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:09.963   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:19:09.970  5726  5726 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 10:19:10.261  5726  5773 W jxcore-log: Initializing JXcore engine
09-28 10:19:10.261  5726  5773 W jxcore-log: JXcore engine is ready
,09-28 10:19:10.285  5773  5773 W Thread-58: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12869 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-28 10:19:10.285  5773  5773 W Thread-58: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[11543]" dev="sockfs" ino=11543 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-28 10:19:10.285  5773  5773 W Thread-58: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-28 10:19:10.285  5773  5773 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32632]" dev="sockfs" ino=32632 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 10:19:10.294  5726  5773 W jxcore-log: Starting JXcore engine
,09-28 10:19:10.346  5726  5773 W jxcore-log: Platform android
09-28 10:19:10.346  5726  5773 W jxcore-log: 
,09-28 10:19:10.346  5726  5773 W jxcore-log: Process ARCH arm
09-28 10:19:10.346  5726  5773 W jxcore-log: 
,09-28 10:19:10.445  5726  5773 I jxcore-log: JXcore Cordova bridge is ready!
09-28 10:19:10.445  5726  5773 I jxcore-log: 
,09-28 10:19:10.445  5726  5773 W jxcore-log: JXcore engine is started
,09-28 10:19:10.452  5726  5766 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 10:19:10.459  5726  5726 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 10:19:18.226   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:19.227   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:20.126  5726  5773 I jxcore-log: 2016-09-28 14:19:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 10:19:20.126  5726  5773 I jxcore-log: 
,09-28 10:19:20.127  5726  5773 I jxcore-log: 2016-09-28 14:19:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 10:19:20.127  5726  5773 I jxcore-log: 
,09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:20.131  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:19:20.133  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:19:20.134  5726  5773 I jxcore-log: 2016-09-28 14:19:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 10:19:20.134  5726  5773 I jxcore-log: 
,09-28 10:19:20.136  5726  5773 I jxcore-log: 2016-09-28 14:19:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 10:19:20.136  5726  5773 I jxcore-log: 
,09-28 10:19:20.228   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:20.385  5726  5773 I jxcore-log: 2016-09-28 14:19:20 - DEBUG UnitTest_app: 'Running unit tests'
09-28 10:19:20.385  5726  5773 I jxcore-log: 
,09-28 10:19:20.386  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:19:20.386  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28e7c38 added. We now have 2 listener(s)
09-28 10:19:20.387  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:19:20.387  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:19:20.387  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:19:20.387  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:19:20.387  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd42411 added. We now have 2 listener(s)
09-28 10:19:20.387  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:19:20.388  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:19:20.390  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:20.392  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:20.393  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:20.393  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:19:20.394  5726  5773 D executeNativeTests: Running unit tests
,09-28 10:19:20.398  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:20.403  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:20.430  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 10:19:20.430  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 added. We now have 3 listener(s)
,09-28 10:19:20.431  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:19:20.431  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:19:20.431  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:19:20.431  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:19:20.431  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 added. We now have 3 listener(s)
09-28 10:19:20.431  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:19:20.431  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:19:20.433  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:20.435  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:20.436  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:19:20.436  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:19:20.437  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 10:19:20.437  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:19:20.437  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-28 10:19:20.437  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:19:20.438  5726  5773 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-28 10:19:20.438  5726  5773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-28 10:19:20.438  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 10:19:20.438  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-28 10:19:20.438  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:19:20.438  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:19:20.438  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:20.439  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:20.439  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:20.439  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:20.439  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.439  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:20.439  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:20.439  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:19:20.439  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 removed from the list
09-28 10:19:20.439  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:20.439  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 removed from the list
,09-28 10:19:20.446  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:20.452  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:20.453  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:20.453  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.454  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.454  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:20.454  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:20.454  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:20.454  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:20.454  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:20.455  5726  5773 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-28 10:19:20.455  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:20.455  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:20.455  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:20.456  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 10:19:20.456  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.456  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.456  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:20.456  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:20.456  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:20.456  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:20.456  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:20.456  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:20.456  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.456  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.456  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.456  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:20.456  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:20.456  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:20.456  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 10:19:20.459  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 10:19:20.460  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:20.460  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:20.460  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 10:19:20.460  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:20.460  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.460  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.460  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:20.460  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:20.460  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:20.460  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:20.460  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:20.460  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.460  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.460  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:20.460  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:20.461  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:19:20.461  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:20.461  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:20.461  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:20.461  5726  5773 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 10:19:20.462  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:20.464  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:20.465  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:19:20.465  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:19:20.465  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 10:19:20.465  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:19:20.466  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:19:20.466  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:19:20.466  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:19:20.468  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:20.469  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:19:20.469  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:19:20.472  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:19:20.472  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:20.472  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:19:20.473  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:19:20.475  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-28 10:19:20.479  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-28 10:19:20.479  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 10:19:20.479  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:19:20.479  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-28 10:19:20.481  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:19:20.481  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 10:19:20.482  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:19:20.488  4682  4701 D BtGatt.GattService: registerClient() - UUID=b8ee2402-5624-4b44-a4a8-20926f6c7ff5
,09-28 10:19:20.489  4682  4758 D BtGatt.GattService: onClientRegistered() - UUID=b8ee2402-5624-4b44-a4a8-20926f6c7ff5, clientIf=5
,09-28 10:19:20.489  5726  5736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:19:20.491  4682  4699 D BtGatt.GattService: start scan with filters
09-28 10:19:20.493  4682  4762 D BtGatt.ScanManager: handling starting scan
09-28 10:19:20.493  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:19:20.494  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:19:20.494  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:19:20.494  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 10:19:20.494  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 10:19:20.494  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:19:20.494  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:19:20.495  4682  4762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:19:20.496  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:19:20.496  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:19:20.497  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:19:20.498  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:19:20.499  5726  5773 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 10:19:20.503  4682  4758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 10:19:20.503  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:20.504  4682  4762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:19:20.510  4682  4758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:19:20.510  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:20.510  4682  4762 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:19:20.511  4682  4762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 10:19:20.521  4682  4758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:19:20.521  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:20.527  4682  4758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:19:20.527  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:20.766   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 10:19:20.997  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 10:19:20.998  5726  5726 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:19:20.998  5726  5726 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 10:19:21.229   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:22.230   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:23.231   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 10:19:23.788   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 10:19:23.797   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-28 10:19:25.503  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:19:25.503  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:25.503  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:19:25.503  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:25.503  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:19:25.503  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:25.504  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:19:25.504  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 10:19:25.504  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:19:25.504  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:19:25.504  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:19:25.505  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 10:19:25.506  5726  5773 D BluetoothAdapter: STATE_ON
09-28 10:19:25.506  4682  5412 D BtGatt.GattService: stopScan() - queue size =1
,09-28 10:19:25.508  4682  4917 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:19:25.509  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:19:25.509  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:19:25.510  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:19:25.510  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:19:25.510  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-28 10:19:25.510  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 10:19:25.510  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:19:25.511  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 10:19:25.512  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:19:25.512  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:19:25.512  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 10:19:25.512  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 10:19:25.513  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:19:25.515  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:25.517  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:25.517  4682  4682 D BtGatt.ScanManager: awakened up at time 236644
09-28 10:19:25.517  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:25.518  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:25.518  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:25.518  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:25.518  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:25.518  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:25.518  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:25.518  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:19:25.519  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:25.519  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:25.519  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:25.524  4682  4758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 10:19:25.525  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:25.525  4682  4762 D BtGatt.ScanManager: stopping BLe Batch
,09-28 10:19:25.536  4682  4758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 10:19:25.536  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:25.536  4682  4762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 10:19:25.567  4682  4758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-28 10:19:25.567  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:25.568  4682  4758 D BtGatt.GattService: current time is 236694340603
09-28 10:19:25.568  4682  4758 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -77, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -76, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -71, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -73, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -52, 11, 57, -70, 107, -17, 1, 0, -96, 79, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -82, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 10:19:25.570  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 10:19:25.571  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 10:19:25.572  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 10:19:25.572  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 10:19:25.572  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 10:19:25.572  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-28 10:19:25.573  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 10:19:26.020  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:19:26.828   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-28 10:19:26.833   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-28 10:19:28.232   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:29.234   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:30.235   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:30.522  5726  5773 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 10:19:30.527  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:30.538  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:19:30.543  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:30.545  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:19:30.545  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:19:30.545  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:19:30.545  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:19:30.545  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:19:30.545  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:19:30.551  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:30.554  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:19:30.554  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:19:30.558  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:30.564  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:19:30.566  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 10:19:30.566  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:19:30.572  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 10:19:30.572  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:19:30.573  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-28 10:19:30.573  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:19:30.573  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-28 10:19:30.574  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:19:30.579  4682  4699 D BtGatt.GattService: registerClient() - UUID=0d6d2d4d-1dbe-4037-8ce8-690d45025da8
09-28 10:19:30.580  4682  4758 D BtGatt.GattService: onClientRegistered() - UUID=0d6d2d4d-1dbe-4037-8ce8-690d45025da8, clientIf=5
,09-28 10:19:30.581  5726  5736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 10:19:30.581  4682  4905 D BtGatt.GattService: start scan with filters
,09-28 10:19:30.586  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 10:19:30.586  4682  4762 D BtGatt.ScanManager: handling starting scan
09-28 10:19:30.586  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:19:30.586  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:19:30.586  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-28 10:19:30.586  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-28 10:19:30.587  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:19:30.587  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 10:19:30.590  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:19:30.591  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:19:30.591  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:19:30.594  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:19:30.596  4682  4758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 10:19:30.596  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.597  4682  4762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:19:30.598  5726  5773 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 10:19:30.602  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:30.602  5726  5773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 10:19:30.602  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:30.602  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:19:30.602  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:30.602  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:19:30.602  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:30.602  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:19:30.602  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:19:30.603  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:19:30.603  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:19:30.603  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:19:30.603  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 10:19:30.604  5726  5773 D BluetoothAdapter: STATE_ON
09-28 10:19:30.605  4682  4699 D BtGatt.GattService: stopScan() - queue size =1
09-28 10:19:30.606  4682  4917 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 10:19:30.606  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:19:30.606  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:19:30.606  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:19:30.606  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:19:30.606  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 10:19:30.606  4682  4758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:19:30.606  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 10:19:30.606  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.606  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:19:30.607  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 10:19:30.607  4682  4762 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:19:30.607  4682  4762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 10:19:30.608  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:19:30.608  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:19:30.608  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 10:19:30.609  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:19:30.609  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 10:19:30.610  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:30.611  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:30.612  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 10:19:30.612  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:30.612  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:30.612  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:30.612  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:19:30.612  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:30.612  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:30.612  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:30.612  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:30.612  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:30.612  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:30.613  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:30.613  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:30.615  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:30.615  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:30.615  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:30.615  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:30.616  5726  5773 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 10:19:30.620  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:19:30.623  4682  4758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:19:30.623  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:30.625  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:19:30.628  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:19:30.629  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:19:30.629  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:19:30.629  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:19:30.629  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:19:30.629  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:19:30.629  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:19:30.632  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:30.633  4682  4758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:19:30.633  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.634  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:19:30.634  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:19:30.636  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:30.638  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:19:30.639  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:19:30.639  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:19:30.642  4682  4758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 10:19:30.642  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.642  4682  4762 D BtGatt.ScanManager: stopping BLe Batch
09-28 10:19:30.647  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 10:19:30.647  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:19:30.647  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 10:19:30.648  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:19:30.648  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 10:19:30.648  5726  5773 D BluetoothAdapter: STATE_ON
09-28 10:19:30.648  4682  4758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 10:19:30.648  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.649  4682  4762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 10:19:30.650  4682  5412 D BtGatt.GattService: registerClient() - UUID=2a0c4e8d-4179-4192-bf0f-3b065e9dc92a
09-28 10:19:30.650  4682  4758 D BtGatt.GattService: onClientRegistered() - UUID=2a0c4e8d-4179-4192-bf0f-3b065e9dc92a, clientIf=5
09-28 10:19:30.651  5726  5737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 10:19:30.652  4682  4699 D BtGatt.GattService: start scan with filters
,09-28 10:19:30.654  4682  4758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 10:19:30.654  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:30.654  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 10:19:30.655  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:19:30.655  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:19:30.655  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 10:19:30.655  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 10:19:30.655  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:19:30.655  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:19:30.658  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:19:30.658  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:19:30.658  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:19:30.659  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:19:30.660  4682  4762 D BtGatt.ScanManager: handling starting scan
,09-28 10:19:30.662  5726  5773 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 10:19:30.667  4682  4758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 10:19:30.667  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.668  4682  4762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:19:30.674  4682  4758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 10:19:30.674  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:30.674  4682  4762 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:19:30.674  4682  4762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 10:19:30.684  4682  4758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:19:30.684  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:30.690  4682  4758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:19:30.690  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:19:31.159  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 10:19:31.160  5726  5726 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:19:31.160  5726  5726 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 10:19:31.237   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:31.256  3533  3533 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:19:32.238   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:33.239   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 10:19:35.662  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:19:35.663  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:35.663  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:19:35.663  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:35.663  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:19:35.663  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:35.663  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-28 10:19:35.663  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:19:35.663  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:19:35.663  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:19:35.664  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:19:35.664  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 10:19:35.669  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:19:35.671  4682  4699 D BtGatt.GattService: stopScan() - queue size =1
09-28 10:19:35.672  4682  4917 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:19:35.673  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:19:35.673  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:19:35.673  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:19:35.673  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:19:35.673  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 10:19:35.673  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 10:19:35.673  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:19:35.673  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 10:19:35.675  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:19:35.675  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:19:35.675  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 10:19:35.675  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:19:35.676  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:19:35.676  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:35.679  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:35.679  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:35.679  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:19:35.679  4682  4682 D BtGatt.ScanManager: awakened up at time 246805
,09-28 10:19:35.689  4682  4758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 10:19:35.689  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:35.689  4682  4762 D BtGatt.ScanManager: stopping BLe Batch
,09-28 10:19:35.695  4682  4758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 10:19:35.695  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:35.695  4682  4762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 10:19:35.710  4682  4758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-28 10:19:35.710  4682  4758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:19:35.710  4682  4758 D BtGatt.GattService: current time is 246836495215
09-28 10:19:35.710  4682  4758 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -75, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -52, 11, 57, -70, 107, -17, 1, 0, -97, 94, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0, 37, -47, 14, -113, 116, -46, 1, -128, -73, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -80, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 10:19:35.710  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 10:19:35.710  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 10:19:35.711  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 10:19:35.711  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
09-28 10:19:35.711  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 10:19:35.711  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 10:19:35.712  4682  4758 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, ,-117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-28 10:19:36.180  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:19:36.180  5726  5726 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:36.181  5726  5726 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 10:19:40.680  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:19:40.680  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:19:40.680  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.681  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.681  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:40.681  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:19:40.681  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.681  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.681  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:40.682  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.682  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.682  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.683  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:40.684  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.686  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.686  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.686  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:40.687  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.688  5726  5773 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-28 10:19:40.690  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.690  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.690  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 10:19:40.690  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.691  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.691  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.691  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.691  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
,09-28 10:19:40.691  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.691  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.691  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 10:19:40.692  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.692  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.692  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.692  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.695  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:19:40.695  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.695  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.695  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.697  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 10:19:40.698  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:19:40.698  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.698  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.698  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.698  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.698  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.698  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:40.698  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.698  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.699  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.699  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.699  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:40.699  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.699  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.699  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.700  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:19:40.701  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.701  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.701  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.701  5726  5773 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-28 10:19:40.702  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.702  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.702  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.702  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.702  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.702  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:40.702  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.702  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.702  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.702  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.703  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.703  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:40.703  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.703  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.703  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.704  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.704  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 10:19:40.704  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.704  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.705  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 10:19:40.705  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.705  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.706  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 10:19:40.706  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.706  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.706  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.706  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.706  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.706  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:40.706  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.706  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.706  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.706  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.706  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.706  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:40.708  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.708  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.708  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:40.708  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.709  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 10:19:40.709  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:19:40.709  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:19:40.709  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 10:19:40.709  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:19:40.709  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-28 10:19:40.709  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 10:19:40.710  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:19:40.710  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:19:40.710  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.710  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.710  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.710  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 10:19:40.710  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.710  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.710  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.710  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.710  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.711  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.711  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 10:19:40.711  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.711  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.711  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.711  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:40.715  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:19:40.715  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.715  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.715  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.718  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:19:40.718  5726  5773 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 10:19:40.719  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 10:19:40.723  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-28 10:19:40.724  5726  5773 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 10:19:40.724  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 10:19:40.725  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 10:19:40.725  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 10:19:40.726  5726  5773 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 10:19:40.726  5726  5773 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-28 10:19:40.726  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:19:40.726  5726  5773 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 10:19:40.726  5726  5773 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-28 10:19:40.726  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:19:40.726  5726  5773 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 10:19:40.726  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-28 10:19:40.730  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-28 10:19:40.731  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-28 10:19:40.731  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-28 10:19:40.731  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 10:19:40.731  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-28 10:19:40.731  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 10:19:40.732  5726  5773 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:19:40.732  5726  5773 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 10:19:40.732  5726  5775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
09-28 10:19:40.732  5726  5775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-28 10:19:40.732  5726  5775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-28 10:19:40.732  5726  5775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-28 10:19:40.733  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.733  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.733  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.733  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.733  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.733  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.733  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.733  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-28 10:19:40.734  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.734  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.734  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.734  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.734  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.734  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.734  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.734  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.735  5726  5775 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-28 10:19:40.735  5726  5776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
09-28 10:19:40.735  5726  5776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
09-28 10:19:40.735  5726  5775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:19:40.735  5726  5776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
09-28 10:19:40.732  5412  5412 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30251]" dev="sockfs" ino=30251 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:19:40.735  5412  5412 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30251]" dev="sockfs" ino=30251 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:19:40.736  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.736  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.736  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.737  5726  5775 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-28 10:19:40.737  5726  5775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-28 10:19:40.737  5726  5775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
09-28 10:19:40.740  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.741  5726  5773 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 10:19:40.742  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.742  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.742  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.742  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.742  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.742  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.742  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.742  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.742  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.742  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.743  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.743  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.743  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.743  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.743  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.744  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.744  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.744  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.744  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.745  5726  5773 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 10:19:40.745  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.745  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.745  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.745  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.745  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.745  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.745  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.746  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.746  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.746  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.746  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.746  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.746  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.746  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.746  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.748  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.748  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.748  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.748  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.749  5726  5773 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 10:19:40.749  5726  5773 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 10:19:40.749  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 10:19:40.749  5726  5773 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 10:19:40.749  5726  5773 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 10:19:40.749  5726  5773 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 10:19:40.749  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 10:19:40.749  5726  5773 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-28 10:19:40.750  5726  5773 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 10:19:40.750  5726  5773 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 10:19:40.750  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 10:19:40.750  5726  5773 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 10:19:40.750  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:40.750  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:40.750  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:40.750  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.750  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.750  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.750  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.750  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.750  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.750  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.750  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.750  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.751  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.751  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.751  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.752  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:40.752  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:40.752  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.752  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.752  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:40.752  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.752  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:40.752  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:40.753  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:40.753  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:40.753  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:40.753  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:40.753  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:40.753  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:43.240   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:44.240   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:45.241   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:45.754  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:45.754  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.754  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.754  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.754  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:45.755  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:45.755  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:45.755  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:45.755  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:19:45.755  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:45.756  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.756  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.756  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.756  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:45.756  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:45.756  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.757  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.757  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:45.757  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:45.757  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.757  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.757  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.760  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:19:45.760  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:45.760  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.761  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.767  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-28 10:19:45.768  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:19:45.770  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 10:19:45.772  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-28 10:19:45.772  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-28 10:19:45.773  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 10:19:45.773  5726  5777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-28 10:19:45.773  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-28 10:19:45.773  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:19:45.773  5726  5726 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-28 10:19:45.774  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.774  5726  5777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:19:45.774  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-28 10:19:45.774  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:19:45.774  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 10:19:45.774  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.774  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-28 10:19:45.774  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 10:19:45.774  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:45.774  5726  5726 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-28 10:19:45.774  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.775  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:19:45.775  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:19:45.775  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:19:45.775  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.775  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.777  5726  5777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-28 10:19:45.777  5726  5777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:19:45.777  5726  5777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 10:19:45.772  4699  4699 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32695]" dev="sockfs" ino=32695 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:19:45.772  4699  4699 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32695]" dev="sockfs" ino=32695 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:19:45.778  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:19:45.778  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.778  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:45.778  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:45.778  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:19:45.778  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:45.779  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:45.779  5726  5726 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-28 10:19:45.779  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.779  5726  5726 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:45.779  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:19:45.779  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.779  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.779  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:19:45.779  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
,09-28 10:19:45.779  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.780  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.780  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:45.780  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.780  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.780  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.780  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:45.782  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:45.782  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:45.782  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.782  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:45.784  5726  5773 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-28 10:19:45.785  5726  5773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 10:19:45.785  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 10:19:45.785  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:19:45.785  5726  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:19:45.785  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:45.785  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:19:45.785  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:45.785  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.785  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.786  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.786  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:45.786  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:45.786  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.786  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:45.786  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:45.786  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:45.786  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.786  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.786  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:45.788  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:45.788  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:45.788  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.788  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:45.795  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:19:45.795  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:19:45.795  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:45.796  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.796  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.796  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.796  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:45.796  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:45.796  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.796  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.796  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:45.796  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.796  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.796  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:45.796  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.797  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:45.797  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:45.797  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.797  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.798  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:19:45.798  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:19:45.798  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:19:45.798  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:19:45.798  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.798  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.798  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:19:45.798  5726  5773 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90bd067 not in the list
09-28 10:19:45.799  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.799  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
09-28 10:19:45.799  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:45.799  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.799  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:45.799  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:45.799  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:45.800  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:19:45.800  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:19:45.800  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:19:45.800  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a314e14 not in the list
,09-28 10:19:45.801  5726  5773 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-28 10:19:45.801  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 10:19:45.801  5726  5773 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 10:19:45.801  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 10:19:45.801  5726  5773 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-28 10:19:45.801  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 10:19:45.803  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-28 10:19:45.804  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-28 10:19:45.805  5726  5773 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-28 10:19:45.805  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 10:19:45.805  5726  5773 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-28 10:19:45.805  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 10:19:45.805  5726  5773 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-28 10:19:45.805  5726  5773 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-28 10:19:45.806  5726  5773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 10:19:45.806  5726  5773 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-28 10:19:45.807  5726  5773 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-28 10:19:45.807  5726  5773 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-28 10:19:45.807  5726  5773 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 10:19:45.807  5726  5773 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-28 10:19:45.808  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:19:45.808  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db02ad6 added. We now have 3 listener(s)
09-28 10:19:45.808  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:19:45.810  5726  5773 D BluetoothAdapter: enable(): BT is already enabled..!
09-28 10:19:45.810   927  3864 D WifiService: setWifiEnabled: true pid=5726, uid=10077
09-28 10:19:45.810   927  3864 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:19:45.863  4682  4887 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-28 10:19:45.863  4682  4903 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-28 10:19:46.242   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:46.279  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:19:47.244   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:19:48.244   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 10:19:49.967   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:19:50.816  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:19:50.816  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@893a157 added. We now have 4 listener(s)
,09-28 10:19:50.816  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:19:50.829  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:50.830  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@893a157 removed from the list
,09-28 10:19:50.830  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:19:50.830  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:19:50.830  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:19:50.832  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:19:50.833  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e6444 added. We now have 4 listener(s)
09-28 10:19:50.833  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:19:50.837  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:19:50.837  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e6444 removed from the list
09-28 10:19:50.837  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 10:19:50.838  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:19:50.838  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:19:50.840  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:19:50.840  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e85992d added. We now have 4 listener(s)
09-28 10:19:50.840  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:19:50.845   927  3895 D WifiService: setWifiEnabled: false pid=5726, uid=10077
09-28 10:19:50.845   927  3895 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:19:50.850   927  3039 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-28 10:19:50.850   927  3039 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-28 10:19:50.850   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 10:19:50.851   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:19:50.856  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:19:50.859  4682  4754 D BluetoothAdapterState: Current state: ON, message: 23
09-28 10:19:50.859  4682  4754 D BluetoothAdapterProperties: Setting state to 13
09-28 10:19:50.860  4682  4754 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 10:19:50.862  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:50.862  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:50.864  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.864  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:50.864  4682  4754 D BluetoothAdapterProperties: onBluetoothDisable()
09-28 10:19:50.864  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:19:50.865  4682  4754 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:19:50.866   927  5442 D DhcpClient: Clearing IP address
,09-28 10:19:50.866  4682  4758 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:19:50.867  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:50.867  4682  4754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 10:19:50.867   506   922 D CommandListener: Clearing all IP addresses on wlan0
09-28 10:19:50.870  4682  4682 D HeadsetService: Received stop request...Stopping profile...
09-28 10:19:50.872  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.877  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:50.877  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:50.878  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.878  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:50.878  3644  5498 V NativeCrypto: Read error: ssl=0x7f810afe80: I/O error during system call, Connection timed out
09-28 10:19:50.879  3193  3986 D BluetoothHeadset: Proxy object disconnected
09-28 10:19:50.879  3193  3193 D HeadsetProfile: Bluetooth service disconnected
,09-28 10:19:50.880   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 10:19:50.880   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 10:19:50.880   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 10:19:50.881  3644  5498 V NativeCrypto: SSL shutdown failed: ssl=0x7f810afe80: I/O error during system call, Broken pipe
09-28 10:19:50.881  3856  4067 D BluetoothHeadset: Proxy object disconnected
09-28 10:19:50.881  4682  4682 D A2dpService: Received stop request...Stopping profile...
09-28 10:19:50.882  4682  4911 D A2dpStateMachine: Exit Disconnected: -1
09-28 10:19:50.883  3193  3193 D BluetoothA2dp: Proxy object disconnected
09-28 10:19:50.883   927   927 D BluetoothA2dp: Proxy object disconnected
09-28 10:19:50.884  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:19:50.884  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:19:50.884   927  3882 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-28 10:19:50.885  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.885   927  5438 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-28 10:19:50.885  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:19:50.885  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.885  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.886  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:50.886  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:19:50.887   927  5438 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-28 10:19:50.888  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.888   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-28 10:19:50.888  4682  4682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 10:19:50.888   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-28 10:19:50.888  4682  4682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 10:19:50.889  4682  4758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 10:19:50.889  4682  4887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:19:50.889  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.889  4682  4887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:19:50.889  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.889  4682  4887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:19:50.889  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:50.889  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:19:50.889  4682  4758 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 10:19:50.890   506   922 D CommandListener: Setting iface cfg
09-28 10:19:50.891   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 10:19:50.891   927  5443 D DhcpClient: Receive thread stopped
09-28 10:19:50.894  4682  4758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 10:19:50.894  4682  4887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 10:19:50.894  4682  4887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:19:50.894  4682  4887 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:19:50.895  4682  4887 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:19:50.895  4682  4887 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:19:50.895  4682  4887 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:19:50.895  4682  4682 D HidService: Received stop request...Stopping profile...
,09-28 10:19:50.896  4682  4682 D HidService: Stopping Bluetooth HidService
09-28 10:19:50.898  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.898  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.898  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:50.899  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:19:50.899  4682  4682 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 10:19:50.899  4682  4682 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 10:19:50.899  3193  3193 D BluetoothInputDevice: Proxy object disconnected
09-28 10:19:50.899  3193  3193 D HidProfile: Bluetooth service disconnected
09-28 10:19:50.899  4682  4682 D HealthService: Received stop request...Stopping profile...
09-28 10:19:50.899  4682  4758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:19:50.901   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 10:19:50.901   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-28 10:19:50.904   541   541 E Parcel  : Reading a NULL string not supported here.
09-28 10:19:50.901  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.905  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.905  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:50.905  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:19:50.906  4682  4682 D PanService: Received stop request...Stopping profile...
09-28 10:19:50.906   927  3041 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-28 10:19:50.907  4682  4682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 10:19:50.907  4682  4758 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 10:19:50.908  4682  4682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 10:19:50.909  3825  3970 W QCNEJ   : |CORE| network lost: 100
,09-28 10:19:50.909  3825  3970 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 10:19:50.911   927   927 D RttService: SCAN_AVAILABLE : 1
,09-28 10:19:50.911   927  3148 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-28 10:19:50.922  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.922  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.922  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 10:19:50.922  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:19:50.922  4682  4682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 10:19:50.922  3193  3193 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 10:19:50.922  3193  3193 D PanProfile: Bluetooth service disconnected
09-28 10:19:50.922  4682  4682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 10:19:50.923  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:50.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:50.925  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.926  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:19:50.927  4682  4682 D BluetoothMapService: Received stop request...Stopping profile...
09-28 10:19:50.927  4682  4682 D BluetoothMapService: stop()
09-28 10:19:50.929  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:50.929  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:50.930   927   940 I ActivityManager: Start proc 5785:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-28 10:19:50.930  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.930  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:19:50.931   927  3039 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 10:19:50.932  4682  4682 D BluetoothMapAppObserver: deinitObservers()
09-28 10:19:50.932  4682  4682 D BluetoothMapAppObserver: removeReceiver()
09-28 10:19:50.932  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:50.932  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:50.933  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.933  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:19:50.933  4682  4682 D SapService: Received stop request...Stopping profile...
09-28 10:19:50.933  4682  4682 V SapService: stop()
09-28 10:19:50.935  4682  4682 D BluetoothMapService: MAP Service closeService in
09-28 10:19:50.935  4682  4682 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 10:19:50.935  4682  4682 D ObexServerSockets0: shutdown(block = true)
09-28 10:19:50.935  4682  4682 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 10:19:50.935  4682  4918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-28 10:19:50.935  4682  4682 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-28 10:19:50.935  4682  4903 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 10:19:50.936  4682  4919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 10:19:50.936  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.936  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.936  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:50.936  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:19:50.936  4682  4682 D BluetoothMapService: cleanup()
09-28 10:19:50.936  4682  4682 D BluetoothMapService: MAP Service closeService in
09-28 10:19:50.938  4682  4682 V BluetoothAdapterState: isTurningOff()=true
09-28 10:19:50.938  4682  4682 V BluetoothAdapterState: isTurningOn()=false
09-28 10:19:50.938  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:50.938  4682  4682 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:19:50.938  4682  4754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 10:19:50.938  4682  4754 D BluetoothAdapterProperties: Setting state to 15
09-28 10:19:50.938  4682  4754 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 10:19:50.938  4682  4682 I BtOppRfcommListener: stopping Accept Thread
09-28 10:19:50.938  4682  4754 I BluetoothAdapterState: Entering BleOnState
09-28 10:19:50.939  4682  5400 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 10:19:50.939  4682  5400 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-28 10:19:50.940  3856  4067 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:19:50.941  3193  3211 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:19:50.941  3193  3206 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 10:19:50.941   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:19:50.942   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:19:50.942  3193  3986 D BluetoothMap: onBluetoothStateChange: up=false
09-28 10:19:50.943   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:19:50.943  3193  4031 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:19:50.943   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:19:50.943   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:19:50.944  3193  3211 D BluetoothPan: onBluetoothStateChange on: false
,09-28 10:19:50.944  3193  3206 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 10:19:50.946  4682  4754 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 10:19:50.946  4682  4754 D BluetoothAdapterProperties: Setting state to 16
09-28 10:19:50.946  4682  4754 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 10:19:50.946  4682  4754 D BluetoothAdapterProperties: onBleDisable
09-28 10:19:50.946  4682  4754 I BluetoothAdapterState: Entering PendingCommandState
09-28 10:19:50.947  4682  4755 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-28 10:19:50.950  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:50.950  4682  4887 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 10:19:50.950  4682  4887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:19:50.950  4682  4758 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:19:50.951  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.953  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:50.956   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 10:19:50.955  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:50.959  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.961  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:50.977   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 10:19:50.977   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:19:50.978   927  3041 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-28 10:19:50.978   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:19:50.980   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-28 10:19:50.982  5323  5323 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@66b0c47 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-28 10:19:50.982   927  3039 D DhcpClient: doQuit
,09-28 10:19:50.982   927  3039 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 10:19:50.983   927  5442 D DhcpClient: onQuitting
09-28 10:19:50.983  3533  3533 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 10:19:50.984  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.986  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:50.987  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:50.988  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.988  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:19:50.989  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:50.990  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:19:50.991  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:19:50.991  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:19:50.992  5107  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 10:19:50.992  5107  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:19:50.993  5107  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 10:19:50.993  5107  5120 E SarControlService: no key has been found,reset the power
09-28 10:19:50.993  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.993  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:50.993  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:50.993  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:19:50.993  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 10:19:50.993  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:19:50.993  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:50.994  5133  5133 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:19:50.994  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:19:50.996  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.996  3533  3533 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 10:19:50.997  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:19:50.997  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:19:50.997  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:19:50.997  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:50.997  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:19:50.997  5133  5133 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 10:19:51.000  3533  3533 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-28 10:19:51.003  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000ea03000000000000ffffffff]
09-28 10:19:51.003  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:19:51.003  5133  5147 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 10:19:51.003  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-28 10:19:51.003  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 10:19:51.005  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000eb03000000000000ffffffff]
09-28 10:19:51.005  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-28 10:19:51.005  5133  5147 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-28 10:19:51.006  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:19:51.006  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 10:19:51.011  5785  5785 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-28 10:19:51.024  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:19:51.025   506   922 E Netd    : netlink response contains error (No such file or directory)
09-28 10:19:51.026   927  3041 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 10:19:51.026   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 10:19:51.029  3533  3533 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 10:19:51.029   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@66d7c65:true
,09-28 10:19:51.031  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:19:51.040  3533  3533 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 10:19:51.044   927  3864 I ActivityManager: Start proc 5804:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 10:19:51.052  5785  5785 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 10:19:51.058  5785  5785 D BluetoothMap: Create BluetoothMap proxy object
,09-28 10:19:51.064  5785  5785 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 10:19:51.082  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:19:51.085  5804  5804 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 10:19:51.087   927  3864 I ActivityManager: Killing 5069:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 10:19:51.144  4481  4481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 10:19:51.144   927  3039 D wifi    : In wifi stop Hal
09-28 10:19:51.144   927  3039 D wifi    : halHandle = 0x7f6f556680, mVM = 0x7f8bb8d140, mCls = 0x100a02
,09-28 10:19:51.145   927  3532 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 10:19:51.145   927  3532 D WifiHAL : Got a signal to exit!!!
09-28 10:19:51.145   927  3532 I WifiHAL : Exit wifi_event_loop
09-28 10:19:51.146   927  3039 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 10:19:51.146   927  3039 E WifiHAL : Event processing terminated
,09-28 10:19:51.146   927  3039 D wifi    : In wifi cleaned up handler
09-28 10:19:51.146   927  3039 I WifiHAL : Internal cleanup completed
09-28 10:19:51.146  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:51.147  3789  4271 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 10:19:51.148  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:51.150  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:51.158  4682  4758 I bt_hci  : shut_down
,09-28 10:19:51.162  4682  4764 D bt_hwcfg: hw_epilog_process
,09-28 10:19:51.162  4682  4764 I bt_vendor: low_power_mode_cb
,09-28 10:19:51.164  4682  4764 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 10:19:51.165  4682  4764 I bt_vendor: epilog_cb
09-28 10:19:51.165  4682  4764 I bt_hci  : epilog_finished_callback
09-28 10:19:51.165   927  3532 D wifi    : set interface wlan0 flags (DOWN)
,09-28 10:19:51.166   927  3039 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 10:19:51.167  4682  4758 I bt_hci_h4: hal_close
09-28 10:19:51.167  4682  4758 I bt_userial_vendor: device fd = 54 close
,09-28 10:19:51.228   506   922 E Netd    : netlink response contains error (No such file or directory)
,09-28 10:19:51.273  4682  4755 D bt_stack_manager: event_shut_down_stack finished.
,09-28 10:19:51.274  4682  4754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 10:19:51.276  4682  4754 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-28 10:19:51.276  4682  4682 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:19:51.276  4682  4682 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 10:19:51.276  4682  4682 D BtGatt.GattService: stop()
09-28 10:19:51.276  4682  4682 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 10:19:51.278  4682  4682 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:19:51.278  4682  4682 V BluetoothAdapterState: isTurningOn()=false
,09-28 10:19:51.278  4682  4682 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:19:51.278  4682  4682 V BluetoothAdapterState: isBleTurningOff()=true
09-28 10:19:51.278  4682  4754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 10:19:51.278  4682  4754 D BluetoothAdapterProperties: Setting state to 10
09-28 10:19:51.278  4682  4754 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 10:19:51.279  4682  4754 I BluetoothAdapterState: Entering OffState
09-28 10:19:51.280   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-28 10:19:51.286  4682  4682 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 10:19:51.286  4682  4682 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 10:19:51.286  4682  4682 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 10:19:51.287  4682  4755 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 10:19:51.299  4682  4755 D bt_stack_manager: event_clean_up_stack finished.
,09-28 10:19:51.300  4682  4682 I art     : System.exit called, status: 0
09-28 10:19:51.300  4682  4682 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.305  5804  5804 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:19:51.305  5804  5804 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:19:51.309  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 10:19:51.326  5785  5785 D DockEventReceiver: finishStartingService: stopping service
09-28 10:19:51.327   927  3864 I ActivityManager: Killing 5473:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-28 10:19:51.355   927  3477 I ActivityManager: Process com.android.bluetooth (pid 4682) has died
09-28 10:19:51.358  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 10:19:51.368   927   944 D Tethering: InitialState.processMessage what=4
09-28 10:19:51.369   927   938 I ActivityManager: Start proc 5842:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
09-28 10:19:51.372   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 10:19:51.445  5842  5842 D AdapterServiceConfig: Adding HeadsetService
09-28 10:19:51.445  5842  5842 D AdapterServiceConfig: Adding A2dpService
09-28 10:19:51.445  5842  5842 D AdapterServiceConfig: Adding HidService
09-28 10:19:51.445  5842  5842 D AdapterServiceConfig: Adding HealthService
09-28 10:19:51.445  5842  5842 D AdapterServiceConfig: Adding PanService
09-28 10:19:51.445  5842  5842 D AdapterServiceConfig: Adding GattService
09-28 10:19:51.446  5842  5842 D AdapterServiceConfig: Adding BluetoothMapService
09-28 10:19:51.446  5842  5842 D AdapterServiceConfig: Adding SapService
,09-28 10:19:51.458   927  3852 I ActivityManager: Killing 5485:com.android.chrome/u0a39 (adj 15): empty #17
,09-28 10:19:51.492  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 10:19:51.495  4073  4073 D SystemUpdateService: onCreate
,09-28 10:19:51.499  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 10:19:51.505  4073  5854 I SystemUpdateService: active receiver: enabled
,09-28 10:19:51.507  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 10:19:51.513  4073  5469 I iu.UploadsManager: num queued entries: 0
,09-28 10:19:51.513  4073  5469 I iu.UploadsManager: num updated entries: 0
,09-28 10:19:51.525  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 10:19:51.526  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:19:51.528  4073  5854 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:19:51.530  4073  5469 I iu.SyncManager: NEXT; no task
,09-28 10:19:51.531  4073  5854 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-28 10:19:51.531  4073  5854 I SystemUpdateService: now status is 0 (complete)
09-28 10:19:51.531  4073  5854 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:19:51.531  4073  5854 I SystemUpdateService: file has been verified
09-28 10:19:51.532  4073  5854 I SystemUpdateService: OTA package size = 21989297
,09-28 10:19:51.539   927  3852 I ActivityManager: Start proc 5856:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-28 10:19:51.557  4073  5854 I SystemUpdateService: showing system update notification
,09-28 10:19:51.572  5856  5856 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-28 10:19:51.579  5856  5856 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:19:51.585  5856  5856 D SprintDMHelper: simOperator: 
09-28 10:19:51.585  5856  5856 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:19:51.597   927  3864 I ActivityManager: Start proc 5868:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-28 10:19:51.612  4073  4073 D SystemUpdateService: onDestroy
,09-28 10:19:51.614   927  3292 I ActivityManager: Killing 5502:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-28 10:19:51.715  4481  5882 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 10:19:51.719   927  3886 I ActivityManager: Start proc 5883:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-28 10:19:51.722   927  3864 I ActivityManager: Killing 5323:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 10:19:51.754  5804  5822 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 10:19:51.780  5883  5883 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-28 10:19:51.932   927  3882 I ActivityManager: Killing 4768:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 10:19:51.950   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@239909a:true
,09-28 10:19:51.979   927  3477 I ActivityManager: Start proc 5897:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 10:19:52.012  5897  5897 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 10:19:52.020   927  3895 I ActivityManager: Killing 5589:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-28 10:19:55.867   927  3292 D WifiService: setWifiEnabled: true pid=5726, uid=10077
,09-28 10:19:55.867   927  3292 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:19:55.878   506   922 D SoftapController: Softap fwReload - Ok
,09-28 10:19:55.883   506   922 D CommandListener: Setting iface cfg
,09-28 10:19:55.884   506   922 D CommandListener: Trying to bring down wlan0
,09-28 10:19:55.885   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:19:55.892   927  3039 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 10:19:56.459   927  3039 D wifi    : set interface wlan0 flags (UP)
,09-28 10:19:56.462   927  3039 I WifiHAL : Initializing wifi
09-28 10:19:56.462   927  3039 I WifiHAL : Creating socket
09-28 10:19:56.464   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 10:19:56.467   927  3039 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 10:19:56.467   927  3039 D wifi    : Did set static halHandle = 0x7f6f556680
09-28 10:19:56.467   927  3039 D wifi    : halHandle = 0x7f6f556680, mVM = 0x7f8bb8d140, mCls = 0x1962
,09-28 10:19:56.467   927  3039 D wifi    : array field set
,09-28 10:19:56.468   927  3039 I WifiNative-HAL: interface[0] = wlan0
,09-28 10:19:56.470   927  5918 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547328714368
,09-28 10:19:56.470   927  5918 D wifi    : waitForHalEvents called, vm = 0x7f8bb8d140, obj = 0x1962, env = 0x7f6ec5e840
,09-28 10:19:56.541  5919  5919 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 10:19:56.555  5919  5919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:19:56.573   927  3039 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 10:19:56.576  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:56.578  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:19:56.578  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:19:56.592  5919  5919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:19:56.592  5919  5919 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 10:19:56.607  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:56.607  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:19:56.607  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:56.607  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:19:56.609  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:56.609  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:56.609  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:56.609  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:19:56.610   927  3039 D WifiConfigStore: Loading config and enabling all networks 
,09-28 10:19:56.611  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:19:56.611  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:19:56.611  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:19:56.611  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:19:56.619   927  3039 D WifiConfigStore: loaded 0 passpoint configs
,09-28 10:19:56.620   927  3039 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 10:19:56.620   927  3039 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 10:19:56.622   927  3039 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 10:19:56.623   927  3039 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 10:19:56.623   927  3039 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 10:19:56.623   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 10:19:56.623   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 10:19:56.627   927  3039 D WifiNative-HAL: Setting external_sim to 1
,09-28 10:19:56.627  4481  4481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:19:56.628   927  3039 D wifi    : setting dfs flag to true, 0x7f6ec49040
09-28 10:19:56.628   927  3039 D WifiStateMachine: Setting OUI to DA-A1-19
,09-28 10:19:56.628   927  3039 D wifi    : setting scan oui 0x7f6ec49040
09-28 10:19:56.628   927  3039 D WifiHAL : Sending mac address OUI
,09-28 10:19:56.632   927  3039 E native  : do suspend false
,09-28 10:19:56.639   927  3039 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 10:19:56.639   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-28 10:19:56.640   927   927 D RttService: SCAN_AVAILABLE : 3
09-28 10:19:56.640   927  3148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 10:19:56.641   506   922 D CommandListener: Setting iface cfg
,09-28 10:19:56.644   927  3038 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
09-28 10:19:56.644   927  3038 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 10:19:56.652   927  3038 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 10:19:56.652   927  3038 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 10:19:56.657   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267783 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-28 10:19:59.791  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:19:59.796  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:19:59.802  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:19:59.865   927  3039 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 10:19:59.866   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 10:19:59.866   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:19:59.878   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 10:19:59.912   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 10:19:59.915  5919  5919 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 10:20:00.348  5919  5919 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 10:20:00.394  5919  5919 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-28 10:20:00.396  5919  5919 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 10:20:00.405   927  3039 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-28 10:20:00.406   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 10:20:00.406   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 10:20:00.425   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:20:00.440   506   922 D CommandListener: Setting iface cfg
,09-28 10:20:00.447   927  3039 D WifiStateMachine: Start Dhcp Watchdog 2
,09-28 10:20:00.456   927  5934 D DhcpClient: Receive thread started
,09-28 10:20:00.458   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 10:20:00.458   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-28 10:20:00.458   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-28 10:20:00.538   927  3039 E native  : do suspend false
,09-28 10:20:00.550   927  5933 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 10:20:00.589   927  5934 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
,09-28 10:20:00.589   927  5933 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
,09-28 10:20:00.592   927  5933 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 10:20:00.614   927  5934 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 10:20:00.615   927  5933 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 10:20:00.618   506   922 D CommandListener: Setting iface cfg
09-28 10:20:00.625   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 10:20:00.627   927  5933 D DhcpClient: Scheduling renewal in 86399s
,09-28 10:20:00.642   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 10:20:00.645   927  3039 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 10:20:00.647   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-28 10:20:00.649   927  3041 D ConnectivityService: Adding iface wlan0 to network 101
,09-28 10:20:00.665   927  3039 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 10:20:00.699   927  3041 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 10:20:00.699   927  3041 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-28 10:20:00.701   927  3041 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-28 10:20:00.702   927  3041 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 10:20:00.707   927  3041 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 10:20:00.714   927  3041 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 10:20:00.719   927  3041 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-28 10:20:00.719   927  3041 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-28 10:20:00.719   927  3041 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-28 10:20:00.719   927  3039 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 10:20:00.719   927  3041 D ConnectivityService:    accepting network in place of null
09-28 10:20:00.719   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:20:00.720   927  3041 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:20:00.738   927  5932 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 10:20:00.743   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:20:00.764   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:20:00.767   927  3041 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-28 10:20:00.767   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 10:20:00.767  3825  3970 W QCNEJ   : |CORE| network available: 101
09-28 10:20:00.769   927  3041 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-28 10:20:00.769   927   944 D Tethering: MasterInitialState.processMessage what=3
09-28 10:20:00.772  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:00.773  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:20:00.773  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.773  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:20:00.775  3825  3970 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 10:20:00.776  3825  3970 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 10:20:00.776  3825  3970 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 10:20:00.778  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:00.778  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:20:00.778  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.778  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:00.781  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:00.781  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:20:00.781  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.781  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:00.782  5107  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 10:20:00.782  5107  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:20:00.782  5107  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 10:20:00.782  5107  5120 E SarControlService: no key has been found,reset the power
09-28 10:20:00.782  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:20:00.782  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:20:00.782  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 10:20:00.783  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 10:20:00.783  5133  5133 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:20:00.784  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:20:00.784  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:20:00.784  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:20:00.785  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:20:00.785  5133  5133 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-28 10:20:00.790  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 10:20:00.791  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000ec03000000000000ffffffff]
09-28 10:20:00.791  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:20:00.791  5133  5147 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 10:20:00.793  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:20:00.794  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 10:20:00.794  4073  4073 D SystemUpdateService: onCreate
09-28 10:20:00.797  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 10:20:00.800  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000ed03000000000000ffffffff]
09-28 10:20:00.800  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:20:00.800  5133  5147 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-28 10:20:00.800  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:20:00.801  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 10:20:00.808  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 10:20:00.812   927  5931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-28 10:20:00.819  4073  5469 I iu.UploadsManager: num queued entries: 0
,09-28 10:20:00.819  4073  5469 I iu.UploadsManager: num updated entries: 0
09-28 10:20:00.820  4073  5469 I iu.SyncManager: NEXT; no task
,09-28 10:20:00.821  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-28 10:20:00.822  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:20:00.824  5856  5856 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:20:00.827  5856  5856 D SprintDMHelper: simOperator: 
09-28 10:20:00.827  5856  5856 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:20:00.835  4073  5946 I SystemUpdateService: active receiver: enabled
,09-28 10:20:00.866  4073  5946 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:20:00.867  4073  5946 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 10:20:00.867  4073  5946 I SystemUpdateService: now status is 0 (complete)
09-28 10:20:00.868  4073  5946 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:20:00.868  4073  5946 I SystemUpdateService: file has been verified
09-28 10:20:00.868  4073  5946 I SystemUpdateService: OTA package size = 21989297
,09-28 10:20:00.874   927  5931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 14:20:00 GMT], X-Android-Received-Millis=[1475072400873], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475072400844]}
,09-28 10:20:00.875   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 10:20:00.875   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-28 10:20:00.875   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 10:20:00.875   927  3886 D WifiService: setWifiEnabled: false pid=5726, uid=10077
09-28 10:20:00.875   927  3886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-28 10:20:00.876  4073  5946 I SystemUpdateService: showing system update notification
09-28 10:20:00.876   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 10:20:00.878   927  3039 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-28 10:20:00.878   927  3039 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 10:20:00.878   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:20:00.879   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:20:00.887   927  5933 D DhcpClient: Clearing IP address
,09-28 10:20:00.887   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:20:00.889   506   922 D CommandListener: Setting iface cfg
,09-28 10:20:00.891  4073  4073 D SystemUpdateService: onDestroy
09-28 10:20:00.893  3644  5947 V NativeCrypto: SSL handshake aborted: ssl=0x7f810aa000: I/O error during system call, Connection timed out
09-28 10:20:00.895   927  5934 D DhcpClient: Receive thread stopped
09-28 10:20:00.899   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 10:20:00.899   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-28 10:20:00.901   927  3912 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-28 10:20:00.901   927  5931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-28 10:20:00.901   927  5931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
09-28 10:20:00.901   541   541 E Parcel  : Reading a NULL string not supported here.
09-28 10:20:00.904  4481  5951 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-28 10:20:00.908   927   927 D RttService: SCAN_AVAILABLE : 1
09-28 10:20:00.908   927  3148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 10:20:00.908   927  5931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-28 10:20:00.911   927  3039 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 10:20:00.912   927  3041 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-28 10:20:00.916   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:20:00.916  3825  3970 W QCNEJ   : |CORE| network lost: 101
09-28 10:20:00.917  3825  3970 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: java.net.ConnectException: failed to connect to clients3.google.com/172.217.16.206 (port 80) after 5000ms: connect failed: ENETUNREACH (Network is unreachable)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:124)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.connect(Native Method)
09-28 10:20:00.919,  4481  5951 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-28 10:20:00.919  4481  5951 W Babel_NetworkConnectionCheckingService: 	... 21 more
09-28 10:20:00.919  4481  5951 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 10:20:00.934   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:20:00.954   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 10:20:00.954   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:20:00.955   927  3041 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 10:20:00.955   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:20:00.956   927  3039 D DhcpClient: doQuit
09-28 10:20:00.956   927  3039 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 10:20:00.956   927  5933 D DhcpClient: onQuitting
09-28 10:20:00.957  5919  5919 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 10:20:00.957   927   944 D Tethering: MasterInitialState.processMessage what=3
09-28 10:20:00.960  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:00.960  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:00.960  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.960  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:00.961  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:00.961  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:00.961  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:20:00.961  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:00.962  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:00.962  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:00.962  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:00.962  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:00.965  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:00.967  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:00.968  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:00.969  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 10:20:00.971  5107  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 10:20:00.971  5107  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:20:00.971  5107  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-28 10:20:00.971  5107  5120 E SarControlService: no key has been found,reset the power
09-28 10:20:00.971  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:20:00.971  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:20:00.971  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 10:20:00.972  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:20:00.972  5133  5133 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:20:00.973  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:20:00.973  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:20:00.973  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:20:00.974  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 10:20:00.974  5133  5133 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 10:20:00.976  4073  4073 D SystemUpdateService: onCreate
09-28 10:20:00.978  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000ee03000000000000ffffffff]
09-28 10:20:00.978  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:20:00.978  5133  5147 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,09-28 10:20:00.978  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:20:00.978  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 10:20:00.981  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 10:20:00.982  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 10:20:00.982  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000ef03000000000000ffffffff]
09-28 10:20:00.982  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:20:00.982  5133  5147 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-28 10:20:00.983  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:20:00.983  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 10:20:00.984  5919  5919 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 10:20:00.991  4073  5966 I SystemUpdateService: active receiver: enabled
,09-28 10:20:00.992  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 10:20:00.998  4073  5469 I iu.UploadsManager: num queued entries: 0
,09-28 10:20:00.998  4073  5469 I iu.UploadsManager: num updated entries: 0
09-28 10:20:00.999  4073  5469 I iu.SyncManager: NEXT; no task
,09-28 10:20:01.000  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 10:20:01.002  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:20:01.004  5856  5856 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:20:01.008  5856  5856 D SprintDMHelper: simOperator: 
,09-28 10:20:01.008  5856  5856 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:20:01.012   506   922 E Netd    : netlink response contains error (No such file or directory)
09-28 10:20:01.012   927  3041 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 10:20:01.012   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 10:20:01.019  4481  5970 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 10:20:01.022  4073  5966 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:20:01.025  4073  5966 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 10:20:01.028  5919  5919 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 10:20:01.025  4073  5966 I SystemUpdateService: now status is 0 (complete)
09-28 10:20:01.029  4073  5966 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:20:01.029  4073  5966 I SystemUpdateService: file has been verified
09-28 10:20:01.029  4073  5966 I SystemUpdateService: OTA package size = 21989297
,09-28 10:20:01.037  4073  5966 I SystemUpdateService: showing system update notification
,09-28 10:20:01.044  5919  5919 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-28 10:20:01.047  4073  4073 D SystemUpdateService: onDestroy
,09-28 10:20:01.148   927  3039 D wifi    : In wifi stop Hal
,09-28 10:20:01.149   927  3039 D wifi    : halHandle = 0x7f6f556680, mVM = 0x7f8bb8d140, mCls = 0x1962
09-28 10:20:01.149  4481  4481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:20:01.149   927  5918 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 10:20:01.149   927  5918 D WifiHAL : Got a signal to exit!!!
09-28 10:20:01.149   927  5918 I WifiHAL : Exit wifi_event_loop
09-28 10:20:01.149   927  3039 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 10:20:01.149   927  3039 E WifiHAL : Event processing terminated
09-28 10:20:01.150   927  3039 D wifi    : In wifi cleaned up handler
,09-28 10:20:01.150   927  3039 I WifiHAL : Internal cleanup completed
09-28 10:20:01.151  3789  4271 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:20:01.152  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:01.153  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:01.154  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:01.187   927  5918 D wifi    : set interface wlan0 flags (DOWN)
,09-28 10:20:01.188   927  3039 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 10:20:01.250   506   922 E Netd    : netlink response contains error (No such file or directory)
,09-28 10:20:01.390   927   944 D Tethering: InitialState.processMessage what=4
,09-28 10:20:01.395   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 10:20:01.767   927  3041 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 10:20:03.246   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:04.247   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:05.248   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:05.914   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b6d6cfe:true
,09-28 10:20:05.915  5842  5842 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 10:20:05.921  5842  5842 I bt_bluedroid: init
,09-28 10:20:05.922  5842  5978 I BluetoothAdapterState: Entering OffState
,09-28 10:20:05.926  5842  5979 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 10:20:05.927  5842  5979 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 10:20:05.927  5842  5979 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 10:20:05.927  5842  5979 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-28 10:20:05.929  5842  5842 I bt_bluedroid: get_profile_interface socket
,09-28 10:20:05.932  5842  5982 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:20:05.935  5842  5842 I bt_bluedroid: get_profile_interface sdp
09-28 10:20:05.935  5842  5982 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:20:05.947  5842  5853 I bt_bluedroid: config_hci_snoop_log
,09-28 10:20:05.950   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 10:20:05.958  5842  5978 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 10:20:05.958  5842  5978 D BluetoothAdapterProperties: Setting state to 14
,09-28 10:20:05.958  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 10:20:05.961  5842  5978 D BluetoothBondStateMachine: make
,09-28 10:20:05.965  5842  5983 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 10:20:05.970  5842  5978 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:20:05.972  5842  5842 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 10:20:05.977  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:05.978  5842  5842 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:20:05.980  5842  5842 D BtGatt.GattService: Received start request. Starting profile...
,09-28 10:20:05.980  5842  5842 D BtGatt.GattService: start()
,09-28 10:20:05.981  5842  5842 I bt_bluedroid: get_profile_interface gatt
09-28 10:20:05.982  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:05.983  5842  5842 D BtGatt.AdvertiseManager: advertise manager created
,09-28 10:20:05.992  5842  5842 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:20:05.992  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:05.992  5842  5842 V BluetoothAdapterState: isBleTurningOn()=true
09-28 10:20:05.992  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:05.992  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 10:20:05.994  5842  5978 I bt_bluedroid: bt_bluedroid
09-28 10:20:05.995  5842  5979 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 10:20:05.995  5842  5979 I bt_hci  : start_up
,09-28 10:20:06.005  5842  5979 I bt_vendor: alloc value 0xf3b7c871
,09-28 10:20:06.005  5842  5979 I bt_vendor: init
09-28 10:20:06.005  5842  5979 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 10:20:06.005  5842  5979 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 10:20:06.117  5842  5979 D bt_hci  : start_up starting async portion
,09-28 10:20:06.117  5842  5986 I bt_hci  : event_finish_startup
09-28 10:20:06.118  5842  5986 I bt_hci_h4: hal_open
09-28 10:20:06.118  5842  5986 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 10:20:06.120  5842  5986 I bt_userial_vendor: device fd = 54 open
,09-28 10:20:06.115  5987  5987 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:20:06.133  5842  5986 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:20:06.135  5842  5986 D bt_hwcfg: Chipset BCM4358A3
,09-28 10:20:06.135  5842  5986 D bt_hwcfg: Target name = [BCM4358A3]
09-28 10:20:06.135  5842  5986 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 10:20:06.249   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:06.523  5842  5986 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 10:20:06.524  5842  5986 D bt_hwcfg: Settlement delay -- 100 ms
,09-28 10:20:06.524  5842  5986 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 10:20:06.657  5842  5986 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:20:06.658  5842  5986 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 10:20:06.659  5842  5986 I bt_hwcfg: vendor lib fwcfg completed
09-28 10:20:06.659  5842  5986 I bt_vendor: firmware callback
09-28 10:20:06.660  5842  5986 I bt_hci  : firmware_config_callback
,09-28 10:20:06.670  5842  5989 I bt_btu  : btu_task pending for preload complete event
,09-28 10:20:06.670  5842  5989 I bt_btu_task: Bluetooth chip preload is complete
,09-28 10:20:06.670  5842  5989 I bt_btu  : btu_task received preload complete event
,09-28 10:20:06.677  5842  5989 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 10:20:06.677  5842  5989 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-28 10:20:06.677  5842  5989 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 10:20:06.677  5842  5989 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-28 10:20:06.677  5842  5989 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-28 10:20:06.677  5842  5989 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_GAP
,09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_GATT
,09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 10:20:06.678  5842  5989 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 10:20:06.760  5842  5989 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3afa549
09-28 10:20:06.760  5842  5989 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3afa549 
,09-28 10:20:06.776  5842  5982 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 10:20:06.778  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 10:20:06.778  5842  5982 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 10:20:06.781  5842  5982 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:20:06.784  5842  5982 D BluetoothAdapterProperties: Scan Mode:20
,09-28 10:20:06.784  5842  5982 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:20:06.785  5842  5982 D bt_hci  : do_postload posting postload work item
09-28 10:20:06.785  5842  5986 I bt_hci  : event_postload
09-28 10:20:06.785  5842  5986 I bt_vendor: sco_config_cb
,09-28 10:20:06.785  5842  5986 I bt_hci  : sco_config_callback postload finished.
,09-28 10:20:06.792  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:06.793  5842  5982 D bt_bte_conf: Device ID record 1 : primary
,09-28 10:20:06.793  5842  5982 D bt_bte_conf:   vendorId            = 000f
,09-28 10:20:06.793  5842  5982 D bt_bte_conf:   vendorIdSource      = 0001
09-28 10:20:06.793  5842  5982 D bt_bte_conf:   product             = 1200
09-28 10:20:06.793  5842  5986 I bt_vendor: low_power_mode_cb
09-28 10:20:06.793  5842  5982 D bt_bte_conf:   version             = 1436
09-28 10:20:06.793  5842  5982 D bt_bte_conf:   clientExecutableURL = 
09-28 10:20:06.793  5842  5982 D bt_bte_conf:   serviceDescription  = 
,09-28 10:20:06.794  5842  5982 D bt_bte_conf:   documentationURL    = 
09-28 10:20:06.794  5842  5982 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 10:20:06.794  5842  5979 D bt_stack_manager: event_start_up_stack finished
09-28 10:20:06.795  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 10:20:06.796  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:06.796  5842  5978 D BluetoothAdapterProperties: Setting state to 15
09-28 10:20:06.798  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 10:20:06.799  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:06.799  5842  5978 I BluetoothAdapterState: Entering BleOnState
09-28 10:20:06.803  5842  5978 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 10:20:06.803  5842  5978 D BluetoothAdapterProperties: Setting state to 11
09-28 10:20:06.803  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 10:20:06.810  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:06.811  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:06.812  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:06.812  5842  5842 D HeadsetService: Received start request. Starting profile...
09-28 10:20:06.816  5842  5842 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 10:20:06.816  5842  5842 D HeadsetStateMachine: make
09-28 10:20:06.816  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:06.824  5842  5978 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:20:06.826  5842  5842 D HeadsetStateMachine: max_hf_connections = 1
09-28 10:20:06.827  5842  5842 I bt_bluedroid: get_profile_interface handsfree
09-28 10:20:06.827  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 10:20:06.827  5842  5982 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-28 10:20:06.830  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:06.830  5842  5842 D A2dpService: Received start request. Starting profile...
,09-28 10:20:06.831  5842  5842 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 10:20:06.831  5842  5842 I bt_bluedroid: get_profile_interface avrcp
,09-28 10:20:06.836  5842  5842 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 10:20:06.837  5842  5842 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 10:20:06.837  5842  5842 D A2dpStateMachine: make
,09-28 10:20:06.838  5842  5842 I bt_bluedroid: get_profile_interface a2dp
,09-28 10:20:06.838  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 10:20:06.840  5842  5998 D A2dpStateMachine: Enter Disconnected: -2
,09-28 10:20:06.840  5842  5842 I BluetoothHidServiceJni: classInitNative: succeeds
,09-28 10:20:06.841  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:06.843  5785  5785 D BluetoothInputDevice: Proxy object connected
09-28 10:20:06.843  5842  5842 D HidService: Received start request. Starting profile...
09-28 10:20:06.843  5842  5842 I bt_bluedroid: get_profile_interface hidhost
,09-28 10:20:06.844  5842  5982 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3adb56d
09-28 10:20:06.844  5842  5842 D HidService: setHidService(): set to: null
09-28 10:20:06.844  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 10:20:06.844  5785  5785 D HidProfile: Bluetooth service connected
,09-28 10:20:06.845  5842  5842 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 10:20:06.846  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 10:20:06.846  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:06.847  5842  5842 D HealthService: Received start request. Starting profile...
,09-28 10:20:06.848  5842  5842 I bt_bluedroid: get_profile_interface health
09-28 10:20:06.849  5842  5842 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 10:20:06.849  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:06.851  5785  5785 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:20:06.851  5842  5842 D PanService: Received start request. Starting profile...
,09-28 10:20:06.851  5842  5842 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 10:20:06.851  5842  5842 I bt_bluedroid: get_profile_interface pan
09-28 10:20:06.851  5785  5785 D PanProfile: Bluetooth service connected
09-28 10:20:06.851  5842  5982 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 10:20:06.853  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:06.854  5785  5785 D BluetoothMap: Proxy object connected
,09-28 10:20:06.854  5842  5842 D BluetoothMapService: Received start request. Starting profile...
09-28 10:20:06.854  5842  5842 D BluetoothMapService: start()
09-28 10:20:06.855  5785  5785 D MapProfile: Bluetooth service connected
09-28 10:20:06.855  5785  5785 D BluetoothMap: getConnectedDevices()
09-28 10:20:06.856  5785  5785 D BluetoothMap: Bluetooth is Not enabled
,09-28 10:20:06.857  5842  5842 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 10:20:06.858  5842  5842 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 10:20:06.858  5842  5842 D BluetoothMapAppObserver: createReceiver()
,09-28 10:20:06.860  5842  5842 D BluetoothMapAppObserver: initObservers()
09-28 10:20:06.860  5842  5842 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 10:20:06.866  5842  5842 V SapService: SapBinder()
,09-28 10:20:06.866  5842  5842 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:06.867  5842  5842 D SapService: Received start request. Starting profile...
09-28 10:20:06.867  5842  5842 V SapService: start()
,09-28 10:20:06.870  5842  5842 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:20:06.870  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.870  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:06.870  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:06.870  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:06.870  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:06.871  5842  5996 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:06.871  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 10:20:06.872  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:06.873  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:06.873  5842  5842 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:06.873  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:06.873  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:06.873  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 10:20:06.873  5842  5978 D BluetoothAdapterProperties: ScanMode =  20
,09-28 10:20:06.873  5842  5978 D BluetoothAdapterProperties: State =  11
09-28 10:20:06.874  5842  5978 D BluetoothAdapterProperties: Setting state to 12
09-28 10:20:06.874  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 10:20:06.874  5842  5978 I BluetoothAdapterState: Entering OnState
09-28 10:20:06.874  3856  4067 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:06.875  5842  5982 D BluetoothAdapterProperties: Scan Mode:21
09-28 10:20:06.875  5842  5982 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:20:06.875  5726  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 10:20:06.878  3193  4031 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:06.878  3193  3211 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:06.879  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:06.880  3193  3193 D BluetoothInputDevice: Proxy object connected
09-28 10:20:06.880  3193  3193 D HidProfile: Bluetooth service connected
,09-28 10:20:06.880  5785  5797 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-28 10:20:06.881   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:06.881  3193  4031 D BluetoothMap: onBluetoothStateChange: up=true
09-28 10:20:06.881  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:06.883   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:20:06.883  3193  3193 D BluetoothMap: Proxy object connected
09-28 10:20:06.883  3193  3193 D MapProfile: Bluetooth service connected
09-28 10:20:06.883  3193  3193 D BluetoothMap: getConnectedDevices()
09-28 10:20:06.883  3193  3206 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-28 10:20:06.884   927   927 D BluetoothA2dp: Proxy object connected
,09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:06.885  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:06.887  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:06.887   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:06.887  3193  3193 D BluetoothA2dp: Proxy object connected
09-28 10:20:06.887   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:06.888  3193  4031 D BluetoothPan: onBluetoothStateChange on: true
,09-28 10:20:06.888  5842  5842 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:20:06.889  5842  5842 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 10:20:06.889  3193  3193 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:20:06.890  3193  3193 D PanProfile: Bluetooth service connected
,09-28 10:20:06.890  5842  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:06.891  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:20:06.892  3193  3211 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:20:06.893  5785  5796 D BluetoothMap: onBluetoothStateChange: up=true
09-28 10:20:06.893  5785  5797 D BluetoothPan: onBluetoothStateChange on: true
09-28 10:20:06.894  5785  5796 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:20:06.894  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:06.894  5842  5842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:06.895   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,09-28 10:20:06.897  5726  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 10:20:06.898  5842  5842 D ObexServerSockets: Succeed to create listening sockets 
,09-28 10:20:06.898  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:06.898  5842  5842 D ObexServerSockets0: startAccept()
09-28 10:20:06.898  5842  5842 D ObexServerSockets0: prepareForNewConnect()
09-28 10:20:06.899  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:06.900  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:06.900  5842  5842 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 10:20:06.900  5842  5842 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 10:20:06.900  5842  6004 D ObexServerSockets0: Accepting socket connection...
09-28 10:20:06.900  5842  5842 D BluetoothMapService: onReceive
09-28 10:20:06.900  5842  5842 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-28 10:20:06.901  5842  5842 D BluetoothMapService: STATE_ON
09-28 10:20:06.901  5842  6005 D ObexServerSockets0: Accepting socket connection...
09-28 10:20:06.901  5785  5785 D LocalBluetoothProfileManager: Adding local A2DP profile
09-28 10:20:06.903  5842  6006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:06.905  5842  6006 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-28 10:20:06.905  5842  6006 D BluetoothSdpJni: SDP Create record success - handle: 1
09-28 10:20:06.906  5785  5785 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-28 10:20:06.912  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:20:06.914  5785  5785 D BluetoothA2dp: Proxy object connected
,09-28 10:20:06.919  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:20:06.920  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:20:06.925  3193  3193 D BluetoothPbap: Proxy object connected
,09-28 10:20:06.925  3193  3193 D PbapServerProfile: Bluetooth service connected
09-28 10:20:06.925  5842  5842 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:20:06.925  5842  5842 D ObexServerSockets0: prepareForNewConnect()
09-28 10:20:06.925  5785  5785 D BluetoothPbap: Proxy object connected
09-28 10:20:06.926  5785  5785 D PbapServerProfile: Bluetooth service connected
,09-28 10:20:06.928  5842  6008 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:06.946  5842  6014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:06.947  5842  6014 I BtOppRfcommListener: Accept thread started.
,09-28 10:20:06.976  3193  3986 D BluetoothHeadset: Proxy object connected
,09-28 10:20:06.976  3193  3193 D HeadsetProfile: Bluetooth service connected
09-28 10:20:06.977   927   927 D BluetoothHeadset: Proxy object connected
09-28 10:20:06.977   927   927 D BluetoothHeadset: Proxy object connected
09-28 10:20:06.977   927   927 D BluetoothHeadset: Proxy object connected
09-28 10:20:06.977  3856  3890 D BluetoothHeadset: Proxy object connected
,09-28 10:20:06.978  3193  4031 D BluetoothHeadset: Proxy object connected
09-28 10:20:06.978  3193  3193 D HeadsetProfile: Bluetooth service connected
,09-28 10:20:06.981   927   944 D BluetoothHeadset: Proxy object connected
,09-28 10:20:06.988   927   944 D BluetoothHeadset: Proxy object connected
,09-28 10:20:06.988   927   944 D BluetoothHeadset: Proxy object connected
,09-28 10:20:07.008  5785  5796 D BluetoothHeadset: Proxy object connected
,09-28 10:20:07.009  5785  5785 D HeadsetProfile: Bluetooth service connected
,09-28 10:20:07.250   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:08.250   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 10:20:08.726   927  3041 D ConnectivityService: handlePromptUnvalidated 101
,09-28 10:20:10.892  5842  5978 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 10:20:10.892  5842  5978 D BluetoothAdapterProperties: Setting state to 13
,09-28 10:20:10.892  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-28 10:20:10.894  5842  5978 D BluetoothAdapterProperties: onBluetoothDisable()
09-28 10:20:10.895  5842  5978 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:20:10.899  5842  5842 D BluetoothMapService: onReceive
09-28 10:20:10.899  5842  5842 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 10:20:10.900  5842  5842 D BluetoothMapService: STATE_TURNING_OFF
09-28 10:20:10.900  5842  5842 D BluetoothMapService: MAP Service closeService in
09-28 10:20:10.901  5842  5842 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 10:20:10.901  5842  5842 D ObexServerSockets0: shutdown(block = true)
09-28 10:20:10.902  5842  5982 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:20:10.902  5842  5842 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 10:20:10.902  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 10:20:10.902  5842  6004 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 10:20:10.903  5842  5842 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-28 10:20:10.903  5842  5991 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 10:20:10.904  5842  6005 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 10:20:10.911  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:10.911  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:20:10.912  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 10:20:10.912  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:20:10.912  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:10.913  5842  5842 I BtOppRfcommListener: stopping Accept Thread
,09-28 10:20:10.914  5842  6014 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 10:20:10.914  5842  6014 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 10:20:10.917  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:10.918  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:20:10.919  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:20:10.919  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:10.923  5842  5842 D HeadsetService: Received stop request...Stopping profile...
09-28 10:20:10.924  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:10.924  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:10.925  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:20:10.925  5726  5726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:20:10.925  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:10.927  3193  4031 D BluetoothHeadset: Proxy object disconnected
09-28 10:20:10.928  5785  5797 D BluetoothHeadset: Proxy object disconnected
09-28 10:20:10.928  3193  3193 D HeadsetProfile: Bluetooth service disconnected
09-28 10:20:10.928   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 10:20:10.928   927   927 D BluetoothHeadset: Proxy object disconnected
,09-28 10:20:10.928   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 10:20:10.929  3856  3892 D BluetoothHeadset: Proxy object disconnected
09-28 10:20:10.929  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:10.930  5842  5842 D A2dpService: Received stop request...Stopping profile...
09-28 10:20:10.930  5785  5785 D HeadsetProfile: Bluetooth service disconnected
09-28 10:20:10.930  5842  5998 D A2dpStateMachine: Exit Disconnected: -1
09-28 10:20:10.932  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:10.933  5785  5785 D BluetoothA2dp: Proxy object disconnected
09-28 10:20:10.933   927   927 D BluetoothA2dp: Proxy object disconnected
09-28 10:20:10.933  3193  3193 D BluetoothA2dp: Proxy object disconnected
09-28 10:20:10.934  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:10.935  5842  5842 D HidService: Received stop request...Stopping profile...
,09-28 10:20:10.935  5842  5842 D HidService: Stopping Bluetooth HidService
09-28 10:20:10.938  3193  3193 D BluetoothInputDevice: Proxy object disconnected
09-28 10:20:10.938  3193  3193 D HidProfile: Bluetooth service disconnected
09-28 10:20:10.938  5842  5842 D HealthService: Received stop request...Stopping profile...
09-28 10:20:10.938  5785  5785 D BluetoothInputDevice: Proxy object disconnected
09-28 10:20:10.938  5785  5785 D HidProfile: Bluetooth service disconnected
,09-28 10:20:10.942  5842  5842 D PanService: Received stop request...Stopping profile...
,09-28 10:20:10.943  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:20:10.943  3193  3193 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 10:20:10.943  3193  3193 D PanProfile: Bluetooth service disconnected
09-28 10:20:10.946  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.946  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:10.946  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.946  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:10.946  5842  5842 D BluetoothMapService: Received stop request...Stopping profile...
09-28 10:20:10.946  5842  5842 D BluetoothMapService: stop()
,09-28 10:20:10.947  5842  5842 D BluetoothMapAppObserver: deinitObservers()
09-28 10:20:10.947  5842  5842 D BluetoothMapAppObserver: removeReceiver()
09-28 10:20:10.948  5785  5785 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 10:20:10.948  3193  3193 D BluetoothMap: Proxy object disconnected
09-28 10:20:10.948  3193  3193 D MapProfile: Bluetooth service disconnected
09-28 10:20:10.948  5785  5785 D PanProfile: Bluetooth service disconnected
09-28 10:20:10.948  5785  5785 D BluetoothMap: Proxy object disconnected
09-28 10:20:10.949  5785  5785 D MapProfile: Bluetooth service disconnected
09-28 10:20:10.949  5842  5842 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 10:20:10.949  5842  5842 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 10:20:10.950  5842  5989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:20:10.950  5842  5989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 10:20:10.950  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.950  5842  5989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:20:10.950  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:10.950  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.950  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:10.950  5842  5842 D SapService: Received stop request...Stopping profile...
09-28 10:20:10.950  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 10:20:10.950  5842  5842 V SapService: stop()
09-28 10:20:10.951  5842  5982 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-28 10:20:10.953  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.953  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:10.953  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.953  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 10:20:10.953  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:10.953  5842  5989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:20:10.953  5842  5989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:20:10.953  5842  5842 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 10:20:10.953  5842  5989 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:20:10.953  5842  5989 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:20:10.953  5842  5989 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:20:10.953  5842  5842 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 10:20:10.953  5842  5989 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:20:10.953  5842  5982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:20:10.953  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.953  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:10.954  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.954  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:10.954  5842  5842 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 10:20:10.954  5842  5842 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 10:20:10.955  5785  5785 D BluetoothPbap: Proxy object disconnected
09-28 10:20:10.956  5785  5785 D PbapServerProfile: Bluetooth service disconnected
09-28 10:20:10.956  3193  3193 D BluetoothPbap: Proxy object disconnected
09-28 10:20:10.956  3193  3193 D PbapServerProfile: Bluetooth service disconnected
09-28 10:20:10.956  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.956  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:10.956  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.956  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:10.956  5842  5842 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 10:20:10.956  5842  5842 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 10:20:10.957  5842  5982 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 10:20:10.957  5842  5842 D BluetoothMapService: MAP Service closeService in
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isTurningOn()=false
,09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:10.958  5842  5842 D BluetoothMapService: cleanup()
09-28 10:20:10.958  5842  5842 D BluetoothMapService: MAP Service closeService in
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isTurningOff()=true
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:10.958  5842  5842 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:10.959  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 10:20:10.959  5842  5978 D BluetoothAdapterProperties: Setting state to 15
,09-28 10:20:10.959  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-28 10:20:10.959  5842  5978 I BluetoothAdapterState: Entering BleOnState
,09-28 10:20:10.960  5785  5797 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:20:10.960  3856  4067 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:20:10.961  3193  4031 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:20:10.961  3193  3206 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 10:20:10.964  5785  5796 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 10:20:10.965   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:20:10.965  3193  3211 D BluetoothMap: onBluetoothStateChange: up=false
09-28 10:20:10.965   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:20:10.965  3193  3986 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:20:10.966   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:20:10.966   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:20:10.966  3193  4031 D BluetoothPan: onBluetoothStateChange on: false
09-28 10:20:10.967  3193  3206 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 10:20:10.968  5785  5797 D BluetoothMap: onBluetoothStateChange: up=false
09-28 10:20:10.969  5785  5796 D BluetoothPan: onBluetoothStateChange on: false
09-28 10:20:10.969  5785  5797 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:20:10.970  5785  5796 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 10:20:10.971  5842  5978 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 10:20:10.971  5842  5978 D BluetoothAdapterProperties: Setting state to 16
09-28 10:20:10.971  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-28 10:20:10.971  5842  5978 D BluetoothAdapterProperties: onBleDisable
09-28 10:20:10.972  5842  5978 I BluetoothAdapterState: Entering PendingCommandState
09-28 10:20:10.972  5842  5979 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 10:20:10.974  5842  5989 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 10:20:10.974  5842  5989 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:20:10.974  5842  5982 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:20:10.975  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:10.975  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 10:20:10.977  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:10.979  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:10.981  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:10.982  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:10.984  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:10.985  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:20:10.986  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:20:11.181  5842  5982 I bt_hci  : shut_down
,09-28 10:20:11.186  5842  5986 D bt_hwcfg: hw_epilog_process
,09-28 10:20:11.187  5842  5986 I bt_vendor: low_power_mode_cb
,09-28 10:20:11.189  5842  5986 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 10:20:11.189  5842  5986 I bt_vendor: epilog_cb
09-28 10:20:11.189  5842  5986 I bt_hci  : epilog_finished_callback
,09-28 10:20:11.191  5842  5982 I bt_hci_h4: hal_close
,09-28 10:20:11.191  5842  5982 I bt_userial_vendor: device fd = 54 close
,09-28 10:20:11.303  5842  5979 D bt_stack_manager: event_shut_down_stack finished.
,09-28 10:20:11.303  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-28 10:20:11.305  5842  5978 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-28 10:20:11.306  5842  5842 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 10:20:11.306  5842  5842 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 10:20:11.306  5842  5842 D BtGatt.GattService: stop()
09-28 10:20:11.306  5842  5842 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 10:20:11.308  5842  5842 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:11.308  5842  5842 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:11.308  5842  5842 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 10:20:11.308  5842  5842 V BluetoothAdapterState: isBleTurningOff()=true
09-28 10:20:11.308  5842  5978 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 10:20:11.309  5842  5978 D BluetoothAdapterProperties: Setting state to 10
09-28 10:20:11.309  5842  5978 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 10:20:11.309  5842  5978 I BluetoothAdapterState: Entering OffState
,09-28 10:20:11.310   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 10:20:11.317  5842  5842 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 10:20:11.317  5842  5842 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 10:20:11.317  5842  5842 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 10:20:11.319  5842  5979 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 10:20:11.324  5842  5842 I art     : System.exit called, status: 0
09-28 10:20:11.324  5842  5842 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 10:20:11.346   927  3864 I ActivityManager: Process com.android.bluetooth (pid 5842) has died
,09-28 10:20:15.892  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:15.893  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:15.898  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:20:15.898  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e85992d removed from the list
,09-28 10:20:15.898  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 10:20:15.899  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:20:15.899  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:15.902  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:15.903  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f46fbf3 added. We now have 4 listener(s)
09-28 10:20:15.904  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:15.905  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:15.905  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f46fbf3 removed from the list
09-28 10:20:15.905  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:15.905  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:15.906  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:15.907  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:15.908  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ef80b0 added. We now have 4 listener(s)
09-28 10:20:15.908  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:20:20.918  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:20.949   927   944 I ActivityManager: Start proc 6022:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 10:20:21.023  6022  6022 D AdapterServiceConfig: Adding HeadsetService
,09-28 10:20:21.023  6022  6022 D AdapterServiceConfig: Adding A2dpService
,09-28 10:20:21.024  6022  6022 D AdapterServiceConfig: Adding HidService
09-28 10:20:21.024  6022  6022 D AdapterServiceConfig: Adding HealthService
09-28 10:20:21.024  6022  6022 D AdapterServiceConfig: Adding PanService
09-28 10:20:21.024  6022  6022 D AdapterServiceConfig: Adding GattService
09-28 10:20:21.024  6022  6022 D AdapterServiceConfig: Adding BluetoothMapService
09-28 10:20:21.025  6022  6022 D AdapterServiceConfig: Adding SapService
,09-28 10:20:21.035   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f9a01f:true
,09-28 10:20:21.035  6022  6022 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 10:20:21.039  6022  6022 I bt_bluedroid: init
,09-28 10:20:21.039  6022  6034 I BluetoothAdapterState: Entering OffState
,09-28 10:20:21.042  6022  6035 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-28 10:20:21.042  6022  6035 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 10:20:21.042  6022  6035 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 10:20:21.042  6022  6035 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-28 10:20:21.043  6022  6022 I bt_bluedroid: get_profile_interface socket
,09-28 10:20:21.044  6022  6038 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:20:21.045  6022  6022 I bt_bluedroid: get_profile_interface sdp
09-28 10:20:21.046  6022  6038 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:20:21.053  6022  6033 I bt_bluedroid: config_hci_snoop_log
,09-28 10:20:21.054   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 10:20:21.061  6022  6034 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 10:20:21.061  6022  6034 D BluetoothAdapterProperties: Setting state to 14
09-28 10:20:21.061  6022  6034 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-28 10:20:21.062  6022  6034 D BluetoothBondStateMachine: make
,09-28 10:20:21.064  6022  6039 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 10:20:21.067  6022  6034 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:20:21.069  6022  6022 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 10:20:21.071  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:21.072  6022  6022 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:20:21.073  6022  6022 D BtGatt.GattService: Received start request. Starting profile...
09-28 10:20:21.073  6022  6022 D BtGatt.GattService: start()
09-28 10:20:21.073  6022  6022 I bt_bluedroid: get_profile_interface gatt
09-28 10:20:21.074  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:21.074  6022  6022 D BtGatt.AdvertiseManager: advertise manager created
,09-28 10:20:21.081  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:21.081  6022  6022 V BluetoothAdapterState: isTurningOn()=false
09-28 10:20:21.081  6022  6022 V BluetoothAdapterState: isBleTurningOn()=true
09-28 10:20:21.081  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:21.081  6022  6034 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 10:20:21.083  6022  6034 I bt_bluedroid: bt_bluedroid
,09-28 10:20:21.083  6022  6035 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 10:20:21.084  6022  6035 I bt_hci  : start_up
,09-28 10:20:21.089  6022  6035 I bt_vendor: alloc value 0xf3b88871
,09-28 10:20:21.089  6022  6035 I bt_vendor: init
09-28 10:20:21.089  6022  6035 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 10:20:21.089  6022  6035 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 10:20:21.201  6022  6035 D bt_hci  : start_up starting async portion
,09-28 10:20:21.202  6022  6042 I bt_hci  : event_finish_startup
09-28 10:20:21.202  6022  6042 I bt_hci_h4: hal_open
,09-28 10:20:21.202  6022  6042 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-28 10:20:21.202  6043  6043 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-28 10:20:21.205  6022  6042 I bt_userial_vendor: device fd = 54 open
,09-28 10:20:21.222  6022  6042 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:20:21.226  6022  6042 D bt_hwcfg: Chipset BCM4358A3
,09-28 10:20:21.227  6022  6042 D bt_hwcfg: Target name = [BCM4358A3]
09-28 10:20:21.227  6022  6042 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 10:20:21.745  6022  6042 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-28 10:20:21.745  6022  6042 D bt_hwcfg: Settlement delay -- 100 ms
,09-28 10:20:21.745  6022  6042 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 10:20:21.880  6022  6042 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:20:21.880  6022  6042 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-28 10:20:21.882  6022  6042 I bt_hwcfg: vendor lib fwcfg completed
,09-28 10:20:21.883  6022  6042 I bt_vendor: firmware callback
,09-28 10:20:21.883  6022  6042 I bt_hci  : firmware_config_callback
,09-28 10:20:21.893  6022  6045 I bt_btu  : btu_task pending for preload complete event
,09-28 10:20:21.893  6022  6045 I bt_btu_task: Bluetooth chip preload is complete
09-28 10:20:21.893  6022  6045 I bt_btu  : btu_task received preload complete event
,09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_A2D
,09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_BNEP
09-28 10:20:21.902  6022  6045 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_PAN
,09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 10:20:21.903  6022  6045 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 10:20:22.000  6022  6045 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b06549
,09-28 10:20:22.000  6022  6045 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b06549 
,09-28 10:20:22.036  6022  6038 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 10:20:22.039  6022  6038 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:20:22.039  6022  6038 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:20:22.041  6022  6038 D BluetoothAdapterProperties: Name is: Nexus 6P
09-28 10:20:22.044  6022  6038 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:20:22.045  6022  6038 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:20:22.045  6022  6038 D bt_hci  : do_postload posting postload work item
09-28 10:20:22.045  6022  6042 I bt_hci  : event_postload
09-28 10:20:22.045  6022  6042 I bt_vendor: sco_config_cb
09-28 10:20:22.045  6022  6042 I bt_hci  : sco_config_callback postload finished.
09-28 10:20:22.048  6022  6038 D bt_bte_conf: Device ID record 1 : primary
09-28 10:20:22.048  6022  6038 D bt_bte_conf:   vendorId            = 000f
09-28 10:20:22.048  6022  6038 D bt_bte_conf:   vendorIdSource      = 0001
09-28 10:20:22.048  6022  6038 D bt_bte_conf:   product             = 1200
09-28 10:20:22.048  6022  6038 D bt_bte_conf:   version             = 1436
09-28 10:20:22.048  6022  6038 D bt_bte_conf:   clientExecutableURL = 
,09-28 10:20:22.048  6022  6038 D bt_bte_conf:   serviceDescription  = 
09-28 10:20:22.048  6022  6038 D bt_bte_conf:   documentationURL    = 
09-28 10:20:22.048  6022  6038 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 10:20:22.049  6022  6035 D bt_stack_manager: event_start_up_stack finished
09-28 10:20:22.050  6022  6034 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 10:20:22.050  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:22.050  6022  6034 D BluetoothAdapterProperties: Setting state to 15
09-28 10:20:22.050  6022  6034 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 10:20:22.051  6022  6034 I BluetoothAdapterState: Entering BleOnState
,09-28 10:20:22.054  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:22.054  6022  6042 I bt_vendor: low_power_mode_cb
09-28 10:20:22.055  6022  6034 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 10:20:22.055  6022  6034 D BluetoothAdapterProperties: Setting state to 11
09-28 10:20:22.055  6022  6034 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 10:20:22.060  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:22.062  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:22.064  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:22.065  6022  6022 D HeadsetService: Received start request. Starting profile...
09-28 10:20:22.067  6022  6022 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 10:20:22.067  6022  6022 D HeadsetStateMachine: make
,09-28 10:20:22.077  6022  6034 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:20:22.078  6022  6022 D HeadsetStateMachine: max_hf_connections = 1
09-28 10:20:22.079  6022  6022 I bt_bluedroid: get_profile_interface handsfree
09-28 10:20:22.079  6022  6038 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 10:20:22.079  6022  6038 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-28 10:20:22.081  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:22.082  6022  6022 D A2dpService: Received start request. Starting profile...
09-28 10:20:22.083  6022  6022 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 10:20:22.083  6022  6022 I bt_bluedroid: get_profile_interface avrcp
,09-28 10:20:22.090  6022  6022 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-28 10:20:22.090  6022  6022 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 10:20:22.090  6022  6022 D A2dpStateMachine: make
,09-28 10:20:22.092  6022  6022 I bt_bluedroid: get_profile_interface a2dp
,09-28 10:20:22.093  6022  6038 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-28 10:20:22.094  6022  6053 D A2dpStateMachine: Enter Disconnected: -2
,09-28 10:20:22.094  6022  6022 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 10:20:22.095  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:22.096  6022  6022 D HidService: Received start request. Starting profile...
09-28 10:20:22.096  6022  6022 I bt_bluedroid: get_profile_interface hidhost
09-28 10:20:22.096  6022  6038 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ae756d
09-28 10:20:22.096  6022  6022 D HidService: setHidService(): set to: null
,09-28 10:20:22.096  6022  6038 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 10:20:22.097  6022  6022 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-28 10:20:22.098  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:22.098  6022  6022 D HealthService: Received start request. Starting profile...
09-28 10:20:22.100  6022  6022 I bt_bluedroid: get_profile_interface health
,09-28 10:20:22.101  6022  6022 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 10:20:22.102  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 10:20:22.103  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:22.104  6022  6022 D PanService: Received start request. Starting profile...
09-28 10:20:22.104  6022  6022 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 10:20:22.104  6022  6022 I bt_bluedroid: get_profile_interface pan
09-28 10:20:22.106  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:22.106  6022  6038 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 10:20:22.107  6022  6022 D BluetoothMapService: Received start request. Starting profile...
09-28 10:20:22.107  6022  6022 D BluetoothMapService: start()
09-28 10:20:22.109  6022  6022 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 10:20:22.110  6022  6022 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 10:20:22.110  6022  6022 D BluetoothMapAppObserver: createReceiver()
,09-28 10:20:22.112  6022  6022 D BluetoothMapAppObserver: initObservers()
09-28 10:20:22.112  6022  6022 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 10:20:22.120  6022  6022 V SapService: SapBinder()
09-28 10:20:22.120  6022  6022 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
,09-28 10:20:22.120  6022  6022 D SapService: Received start request. Starting profile...
09-28 10:20:22.120  6022  6022 V SapService: start()
,09-28 10:20:22.123  6022  6022 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:20:22.123  6022  6022 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:22.124  6022  6051 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 10:20:22.124  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isTurningOn()=true
,09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.125  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.126  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:22.127  6022  6022 V BluetoothAdapterState: isTurningOff()=false
09-28 10:20:22.127  6022  6022 V BluetoothAdapterState: isTurningOn()=true
09-28 10:20:22.127  6022  6022 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:20:22.127  6022  6022 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:20:22.128  6022  6034 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 10:20:22.128  6022  6034 D BluetoothAdapterProperties: ScanMode =  20
09-28 10:20:22.128  6022  6034 D BluetoothAdapterProperties: State =  11
09-28 10:20:22.128  6022  6034 D BluetoothAdapterProperties: Setting state to 12
09-28 10:20:22.128  6022  6034 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-28 10:20:22.129  6022  6034 I BluetoothAdapterState: Entering OnState
,09-28 10:20:22.129  5785  5796 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:22.130  6022  6038 D BluetoothAdapterProperties: Scan Mode:21
09-28 10:20:22.130  3856  3890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:22.130  6022  6038 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:20:22.130  5726  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-28 10:20:22.131  3193  3211 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:22.131  3193  4031 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 10:20:22.133  5785  5797 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:22.133  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:22.134  3193  3193 D BluetoothInputDevice: Proxy object connected
09-28 10:20:22.134  3193  3193 D HidProfile: Bluetooth service connected
09-28 10:20:22.135   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:22.135  3193  3986 D BluetoothMap: onBluetoothStateChange: up=true
09-28 10:20:22.136  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:22.136   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:20:22.137  5785  5785 D BluetoothInputDevice: Proxy object connected
09-28 10:20:22.137  5785  5785 D HidProfile: Bluetooth service connected
,09-28 10:20:22.137  3193  3193 D BluetoothMap: Proxy object connected
09-28 10:20:22.137  3193  3193 D MapProfile: Bluetooth service connected
09-28 10:20:22.137  3193  3193 D BluetoothMap: getConnectedDevices()
09-28 10:20:22.138  3193  3206 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:22.139  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:22.139  6022  6022 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:20:22.139   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:22.140   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:20:22.140  6022  6022 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 10:20:22.140  3193  3986 D BluetoothPan: onBluetoothStateChange on: true
09-28 10:20:22.141  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:20:22.142  3193  3211 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 10:20:22.142  6022  6022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:22.144  5785  5796 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 10:20:22.145  6022  6022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:20:22.145  5785  5785 D BluetoothMap: Proxy object connected
09-28 10:20:22.145  5785  5785 D MapProfile: Bluetooth service connected
09-28 10:20:22.145  5785  5785 D BluetoothMap: getConnectedDevices()
09-28 10:20:22.147  5785  6058 D BluetoothPan: onBluetoothStateChange on: true
09-28 10:20:22.147  6022  6022 D ObexServerSockets: Succeed to create listening sockets 
09-28 10:20:22.147  6022  6022 D ObexServerSockets0: startAccept()
,09-28 10:20:22.147  6022  6022 D ObexServerSockets0: prepareForNewConnect()
09-28 10:20:22.148  5785  5797 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:20:22.149  6022  6022 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 10:20:22.149  6022  6022 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 10:20:22.149  5785  5796 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:20:22.150  6022  6061 D ObexServerSockets0: Accepting socket connection...
09-28 10:20:22.150   927   927 D BluetoothA2dp: Proxy object connected
09-28 10:20:22.150  3193  3193 D BluetoothA2dp: Proxy object connected
09-28 10:20:22.152  5785  5785 D BluetoothA2dp: Proxy object connected
09-28 10:20:22.152  6022  6062 D ObexServerSockets0: Accepting socket connection...
09-28 10:20:22.153  5726  5726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-28 10:20:22.153   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 10:20:22.153  6022  6022 D BluetoothMapService: onReceive
,09-28 10:20:22.153  6022  6022 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 10:20:22.153  6022  6022 D BluetoothMapService: STATE_ON
09-28 10:20:22.154  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:22.155  6022  6063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:20:22.156  3193  3193 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:20:22.156  5785  5785 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:20:22.156  5785  5785 D PanProfile: Bluetooth service connected
09-28 10:20:22.156  3193  3193 D PanProfile: Bluetooth service connected
09-28 10:20:22.157  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:22.159  6022  6063 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 10:20:22.159  6022  6063 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 10:20:22.161  5785  5785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:20:22.167  5785  5785 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:20:22.167  3644  3644 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:20:22.175  3193  3193 D BluetoothPbap: Proxy object connected
,09-28 10:20:22.175  3193  3193 D PbapServerProfile: Bluetooth service connected
,09-28 10:20:22.177  5785  5785 D BluetoothPbap: Proxy object connected
,09-28 10:20:22.177  5785  5785 D PbapServerProfile: Bluetooth service connected
,09-28 10:20:22.180  6022  6022 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:20:22.180  6022  6022 D ObexServerSockets0: prepareForNewConnect()
,09-28 10:20:22.186  6022  6069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:22.201  6022  6073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:20:22.202  6022  6073 I BtOppRfcommListener: Accept thread started.
,09-28 10:20:22.233  3193  4031 D BluetoothHeadset: Proxy object connected
,09-28 10:20:22.233  3193  3193 D HeadsetProfile: Bluetooth service connected
09-28 10:20:22.233  5785  5796 D BluetoothHeadset: Proxy object connected
09-28 10:20:22.233   927   927 D BluetoothHeadset: Proxy object connected
09-28 10:20:22.233   927   927 D BluetoothHeadset: Proxy object connected
09-28 10:20:22.233   927   927 D BluetoothHeadset: Proxy object connected
,09-28 10:20:22.234  3856  3892 D BluetoothHeadset: Proxy object connected
,09-28 10:20:22.235   927   944 D BluetoothHeadset: Proxy object connected
09-28 10:20:22.235  5785  5785 D HeadsetProfile: Bluetooth service connected
,09-28 10:20:22.240   927   944 D BluetoothHeadset: Proxy object connected
09-28 10:20:22.240   927   944 D BluetoothHeadset: Proxy object connected
,09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:25.935  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:20:25.941  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:20:25.941  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:25.942  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ef80b0 removed from the list
,09-28 10:20:25.942  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:25.942  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:20:25.942  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:25.944  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:20:25.944  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14f9b29 added. We now have 4 listener(s)
09-28 10:20:25.944  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:20:25.948   927  3835 D WifiService: setWifiEnabled: false pid=5726, uid=10077
09-28 10:20:25.948   927  3835 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:20:28.252   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:29.253   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:30.255   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:30.960  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:30.961   927  3864 D WifiService: setWifiEnabled: true pid=5726, uid=10077
,09-28 10:20:30.961   927  3864 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:20:30.969   506   922 D SoftapController: Softap fwReload - Ok
,09-28 10:20:30.975   506   922 D CommandListener: Setting iface cfg
,09-28 10:20:30.976   506   922 D CommandListener: Trying to bring down wlan0
09-28 10:20:30.977   506   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:20:30.985   927  3039 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 10:20:31.257   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:31.645   927  3039 D wifi    : set interface wlan0 flags (UP)
,09-28 10:20:31.645   927  3039 I WifiHAL : Initializing wifi
,09-28 10:20:31.645   927  3039 I WifiHAL : Creating socket
,09-28 10:20:31.655   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 10:20:31.658   927  3039 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-28 10:20:31.658   927  3039 D wifi    : Did set static halHandle = 0x7f6f556680
,09-28 10:20:31.658   927  3039 D wifi    : halHandle = 0x7f6f556680, mVM = 0x7f8bb8d140, mCls = 0x20150a
09-28 10:20:31.658   927  3039 D wifi    : array field set
09-28 10:20:31.659   927  3039 I WifiNative-HAL: interface[0] = wlan0
09-28 10:20:31.662   927  6080 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547328714368
09-28 10:20:31.662   927  6080 D wifi    : waitForHalEvents called, vm = 0x7f8bb8d140, obj = 0x20150a, env = 0x7f6ffbcc00
,09-28 10:20:31.710  6081  6081 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 10:20:31.731  6081  6081 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:20:31.762   927  3039 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 10:20:31.767  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:31.769  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:31.772  6081  6081 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:20:31.772  6081  6081 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 10:20:31.789   927  3039 D WifiConfigStore: Loading config and enabling all networks 
,09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:31.791  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:31.793  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:20:31.796  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:20:31.797  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:20:31.802   927  3039 D WifiConfigStore: loaded 0 passpoint configs
,09-28 10:20:31.803   927  3039 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 10:20:31.803   927  3039 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 10:20:31.804   927  3039 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 10:20:31.805   927  3039 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-28 10:20:31.806   927  3039 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 10:20:31.806   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-28 10:20:31.806   927  3039 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 10:20:31.809   927  3039 D WifiNative-HAL: Setting external_sim to 1
09-28 10:20:31.809  4481  4481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:20:31.810   927  3039 D wifi    : setting dfs flag to true, 0x7f6d283d00
,09-28 10:20:31.810   927  3039 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 10:20:31.810   927  3039 D wifi    : setting scan oui 0x7f6d283d00
09-28 10:20:31.810   927  3039 D WifiHAL : Sending mac address OUI
,09-28 10:20:31.814   927  3039 E native  : do suspend false
,09-28 10:20:31.823   927  3039 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-28 10:20:31.823   927   927 D RttService: SCAN_AVAILABLE : 3
09-28 10:20:31.824   927  3148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 10:20:31.824   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-28 10:20:31.825   506   922 D CommandListener: Setting iface cfg
,09-28 10:20:31.830   927  3038 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-28 10:20:31.830   927  3038 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 10:20:31.840   927  3038 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 10:20:31.840   927  3038 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 10:20:31.868   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302994 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=39 mControllerEnergyUsed=148 }
,09-28 10:20:32.260   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:20:33.261   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 10:20:34.992  6081  6081 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:20:34.997  6081  6081 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:20:35.001  6081  6081 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:20:35.006  6081  6081 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:20:35.062   927  3039 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-28 10:20:35.064   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-28 10:20:35.064   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:20:35.074   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 10:20:35.107   927  3039 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 10:20:35.109  6081  6081 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 10:20:35.534  6081  6081 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 10:20:35.570  6081  6081 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 10:20:35.572  6081  6081 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 10:20:35.580   927  3039 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:20:35.581   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 10:20:35.581   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 10:20:35.599   927  3039 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:20:35.615   506   922 D CommandListener: Setting iface cfg
,09-28 10:20:35.620   927  3039 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 10:20:35.626   927  6095 D DhcpClient: Receive thread started
,09-28 10:20:35.631   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 10:20:35.631   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 10:20:35.631   927  3041 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 10:20:35.712   927  3039 E native  : do suspend false
,09-28 10:20:35.727   927  6094 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 10:20:35.739   927  6095 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-28 10:20:35.740   927  6094 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-28 10:20:35.743   927  6094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 10:20:35.757   927  6095 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 10:20:35.757   927  6094 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 10:20:35.761   506   922 D CommandListener: Setting iface cfg
09-28 10:20:35.765   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 10:20:35.772   927  6094 D DhcpClient: Scheduling renewal in 86399s
,09-28 10:20:35.782   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 10:20:35.783   927  3039 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 10:20:35.784   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 10:20:35.786   927  3041 D ConnectivityService: Adding iface wlan0 to network 102
,09-28 10:20:35.794   927  3039 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 10:20:35.837   927  3041 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-28 10:20:35.837   927  3041 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-28 10:20:35.839   927  3041 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-28 10:20:35.842   927  3041 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-28 10:20:35.844   927  3041 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 10:20:35.850   927  3041 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:20:35.855   927  3041 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-28 10:20:35.855   927  3041 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 10:20:35.855   927  3041 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 10:20:35.855   927  3039 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 10:20:35.855   927  3041 D ConnectivityService:    accepting network in place of null
09-28 10:20:35.855   927  3039 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:20:35.856   927  3041 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:20:35.867   927  6093 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306994, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-28 10:20:35.880   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:20:35.902   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:20:35.905   927  3041 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-28 10:20:35.905   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 10:20:35.905  3825  3970 W QCNEJ   : |CORE| network available: 102
,09-28 10:20:35.907   927  3041 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-28 10:20:35.907  3825  3970 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 10:20:35.908  3825  3970 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-28 10:20:35.909  3825  3970 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 10:20:35.909   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:35.914  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:20:35.917  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:20:35.919  5107  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 10:20:35.919  5107  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:20:35.919  5107  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 10:20:35.919  5107  5120 E SarControlService: no key has been found,reset the power
09-28 10:20:35.919  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:20:35.919  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:20:35.919  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 10:20:35.920  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 10:20:35.920  5133  5133 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:35.923  5726  5726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:20:35.925  5726  5726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:35.927  5107  5145 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:20:35.927  5107  5145 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:20:35.927  5107  5145 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 10:20:35.929  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:20:35.930  4073  4073 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 10:20:35.933  5133  5133 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 10:20:35.934  4073  4073 D SystemUpdateService: onCreate
09-28 10:20:35.936  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000f003000000000000ffffffff]
09-28 10:20:35.936  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:20:35.936  5133  5147 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-28 10:20:35.936  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:20:35.936  5107  5118 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 10:20:35.937  5133  5147 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@274d525 HexData = [00000000f103000000000000ffffffff]
09-28 10:20:35.937  5133  5147 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:20:35.937  5133  5147 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 10:20:35.938  5133  5133 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:20:35.938  5107  5117 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 10:20:35.938   927  6092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
09-28 10:20:35.940  4073  4073 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 10:20:35.951  4073  4073 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-28 10:20:35.955  4073  5469 I iu.UploadsManager: num queued entries: 0
09-28 10:20:35.956  4073  5469 I iu.UploadsManager: num updated entries: 0
09-28 10:20:35.956  4073  5469 I iu.SyncManager: NEXT; no task
09-28 10:20:35.958  4073  6107 I SystemUpdateService: active receiver: enabled
,09-28 10:20:35.961  4073  4073 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-28 10:20:35.962  4073  4073 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-28 10:20:35.963  5856  5856 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-28 10:20:35.966  5856  5856 D SprintDMHelper: simOperator: 
09-28 10:20:35.966  5856  5856 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:35.973  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:20:35.975  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:35.975  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:35.976  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14f9b29 removed from the list
09-28 10:20:35.976  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:35.976  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:35.976  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:35.979  5726  6113 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-28 10:20:35.979  5726  6113 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-28 10:20:35.985  4073  6107 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-28 10:20:36.001  4073  6107 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-28 10:20:36.002  4073  6107 I SystemUpdateService: now status is 0 (complete)
09-28 10:20:36.002  4073  6107 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:20:36.002  4073  6107 I SystemUpdateService: file has been verified
09-28 10:20:36.002  4073  6107 I SystemUpdateService: OTA package size = 21989297
,09-28 10:20:36.005   927  6092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 14:20:35 GMT], X-Android-Received-Millis=[1475072436004], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475072435969]}
09-28 10:20:36.005   927  3041 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 10:20:36.005   927  3041 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-28 10:20:36.005   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 10:20:36.006   927  3041 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 10:20:36.007  4073  6107 I SystemUpdateService: showing system update notification
09-28 10:20:36.018  4073  4073 D SystemUpdateService: onDestroy
,09-28 10:20:36.103  4481  6111 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 10:20:36.964   927  3039 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-28 10:20:36.977   927  3041 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:20:36.983  3825  3970 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-28 10:20:36.984  3825  3970 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 10:20:38.654   927  3041 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:20:38.989  5726  6113 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-28 10:20:38.990  5726  6113 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:20:38.991  5726  6120 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-28 10:20:38.991  5726  6113 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:20:38.991  5726  6120 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:20:38.991  5726  6120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:20:38.992  5726  6113 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:20:38.992  5726  6120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:20:38.995  5726  6122 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:38.995  5726  6122 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:38.996  5726  6120 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 10:20:38.996  5726  6113 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 10:20:38.999  5726  6123 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:38.999  5726  6123 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:39.000  5726  6125 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:39.000  5726  6125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:39.001  5726  6124 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:39.001  5726  6124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:39.002  5726  6125 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:39.002  5726  6125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:39.002  5726  6125 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:20:39.002  5726  6125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:39.002  5726  6125 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:20:39.002  5726  6125 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 10:20:39.003  5726  6122 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 153, thread name: OutgoingSocketThread/Sender): Socket closed
09-28 10:20:39.003  5726  6125 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 10:20:39.003  5726  6124 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 10:20:39.004  5726  6125 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-28 10:20:39.004  5726  6124 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-28 10:20:39.004  5726  6125 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 10:20:39.004  5726  6122 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:39.004  5726  6122 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 10:20:39.004  5726  6125 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 10:20:39.004  5726  6124 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 10:20:39.004  5726  6122 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 10:20:39.004  5726  6122 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 10:20:39.004  5726  6125 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:39.004  5726  6125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 10:20:39.004  5726  6124 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:39.004  5726  6124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 10:20:39.004  5726  6122 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:39.004  5726  6122 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 10:20:39.008  5726  6123 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 154, thread name: IncomingSocketThread/Sender): Socket closed
09-28 10:20:39.008  5726  6123 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:39.008  5726  6123 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 10:20:39.009  5726  6123 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 10:20:39.009  5726  6123 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 10:20:39.009  5726  6123 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:39.009  5726  6123 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-28 10:20:41.990  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 10:20:41.992  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 10:20:41.998  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@85f80d9 Bundle[{}]
09-28 10:20:41.999  5726  5773 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 10:20:42.000  5726  5773 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-28 10:20:42.001  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-28 10:20:42.002  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-28 10:20:42.002  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-28 10:20:42.004  5726  5773 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-28 10:20:42.009  5726  5773 I System.out: Running OutgoingSocketThread
,09-28 10:20:42.012  5726  6126 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-28 10:20:42.012  5726  6126 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 10:20:43.860   927  3041 D ConnectivityService: handlePromptUnvalidated 102
,09-28 10:20:45.022  5726  6126 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-28 10:20:45.023  5726  6126 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:20:45.023  5726  6126 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:20:45.024  5726  6126 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:20:45.026  5726  6127 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-28 10:20:45.026  5726  6127 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:20:45.026  5726  6126 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 10:20:45.027  5726  6129 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:45.027  5726  6129 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:45.028  5726  6127 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:20:45.031  5726  6127 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:20:45.032  5726  6131 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:45.032  5726  6131 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:45.033  5726  6130 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:45.033  5726  6130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:45.034  5726  6127 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 10:20:45.035  5726  6130 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:45.035  5726  6130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:45.035  5726  6130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:20:45.035  5726  6130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:45.035  5726  6130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:20:45.035  5726  6130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 10:20:45.035  5726  6132 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:45.035  5726  6132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:45.036  5726  6130 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 10:20:45.036  5726  6129 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 165, thread name: OutgoingSocketThread/Sender): Socket closed
09-28 10:20:45.036  5726  6130 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 10:20:45.036  5726  6130 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 10:20:45.036  5726  6129 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:45.036  5726  6129 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 10:20:45.036  5726  6130 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 10:20:45.036  5726  6129 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 10:20:45.037  5726  6129 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:45.037  5726  6130 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:45.037  5726  6130 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 10:20:45.037  5726  6129 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:45.037  5726  6129 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 10:20:45.037  5726  6132 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 10:20:45.038  5726  6132 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 10:20:45.038  5726  6132 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 10:20:45.038  5726  6132 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 10:20:45.038  5726  6132 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 10:20:45.038  5726  6132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 10:20:45.040  5726  6131 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 167, thread name: IncomingSocketThread/Sender): Socket closed
09-28 10:20:45.040  5726  6131 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:45.040  5726  6131 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 10:20:45.040  5726  6131 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 10:20:45.040  5726  6131 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 10:20:45.041  5726  6131 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 10:20:45.041  5726  6131 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-28 10:20:46.840   927  3039 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-28 10:20:48.022  5726  5773 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-28 10:20:48.024  5726  5773 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-28 10:20:48.024  5726  5773 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,09-28 10:20:48.029  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 10:20:48.030  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae1beae added. We now have 3 listener(s)
,09-28 10:20:48.034  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:20:48.034  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.034  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.034  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.034  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb644f added. We now have 4 listener(s)
09-28 10:20:48.034  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.036  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:20:48.041  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:48.047  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:20:48.050  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.050  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:20:48.051  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 10:20:48.051  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9dc0e5 added. We now have 4 listener(s)
,09-28 10:20:48.053  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.053  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:20:48.053  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.054  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.054  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90f17ba added. We now have 5 listener(s)
09-28 10:20:48.054  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.054  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.054  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:20:48.054  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:20:48.054  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:20:48.054  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.055  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.055  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.055  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 10:20:48.055  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.055  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae1beae removed from the list
09-28 10:20:48.055  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.055  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb644f removed from the list
09-28 10:20:48.057  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.058  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:48.058  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:48.058  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.059  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:48.060  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.060  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.060  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.060  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cb644f not in the list
09-28 10:20:48.060  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.060  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:48.061  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.061  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:20:48.061  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.061  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90f17ba removed from the list
09-28 10:20:48.061  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.061  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.061  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.062  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.062  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.062  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9dc0e5 removed from the list
09-28 10:20:48.062  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:20:48.062  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883f66b added. We now have 3 listener(s)
09-28 10:20:48.064  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.064  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.064  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 10:20:48.064  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.064  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@706b5c8 added. We now have 4 listener(s)
09-28 10:20:48.064  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.065  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:20:48.067  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:48.072  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:20:48.074  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.075  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:20:48.075  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 10:20:48.075  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@786f586 added. We now have 4 listener(s)
,09-28 10:20:48.078  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.079  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:20:48.079  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.079  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.079  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.079  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee98e47 added. We now have 5 listener(s)
09-28 10:20:48.079  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.080  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:20:48.080  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:20:48.080  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:20:48.080  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:20:48.080  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:20:48.081  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:20:48.083  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:20:48.083  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:20:48.086  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:20:48.087  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 10:20:48.087  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:20:48.091  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 10:20:48.091  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-28 10:20:48.091  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 10:20:48.091  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:20:48.091  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 10:20:48.092  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:20:48.095  6022  6050 D BtGatt.GattService: registerClient() - UUID=e186a5e8-abde-4faa-83b4-992f54b03372
09-28 10:20:48.095  6022  6038 D BtGatt.GattService: onClientRegistered() - UUID=e186a5e8-abde-4faa-83b4-992f54b03372, clientIf=5
,09-28 10:20:48.096  5726  5736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:20:48.097  6022  6032 D BtGatt.GattService: start scan with filters
,09-28 10:20:48.101  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:20:48.101  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:20:48.101  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:20:48.101  6022  6041 D BtGatt.ScanManager: handling starting scan
09-28 10:20:48.101  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 10:20:48.101  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-28 10:20:48.101  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:20:48.101  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:20:48.103  6022  6041 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e8ab52
09-28 10:20:48.104  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:20:48.104  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:20:48.104  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:20:48.105  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:20:48.108  5726  5773 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 10:20:48.108  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 10:20:48.108  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 10:20:48.108  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.108  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:20:48.108  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.108  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:20:48.108  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:20:48.108  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:20:48.108  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:20:48.109  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:20:48.109  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 10:20:48.110  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:20:48.111  6022  6038 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 10:20:48.111  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.111  6022  6064 D BtGatt.GattService: stopScan() - queue size =1
09-28 10:20:48.112  6022  6041 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 10:20:48.112  6022  6059 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:20:48.112  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:20:48.112  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:20:48.112  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:20:48.112  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:20:48.113  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 10:20:48.113  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 10:20:48.113  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:20:48.113  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 10:20:48.118  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:20:48.119  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:20:48.119  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 10:20:48.119  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:20:48.119  6022  6038 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:20:48.119  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:20:48.119  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.119  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.119  6022  6041 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:20:48.120  6022  6041 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 10:20:48.121  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:20:48.121  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:20:48.121  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:20:48.123  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:20:48.123  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:20:48.123  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:20:48.123  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.123  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.123  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.123  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.123  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.123  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@883f66b removed from the list
09-28 10:20:48.123  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.123  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@706b5c8 removed from the list
09-28 10:20:48.123  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:48.123  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.124  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.124  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.125  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.125  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.125  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.125  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@706b5c8 not in the list
09-28 10:20:48.125  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.125  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.126  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.126  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 10:20:48.126  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.126  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee98e47 removed from the list
09-28 10:20:48.126  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.126  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.126  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.126  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.127  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.127  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@786f586 removed from the list
09-28 10:20:48.127  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:20:48.127  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@926c7e3 added. We now have 3 listener(s)
09-28 10:20:48.129  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.129  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.129  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.129  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.129  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc75e0 added. We now have 4 listener(s)
09-28 10:20:48.129  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:20:48.130  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:20:48.130  6022  6038 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 10:20:48.130  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.133  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:20:48.138  6022  6038 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:20:48.138  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:48.138  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:20:48.141  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:20:48.141  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:20:48.141  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:20:48.141  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4112f5e added. We now have 4 listener(s)
,09-28 10:20:48.142  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.142  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.142  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.143  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.143  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@873ff3f added. We now have 5 listener(s)
09-28 10:20:48.143  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.143  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:20:48.143  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.144  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:20:48.144  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-28 10:20:48.144  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:20:48.144  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:20:48.144  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:20:48.145  6022  6038 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 10:20:48.145  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.146  6022  6041 D BtGatt.ScanManager: stopping BLe Batch
09-28 10:20:48.147  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:20:48.147  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:20:48.150  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:20:48.151  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:20:48.151  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:20:48.152  6022  6038 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 10:20:48.152  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.152  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.152  6022  6041 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 10:20:48.157  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 10:20:48.157  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:20:48.157  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-28 10:20:48.157  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:20:48.157  6022  6038 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 10:20:48.157  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 10:20:48.157  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.158  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:20:48.162  6022  6059 D BtGatt.GattService: registerClient() - UUID=1c585ce3-5559-4745-9bad-e07360c2899d
,09-28 10:20:48.162  6022  6038 D BtGatt.GattService: onClientRegistered() - UUID=1c585ce3-5559-4745-9bad-e07360c2899d, clientIf=5
,09-28 10:20:48.162  5726  5737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 10:20:48.162  6022  6050 D BtGatt.GattService: start scan with filters
,09-28 10:20:48.165  6022  6041 D BtGatt.ScanManager: handling starting scan
09-28 10:20:48.165  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:20:48.165  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-28 10:20:48.165  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:20:48.165  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 10:20:48.165  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 10:20:48.166  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:20:48.166  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:20:48.167  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:20:48.168  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:20:48.168  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:20:48.169  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:20:48.171  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:20:48.171  5726  5773 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-28 10:20:48.171  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:20:48.171  6022  6038 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 10:20:48.171  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.171  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:20:48.171  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:20:48.171  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.171  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 10:20:48.171  6022  6041 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 10:20:48.171  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:20:48.171  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.171  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.171  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@926c7e3 removed from the list
09-28 10:20:48.171  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.172  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc75e0 removed from the list
09-28 10:20:48.172  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:48.172  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.172  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.173  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-28 10:20:48.173  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.173  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:20:48.174  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.174  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.174  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.174  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc75e0 not in the list
09-28 10:20:48.174  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:20:48.174  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:20:48.174  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:20:48.174  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-28 10:20:48.174  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 10:20:48.175  5726  5773 D BluetoothAdapter: STATE_ON
09-28 10:20:48.175  6022  6050 D BtGatt.GattService: stopScan() - queue size =1
09-28 10:20:48.176  6022  6033 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:20:48.176  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 10:20:48.176  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:20:48.176  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:20:48.176  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:20:48.176  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 10:20:48.176  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 10:20:48.176  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:20:48.176  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 10:20:48.177  6022  6038 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:20:48.177  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.177  6022  6041 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:20:48.177  6022  6041 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 10:20:48.177  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:20:48.177  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:20:48.177  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-28 10:20:48.177  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:20:48.177  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 10:20:48.180  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:48.181  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.181  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.181  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:20:48.181  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:20:48.181  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@873ff3f removed from the list
09-28 10:20:48.181  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.181  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:20:48.181  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.181  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:20:48.182  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.182  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.182  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.182  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4112f5e removed from the list
09-28 10:20:48.182  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:20:48.182  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f33505b added. We now have 3 listener(s)
09-28 10:20:48.184  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.184  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:20:48.184  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.185  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.185  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb720f8 added. We now have 4 listener(s)
09-28 10:20:48.185  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.185  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:20:48.186  6022  6038 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 10:20:48.186  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.189  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:20:48.191  6022  6038 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 10:20:48.191  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:48.194  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:20:48.196  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.196  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:20:48.196  6022  6038 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 10:20:48.196  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.196  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:20:48.197  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdcc36 added. We now have 4 listener(s)
09-28 10:20:48.197  6022  6041 D BtGatt.ScanManager: stopping BLe Batch
,09-28 10:20:48.198  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.198  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.198  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.198  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.198  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9cc9737 added. We now have 5 listener(s)
09-28 10:20:48.198  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.198  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:20:48.198  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-28 10:20:48.198  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:20:48.199  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:20:48.199  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:20:48.199  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.201  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.202  5726  5773 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:20:48.202  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 10:20:48.203  6022  6038 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 10:20:48.203  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.203  6022  6041 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 10:20:48.205  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:20:48.207  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:20:48.207  6022  6038 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 10:20:48.207  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:20:48.207  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.212  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 10:20:48.212  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:20:48.212  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 10:20:48.212  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:20:48.212  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-28 10:20:48.213  5726  5773 D BluetoothAdapter: STATE_ON
,09-28 10:20:48.215  6022  6060 D BtGatt.GattService: registerClient() - UUID=2076835f-f217-4bf5-a894-a32aca64e7b1
,09-28 10:20:48.216  6022  6038 D BtGatt.GattService: onClientRegistered() - UUID=2076835f-f217-4bf5-a894-a32aca64e7b1, clientIf=5
09-28 10:20:48.216  5726  5736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:20:48.217  6022  6064 D BtGatt.GattService: start scan with filters
,09-28 10:20:48.219  6022  6041 D BtGatt.ScanManager: handling starting scan
,09-28 10:20:48.220  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:20:48.220  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:20:48.220  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:20:48.220  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 10:20:48.221  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 10:20:48.221  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:20:48.221  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:20:48.223  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:20:48.223  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:20:48.224  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:20:48.224  6022  6038 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 10:20:48.224  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.224  6022  6041 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:20:48.225  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:20:48.229  6022  6038 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:20:48.229  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.229  6022  6041 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:20:48.229  6022  6041 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 10:20:48.230  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:20:48.230  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:20:48.230  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:20:48.230  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.230  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.230  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:20:48.231  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.231  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.231  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f33505b removed from the list
09-28 10:20:48.231  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.231  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb720f8 removed from the list
09-28 10:20:48.231  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:48.231  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.232  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.232  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-28 10:20:48.232  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.232  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.233  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.233  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 10:20:48.233  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.233  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb720f8 not in the list
09-28 10:20:48.233  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:20:48.233  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:20:48.234  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:20:48.234  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-28 10:20:48.234  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 10:20:48.235  5726  5773 D BluetoothAdapter: STATE_ON
09-28 10:20:48.235  6022  6065 D BtGatt.GattService: stopScan() - queue size =1
,09-28 10:20:48.236  6022  6033 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:20:48.236  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:20:48.236  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:20:48.236  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 10:20:48.236  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 10:20:48.236  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 10:20:48.236  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 10:20:48.237  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:20:48.237  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 10:20:48.239  6022  6038 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:20:48.239  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:20:48.239  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.239  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:20:48.239  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 10:20:48.239  5726  5773 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:20:48.239  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:20:48.240  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:48.241  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.241  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.241  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:20:48.241  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9cc9737 removed from the list
09-28 10:20:48.241  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:20:48.241  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.241  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.241  5726  5726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:20:48.241  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.241  5726  5726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:20:48.241  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.241  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.241  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdcc36 removed from the list
09-28 10:20:48.242  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:20:48.242  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9496fd3 added. We now have 3 listener(s)
09-28 10:20:48.243  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.243  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.243  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.243  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:20:48.243  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4891710 added. We now have 4 listener(s)
,09-28 10:20:48.243  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.244  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:20:48.245  6022  6038 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:20:48.245  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.246  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:20:48.249  5726  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:20:48.251  5726  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:20:48.251  6022  6038 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 10:20:48.251  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.251  5726  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:20:48.251  6022  6041 D BtGatt.ScanManager: stopping BLe Batch
09-28 10:20:48.251  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 10:20:48.251  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162c0e added. We now have 4 listener(s)
09-28 10:20:48.252  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:20:48.252  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:20:48.252  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:20:48.252  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:20:48.252  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb1362f added. We now have 5 listener(s)
09-28 10:20:48.253  5726  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:20:48.253  5726  5773 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:20:48.253  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:20:48.253  5726  5773 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 10:20:48.253  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.253  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.253  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:20:48.253  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.253  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-28 10:20:48.253  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9496fd3 removed from the list
09-28 10:20:48.253  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.253  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4891710 removed from the list
,09-28 10:20:48.254  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.256  6022  6038 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 10:20:48.256  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:20:48.256  6022  6041 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 10:20:48.257  5726  5726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:20:48.258  5726  5773 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:20:48.258  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.258  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.259  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:20:48.260  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.261  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.261  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.261  5726  5773 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4891710 not in the list
09-28 10:20:48.261  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.261  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.261  6022  6038 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 10:20:48.261  6022  6038 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:20:48.262  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:20:48.262  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 10:20:48.262  5726  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:20:48.262  5726  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb1362f removed from the list
,09-28 10:20:48.262  5726  5773 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:20:48.262  5726  5773 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:20:48.262  5726  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:20:48.262  5726  5773 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 10:20:48.262  5726  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:20:48.263  5726  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@162c0e removed from the list
09-28 10:20:48.263  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-28 10:20:48.263  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 10:20:48.263  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 10:20:48.264  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:20:48.264  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 10:20:48.264  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:20:48.622  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:20:48.682  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:20:48.741  5726  5726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:20:50.409  5726  6133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 10:20:50.409  5726  6133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:51.278  5726  6133 W !!      : call onHalfStreamCopied
,09-28 10:20:51.278  5726  6133 I testCopyDataAndClose: closing input stream
,09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 186, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 10:20:52.051  5726  6133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-28 10:20:55.768  5726  6134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:20:55.768  5726  6134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:57.769  5726  5773 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 189. Connection data: Peer properties: [null null].
09-28 10:20:57.769  5726  5773 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:57.769  5726  5773 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 189, name: My test thread name)
,09-28 10:20:57.881  5726  6135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 10:20:57.881  5726  6135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:57.948  5726  6134 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-28 10:20:57.948  5726  6134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:20:57.948  5726  6134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-28 10:20:58.261   543   543 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 10:20:58.261   543   543 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 10:20:59.554  5726  6135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-28 10:21:03.381  5726  6137 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:21:03.381  5726  6137 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:21:03.381  5726  6137 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:21:03.381  5726  6137 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:21:03.382  5726  6137 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-28 10:21:03.384  5726  5773 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:21:03.387  5726  6138 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:21:03.387  5726  6138 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 10:21:03.388  5726  6138 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 197, thread name: My test thread name): Test exception.
,09-28 10:21:03.388  5726  6138 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:21:03.388  5726  6138 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-28 10:21:03.388  5726  6138 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-28 10:21:03.388  5726  6138 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 10:21:03.388  5726  6138 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 10:21:03.392  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-28 10:21:03.392  5726  5773 I jxcore-log: 
,09-28 10:21:03.393  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-28 10:21:03.393  5726  5773 I jxcore-log: 
09-28 10:21:03.393  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-28 10:21:03.393  5726  5773 I jxcore-log: 
09-28 10:21:03.393  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-28 10:21:03.393  5726  5773 I jxcore-log: 
09-28 10:21:03.394  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Total duration:  102960'
09-28 10:21:03.394  5726  5773 I jxcore-log: 
09-28 10:21:03.395  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Failures: 
09-28 10:21:03.395  5726  5773 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-28 10:21:03.395  5726  5773 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-28 10:21:03.395  5726  5773 I jxcore-log:      but: was ""
09-28 10:21:03.395  5726  5773 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-28 10:21:03.395  5726  5773 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-28 10:21:03.395  5726  5773 I jxcore-log:      but: was ""
09-28 10:21:03.395  5726  5773 I jxcore-log: '
09-28 10:21:03.395  5726  5773 I jxcore-log: 
,09-28 10:21:03.395  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-28 10:21:03.395  5726  5773 I jxcore-log: 
09-28 10:21:03.397  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-28 10:21:03.397  5726  5773 I jxcore-log: 
,09-28 10:21:03.400  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.400  5726  5773 I jxcore-log: 
,09-28 10:21:03.402  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.402  5726  5773 I jxcore-log: 
09-28 10:21:03.402  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.402  5726  5773 I jxcore-log: 
09-28 10:21:03.402  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.402  5726  5773 I jxcore-log: 
09-28 10:21:03.402  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 10:21:03.402  5726  5773 I jxcore-log: 
09-28 10:21:03.403  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:21:03.403  5726  5773 I jxcore-log: 
09-28 10:21:03.403  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.403  5726  5773 I jxcore-log: 
,09-28 10:21:03.404  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.404  5726  5773 I jxcore-log: 
09-28 10:21:03.404  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 10:21:03.404  5726  5773 I jxcore-log: 
09-28 10:21:03.404  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:21:03.404  5726  5773 I jxcore-log: 
09-28 10:21:03.404  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:21:03.404  5726  5773 I jxcore-log: 
09-28 10:21:03.405  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.405  5726  5773 I jxcore-log: 
09-28 10:21:03.405  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.405  5726  5773 I jxcore-log: 
09-28 10:21:03.405  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.405  5726  5773 I jxcore-log: 
09-28 10:21:03.405  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.405  5726  5773 I jxcore-log: 
,09-28 10:21:03.406  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.406  5726  5773 I jxcore-log: 
09-28 10:21:03.406  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.406  5726  5773 I jxcore-log: 
09-28 10:21:03.406  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.406  5726  5773 I jxcore-log: 
,09-28 10:21:03.407  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.407  5726  5773 I jxcore-log: 
09-28 10:21:03.407  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.407  5726  5773 I jxcore-log: 
,09-28 10:21:03.407  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.407  5726  5773 I jxcore-log: 
09-28 10:21:03.407  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.407  5726  5773 I jxcore-log: 
09-28 10:21:03.409  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.409  5726  5773 I jxcore-log: 
09-28 10:21:03.410  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.410  5726  5773 I jxcore-log: 
09-28 10:21:03.410  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.410  5726  5773 I jxcore-log: 
09-28 10:21:03.410  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.410  5726  5773 I jxcore-log: 
09-28 10:21:03.410  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.410  5726  5773 I jxcore-log: 
09-28 10:21:03.411  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.411  5726  5773 I jxcore-log: 
,09-28 10:21:03.411  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.411  5726  5773 I jxcore-log: 
09-28 10:21:03.411  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.411  5726  5773 I jxcore-log: 
09-28 10:21:03.411  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.411  5726  5773 I jxcore-log: 
09-28 10:21:03.412  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.412  5726  5773 I jxcore-log: 
09-28 10:21:03.412  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.412  5726  5773 I jxcore-log: 
09-28 10:21:03.412  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.412  5726  5773 I jxcore-log: 
09-28 10:21:03.412  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.412  5726  5773 I jxcore-log: 
09-28 10:21:03.412  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.412  5726  5773 I jxcore-log: 
,09-28 10:21:03.413  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.413  5726  5773 I jxcore-log: 
09-28 10:21:03.413  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 10:21:03.413  5726  5773 I jxcore-log: 
09-28 10:21:03.413  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.413  5726  5773 I jxcore-log: 
09-28 10:21:03.413  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 10:21:03.413  5726  5773 I jxcore-log: 
09-28 10:21:03.414  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.414  5726  5773 I jxcore-log: 
09-28 10:21:03.414  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.414  5726  5773 I jxcore-log: 
09-28 10:21:03.414  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.414  5726  5773 I jxcore-log: 
09-28 10:21:03.414  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.414  5726  5773 I jxcore-log: 
09-28 10:21:03.414  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.414  5726  5773 I jxcore-log: 
,09-28 10:21:03.415  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:21:03.415  5726  5773 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-28 10:21:03.415  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.415  5726  5773 I jxcore-log: 
09-28 10:21:03.415  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.415  5726  5773 I jxcore-log: 
09-28 10:21:03.415  5726  5773 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:21:03.415  5726  5773 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-28 10:21:03.415  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 10:21:03.415  5726  5773 I jxcore-log: 
09-28 10:21:03.416  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:21:03.416  5726  5773 I jxcore-log: 
,09-28 10:21:03.416  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:21:03.416  5726  5773 I jxcore-log: 
09-28 10:21:03.416  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 10:21:03.416  5726  5773 I jxcore-log: 
,09-28 10:21:03.421  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-28 10:21:03.421  5726  5773 I jxcore-log: 
09-28 10:21:03.422  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - WARN testUtils: 'myNameCallback not set!'
09-28 10:21:03.422  5726  5773 I jxcore-log: 
,09-28 10:21:03.423  5726  5773 I jxcore-log: 2016-09-28 14:21:03 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-28 10:21:03.423  5726  5773 I jxcore-log: 
,09-28 10:21:03.424  5726  5726 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-28 10:21:05.474  5726  5773 I jxcore-log: 2016-09-28 14:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-28 10:21:05.474  5726  5773 I jxcore-log: 
,09-28 10:21:05.804  5726  5773 I jxcore-log: 2016-09-28 14:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-28 10:21:05.804  5726  5773 I jxcore-log: 
,09-28 10:21:05.817  5726  5773 I jxcore-log: 2016-09-28 14:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-28 10:21:05.817  5726  5773 I jxcore-log: 
,09-28 10:21:06.908  5726  5773 I jxcore-log: 2016-09-28 14:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-28 10:21:06.908  5726  5773 I jxcore-log: 
,09-28 10:21:07.068  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-28 10:21:07.068  5726  5773 I jxcore-log: 
,09-28 10:21:07.073  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-28 10:21:07.073  5726  5773 I jxcore-log: 
,09-28 10:21:07.077  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-28 10:21:07.077  5726  5773 I jxcore-log: 
,09-28 10:21:07.610  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-28 10:21:07.610  5726  5773 I jxcore-log: 
,09-28 10:21:07.661  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-28 10:21:07.661  5726  5773 I jxcore-log: 
,09-28 10:21:07.674  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-28 10:21:07.674  5726  5773 I jxcore-log: 
,09-28 10:21:07.678  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-28 10:21:07.678  5726  5773 I jxcore-log: 
,09-28 10:21:07.956  5726  5773 I jxcore-log: 2016-09-28 14:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-28 10:21:07.956  5726  5773 I jxcore-log: 
,09-28 10:21:08.081  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-28 10:21:08.081  5726  5773 I jxcore-log: 
,09-28 10:21:08.459  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-28 10:21:08.459  5726  5773 I jxcore-log: 
,09-28 10:21:08.467  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-28 10:21:08.467  5726  5773 I jxcore-log: 
,09-28 10:21:08.470  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-28 10:21:08.470  5726  5773 I jxcore-log: 
,09-28 10:21:08.475  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-28 10:21:08.475  5726  5773 I jxcore-log: 
,09-28 10:21:08.479  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-28 10:21:08.479  5726  5773 I jxcore-log: 
,09-28 10:21:08.506  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-28 10:21:08.506  5726  5773 I jxcore-log: 
,09-28 10:21:08.540  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-28 10:21:08.540  5726  5773 I jxcore-log: 
,09-28 10:21:08.548  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-28 10:21:08.548  5726  5773 I jxcore-log: 
,09-28 10:21:08.555  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-28 10:21:08.555  5726  5773 I jxcore-log: 
,09-28 10:21:08.570  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-28 10:21:08.570  5726  5773 I jxcore-log: 
,09-28 10:21:08.576  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-28 10:21:08.576  5726  5773 I jxcore-log: 
,09-28 10:21:08.582  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-28 10:21:08.582  5726  5773 I jxcore-log: 
,09-28 10:21:08.587  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-28 10:21:08.587  5726  5773 I jxcore-log: 
,09-28 10:21:08.600  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-28 10:21:08.600  5726  5773 I jxcore-log: 
,09-28 10:21:08.621  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-28 10:21:08.621  5726  5773 I jxcore-log: 
,09-28 10:21:08.630  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-28 10:21:08.630  5726  5773 I jxcore-log: 
,09-28 10:21:08.641  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-28 10:21:08.641  5726  5773 I jxcore-log: 
,09-28 10:21:08.651  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-28 10:21:08.651  5726  5773 I jxcore-log: 
,09-28 10:21:08.663  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-28 10:21:08.663  5726  5773 I jxcore-log: 
,09-28 10:21:08.673  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-28 10:21:08.673  5726  5773 I jxcore-log: 
,09-28 10:21:08.678  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-28 10:21:08.678  5726  5773 I jxcore-log: 
,09-28 10:21:08.699  5726  5773 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-28 10:21:08.700  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - INFO testUtils: 'BLE multiple advertisement supported'
09-28 10:21:08.700  5726  5773 I jxcore-log: 
,09-28 10:21:08.800  5726  5773 I jxcore-log: 2016-09-28 14:21:08 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 10:21:08.800  5726  5773 I jxcore-log: 
,09-28 10:21:09.223  5726  5773 I jxcore-log: TAP version 13
09-28 10:21:09.223  5726  5773 I jxcore-log: 
,09-28 10:21:09.264  5726  5773 I jxcore-log: # setup
09-28 10:21:09.264  5726  5773 I jxcore-log: 
,09-28 10:21:10.074  5726  5773 I jxcore-log: # calling createNativeListener directly rejects
09-28 10:21:10.074  5726  5773 I jxcore-log: 
,09-28 10:21:10.143  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:10.143  5726  5773 I jxcore-log: 
,09-28 10:21:10.147  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'listening 42506'
09-28 10:21:10.147  5726  5773 I jxcore-log: 
,09-28 10:21:10.153  5726  5773 I jxcore-log: ok 1 Should throw
09-28 10:21:10.153  5726  5773 I jxcore-log: 
,09-28 10:21:10.161  5726  5773 I jxcore-log: # teardown
09-28 10:21:10.161  5726  5773 I jxcore-log: 
,09-28 10:21:10.249  5726  5773 I jxcore-log: # setup
09-28 10:21:10.249  5726  5773 I jxcore-log: 
,09-28 10:21:10.332  5726  5773 I jxcore-log: # emits incomingConnectionState
09-28 10:21:10.332  5726  5773 I jxcore-log: 
,09-28 10:21:10.475  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:10.475  5726  5773 I jxcore-log: 
,09-28 10:21:10.481  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'listening 44207'
09-28 10:21:10.481  5726  5773 I jxcore-log: 
,09-28 10:21:10.491  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:10.491  5726  5773 I jxcore-log: 
,09-28 10:21:10.494  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:10.494  5726  5773 I jxcore-log: 
,09-28 10:21:10.506  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'new mux'
09-28 10:21:10.506  5726  5773 I jxcore-log: 
,09-28 10:21:10.512  5726  5773 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-28 10:21:10.512  5726  5773 I jxcore-log: 
,09-28 10:21:10.537  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:10.537  5726  5773 I jxcore-log: 
,09-28 10:21:10.538  5726  5773 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-28 10:21:10.538  5726  5773 I jxcore-log: 
,09-28 10:21:10.547  5726  5773 I jxcore-log: # teardown
09-28 10:21:10.547  5726  5773 I jxcore-log: 
,09-28 10:21:10.582  5726  5773 I jxcore-log: # setup
09-28 10:21:10.582  5726  5773 I jxcore-log: 
,09-28 10:21:10.640  5726  5773 I jxcore-log: # emits routerPortConnectionFailed
09-28 10:21:10.640  5726  5773 I jxcore-log: 
,09-28 10:21:10.732  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:10.732  5726  5773 I jxcore-log: 
,09-28 10:21:10.736  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'listening 37455'
09-28 10:21:10.736  5726  5773 I jxcore-log: 
,09-28 10:21:10.743  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:10.743  5726  5773 I jxcore-log: 
,09-28 10:21:10.745  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:10.745  5726  5773 I jxcore-log: 
09-28 10:21:10.746  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'new mux'
09-28 10:21:10.746  5726  5773 I jxcore-log: 
,09-28 10:21:10.776  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:10.776  5726  5773 I jxcore-log: 
,09-28 10:21:10.778  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:10.778  5726  5773 I jxcore-log: 
,09-28 10:21:10.783  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: ''
09-28 10:21:10.783  5726  5773 I jxcore-log: 
,09-28 10:21:10.784  5726  5773 I jxcore-log: ok 4 tried to connect to right port
09-28 10:21:10.784  5726  5773 I jxcore-log: 
,09-28 10:21:10.785  5726  5773 I jxcore-log: ok 5 failed due to refused connection
09-28 10:21:10.785  5726  5773 I jxcore-log: 
09-28 10:21:10.786  5726  5773 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-28 10:21:10.786  5726  5773 I jxcore-log: 
09-28 10:21:10.788  5726  5773 I jxcore-log: # teardown
09-28 10:21:10.788  5726  5773 I jxcore-log: 
,09-28 10:21:10.791  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:10.791  5726  5773 I jxcore-log: 
,09-28 10:21:10.839  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'mux close'
09-28 10:21:10.839  5726  5773 I jxcore-log: 
,09-28 10:21:10.843  5726  5773 I jxcore-log: 2016-09-28 14:21:10 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:10.843  5726  5773 I jxcore-log: 
,09-28 10:21:10.854  5726  5773 I jxcore-log: # setup
09-28 10:21:10.854  5726  5773 I jxcore-log: 
,09-28 10:21:11.159  5726  5773 I jxcore-log: # native server connections all up
09-28 10:21:11.159  5726  5773 I jxcore-log: 
,09-28 10:21:12.898  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'creating native server',
09-28 10:21:12.898  5726  5773 I jxcore-log: 
,09-28 10:21:12.904  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'listening 37967'
09-28 10:21:12.904  5726  5773 I jxcore-log: 
,09-28 10:21:12.913  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:12.913  5726  5773 I jxcore-log: 
,09-28 10:21:12.915  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:12.915  5726  5773 I jxcore-log: 
,09-28 10:21:12.917  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'new mux'
09-28 10:21:12.917  5726  5773 I jxcore-log: 
,09-28 10:21:12.949  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:12.949  5726  5773 I jxcore-log: 
,09-28 10:21:12.953  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:12.953  5726  5773 I jxcore-log: 
,09-28 10:21:12.956  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:12.956  5726  5773 I jxcore-log: 
,09-28 10:21:12.959  5726  5773 I jxcore-log: 2016-09-28 14:21:12 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:12.959  5726  5773 I jxcore-log: 
,09-28 10:21:12.984  5726  5773 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-28 10:21:12.984  5726  5773 I jxcore-log: 
,09-28 10:21:12.985  5726  5773 I jxcore-log: ok 8 Send/recvd #1 should be same
09-28 10:21:12.985  5726  5773 I jxcore-log: 
,09-28 10:21:12.987  5726  5773 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-28 10:21:12.987  5726  5773 I jxcore-log: 
,09-28 10:21:12.988  5726  5773 I jxcore-log: ok 10 Send/recvd #2 should be same
09-28 10:21:12.988  5726  5773 I jxcore-log: 
09-28 10:21:12.992  5726  5773 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-28 10:21:12.992  5726  5773 I jxcore-log: 
,09-28 10:21:12.999  5726  5773 I jxcore-log: # teardown
09-28 10:21:12.999  5726  5773 I jxcore-log: 
,09-28 10:21:13.028  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:13.028  5726  5773 I jxcore-log: 
,09-28 10:21:13.030  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:13.030  5726  5773 I jxcore-log: 
,09-28 10:21:13.032  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'mux close'
09-28 10:21:13.032  5726  5773 I jxcore-log: 
,09-28 10:21:13.036  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:13.036  5726  5773 I jxcore-log: 
,09-28 10:21:13.045  5726  5773 I jxcore-log: # setup
09-28 10:21:13.045  5726  5773 I jxcore-log: 
,09-28 10:21:13.263   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:13.517  5726  5773 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-28 10:21:13.517  5726  5773 I jxcore-log: 
,09-28 10:21:13.572  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:13.572  5726  5773 I jxcore-log: 
,09-28 10:21:13.577  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'listening 37992'
09-28 10:21:13.577  5726  5773 I jxcore-log: 
,09-28 10:21:13.587  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:13.587  5726  5773 I jxcore-log: 
,09-28 10:21:13.589  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:13.589  5726  5773 I jxcore-log: 
,09-28 10:21:13.596  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new mux'
09-28 10:21:13.596  5726  5773 I jxcore-log: 
,09-28 10:21:13.615  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:13.615  5726  5773 I jxcore-log: 
,09-28 10:21:13.618  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:13.618  5726  5773 I jxcore-log: 
,09-28 10:21:13.632  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:13.632  5726  5773 I jxcore-log: 
,09-28 10:21:13.646  5726  5773 I jxcore-log: ok 12 socket shouldn't close until after stream
09-28 10:21:13.646  5726  5773 I jxcore-log: 
,09-28 10:21:13.646  5726  5773 I jxcore-log: ok 13 incoming remains open
09-28 10:21:13.646  5726  5773 I jxcore-log: 
,09-28 10:21:13.653  5726  5773 I jxcore-log: # teardown
09-28 10:21:13.653  5726  5773 I jxcore-log: 
,09-28 10:21:13.713  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'mux close'
09-28 10:21:13.713  5726  5773 I jxcore-log: 
,09-28 10:21:13.721  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:13.721  5726  5773 I jxcore-log: 
,09-28 10:21:13.730  5726  5773 I jxcore-log: # setup
09-28 10:21:13.730  5726  5773 I jxcore-log: 
,09-28 10:21:13.822  5726  5773 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-28 10:21:13.822  5726  5773 I jxcore-log: 
,09-28 10:21:13.877  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:13.877  5726  5773 I jxcore-log: 
,09-28 10:21:13.884  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'listening 44927'
09-28 10:21:13.884  5726  5773 I jxcore-log: 
,09-28 10:21:13.894  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:13.894  5726  5773 I jxcore-log: 
,09-28 10:21:13.896  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:13.896  5726  5773 I jxcore-log: 
,09-28 10:21:13.898  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new mux'
09-28 10:21:13.898  5726  5773 I jxcore-log: 
,09-28 10:21:13.911  5726  5773 I jxcore-log: ok 14 we should not have gotten an error
09-28 10:21:13.911  5726  5773 I jxcore-log: 
,09-28 10:21:13.921  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:13.921  5726  5773 I jxcore-log: 
,09-28 10:21:13.927  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:13.927  5726  5773 I jxcore-log: 
,09-28 10:21:13.938  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:13.938  5726  5773 I jxcore-log: 
,09-28 10:21:13.941  5726  5773 I jxcore-log: 2016-09-28 14:21:13 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:13.941  5726  5773 I jxcore-log: 
,09-28 10:21:13.949  5726  5773 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-28 10:21:13.949  5726  5773 I jxcore-log: 
,09-28 10:21:13.950  5726  5773 I jxcore-log: ok 16 incoming is cleaned up
09-28 10:21:13.950  5726  5773 I jxcore-log: 
,09-28 10:21:13.952  5726  5773 I jxcore-log: # teardown
09-28 10:21:13.952  5726  5773 I jxcore-log: 
,09-28 10:21:13.998  5726  5773 I jxcore-log: # setup
09-28 10:21:13.998  5726  5773 I jxcore-log: 
,09-28 10:21:14.088  5726  5773 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-28 10:21:14.088  5726  5773 I jxcore-log: 
,09-28 10:21:14.160  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:14.160  5726  5773 I jxcore-log: 
,09-28 10:21:14.164  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'listening 37038'
09-28 10:21:14.164  5726  5773 I jxcore-log: 
,09-28 10:21:14.170  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.170  5726  5773 I jxcore-log: 
,09-28 10:21:14.171  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.171  5726  5773 I jxcore-log: 
09-28 10:21:14.173  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.173  5726  5773 I jxcore-log: 
,09-28 10:21:14.188  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.188  5726  5773 I jxcore-log: 
,09-28 10:21:14.190  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.190  5726  5773 I jxcore-log: 
,09-28 10:21:14.202  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:14.202  5726  5773 I jxcore-log: 
,09-28 10:21:14.216  5726  5773 I jxcore-log: ok 17 stream was closed
09-28 10:21:14.216  5726  5773 I jxcore-log: 
,09-28 10:21:14.217  5726  5773 I jxcore-log: ok 18 incoming should survive
09-28 10:21:14.217  5726  5773 I jxcore-log: 
,09-28 10:21:14.217  5726  5773 I jxcore-log: ok 19 mux should have no streams
09-28 10:21:14.217  5726  5773 I jxcore-log: 
,09-28 10:21:14.222  5726  5773 I jxcore-log: # teardown
09-28 10:21:14.222  5726  5773 I jxcore-log: 
,09-28 10:21:14.263   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:14.273  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'mux close'
09-28 10:21:14.273  5726  5773 I jxcore-log: 
,09-28 10:21:14.278  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:14.278  5726  5773 I jxcore-log: 
,09-28 10:21:14.285  5726  5773 I jxcore-log: # setup
09-28 10:21:14.285  5726  5773 I jxcore-log: 
,09-28 10:21:14.410  5726  5773 I jxcore-log: # native server - closing the whole server cleans everything up
09-28 10:21:14.410  5726  5773 I jxcore-log: 
,09-28 10:21:14.491  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:14.491  5726  5773 I jxcore-log: 
,09-28 10:21:14.497  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'listening 44567'
09-28 10:21:14.497  5726  5773 I jxcore-log: 
,09-28 10:21:14.511  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.511  5726  5773 I jxcore-log: 
,09-28 10:21:14.512  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.512  5726  5773 I jxcore-log: 
09-28 10:21:14.514  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.514  5726  5773 I jxcore-log: 
,09-28 10:21:14.526  5726  5773 I jxcore-log: ok 20 we should not have gotten an error
09-28 10:21:14.526  5726  5773 I jxcore-log: 
,09-28 10:21:14.540  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.540  5726  5773 I jxcore-log: 
,09-28 10:21:14.543  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.543  5726  5773 I jxcore-log: 
,09-28 10:21:14.553  5726  5773 I jxcore-log: ok 21 Buffers are identical
09-28 10:21:14.553  5726  5773 I jxcore-log: 
,09-28 10:21:14.555  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:14.555  5726  5773 I jxcore-log: 
,09-28 10:21:14.558  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'mux close'
09-28 10:21:14.558  5726  5773 I jxcore-log: 
,09-28 10:21:14.561  5726  5773 I jxcore-log: ok 22 native server is nulled out
09-28 10:21:14.561  5726  5773 I jxcore-log: 
09-28 10:21:14.561  5726  5773 I jxcore-log: ok 23 native server should be closed
09-28 10:21:14.561  5726  5773 I jxcore-log: 
,09-28 10:21:14.562  5726  5773 I jxcore-log: ok 24 incoming has been removed
09-28 10:21:14.562  5726  5773 I jxcore-log: 
09-28 10:21:14.562  5726  5773 I jxcore-log: ok 25 Incoming should be done
09-28 10:21:14.562  5726  5773 I jxcore-log: 
09-28 10:21:14.562  5726  5773 I jxcore-log: ok 26 The mux object should be closed
09-28 10:21:14.562  5726  5773 I jxcore-log: 
09-28 10:21:14.562  5726  5773 I jxcore-log: ok 27 The mux stream should be closed
09-28 10:21:14.562  5726  5773 I jxcore-log: 
09-28 10:21:14.563  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:14.563  5726  5773 I jxcore-log: 
,09-28 10:21:14.577  5726  5773 I jxcore-log: # teardown
09-28 10:21:14.577  5726  5773 I jxcore-log: 
,09-28 10:21:14.631  5726  5773 I jxcore-log: # setup
09-28 10:21:14.631  5726  5773 I jxcore-log: 
,09-28 10:21:14.690  5726  5773 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-28 10:21:14.690  5726  5773 I jxcore-log: 
,09-28 10:21:14.766  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:14.766  5726  5773 I jxcore-log: 
,09-28 10:21:14.773  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'listening 47503'
09-28 10:21:14.773  5726  5773 I jxcore-log: 
,09-28 10:21:14.813  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.813  5726  5773 I jxcore-log: 
,09-28 10:21:14.814  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.814  5726  5773 I jxcore-log: 
09-28 10:21:14.816  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.816  5726  5773 I jxcore-log: 
09-28 10:21:14.819  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.819  5726  5773 I jxcore-log: 
09-28 10:21:14.819  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.819  5726  5773 I jxcore-log: 
,09-28 10:21:14.821  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.821  5726  5773 I jxcore-log: 
,09-28 10:21:14.824  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.824  5726  5773 I jxcore-log: 
,09-28 10:21:14.825  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.825  5726  5773 I jxcore-log: 
09-28 10:21:14.826  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.826  5726  5773 I jxcore-log: 
,09-28 10:21:14.830  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.830  5726  5773 I jxcore-log: 
,09-28 10:21:14.831  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.831  5726  5773 I jxcore-log: 
,09-28 10:21:14.832  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.832  5726  5773 I jxcore-log: 
,09-28 10:21:14.836  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.836  5726  5773 I jxcore-log: 
,09-28 10:21:14.837  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.837  5726  5773 I jxcore-log: 
,09-28 10:21:14.840  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.840  5726  5773 I jxcore-log: 
,09-28 10:21:14.843  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.843  5726  5773 I jxcore-log: 
09-28 10:21:14.844  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.844  5726  5773 I jxcore-log: 
,09-28 10:21:14.846  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.846  5726  5773 I jxcore-log: 
,09-28 10:21:14.848  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.848  5726  5773 I jxcore-log: 
,09-28 10:21:14.849  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.849  5726  5773 I jxcore-log: 
09-28 10:21:14.850  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.850  5726  5773 I jxcore-log: 
,09-28 10:21:14.859  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.859  5726  5773 I jxcore-log: 
,09-28 10:21:14.861  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.861  5726  5773 I jxcore-log: 
,09-28 10:21:14.863  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.863  5726  5773 I jxcore-log: 
,09-28 10:21:14.866  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.866  5726  5773 I jxcore-log: 
,09-28 10:21:14.867  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.867  5726  5773 I jxcore-log: 
,09-28 10:21:14.868  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.868  5726  5773 I jxcore-log: 
,09-28 10:21:14.870  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:14.870  5726  5773 I jxcore-log: 
,09-28 10:21:14.871  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:14.871  5726  5773 I jxcore-log: 
,09-28 10:21:14.872  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new mux'
09-28 10:21:14.872  5726  5773 I jxcore-log: 
,09-28 10:21:14.929  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.929  5726  5773 I jxcore-log: 
,09-28 10:21:14.931  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.931  5726  5773 I jxcore-log: 
,09-28 10:21:14.932  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.932  5726  5773 I jxcore-log: 
,09-28 10:21:14.933  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.933  5726  5773 I jxcore-log: 
,09-28 10:21:14.934  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.934  5726  5773 I jxcore-log: 
,09-28 10:21:14.935  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.935  5726  5773 I jxcore-log: 
,09-28 10:21:14.937  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.937  5726  5773 I jxcore-log: 
,09-28 10:21:14.938  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.938  5726  5773 I jxcore-log: 
,09-28 10:21:14.939  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.939  5726  5773 I jxcore-log: 
,09-28 10:21:14.940  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.940  5726  5773 I jxcore-log: 
,09-28 10:21:14.941  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.941  5726  5773 I jxcore-log: 
,09-28 10:21:14.942  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.942  5726  5773 I jxcore-log: 
09-28 10:21:14.943  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.943  5726  5773 I jxcore-log: 
,09-28 10:21:14.944  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.944  5726  5773 I jxcore-log: 
,09-28 10:21:14.944  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.944  5726  5773 I jxcore-log: 
,09-28 10:21:14.945  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.945  5726  5773 I jxcore-log: 
,09-28 10:21:14.947  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.947  5726  5773 I jxcore-log: 
,09-28 10:21:14.948  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.948  5726  5773 I jxcore-log: 
,09-28 10:21:14.948  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.948  5726  5773 I jxcore-log: 
,09-28 10:21:14.949  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.949  5726  5773 I jxcore-log: 
09-28 10:21:14.950  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.950  5726  5773 I jxcore-log: 
,09-28 10:21:14.951  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.951  5726  5773 I jxcore-log: 
09-28 10:21:14.952  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.952  5726  5773 I jxcore-log: 
,09-28 10:21:14.952  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.952  5726  5773 I jxcore-log: 
,09-28 10:21:14.954  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.954  5726  5773 I jxcore-log: 
09-28 10:21:14.955  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.955  5726  5773 I jxcore-log: 
,09-28 10:21:14.955  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.955  5726  5773 I jxcore-log: 
,09-28 10:21:14.961  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.961  5726  5773 I jxcore-log: 
,09-28 10:21:14.963  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.963  5726  5773 I jxcore-log: 
,09-28 10:21:14.964  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.964  5726  5773 I jxcore-log: 
,09-28 10:21:14.965  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.965  5726  5773 I jxcore-log: 
,09-28 10:21:14.966  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.966  5726  5773 I jxcore-log: 
,09-28 10:21:14.967  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.967  5726  5773 I jxcore-log: 
,09-28 10:21:14.968  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.968  5726  5773 I jxcore-log: 
,09-28 10:21:14.969  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.969  5726  5773 I jxcore-log: 
,09-28 10:21:14.970  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.970  5726  5773 I jxcore-log: 
,09-28 10:21:14.971  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.971  5726  5773 I jxcore-log: 
09-28 10:21:14.972  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.972  5726  5773 I jxcore-log: 
,09-28 10:21:14.972  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.972  5726  5773 I jxcore-log: 
,09-28 10:21:14.973  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.973  5726  5773 I jxcore-log: 
,09-28 10:21:14.974  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.974  5726  5773 I jxcore-log: 
,09-28 10:21:14.975  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.975  5726  5773 I jxcore-log: 
09-28 10:21:14.976  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.976  5726  5773 I jxcore-log: 
,09-28 10:21:14.977  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.977  5726  5773 I jxcore-log: 
,09-28 10:21:14.977  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.977  5726  5773 I jxcore-log: 
,09-28 10:21:14.978  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.978  5726  5773 I jxcore-log: 
09-28 10:21:14.979  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.979  5726  5773 I jxcore-log: 
,09-28 10:21:14.979  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.979  5726  5773 I jxcore-log: 
,09-28 10:21:14.981  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.981  5726  5773 I jxcore-log: 
,09-28 10:21:14.982  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.982  5726  5773 I jxcore-log: 
,09-28 10:21:14.982  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.982  5726  5773 I jxcore-log: 
09-28 10:21:14.983  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.983  5726  5773 I jxcore-log: 
,09-28 10:21:14.984  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.984  5726  5773 I jxcore-log: 
,09-28 10:21:14.985  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.985  5726  5773 I jxcore-log: 
09-28 10:21:14.985  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.985  5726  5773 I jxcore-log: 
09-28 10:21:14.986  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.986  5726  5773 I jxcore-log: 
,09-28 10:21:14.988  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.988  5726  5773 I jxcore-log: 
,09-28 10:21:14.989  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.989  5726  5773 I jxcore-log: 
09-28 10:21:14.990  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.990  5726  5773 I jxcore-log: 
,09-28 10:21:14.990  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.990  5726  5773 I jxcore-log: 
09-28 10:21:14.991  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.991  5726  5773 I jxcore-log: 
,09-28 10:21:14.992  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.992  5726  5773 I jxcore-log: 
,09-28 10:21:14.992  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.992  5726  5773 I jxcore-log: 
09-28 10:21:14.993  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.993  5726  5773 I jxcore-log: 
09-28 10:21:14.994  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.994  5726  5773 I jxcore-log: 
,09-28 10:21:14.995  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.995  5726  5773 I jxcore-log: 
,09-28 10:21:14.995  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.995  5726  5773 I jxcore-log: 
09-28 10:21:14.996  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.996  5726  5773 I jxcore-log: 
,09-28 10:21:14.997  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.997  5726  5773 I jxcore-log: 
,09-28 10:21:14.997  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.997  5726  5773 I jxcore-log: 
09-28 10:21:14.998  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:14.998  5726  5773 I jxcore-log: 
,09-28 10:21:14.999  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:14.999  5726  5773 I jxcore-log: 
09-28 10:21:15.000  5726  5773 I jxcore-log: 2016-09-28 14:21:14 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:15.000  5726  5773 I jxcore-log: 
,09-28 10:21:15.001  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:15.001  5726  5773 I jxcore-log: 
09-28 10:21:15.001  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:15.001  5726  5773 I jxcore-log: 
,09-28 10:21:15.002  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:15.002  5726  5773 I jxcore-log: 
09-28 10:21:15.002  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:15.002  5726  5773 I jxcore-log: 
,09-28 10:21:15.003  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:15.003  5726  5773 I jxcore-log: 
09-28 10:21:15.004  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:15.004  5726  5773 I jxcore-log: 
09-28 10:21:15.004  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:15.004  5726  5773 I jxcore-log: 
,09-28 10:21:15.055  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.055  5726  5773 I jxcore-log: 
,09-28 10:21:15.056  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.056  5726  5773 I jxcore-log: 
,09-28 10:21:15.057  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.057  5726  5773 I jxcore-log: 
,09-28 10:21:15.058  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.058  5726  5773 I jxcore-log: 
09-28 10:21:15.059  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.059  5726  5773 I jxcore-log: 
,09-28 10:21:15.059  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.059  5726  5773 I jxcore-log: 
09-28 10:21:15.060  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.060  5726  5773 I jxcore-log: 
,09-28 10:21:15.060  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.060  5726  5773 I jxcore-log: 
09-28 10:21:15.061  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.061  5726  5773 I jxcore-log: 
,09-28 10:21:15.061  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.061  5726  5773 I jxcore-log: 
09-28 10:21:15.062  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.062  5726  5773 I jxcore-log: 
,09-28 10:21:15.064  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.064  5726  5773 I jxcore-log: 
,09-28 10:21:15.064  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.064  5726  5773 I jxcore-log: 
09-28 10:21:15.065  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.065  5726  5773 I jxcore-log: 
,09-28 10:21:15.066  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.066  5726  5773 I jxcore-log: 
,09-28 10:21:15.070  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.070  5726  5773 I jxcore-log: 
,09-28 10:21:15.071  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.071  5726  5773 I jxcore-log: 
,09-28 10:21:15.072  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.072  5726  5773 I jxcore-log: 
,09-28 10:21:15.072  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.072  5726  5773 I jxcore-log: 
09-28 10:21:15.073  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.073  5726  5773 I jxcore-log: 
,09-28 10:21:15.073  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.073  5726  5773 I jxcore-log: 
09-28 10:21:15.074  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.074  5726  5773 I jxcore-log: 
09-28 10:21:15.074  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.074  5726  5773 I jxcore-log: 
,09-28 10:21:15.075  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.075  5726  5773 I jxcore-log: 
09-28 10:21:15.075  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.075  5726  5773 I jxcore-log: 
,09-28 10:21:15.076  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.076  5726  5773 I jxcore-log: 
,09-28 10:21:15.076  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.076  5726  5773 I jxcore-log: 
09-28 10:21:15.077  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.077  5726  5773 I jxcore-log: 
09-28 10:21:15.077  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.077  5726  5773 I jxcore-log: 
,09-28 10:21:15.078  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.078  5726  5773 I jxcore-log: 
09-28 10:21:15.078  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.078  5726  5773 I jxcore-log: 
09-28 10:21:15.078  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.078  5726  5773 I jxcore-log: 
,09-28 10:21:15.079  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.079  5726  5773 I jxcore-log: 
09-28 10:21:15.079  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.079  5726  5773 I jxcore-log: 
,09-28 10:21:15.080  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.080  5726  5773 I jxcore-log: 
09-28 10:21:15.080  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.080  5726  5773 I jxcore-log: 
09-28 10:21:15.081  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.081  5726  5773 I jxcore-log: 
,09-28 10:21:15.081  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.081  5726  5773 I jxcore-log: 
09-28 10:21:15.081  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.081  5726  5773 I jxcore-log: 
,09-28 10:21:15.082  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.082  5726  5773 I jxcore-log: 
09-28 10:21:15.082  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.082  5726  5773 I jxcore-log: 
,09-28 10:21:15.082  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.082  5726  5773 I jxcore-log: 
09-28 10:21:15.083  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.083  5726  5773 I jxcore-log: 
,09-28 10:21:15.083  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.083  5726  5773 I jxcore-log: 
09-28 10:21:15.084  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.084  5726  5773 I jxcore-log: 
,09-28 10:21:15.084  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.084  5726  5773 I jxcore-log: 
09-28 10:21:15.085  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.085  5726  5773 I jxcore-log: 
,09-28 10:21:15.087  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.087  5726  5773 I jxcore-log: 
,09-28 10:21:15.088  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:15.088  5726  5773 I jxcore-log: 
,09-28 10:21:15.089  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'mux close'
09-28 10:21:15.089  5726  5773 I jxcore-log: 
,09-28 10:21:15.091  5726  5773 I jxcore-log: ok 28 native server is nulled out
09-28 10:21:15.091  5726  5773 I jxcore-log: 
,09-28 10:21:15.091  5726  5773 I jxcore-log: ok 29 native server should be closed
09-28 10:21:15.091  5726  5773 I jxcore-log: 
09-28 10:21:15.091  5726  5773 I jxcore-log: ok 30 incoming has been removed
09-28 10:21:15.091  5726  5773 I jxcore-log: 
09-28 10:21:15.092  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.092  5726  5773 I jxcore-log: 
09-28 10:21:15.092  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.092  5726  5773 I jxcore-log: 
,09-28 10:21:15.093  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.093  5726  5773 I jxcore-log: 
09-28 10:21:15.093  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.093  5726  5773 I jxcore-log: 
09-28 10:21:15.093  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.093  5726  5773 I jxcore-log: 
,09-28 10:21:15.094  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.094  5726  5773 I jxcore-log: 
09-28 10:21:15.094  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.094  5726  5773 I jxcore-log: 
09-28 10:21:15.094  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.094  5726  5773 I jxcore-log: 
09-28 10:21:15.094  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.094  5726  5773 I jxcore-log: 
09-28 10:21:15.094  5726  5773 I jxcore-log: 2016-09-28 14:21:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:15.094  5726  5773 I jxcore-log: 
,09-28 10:21:15.174  5726  5773 I jxcore-log: # teardown
09-28 10:21:15.174  5726  5773 I jxcore-log: 
,09-28 10:21:15.235  5726  5773 I jxcore-log: # setup
09-28 10:21:15.235  5726  5773 I jxcore-log: 
,09-28 10:21:15.264   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:15.839   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:21:16.265   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:17.193  5726  5773 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-28 10:21:17.193  5726  5773 I jxcore-log: 
,09-28 10:21:17.266   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:17.376  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:17.376  5726  5773 I jxcore-log: 
,09-28 10:21:17.383  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'listening 49074'
09-28 10:21:17.383  5726  5773 I jxcore-log: 
,09-28 10:21:17.393  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:17.393  5726  5773 I jxcore-log: 
,09-28 10:21:17.394  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:17.394  5726  5773 I jxcore-log: 
,09-28 10:21:17.396  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'new mux'
09-28 10:21:17.396  5726  5773 I jxcore-log: 
,09-28 10:21:17.404  5726  5773 I jxcore-log: ok 31 we should not have gotten an error
09-28 10:21:17.404  5726  5773 I jxcore-log: 
,09-28 10:21:17.412  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:17.412  5726  5773 I jxcore-log: 
,09-28 10:21:17.414  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:17.414  5726  5773 I jxcore-log: 
,09-28 10:21:17.421  5726  5773 I jxcore-log: ok 32 Buffers are identical
09-28 10:21:17.421  5726  5773 I jxcore-log: 
,09-28 10:21:17.422  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:17.422  5726  5773 I jxcore-log: 
09-28 10:21:17.424  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'mux close'
09-28 10:21:17.424  5726  5773 I jxcore-log: 
,09-28 10:21:17.434  5726  5773 I jxcore-log: 2016-09-28 14:21:17 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:17.434  5726  5773 I jxcore-log: 
,09-28 10:21:17.435  5726  5773 I jxcore-log: ok 33 server should be fine
09-28 10:21:17.435  5726  5773 I jxcore-log: 
09-28 10:21:17.435  5726  5773 I jxcore-log: ok 34 server should be open
09-28 10:21:17.435  5726  5773 I jxcore-log: 
09-28 10:21:17.436  5726  5773 I jxcore-log: ok 35 incoming has been removed
09-28 10:21:17.436  5726  5773 I jxcore-log: 
09-28 10:21:17.436  5726  5773 I jxcore-log: ok 36 The mux object should be closed
09-28 10:21:17.436  5726  5773 I jxcore-log: 
09-28 10:21:17.436  5726  5773 I jxcore-log: ok 37 The mux stream should be closed
09-28 10:21:17.436  5726  5773 I jxcore-log: 
,09-28 10:21:17.439  5726  5773 I jxcore-log: # teardown
09-28 10:21:17.439  5726  5773 I jxcore-log: 
,09-28 10:21:18.266   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 10:21:18.429  5726  5773 I jxcore-log: # setup
09-28 10:21:18.429  5726  5773 I jxcore-log: 
,09-28 10:21:18.597  5726  5773 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-28 10:21:18.597  5726  5773 I jxcore-log: 
,09-28 10:21:18.671  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'creating native server'
09-28 10:21:18.671  5726  5773 I jxcore-log: 
,09-28 10:21:18.675  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'listening 46565'
09-28 10:21:18.675  5726  5773 I jxcore-log: 
,09-28 10:21:18.684  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'new incoming socket'
09-28 10:21:18.684  5726  5773 I jxcore-log: 
,09-28 10:21:18.686  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'creating incoming mux'
09-28 10:21:18.686  5726  5773 I jxcore-log: 
09-28 10:21:18.688  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'new mux'
09-28 10:21:18.688  5726  5773 I jxcore-log: 
,09-28 10:21:18.696  5726  5773 I jxcore-log: ok 38 we should not have gotten an error
09-28 10:21:18.696  5726  5773 I jxcore-log: 
,09-28 10:21:18.704  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'new stream: '
09-28 10:21:18.704  5726  5773 I jxcore-log: 
,09-28 10:21:18.707  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'new outgoing socket'
09-28 10:21:18.707  5726  5773 I jxcore-log: 
,09-28 10:21:18.714  5726  5773 I jxcore-log: ok 39 Buffers are identical
09-28 10:21:18.714  5726  5773 I jxcore-log: 
,09-28 10:21:18.718  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'incoming socket timeout'
09-28 10:21:18.718  5726  5773 I jxcore-log: 
,09-28 10:21:18.719  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'stream close:'
09-28 10:21:18.719  5726  5773 I jxcore-log: 
,09-28 10:21:18.720  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'mux close'
09-28 10:21:18.720  5726  5773 I jxcore-log: 
,09-28 10:21:18.725  5726  5773 I jxcore-log: 2016-09-28 14:21:18 - DEBUG createNativeListener: 'incoming socket close'
09-28 10:21:18.725  5726  5773 I jxcore-log: 
,09-28 10:21:18.725  5726  5773 I jxcore-log: ok 40 server should be fine
09-28 10:21:18.725  5726  5773 I jxcore-log: 
09-28 10:21:18.725  5726  5773 I jxcore-log: ok 41 server should be open
09-28 10:21:18.725  5726  5773 I jxcore-log: 
09-28 10:21:18.726  5726  5773 I jxcore-log: ok 42 incoming has been removed
09-28 10:21:18.726  5726  5773 I jxcore-log: 
09-28 10:21:18.726  5726  5773 I jxcore-log: ok 43 The mux object should be closed
09-28 10:21:18.726  5726  5773 I jxcore-log: 
09-28 10:21:18.726  5726  5773 I jxcore-log: ok 44 The mux stream should be closed
09-28 10:21:18.726  5726  5773 I jxcore-log: 
,09-28 10:21:18.731  5726  5773 I jxcore-log: # teardown
09-28 10:21:18.731  5726  5773 I jxcore-log: 
,09-28 10:21:18.784  5726  5773 I jxcore-log: # setup
09-28 10:21:18.784  5726  5773 I jxcore-log: 
,09-28 10:21:18.838  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-28 10:21:18.838  5726  5773 I jxcore-log: 
,09-28 10:21:19.029  5726  5773 I jxcore-log: 2016-09-28 14:21:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-28 10:21:19.029  5726  5773 I jxcore-log: 
,09-28 10:21:19.030  5726  5773 I jxcore-log: ok 45 Got right error
09-28 10:21:19.030  5726  5773 I jxcore-log: 
,09-28 10:21:19.034  5726  5773 I jxcore-log: # teardown
09-28 10:21:19.034  5726  5773 I jxcore-log: 
,09-28 10:21:19.106  5726  5773 I jxcore-log: # setup
09-28 10:21:19.106  5726  5773 I jxcore-log: 
,09-28 10:21:19.156  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-28 10:21:19.156  5726  5773 I jxcore-log: 
,09-28 10:21:19.294  5726  5773 I jxcore-log: 2016-09-28 14:21:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-28 10:21:19.294  5726  5773 I jxcore-log: 
,09-28 10:21:19.295  5726  5773 I jxcore-log: ok 46 Got socket hang up
09-28 10:21:19.295  5726  5773 I jxcore-log: 
,09-28 10:21:19.299  5726  5773 I jxcore-log: # teardown
09-28 10:21:19.299  5726  5773 I jxcore-log: 
,09-28 10:21:19.335  5726  5773 I jxcore-log: # setup
09-28 10:21:19.335  5726  5773 I jxcore-log: 
,09-28 10:21:19.423  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-28 10:21:19.423  5726  5773 I jxcore-log: 
,09-28 10:21:19.570  5726  5773 I jxcore-log: 2016-09-28 14:21:19 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-28 10:21:19.570  5726  5773 I jxcore-log: 
,09-28 10:21:19.571  5726  5773 I jxcore-log: ok 47 Got 500 as expected
09-28 10:21:19.571  5726  5773 I jxcore-log: 
,09-28 10:21:19.574  5726  5773 I jxcore-log: # teardown
09-28 10:21:19.574  5726  5773 I jxcore-log: 
,09-28 10:21:19.633  5726  5773 I jxcore-log: # setup
09-28 10:21:19.633  5726  5773 I jxcore-log: 
,09-28 10:21:19.696  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-28 10:21:19.696  5726  5773 I jxcore-log: 
,09-28 10:21:21.157  5726  5773 I jxcore-log: ok 48 should be equal
09-28 10:21:21.157  5726  5773 I jxcore-log: 
,09-28 10:21:21.157  5726  5773 I jxcore-log: ok 49 revs are equal
09-28 10:21:21.157  5726  5773 I jxcore-log: 
,09-28 10:21:21.161  5726  5773 I jxcore-log: # teardown
09-28 10:21:21.161  5726  5773 I jxcore-log: 
,09-28 10:21:21.239  5726  5773 I jxcore-log: # setup
09-28 10:21:21.239  5726  5773 I jxcore-log: 
,09-28 10:21:22.217  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-28 10:21:22.217  5726  5773 I jxcore-log: 
,09-28 10:21:23.049  5726  5773 I jxcore-log: ok 50 should be equal
09-28 10:21:23.049  5726  5773 I jxcore-log: 
,09-28 10:21:23.050  5726  5773 I jxcore-log: ok 51 revs are equal
09-28 10:21:23.050  5726  5773 I jxcore-log: 
,09-28 10:21:23.056  5726  5773 I jxcore-log: # teardown
09-28 10:21:23.056  5726  5773 I jxcore-log: 
,09-28 10:21:23.267   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:23.270  5726  5773 I jxcore-log: # setup
09-28 10:21:23.270  5726  5773 I jxcore-log: 
,09-28 10:21:23.336  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-28 10:21:23.336  5726  5773 I jxcore-log: 
,09-28 10:21:23.925  5726  5773 I jxcore-log: ok 52 should be equal
09-28 10:21:23.925  5726  5773 I jxcore-log: 
,09-28 10:21:23.926  5726  5773 I jxcore-log: ok 53 revs are equal
09-28 10:21:23.926  5726  5773 I jxcore-log: 
,09-28 10:21:24.036  5726  5773 I jxcore-log: ok 54 should be equal
09-28 10:21:24.036  5726  5773 I jxcore-log: 
,09-28 10:21:24.037  5726  5773 I jxcore-log: ok 55 revs are equal
09-28 10:21:24.037  5726  5773 I jxcore-log: 
,09-28 10:21:24.152  5726  5773 I jxcore-log: ok 56 should be equal
09-28 10:21:24.152  5726  5773 I jxcore-log: 
,09-28 10:21:24.153  5726  5773 I jxcore-log: ok 57 revs are equal
09-28 10:21:24.153  5726  5773 I jxcore-log: 
,09-28 10:21:24.158  5726  5773 I jxcore-log: # teardown
09-28 10:21:24.158  5726  5773 I jxcore-log: 
,09-28 10:21:24.268   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:25.269   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:26.271   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:27.272   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:28.088  5726  5773 I jxcore-log: # setup
09-28 10:21:28.088  5726  5773 I jxcore-log: 
,09-28 10:21:28.141  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-28 10:21:28.141  5726  5773 I jxcore-log: 
,09-28 10:21:28.273   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 10:21:28.806  5726  5773 I jxcore-log: 2016-09-28 14:21:28 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-28 10:21:28.806  5726  5773 I jxcore-log: 
,09-28 10:21:28.808  5726  5773 I jxcore-log: ok 58 Our rev is old so we should fail
09-28 10:21:28.808  5726  5773 I jxcore-log: 
,09-28 10:21:28.812  5726  5773 I jxcore-log: # teardown
09-28 10:21:28.812  5726  5773 I jxcore-log: 
,09-28 10:21:28.869  5726  5773 I jxcore-log: # setup
09-28 10:21:28.869  5726  5773 I jxcore-log: 
,09-28 10:21:28.949  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-28 10:21:28.949  5726  5773 I jxcore-log: 
,09-28 10:21:29.045  5726  5773 I jxcore-log: ok 59 confirm stop caused failure
09-28 10:21:29.045  5726  5773 I jxcore-log: 
,09-28 10:21:29.060  5726  5773 I jxcore-log: # teardown
09-28 10:21:29.060  5726  5773 I jxcore-log: 
,09-28 10:21:29.105  5726  5773 I jxcore-log: # setup
09-28 10:21:29.105  5726  5773 I jxcore-log: 
,09-28 10:21:29.169  5726  5773 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-28 10:21:29.169  5726  5773 I jxcore-log: 
,09-28 10:21:29.493  5726  5773 I jxcore-log: 2016-09-28 14:21:29 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-28 10:21:29.493  5726  5773 I jxcore-log: 
,09-28 10:21:29.495  5726  5773 I jxcore-log: ok 60 stop caused us to fail
09-28 10:21:29.495  5726  5773 I jxcore-log: 
09-28 10:21:29.495  5726  5773 I jxcore-log: ok 61 We specifically failed on a stop before put
09-28 10:21:29.495  5726  5773 I jxcore-log: 
,09-28 10:21:29.501  5726  5773 I jxcore-log: # teardown
09-28 10:21:29.501  5726  5773 I jxcore-log: 
,09-28 10:21:29.587  5726  5773 I jxcore-log: # setup
09-28 10:21:29.587  5726  5773 I jxcore-log: 
,09-28 10:21:29.689  5726  5773 I jxcore-log: # #update - fail if stop is called
09-28 10:21:29.689  5726  5773 I jxcore-log: 
,09-28 10:21:29.788  5726  5773 I jxcore-log: ok 62 failed due to stop
09-28 10:21:29.788  5726  5773 I jxcore-log: 
,09-28 10:21:29.791  5726  5773 I jxcore-log: ok 63 failed due to stop
09-28 10:21:29.791  5726  5773 I jxcore-log: 
,09-28 10:21:29.805  5726  5773 I jxcore-log: # teardown
09-28 10:21:29.805  5726  5773 I jxcore-log: 
,09-28 10:21:29.867  5726  5773 I jxcore-log: # setup
09-28 10:21:29.867  5726  5773 I jxcore-log: 
,09-28 10:21:30.089  5726  5773 I jxcore-log: # #update - set seq for first time
09-28 10:21:30.089  5726  5773 I jxcore-log: 
,09-28 10:21:30.650  5726  5773 I jxcore-log: ok 64 should be equal
09-28 10:21:30.650  5726  5773 I jxcore-log: 
,09-28 10:21:30.656  5726  5773 I jxcore-log: # teardown
09-28 10:21:30.656  5726  5773 I jxcore-log: 
,09-28 10:21:30.711  5726  5773 I jxcore-log: # setup
09-28 10:21:30.711  5726  5773 I jxcore-log: 
,09-28 10:21:30.802  5726  5773 I jxcore-log: # #update - Fail on bad seq value
09-28 10:21:30.802  5726  5773 I jxcore-log: 
,09-28 10:21:31.247  5726  5773 I jxcore-log: 2016-09-28 14:21:31 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-28 10:21:31.247  5726  5773 I jxcore-log: 
,09-28 10:21:31.249  5726  5773 I jxcore-log: ok 65 Expected bad seq error
09-28 10:21:31.249  5726  5773 I jxcore-log: 
09-28 10:21:31.252  5726  5773 I jxcore-log: # teardown
09-28 10:21:31.252  5726  5773 I jxcore-log: 
,09-28 10:21:31.316  5726  5773 I jxcore-log: # setup
09-28 10:21:31.316  5726  5773 I jxcore-log: 
,09-28 10:21:31.411  5726  5773 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-28 10:21:31.411  5726  5773 I jxcore-log: 
,09-28 10:21:31.886  5726  5773 I jxcore-log: ok 66 Different promises
09-28 10:21:31.886  5726  5773 I jxcore-log: 
,09-28 10:21:31.888  5726  5773 I jxcore-log: ok 67 Timer was cancelled
09-28 10:21:31.888  5726  5773 I jxcore-log: 
,09-28 10:21:32.029  5726  5773 I jxcore-log: ok 68 should be equal
09-28 10:21:32.029  5726  5773 I jxcore-log: 
,09-28 10:21:32.035  5726  5773 I jxcore-log: # teardown
09-28 10:21:32.035  5726  5773 I jxcore-log: 
,09-28 10:21:35.842   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:21:38.274   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:39.276   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:40.277   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:41.279   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:42.280   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:43.281   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 10:21:58.283   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:21:59.284   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:00.285   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:01.286   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:02.288   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:03.288   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 10:22:15.844   927  3039 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:22:23.290   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:24.291   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:25.292   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:26.294   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:27.295   543   543 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:22:28.296   543   543 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 10:22:32.424  5726  5773 I jxcore-log: 2016-09-28 14:22:32 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-28 10:22:32.424  5726  5773 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 10:22:32.424  5726  5773 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 10:22:32.424  5726  5773 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 10:22:32.424  5726  5773 I jxcore-log:     at $9@timers.js:120:1
09-28 10:22:32.424  5726  5773 I jxcore-log: ''
09-28 10:22:32.424  5726  5773 I jxcore-log: 
,09-28 10:22:32.425  5726  5773 I jxcore-log: 2016-09-28 14:22:32 - DEBUG CoordinatedClient: 'test client failed'
09-28 10:22:32.425  5726  5773 I jxcore-log: 
,09-28 10:22:32.427  5726  5773 I jxcore-log: 2016-09-28 14:22:32 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-28 10:22:32.427  5726  5773 I jxcore-log: 
,09-28 10:22:32.429  5726  5773 I jxcore-log: 2016-09-28 14:22:32 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-28 10:22:32.429  5726  5773 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 10:22:32.429  5726  5773 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 10:22:32.429  5726  5773 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 10:22:32.429  5726  5773 I jxcore-log:     at $9@timers.js:120:1
09-28 10:22:32.429  5726  5773 I jxcore-log: ''
09-28 10:22:32.429  5726  5773 I jxcore-log: 
09-28 10:22:32.429  5726  5773 I jxcore-log: 2016-09-28 14:22:32 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-28 10:22:32.429  5726  5773 I jxcore-log: 
,09-28 10:22:33.043  6148  6148 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-28 10:22:33.065  6148  6148 D AndroidRuntime: CheckJNI is OFF
,09-28 10:22:33.095  6148  6148 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-28 10:22:33.132  6148  6148 I Radio-JNI: register_android_hardware_Radio DONE
,09-28 10:22:33.151  6148  6148 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-28 10:22:33.162   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-28 10:22:33.163   927   940 I ActivityManager: Killing 5726:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-28 10:22:33.282   927  3864 D GraphicsStats: Buffer count: 2
,09-28 10:22:33.282   927  3477 I WindowState: WIN DEATH: Window{9abfbcd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-28 10:22:33.282   927  3040 D WifiService: Client connection lost with reason: 4
,09-28 10:22:33.322   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-28 10:22:33.323   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-28 10:22:33.324   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-28 10:22:33.324   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-28 10:22:33.324   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:22:33.324   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.324   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:22:33.324   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 10:22:33.326   927   940 I ActivityManager:   Force finishing activity ActivityRecord{7fd4596 u0 com.test.thalitest/.MainActivity t2}
09-28 10:22:33.326   927   950 I art     : Starting a blocking GC Explicit
,09-28 10:22:33.336   927  3882 W ActivityManager: Spurious death for ProcessRecord{8f0368f 0:com.test.thalitest/u0a77}, curProc for 5726: null
,09-28 10:22:33.342   927   945 W WindowManager: Attempted to add application window with unknown token Token{a0e8517 ActivityRecord{7fd4596 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-28 10:22:33.343   927   945 W WindowManager: Token{a0e8517 ActivityRecord{7fd4596 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{a0e8517 ActivityRecord{7fd4596 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-28 10:22:33.343   927   945 W WindowManager: view not successfully added to wm, removing view
09-28 10:22:33.343   927   945 W WindowManager: Exception when adding starting window
09-28 10:22:33.343   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{da9d0c6 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-28 10:22:33.343   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-28 10:22:33.343   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-28 10:22:33.343   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-28 10:22:33.343   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-28 10:22:33.343   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-28 10:22:33.343   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:22:33.343   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.343   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:22:33.343   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 10:22:33.418   927   950 I art     : Explicit concurrent mark sweep GC freed 86873(6MB) AllocSpace objects, 42(1692KB) LOS objects, 33% free, 29MB/43MB, paused 1.685ms total 91.718ms
,09-28 10:22:33.441   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-28 10:22:33.444  6148  6148 I art     : System.exit called, status: 0
,09-28 10:22:33.444  6148  6148 I AndroidRuntime: VM exiting with result code 0.
,09-28 10:22:33.462   927   950 I ActivityManager: Start proc 6158:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-28 10:22:33.462   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-28 10:22:33.466   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-28 10:22:33.469  6022  6022 D BluetoothMapAppObserver: onReceive
,09-28 10:22:33.469  6022  6022 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-28 10:22:33.475   927  3030 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-28 10:22:33.477  3752  3752 I Keyboard.Facilitator: resetDictionaries() : en_US
09-28 10:22:33.484  3789  4170 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-28 10:22:33.502  3856  3856 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-28 10:22:33.504  3459  6171 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-28 10:22:33.505  3752  6170 I Keyboard.Facilitator.DecoderInitializer: run()
,09-28 10:22:33.518  3752  6170 I Decoder : createOrResetDecoder
,09-28 10:22:33.532    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:22:33.542    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:22:33.550   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-28 10:22:33.561  3644  3644 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-28 10:22:33.558    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-28 10:22:33.562  3644  3644 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-28 10:22:33.563  3644  3644 E AndroidRuntime: FATAL EXCEPTION: main
09-28 10:22:33.563  3644  3644 E AndroidRuntime: Process: com.google.process.gapps, PID: 3644
09-28 10:22:33.563  3644  3644 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-28 10:22:33.563  3644  3644 E AndroidRuntime: 	... 8 more
,09-28 10:22:33.567  3459  3490 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,09-28 10:22:33.567  3459  3490 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjB66822981) - 
09-28 10:22:33.568  3459  3490 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-28 10:22:33.568  3459  3490 E AndroidRuntime: Process: android.process.acore, PID: 3459
09-28 10:22:33.568  3459  3490 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.568  3459  3490 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 10:22:33.594   927  6177 E DropBoxManagerService: Can't write: system_app_crash
09-28 10:22:33.594   927  6177 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:22:33.594   927  6177 E DropBoxManagerService: 	... 5 more
,09-28 10:22:33.597  3459  6171 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-28 10:22:33.597  3459  6171 I Process : Sending signal. PID: 3459 SIG: 9
09-28 10:22:33.598  3644  3644 I Process : Sending signal. PID: 3644 SIG: 9
09-28 10:22:33.599   927  6178 E DropBoxManagerService: Can't write: system_app_crash
09-28 10:22:33.599   927  6178 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:22:33.599   927  6178 E DropBoxManagerService: 	... 5 more
09-28 10:22:33.601  3894  4006 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-28 10:22:33.601   927   939 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-28 10:22:33.602   927   939 E PackageManager: Failed to write settings, restoring backup
09-28 10:22:33.602   927   939 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-28 10:22:33.602   927   939 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-28 10:22:33.602   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-28 10:22:33.602   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-28 10:22:33.602   927   939 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-28 10:22:33.602   927   939 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:22:33.602   927   939 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.602   927   939 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:22:33.604   927   940 E DropBoxManagerService: Can't write: system_server_wtf
09-28 10:22:33.604   927   940 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-28 10:22:33.604   927   940 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:22:33.604   927   940 E DropBoxManagerService: 	... 13 more
,09-28 10:22:33.615   927  3476 I ActivityManager: Start proc 6179:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-28 10:22:33.616  3894  4006 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-28 10:22:33.616  3894  4006 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3894
09-28 10:22:33.616  3894  4006 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:22:33.616  3894  4006 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 10:22:33.619   927   938 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-28 10:22:33.620   927  6186 E DropBoxManagerService: Can't write: system_app_crash
09-28 10:22:33.620   927  6186 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:22:33.620   927  6186 E DropBoxManagerService: 	... 5 more
,09-28 10:22:33.623  3894  4006 I Process : Sending signal. PID: 3894 SIG: 9
,09-28 10:22:33.632   927  3040 D WifiService: Client connection lost with reason: 4
,09-28 10:22:33.637   927   938 I ActivityManager: Process com.google.process.gapps (pid 3644) has died
09-28 10:22:33.638   927   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-28 10:22:33.638   927   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
09-28 10:22:33.638   927   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-28 10:22:33.638   927   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,09-28 10:22:33.659   927  3292 I ActivityManager: Start proc 6193:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-28 10:22:33.682   927  3220 D GraphicsStats: Buffer count: 1
,09-28 10:22:33.682   927   938 I WindowState: WIN DEATH: Window{4eae4d7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-28 10:22:33.688   927  3220 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3894) has died
09-28 10:22:33.688   927  3220 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-28 10:22:33.689   927  3220 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-28 10:22:33.708   927   940 I ActivityManager: Start proc 6205:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-28 10:22:33.722   927  3835 I ActivityManager: Process android.process.acore (pid 3459) has died
09-28 10:22:33.722   927  3835 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-28 10:22:33.931   381   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
