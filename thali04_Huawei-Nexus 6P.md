#### Test 83627337176b608_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 10:30:50.110   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 10:30:50.110   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 10:30:50.626  5362  5362 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 10:30:50.631  5362  5362 D AndroidRuntime: CheckJNI is OFF
09-15 10:30:50.660  5362  5362 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 10:30:50.707  5362  5362 I Radio-JNI: register_android_hardware_Radio DONE
09-15 10:30:50.722  5362  5362 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 10:30:50.735   929  3732 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 10:30:50.778   929  3732 I ActivityManager: Start proc 5371:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 10:30:50.783  5362  5362 D AndroidRuntime: Shutting down VM
09-15 10:30:50.879  5371  5371 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 10:30:50.911  5371  5371 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 10:30:50.942  5371  5371 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 9846-9866)
09-15 10:30:50.942  5371  5371 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 10:30:50.961  5371  5371 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79b3b69}
09-15 10:30:50.961  5371  5371 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 10:30:50.961  5371  5371 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 10:30:50.967  5371  5371 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 10:30:50.968  5371  5371 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-15 10:30:51.010  5371  5371 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-15 10:30:51.024  5371  5371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-15 10:30:51.024  5371  5371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 10:30:51.024  5371  5371 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 10:30:51.024  5371  5371 I Adreno  : Build Date                       : 12/06/15
09-15 10:30:51.024  5371  5371 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 10:30:51.024  5371  5371 I Adreno  : Local Branch                     : mybranch17112971
09-15 10:30:51.024  5371  5371 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 10:30:51.024  5371  5371 I Adreno  : Remote Branch                    : NONE
09-15 10:30:51.024  5371  5371 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 10:30:51.093   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cf2285b:true
,09-15 10:30:51.134   732   732 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31476]" dev="sockfs" ino=31476 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:30:51.134   732   732 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31476]" dev="sockfs" ino=31476 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:30:51.153  5371  5371 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 10:30:51.163  5371  5371 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 10:30:51.250   732   732 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32048]" dev="sockfs" ino=32048 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:30:51.253  5371  5408 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-15 10:30:51.250   732   732 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32048]" dev="sockfs" ino=32048 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 10:30:51.254  3497  3497 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[29327]" dev="sockfs" ino=29327 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 10:30:51.254  3497  3497 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[29327]" dev="sockfs" ino=29327 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 10:30:51.263  5371  5395 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 10:30:51.304  5371  5408 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 10:30:51.378   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms (total +629ms)
,09-15 10:30:51.400  5371  5371 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5371
,09-15 10:30:51.481  5371  5371 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 10:30:51.604  5371  5411 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -583263952
,09-15 10:30:51.609  5371  5411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 10:30:51.609  5371  5411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 10:30:51.609  5371  5411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 10:30:51.609  5371  5411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 10:30:51.609  5371  5411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-15 10:30:51.609  5371  5411 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@560bb86 added. We now have 1 listener(s)
09-15 10:30:51.612  5371  5411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-15 10:30:51.612  5371  5411 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:30:51.613  5371  5411 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:30:51.613  5371  5411 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 10:30:51.615  5371  5411 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8d259d added. We now have 1 listener(s)
09-15 10:30:51.615  5371  5411 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:30:51.622   929  2960 D WifiService: New client listening to asynchronous messages
,09-15 10:30:51.622  5371  5411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:30:51.622  5371  5411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 10:30:51.622  5371  5411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-15 10:30:51.622  5371  5411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-15 10:30:51.622  5371  5411 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-15 10:30:51.624  5371  5411 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:30:51.624  5371  5411 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-15 10:30:51.629  5371  5411 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:30:51.629  5371  5411 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:30:51.629  5371  5411 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 10:30:51.629  5371  5411 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:30:51.630  5371  5411 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 10:30:51.635  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:30:51.641  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:30:51.645  5371  5371 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 10:30:51.954  5371  5417 W jxcore-log: Initializing JXcore engine
09-15 10:30:51.954  5371  5417 W jxcore-log: JXcore engine is ready
,09-15 10:30:51.977  5417  5417 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12601 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-15 10:30:51.977  5417  5417 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[16402]" dev="sockfs" ino=16402 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-15 10:30:51.977  5417  5417 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-15 10:30:51.977  5417  5417 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31462]" dev="sockfs" ino=31462 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 10:30:51.987  5371  5417 W jxcore-log: Starting JXcore engine
,09-15 10:30:52.036  5371  5417 W jxcore-log: Platform android
09-15 10:30:52.036  5371  5417 W jxcore-log: 
,09-15 10:30:52.036  5371  5417 W jxcore-log: Process ARCH arm
09-15 10:30:52.036  5371  5417 W jxcore-log: 
,09-15 10:30:52.131  5371  5417 I jxcore-log: JXcore Cordova bridge is ready!
09-15 10:30:52.131  5371  5417 I jxcore-log: 
09-15 10:30:52.131  5371  5417 W jxcore-log: JXcore engine is started
,09-15 10:30:52.135  5371  5411 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 10:30:52.139  5371  5371 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 10:30:53.794   929  5124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222716, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 10:30:58.827  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 10:30:58.827  5371  5417 I jxcore-log: 
,09-15 10:30:58.829  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 10:30:58.829  5371  5417 I jxcore-log: 
,09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:30:58.833  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:30:58.834  5371  5417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 10:30:58.836  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 10:30:58.836  5371  5417 I jxcore-log: 
,09-15 10:30:58.837  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 10:30:58.837  5371  5417 I jxcore-log: 
,09-15 10:30:59.189  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 10:30:59.189  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3cbeb2 added. We now have 2 listener(s)
09-15 10:30:59.190  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:30:59.190  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:30:59.190  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:30:59.190  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:30:59.190  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a39e03 added. We now have 2 listener(s)
09-15 10:30:59.190  5371  5417 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:30:59.191  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 10:30:59.192  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:30:59.195  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:30:59.196  5371  5417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:30:59.197  5371  5417 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 10:30:59.197  5371  5417 D ExecuteNativeTests: Running unit tests
09-15 10:30:59.198  5371  5417 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 10:30:59.198   929  3587 D WifiService: setWifiEnabled: true pid=5371, uid=10077
09-15 10:30:59.198   929  3587 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:30:59.202  5371  5417 I System.out: Running UT
,09-15 10:30:59.203  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:30:59.209  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:00.112   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:01.113   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:02.114   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:03.116   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:04.117   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:05.118   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 10:31:09.272  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 10:31:09.272  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f03fd29 added. We now have 3 listener(s)
,09-15 10:31:09.273  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:31:09.273  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 10:31:09.273  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:31:09.273  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 10:31:09.274  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28b78ae added. We now have 3 listener(s)
09-15 10:31:09.274  5371  5417 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:31:09.275  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:31:09.277  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:31:09.282  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 10:31:09.283  5371  5417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:31:09.283  5371  5417 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:31:09.288  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-15 10:31:09.288  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-15 10:31:09.288  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:09.288  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:09.290  5371  5417 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 10:31:09.290  5371  5417 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 10:31:09.290  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 10:31:09.290  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:09.290  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:09.290  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:09.292  5371  5417 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 10:31:09.292  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:09.294  5371  5417 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-15 10:31:09.299  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:09.300  5371  5417 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 10:31:09.300  5371  5417 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-15 10:31:09.300  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-15 10:31:09.300  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:09.301  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 10:31:09.301  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 10:31:09.301  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:09.301  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 10:31:09.302  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:31:09.302  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:31:09.302  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-15 10:31:09.302  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-15 10:31:09.302  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:09.302  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:31:09.303  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-15 10:31:09.304  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:31:09.305  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 10:31:09.306  5371  5419 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:31:09.304  4589  4589 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[27377]" dev="sockfs" ino=27377 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:31:09.308  5371  5419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-15 10:31:09.308  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:31:09.304  4589  4589 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[27377]" dev="sockfs" ino=27377 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:09.309  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:31:09.309  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:31:09.310  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 10:31:09.310  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:31:09.311  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-15 10:31:09.311  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:09.311  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:09.311  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-15 10:31:09.312  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:09.314  4372  4598 D BtGatt.GattService: registerClient() - UUID=b1eb275b-cfd1-4854-b35c-090207865e84
,09-15 10:31:09.316  4372  4439 D BtGatt.GattService: onClientRegistered() - UUID=b1eb275b-cfd1-4854-b35c-090207865e84, clientIf=5
,09-15 10:31:09.318  5371  5382 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-15 10:31:09.321  4372  4458 D BtGatt.AdvertiseManager: message : 0
,09-15 10:31:09.324  4372  4458 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:31:09.338  4372  4439 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:31:09.347  4372  4439 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:31:09.348  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-15 10:31:09.348  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 10:31:09.349  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:31:09.350  5371  5417 I io.jxcore.node.ConnectionHelper: start: OK
09-15 10:31:09.350  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-15 10:31:09.351  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:31:09.351  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:31:09.351  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 10:31:09.351  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 10:31:09.351  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-15 10:31:09.354  5371  5371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 10:31:09.355  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:09.854  5371  5417 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 10:31:09.854  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 10:31:09.854  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 10:31:09.854  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 10:31:09.854  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-15 10:31:09.854  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 10:31:09.855  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 10:31:09.856  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 10:31:09.856  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 10:31:09.857  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 10:31:09.857  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 10:31:09.857  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 10:31:09.859  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-15 10:31:09.859  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 10:31:09.860  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 10:31:09.860  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:31:09.860  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 10:31:09.861  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:31:09.861  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 10:31:09.861  5371  5419 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:31:09.861  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:31:09.862  5371  5419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:31:09.862  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 10:31:09.862  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:31:09.862  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:31:09.862  5371  5419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 10:31:09.862  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:31:09.863  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 10:31:09.865  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:09.865  5371  5417 D BluetoothLeScanner: could not find callback wrapper
09-15 10:31:09.865  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:31:09.866  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 10:31:09.868  4372  4458 D BtGatt.AdvertiseManager: message : 1
09-15 10:31:09.869  4372  4458 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 10:31:09.880  4372  4439 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-15 10:31:09.880  4372  4439 D BtGatt.GattService: Client app is not null!
,09-15 10:31:09.881  4372  4597 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 10:31:09.882  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 10:31:09.882  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 10:31:09.882  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 10:31:09.882  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 10:31:09.882  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 10:31:09.884  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:09.885  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 10:31:09.885  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:31:09.886  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 10:31:09.888  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:31:09.888  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 10:31:09.888  5371  5371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:31:09.889  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 10:31:09.889  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:09.889  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:09.890  5371  5417 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-15 10:31:09.890  5371  5417 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 10:31:09.890  5371  5417 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-15 10:31:09.890  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-15 10:31:09.891  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:09.891  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 10:31:09.891  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 10:31:09.891  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:09.893  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 10:31:09.893  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-15 10:31:09.894  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:31:09.894  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 10:31:09.894  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 10:31:09.894  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 10:31:09.894  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:09.894  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:31:09.896  5371  5422 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:09.894  4589  4589 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29343]" dev="sockfs" ino=29343 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:31:09.894  4589  4589 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29343]" dev="sockfs" ino=29343 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:31:09.899  5371  5422 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 10:31:09.901  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:31:09.901  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 10:31:09.906  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:31:09.907  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 10:31:09.908  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 10:31:09.911  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-15 10:31:09.911  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:31:09.911  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-15 10:31:09.911  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-15 10:31:09.911  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:09.912  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 10:31:09.913  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:09.916  4372  4387 D BtGatt.GattService: registerClient() - UUID=338add47-6f90-496e-9771-3063f02220eb
,09-15 10:31:09.917  4372  4439 D BtGatt.GattService: onClientRegistered() - UUID=338add47-6f90-496e-9771-3063f02220eb, clientIf=5
09-15 10:31:09.917  5371  5382 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 10:31:09.918  4372  4458 D BtGatt.AdvertiseManager: message : 0
,09-15 10:31:09.921  4372  4458 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:31:09.934  4372  4439 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:31:09.942  4372  4439 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:31:09.943  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 10:31:09.943  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 10:31:09.945  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:31:09.946  5371  5417 I io.jxcore.node.ConnectionHelper: start: OK
09-15 10:31:09.946  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:09.947  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:31:09.947  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:31:09.947  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 10:31:09.947  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-15 10:31:09.947  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-15 10:31:09.950  5371  5371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:09.950  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:10.120   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:10.451  5371  5417 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-15 10:31:10.452  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-15 10:31:10.452  5371  5417 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 10:31:10.452  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:31:10.452  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:31:10.453  5371  5417 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-15 10:31:10.453  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-15 10:31:10.454  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-15 10:31:10.456  4372  4458 D BtGatt.AdvertiseManager: message : 1
09-15 10:31:10.457  4372  4458 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 10:31:10.475  4372  4439 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 10:31:10.476  4372  4439 D BtGatt.GattService: Client app is not null!
,09-15 10:31:10.477  4372  4387 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 10:31:10.478  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:31:10.478  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 10:31:10.478  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:31:10.478  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 10:31:10.478  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:31:10.478  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-15 10:31:10.479  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:10.479  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:10.479  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 10:31:10.480  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:10.485  4372  4597 D BtGatt.GattService: registerClient() - UUID=deaf763c-9245-4ffa-bae9-aabebd444409
09-15 10:31:10.486  4372  4439 D BtGatt.GattService: onClientRegistered() - UUID=deaf763c-9245-4ffa-bae9-aabebd444409, clientIf=5
09-15 10:31:10.487  5371  5381 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 10:31:10.490  4372  4458 D BtGatt.AdvertiseManager: message : 0
,09-15 10:31:10.494  4372  4458 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:31:10.507  4372  4439 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:31:10.514  4372  4439 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:31:10.515  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 10:31:10.515  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:31:10.515  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:31:10.515  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:31:10.515  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 10:31:10.515  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-15 10:31:10.515  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:31:10.515  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 10:31:10.515  5371  5417 I io.jxcore.node.ConnectionHelper: start: OK
09-15 10:31:10.516  5371  5417 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 10:31:10.516  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-15 10:31:10.517  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 10:31:10.517  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 10:31:10.517  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:31:10.517  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 10:31:10.517  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:31:10.517  5371  5422 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:31:10.517  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 10:31:10.517  5371  5422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:31:10.517  5371  5422 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 10:31:10.517  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:31:10.517  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:31:10.517  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:31:10.517  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:31:10.517  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:31:10.517  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 10:31:10.518  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:10.518  5371  5417 D BluetoothLeScanner: could not find callback wrapper
09-15 10:31:10.518  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:31:10.518  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 10:31:10.519  4372  4458 D BtGatt.AdvertiseManager: message : 1
09-15 10:31:10.520  4372  4458 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 10:31:10.526  4372  4439 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 10:31:10.526  4372  4439 D BtGatt.GattService: Client app is not null!
09-15 10:31:10.527  4372  4589 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 10:31:10.528  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:31:10.528  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-15 10:31:10.528  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 10:31:10.528  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 10:31:10.528  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-15 10:31:10.529  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:10.529  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:31:10.529  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:31:10.530  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 10:31:10.531  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:31:10.531  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-15 10:31:10.531  5371  5371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-15 10:31:10.531  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:10.531  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:10.531  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:10.532  5371  5417 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-15 10:31:10.534  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 10:31:10.534  5371  5417 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 10:31:10.535  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-15 10:31:10.535  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:10.536  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:10.536  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:10.536  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 10:31:10.537  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-15 10:31:10.537  5371  5417 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 10:31:10.537  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 10:31:10.540  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:31:10.540  5371  5417 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 10:31:10.540  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 10:31:10.541  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-15 10:31:10.541  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 10:31:10.542  5371  5417 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 10:31:10.542  5371  5417 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 10:31:10.542  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:31:10.542  5371  5417 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 10:31:10.542  5371  5417 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 10:31:10.542  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:31:10.542  5371  5417 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 10:31:10.542  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 10:31:10.545  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 10:31:10.546  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-15 10:31:10.546  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 10:31:10.547  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 10:31:10.547  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 10:31:10.547  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 10:31:10.547  5371  5417 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 10:31:10.547  5371  5417 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-15 10:31:10.547  5371  5426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 157)
09-15 10:31:10.548  5371  5426 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-15 10:31:10.548  5371  5426 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:10.549  5371  5417 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 10:31:10.550  5371  5417 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 10:31:10.550  5371  5417 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 10:31:10.551  5371  5417 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 10:31:10.551  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 10:31:10.551  5371  5417 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 10:31:10.551  5371  5417 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 10:31:10.551  5371  5417 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 10:31:10.551  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-15 10:31:10.551  5371  5417 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-15 10:31:10.551  5371  5417 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-15 10:31:10.551  5371  5417 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 10:31:10.551  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 10:31:10.551  5371  5417 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 10:31:10.552  5371  5417 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-15 10:31:10.552  5371  5417 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-15 10:31:10.552  5371  5417 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-15 10:31:10.552  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-15 10:31:10.552  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:10.552  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 10:31:10.552  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 10:31:10.552  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:10.550  4598  4598 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33662]" dev="sockfs" ino=33662 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:31:10.550  4598  4598 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33662]" dev="sockfs" ino=33662 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:10.556  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 10:31:10.556  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:31:10.556  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:31:10.556  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 10:31:10.556  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 10:31:10.556  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-15 10:31:10.557  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:10.557  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:31:10.559  5371  5427 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:31:10.557  4387  4387 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32068]" dev="sockfs" ino=32068 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:10.557  4387  4387 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32068]" dev="sockfs" ino=32068 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:10.561  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 10:31:10.561  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 10:31:10.563  5371  5427 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-15 10:31:10.564  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:31:10.564  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:31:10.564  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 10:31:10.566  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 10:31:10.566  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:31:10.566  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-15 10:31:10.566  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:10.567  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:10.567  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-15 10:31:10.567  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:10.569  4372  4388 D BtGatt.GattService: registerClient() - UUID=ae39cfeb-4ac5-42e8-83e5-ac1c174af134
09-15 10:31:10.570  4372  4439 D BtGatt.GattService: onClientRegistered() - UUID=ae39cfeb-4ac5-42e8-83e5-ac1c174af134, clientIf=5
,09-15 10:31:10.570  5371  5381 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 10:31:10.571  4372  4458 D BtGatt.AdvertiseManager: message : 0
,09-15 10:31:10.573  4372  4458 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:31:10.582  4372  4439 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:31:10.588  4372  4439 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:31:10.589  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 10:31:10.589  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 10:31:10.590  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 10:31:10.591  5371  5417 I io.jxcore.node.ConnectionHelper: start: OK
09-15 10:31:10.591  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:10.591  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:31:10.591  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:31:10.591  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 10:31:10.591  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 10:31:10.591  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-15 10:31:10.594  5371  5371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:10.594  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:11.094  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:31:11.095  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-15 10:31:11.095  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:31:11.095  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 10:31:11.095  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-15 10:31:11.095  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-15 10:31:11.096  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 10:31:11.096  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:31:11.096  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:31:11.096  5371  5427 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:31:11.096  5371  5427 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-15 10:31:11.096  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-15 10:31:11.097  5371  5427 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 10:31:11.097  5371  5371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:31:11.099  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f03fd29 removed from the list
,09-15 10:31:11.099  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:31:11.100  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:31:11.100  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:31:11.100  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:31:11.100  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:31:11.102  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:11.102  5371  5429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 157
09-15 10:31:11.102  5371  5417 D BluetoothLeScanner: could not find callback wrapper
09-15 10:31:11.102  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 10:31:11.103  5371  5429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 157)
09-15 10:31:11.103  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 10:31:11.103  4372  4587 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-15 10:31:11.103  5371  5429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 157)
,09-15 10:31:11.103  5371  5426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 157)
09-15 10:31:11.105  4372  4458 D BtGatt.AdvertiseManager: message : 1
09-15 10:31:11.106  4372  4458 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 10:31:11.117  4372  4439 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 10:31:11.117  4372  4439 D BtGatt.GattService: Client app is not null!
09-15 10:31:11.118  4372  4598 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 10:31:11.119  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 10:31:11.119  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 10:31:11.119  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 10:31:11.119  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 10:31:11.119  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 10:31:11.120   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:11.121  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:11.121  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:31:11.121  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 10:31:11.122  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:31:11.123  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28b78ae removed from the list
,09-15 10:31:11.123  5371  5417 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:31:11.123  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:31:11.124  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:11.124  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:11.124  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:11.127  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 10:31:11.127  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:31:11.130  4598  4598 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29364]" dev="sockfs" ino=29364 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:11.130  4598  4598 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[29364]" dev="sockfs" ino=29364 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:11.130  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 10:31:11.130  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:31:11.130  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:31:11.131  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 10:31:11.131  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:31:11.131  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 10:31:11.131  5371  5431 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:31:11.133  5371  5417 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 10:31:11.133  5371  5417 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 10:31:11.133  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 10:31:11.133  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:11.133  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 10:31:11.134  5371  5431 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-15 10:31:11.145  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:31:11.146  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 10:31:11.146  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:31:11.146  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 10:31:11.146  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:31:11.146  5371  5431 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-15 10:31:11.146  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 10:31:11.146  5371  5431 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:31:11.146  5371  5431 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 10:31:11.146  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:31:11.146  5371  5371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:31:11.147  5371  5417 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f03fd29 not in the list
09-15 10:31:11.147  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:31:11.147  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 10:31:11.147  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:31:11.147  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:31:11.148  5371  5417 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:31:11.148  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:31:11.149  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:11.149  5371  5417 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28b78ae not in the list
,09-15 10:31:11.149  5371  5417 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:31:11.149  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:11.149  5371  5417 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:31:11.150  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:11.150  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:31:11.150  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:11.151  5371  5417 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 10:31:11.151  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 10:31:11.151  5371  5417 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 10:31:11.151  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-15 10:31:11.151  5371  5417 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 10:31:11.151  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-15 10:31:11.154  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-15 10:31:11.154  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 10:31:11.154  5371  5417 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 10:31:11.154  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 10:31:11.154  5371  5417 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 10:31:11.154  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 10:31:11.155  5371  5417 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 10:31:11.155  5371  5417 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-15 10:31:11.155  5371  5417 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-15 10:31:11.155  5371  5417 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 10:31:11.155  5371  5417 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 10:31:11.156  5371  5417 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-15 10:31:11.156  5371  5417 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 10:31:11.156  5371  5417 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-15 10:31:11.157  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 10:31:11.157  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e99d added. We now have 3 listener(s)
,09-15 10:31:11.158  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:31:11.158  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 10:31:11.158  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:31:11.159  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:31:11.159  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a97e12 added. We now have 3 listener(s)
09-15 10:31:11.159  5371  5417 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 10:31:11.159  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:31:11.162  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 10:31:11.166  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 10:31:11.167  5371  5417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 10:31:11.168  5371  5417 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:31:11.169  5371  5417 D BluetoothAdapter: enable(): BT is already enabled..!
,09-15 10:31:11.169   929  3500 D WifiService: setWifiEnabled: true pid=5371, uid=10077
09-15 10:31:11.170   929  3500 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 10:31:11.170  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:11.174  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:11.177   929  3587 D WifiService: setWifiEnabled: false pid=5371, uid=10077
09-15 10:31:11.177   929  3587 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:11.181   929  2951 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-15 10:31:11.181   929  2951 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-15 10:31:11.181   929  2951 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:31:11.182   929  2951 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 10:31:11.188   929  2951 E native  : do suspend true
,09-15 10:31:11.211   929  5125 D DhcpClient: Clearing IP address
,09-15 10:31:11.211   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:31:11.216   507   923 D CommandListener: Setting iface cfg
,09-15 10:31:11.231  3557  5183 V NativeCrypto: Read error: ssl=0x7f9725b880: I/O error during system call, Connection timed out
,09-15 10:31:11.234   929  5126 D DhcpClient: Receive thread stopped
09-15 10:31:11.234  3557  5183 V NativeCrypto: SSL shutdown failed: ssl=0x7f9725b880: I/O error during system call, Broken pipe
,09-15 10:31:11.237   929  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-15 10:31:11.237   929  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-15 10:31:11.245   536   536 E Parcel  : Reading a NULL string not supported here.
09-15 10:31:11.247   929   929 D RttService: SCAN_AVAILABLE : 1
09-15 10:31:11.248   929  3029 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 10:31:11.257   929  2964 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-15 10:31:11.258  3448  3581 W QCNEJ   : |CORE| network lost: 100
09-15 10:31:11.259  3448  3581 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-15 10:31:11.268   929  2951 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 10:31:11.280   929  2951 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:31:11.280   929  2951 E native  : do suspend true
,09-15 10:31:11.287   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 10:31:11.306   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-15 10:31:11.307   507   923 D CommandListener: Clearing all IP addresses on wlan0
09-15 10:31:11.307   929  2964 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 10:31:11.307   507   923 D TetherController: Setting IP forward enable = 0
09-15 10:31:11.307   929  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-15 10:31:11.310   929   946 D Tethering: MasterInitialState.processMessage what=3
09-15 10:31:11.315   929  2951 D DhcpClient: doQuit
09-15 10:31:11.315  4217  4217 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e14fee5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-15 10:31:11.315   929  2951 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 10:31:11.315  3600  3600 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 10:31:11.318   929  5125 D DhcpClient: onQuitting
,09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:11.320  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:11.323  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:11.326  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:11.328  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:11.339  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:11.339  4736  4756 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 10:31:11.339  4736  4756 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 10:31:11.339  4736  4756 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 10:31:11.339  4736  4756 E SarControlService: no key has been found,reset the power
09-15 10:31:11.340  4736  4775 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 10:31:11.340  4736  4775 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-15 10:31:11.340  4736  4775 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 10:31:11.340  4765  4765 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:31:11.340  4765  4765 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 10:31:11.341  3600  3600 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-15 10:31:11.341  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:11.342  4736  4775 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 10:31:11.342  4736  4775 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 10:31:11.342  4736  4775 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-15 10:31:11.343  4765  4765 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 10:31:11.343  4765  4765 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-15 10:31:11.344  4765  4779 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@4a71233 HexData = [00000000ea03000000000000ffffffff]
,09-15 10:31:11.345  4765  4779 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:31:11.345  4765  4779 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 10:31:11.345  4765  4765 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:31:11.345  4736  4747 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:11.347  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:11.350  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:11.351  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:11.351  3600  3600 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-15 10:31:11.352  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:11.353  3890  3890 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-15 10:31:11.358  4765  4779 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@4a71233 HexData = [00000000eb03000000000000ffffffff]
09-15 10:31:11.358  4765  4779 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 10:31:11.358  4765  4779 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-15 10:31:11.359  4765  4765 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 10:31:11.359  4736  4748 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 10:31:11.362  3890  5153 I iu.UploadsManager: num queued entries: 0
,09-15 10:31:11.364  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 10:31:11.365  3890  3890 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 10:31:11.367  5157  5157 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 10:31:11.371  5157  5157 D SprintDMHelper: simOperator: 
09-15 10:31:11.371  5157  5157 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 10:31:11.382   507   923 E Netd    : netlink response contains error (No such file or directory)
,09-15 10:31:11.383   507   923 D TetherController: Setting IP forward enable = 0
09-15 10:31:11.384   929  2964 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-15 10:31:11.384  4251  5452 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 10:31:11.387  3890  5153 I iu.UploadsManager: num updated entries: 0
,09-15 10:31:11.388  3890  5153 I iu.SyncManager: NEXT; no task
,09-15 10:31:11.402   929  3550 I ActivityManager: Start proc 5455:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 10:31:11.407  3600  3600 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 10:31:11.416  3600  3600 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 10:31:11.426  5455  5455 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 10:31:11.433   929  3732 I ActivityManager: Killing 4716:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 10:31:11.519   929  2951 D wifi    : In wifi stop Hal
09-15 10:31:11.519   929  2951 D wifi    : halHandle = 0x7f965f7700, mVM = 0x7fb1d4d140, mCls = 0x100b5a
09-15 10:31:11.519   929  3598 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 10:31:11.519   929  3598 D WifiHAL : Got a signal to exit!!!
09-15 10:31:11.519   929  3598 I WifiHAL : Exit wifi_event_loop
09-15 10:31:11.520   929  2951 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 10:31:11.520   929  2951 E WifiHAL : Event processing terminated
09-15 10:31:11.520   929  2951 D wifi    : In wifi cleaned up handler
09-15 10:31:11.520   929  2951 I WifiHAL : Internal cleanup completed
09-15 10:31:11.521  3583  3991 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 10:31:11.522  4251  4251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 10:31:11.523  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:11.524  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:11.525  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:11.545   929  3598 D wifi    : set interface wlan0 flags (DOWN)
,09-15 10:31:11.545   929  2951 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 10:31:11.650  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:31:11.685  5371  5432 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:11.691   929  3497 D WifiService: setWifiEnabled: true pid=5371, uid=10077
09-15 10:31:11.692   929  3497 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:11.749   507   923 D SoftapController: Softap fwReload - Ok
,09-15 10:31:11.749   929   946 D Tethering: InitialState.processMessage what=4
,09-15 10:31:11.753   507   923 D CommandListener: Setting iface cfg
,09-15 10:31:11.754   507   923 D CommandListener: Trying to bring down wlan0
09-15 10:31:11.754   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-15 10:31:11.755   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:31:11.762   929  2951 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 10:31:12.121   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:12.197   929  3732 D WifiService: setWifiEnabled: true pid=5371, uid=10077
,09-15 10:31:12.197   929  3732 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:12.373   929  2951 D wifi    : set interface wlan0 flags (UP)
,09-15 10:31:12.380   929  2951 I WifiHAL : Initializing wifi
,09-15 10:31:12.380   929  2951 I WifiHAL : Creating socket
,09-15 10:31:12.386   929  2951 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 10:31:12.385   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 10:31:12.386   929  2951 D wifi    : Did set static halHandle = 0x7f965f7700
,09-15 10:31:12.386   929  2951 D wifi    : halHandle = 0x7f965f7700, mVM = 0x7fb1d4d140, mCls = 0x186a
09-15 10:31:12.387   929  2951 D wifi    : array field set
09-15 10:31:12.387   929  2951 I WifiNative-HAL: interface[0] = wlan0
09-15 10:31:12.389   929  5471 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547983685376
,09-15 10:31:12.390   929  5471 D wifi    : waitForHalEvents called, vm = 0x7fb1d4d140, obj = 0x186a, env = 0x7f989e7840
09-15 10:31:12.394   929  2951 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-15 10:31:12.396   929  2951 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-15 10:31:12.404  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:12.408  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:12.411  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:12.474  5472  5472 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 10:31:12.495  5472  5472 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:31:12.502  5472  5472 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:31:12.502  5472  5472 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 10:31:12.700   929   939 D WifiService: setWifiEnabled: true pid=5371, uid=10077
,09-15 10:31:12.701   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:13.123   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:13.204   929  3747 D WifiService: setWifiEnabled: true pid=5371, uid=10077
,09-15 10:31:13.204   929  3747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:13.411   929  2951 D WifiConfigStore: Loading config and enabling all networks 
,09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:13.422  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:13.427  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:13.434  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:13.437   929  2951 D WifiConfigStore: loaded 0 passpoint configs
,09-15 10:31:13.437   929  2951 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 10:31:13.438   929  2951 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 10:31:13.439  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:13.440   929  2951 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-15 10:31:13.442   929  2951 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 10:31:13.442   929  2951 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 10:31:13.442   929  2951 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 10:31:13.443   929  2951 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:13.445  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:13.448  4251  4251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 10:31:13.448   929  2951 D WifiNative-HAL: Setting external_sim to 1
09-15 10:31:13.449   929  2951 D wifi    : setting dfs flag to true, 0x7f9bacc3e0
09-15 10:31:13.449  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:13.449   929  2951 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 10:31:13.450   929  2951 D wifi    : setting scan oui 0x7f9bacc3e0
09-15 10:31:13.450   929  2951 D WifiHAL : Sending mac address OUI
,09-15 10:31:13.470   929  2951 E native  : do suspend true
,09-15 10:31:13.478   929  2951 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-15 10:31:13.478   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-15 10:31:13.479   929   929 D RttService: SCAN_AVAILABLE : 3
09-15 10:31:13.479   929  3029 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 10:31:13.481   507   923 D CommandListener: Setting iface cfg
,09-15 10:31:13.486   929  2950 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-15 10:31:13.486   929  2950 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 10:31:13.495   929  2950 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 10:31:13.502   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=242425 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,09-15 10:31:13.503   929  2950 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 10:31:13.709  5371  5469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.728  4372  4435 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 10:31:13.728  4372  4435 D BluetoothAdapterProperties: Setting state to 13
09-15 10:31:13.728  4372  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-15 10:31:13.729  4372  4435 D BluetoothAdapterProperties: onBluetoothDisable()
,09-15 10:31:13.730  4372  4435 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:31:13.735  4372  4372 D BluetoothMapService: onReceive
09-15 10:31:13.735  4372  4372 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 10:31:13.735  4372  4372 D BluetoothMapService: STATE_TURNING_OFF
09-15 10:31:13.738  4372  4372 D BluetoothMapService: MAP Service closeService in
,09-15 10:31:13.738  4372  4372 D BluetoothMapMasInstance0: MAP Service shutdown
,09-15 10:31:13.738  4372  4372 D ObexServerSockets0: shutdown(block = true)
,09-15 10:31:13.739  4372  4601 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 10:31:13.740  4372  4372 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:31:13.740  4372  4587 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 10:31:13.740  4372  4372 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:31:13.740  4372  4602 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 10:31:13.741  4372  4372 I BtOppRfcommListener: stopping Accept Thread
09-15 10:31:13.742  4372  5054 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 10:31:13.742  4372  5054 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 10:31:13.747  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:13.747  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:13.748  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:13.748  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:13.752  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:13.752  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:13.753  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:13.753  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:13.757  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:13.757  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:13.758   929   942 I ActivityManager: Start proc 5477:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-15 10:31:13.759  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:13.759  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:13.759  4372  4439 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:31:13.759  4372  4435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-15 10:31:13.766  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.768  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.769  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:13.771  4372  4372 D HeadsetService: Received stop request...Stopping profile...
09-15 10:31:13.773   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 10:31:13.773  4372  4372 D A2dpService: Received stop request...Stopping profile...
09-15 10:31:13.773  3087  3104 D BluetoothHeadset: Proxy object disconnected
09-15 10:31:13.774  4372  4592 D A2dpStateMachine: Exit Disconnected: -1
09-15 10:31:13.774  3478  3499 D BluetoothHeadset: Proxy object disconnected
09-15 10:31:13.775   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 10:31:13.775  3087  3087 D HeadsetProfile: Bluetooth service disconnected
09-15 10:31:13.775   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 10:31:13.775   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 10:31:13.775  3087  3087 D BluetoothA2dp: Proxy object disconnected
,09-15 10:31:13.776  4372  4372 D HidService: Received stop request...Stopping profile...
09-15 10:31:13.776  4372  4372 D HidService: Stopping Bluetooth HidService
09-15 10:31:13.778  4372  4372 D HealthService: Received stop request...Stopping profile...
09-15 10:31:13.777  3087  3087 D BluetoothInputDevice: Proxy object disconnected
09-15 10:31:13.778  3087  3087 D HidProfile: Bluetooth service disconnected
09-15 10:31:13.779  4372  4372 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:13.779  4372  4372 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:13.780  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.780  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:13.780  4372  4372 D PanService: Received stop request...Stopping profile...
09-15 10:31:13.781  3087  3087 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 10:31:13.781  3087  3087 D PanProfile: Bluetooth service disconnected
,09-15 10:31:13.784  4372  4372 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 10:31:13.784  4372  4372 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 10:31:13.784  4372  4573 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:13.784  4372  4573 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:13.784  4372  4573 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:13.785  4372  4372 D BluetoothMapService: Received stop request...Stopping profile...
09-15 10:31:13.785  4372  4372 D BluetoothMapService: stop()
,09-15 10:31:13.785  4372  4372 D BluetoothMapAppObserver: deinitObservers()
,09-15 10:31:13.785  4372  4372 D BluetoothMapAppObserver: removeReceiver()
09-15 10:31:13.785  4372  4439 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 10:31:13.786  4372  4439 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-15 10:31:13.786  4372  4372 V BluetoothAdapterState: isTurningOff()=true
,09-15 10:31:13.786  4372  4372 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:13.786  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.786  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:13.787  4372  4372 D SapService: Received stop request...Stopping profile...
09-15 10:31:13.787  4372  4372 V SapService: stop()
09-15 10:31:13.788  3087  3087 D BluetoothMap: Proxy object disconnected
09-15 10:31:13.788  3087  3087 D MapProfile: Bluetooth service disconnected
09-15 10:31:13.789  4372  4573 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:13.790  4372  4573 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:13.790  4372  4372 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 10:31:13.790  4372  4372 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 10:31:13.790  4372  4573 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:31:13.790  4372  4573 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:31:13.790  4372  4573 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:31:13.790  4372  4573 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.790  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:13.790  4372  4439 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 10:31:13.791  4372  4372 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 10:31:13.791  4372  4439 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 10:31:13.791  4372  4439 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 10:31:13.791  4372  4372 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 10:31:13.792  4372  4372 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:13.792  4372  4372 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:13.792  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.792  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:31:13.792  4372  4372 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 10:31:13.792  4372  4372 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 10:31:13.793  4372  4372 D BluetoothMapService: MAP Service closeService in
09-15 10:31:13.793  4372  4372 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:13.793  4372  4372 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:13.793  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.793  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:13.794  4372  4372 D BluetoothMapService: cleanup()
09-15 10:31:13.794  4372  4372 D BluetoothMapService: MAP Service closeService in
09-15 10:31:13.794  4372  4372 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:13.794  4372  4372 V BluetoothAdapterState: isTurningOn()=false
,09-15 10:31:13.794  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:13.794  4372  4372 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:13.794  4372  4435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 10:31:13.794  4372  4435 D BluetoothAdapterProperties: Setting state to 15
09-15 10:31:13.794  4372  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 10:31:13.795  4372  4435 I BluetoothAdapterState: Entering BleOnState
09-15 10:31:13.795  3087  3104 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:31:13.796   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:13.796   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 10:31:13.796   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:13.796   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:13.796  3087  3683 D BluetoothPan: onBluetoothStateChange on: false
09-15 10:31:13.797  3087  3101 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:13.797  3087  3104 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 10:31:13.801  3087  3683 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-15 10:31:13.803  3478  3702 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:13.804  3087  3101 D BluetoothMap: onBluetoothStateChange: up=false
09-15 10:31:13.805  4372  4435 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 10:31:13.805  4372  4435 D BluetoothAdapterProperties: Setting state to 16
09-15 10:31:13.805  4372  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 10:31:13.806  4372  4435 D BluetoothAdapterProperties: onBleDisable
09-15 10:31:13.806  4372  4435 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:31:13.806  4372  4436 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-15 10:31:13.807  4372  4439 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:31:13.808  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.809  4372  4573 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-15 10:31:13.809  4372  4573 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:13.810  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:13.811  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.813  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.815  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:13.816  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:13.817  5477  5477 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-15 10:31:13.831  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:31:13.836   929   938 I art     : Background partial concurrent mark sweep GC freed 45452(3MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.137ms total 101.235ms
,09-15 10:31:13.837   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b70a659:true
,09-15 10:31:13.838  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:13.851   929  3500 I ActivityManager: Start proc 5489:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-15 10:31:13.862  5477  5477 D LocalBluetoothProfileManager: Adding local MAP profile
,09-15 10:31:13.865  5477  5477 D BluetoothMap: Create BluetoothMap proxy object
,09-15 10:31:13.874  5477  5477 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 10:31:13.886  5489  5489 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 10:31:13.889  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:31:13.897   929  3732 I ActivityManager: Killing 4217:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-15 10:31:14.016  4372  4439 I bt_hci  : shut_down
,09-15 10:31:14.020  4372  4460 D bt_hwcfg: hw_epilog_process
,09-15 10:31:14.020  4372  4460 I bt_vendor: low_power_mode_cb
,09-15 10:31:14.022  4372  4460 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 10:31:14.022  4372  4460 I bt_vendor: epilog_cb
09-15 10:31:14.022  4372  4460 I bt_hci  : epilog_finished_callback
,09-15 10:31:14.025  4372  4439 I bt_hci_h4: hal_close
,09-15 10:31:14.025  4372  4439 I bt_userial_vendor: device fd = 54 close
,09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.080  5489  5489 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.080  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.081  5489  5489 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 10:31:14.081  5489  5489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 10:31:14.084  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 10:31:14.089  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 10:31:14.097  5477  5477 D DockEventReceiver: finishStartingService: stopping service
09-15 10:31:14.098   929  3391 I ActivityManager: Killing 4445:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 10:31:14.123   538   538 I ServiceManager: Waiting for service AtCmdFwd...
09-15 10:31:14.135  4372  4436 D bt_stack_manager: event_shut_down_stack finished.
09-15 10:31:14.136  4372  4435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-15 10:31:14.138  4372  4435 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 10:31:14.138  4372  4372 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 10:31:14.140  4372  4372 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 10:31:14.140  4372  4372 D BtGatt.GattService: stop()
09-15 10:31:14.140  4372  4372 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 10:31:14.142  4372  4372 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:14.142  4372  4372 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:14.142  4372  4372 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:14.142  4372  4372 V BluetoothAdapterState: isBleTurningOff()=true
09-15 10:31:14.143  4372  4435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 10:31:14.143  4372  4435 D BluetoothAdapterProperties: Setting state to 10
09-15 10:31:14.143  4372  4435 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 10:31:14.143  4372  4435 I BluetoothAdapterState: Entering OffState
09-15 10:31:14.144   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-15 10:31:14.150  4372  4372 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 10:31:14.150  4372  4372 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 10:31:14.150  4372  4372 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 10:31:14.152  4372  4436 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-15 10:31:14.156  4372  4372 I art     : System.exit called, status: 0
09-15 10:31:14.156  4372  4372 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 10:31:14.204   929  3131 I ActivityManager: Process com.android.bluetooth (pid 4372) has died
,09-15 10:31:14.225  5371  5475 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:14.239   929   946 I ActivityManager: Start proc 5522:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 10:31:14.300  5522  5522 D AdapterServiceConfig: Adding HeadsetService
,09-15 10:31:14.300  5522  5522 D AdapterServiceConfig: Adding A2dpService
09-15 10:31:14.300  5522  5522 D AdapterServiceConfig: Adding HidService
09-15 10:31:14.301  5522  5522 D AdapterServiceConfig: Adding HealthService
09-15 10:31:14.301  5522  5522 D AdapterServiceConfig: Adding PanService
09-15 10:31:14.301  5522  5522 D AdapterServiceConfig: Adding GattService
09-15 10:31:14.301  5522  5522 D AdapterServiceConfig: Adding BluetoothMapService
09-15 10:31:14.301  5522  5522 D AdapterServiceConfig: Adding SapService
,09-15 10:31:14.311   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18669a6:true
,09-15 10:31:14.311  5522  5522 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 10:31:14.314  5522  5522 I bt_bluedroid: init
,09-15 10:31:14.314  5522  5534 I BluetoothAdapterState: Entering OffState
,09-15 10:31:14.316  5522  5535 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 10:31:14.316  5522  5535 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 10:31:14.316  5522  5535 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 10:31:14.316  5522  5535 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 10:31:14.317  5522  5522 I bt_bluedroid: get_profile_interface socket
,09-15 10:31:14.318  5522  5538 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 10:31:14.318  5522  5522 I bt_bluedroid: get_profile_interface sdp
,09-15 10:31:14.319  5522  5538 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:31:14.322  5522  5533 I bt_bluedroid: config_hci_snoop_log
,09-15 10:31:14.323   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-15 10:31:14.326  5522  5534 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 10:31:14.326  5522  5534 D BluetoothAdapterProperties: Setting state to 14
09-15 10:31:14.326  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 10:31:14.327  5522  5534 D BluetoothBondStateMachine: make
09-15 10:31:14.329  5522  5539 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 10:31:14.331  5522  5534 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:31:14.332  5522  5522 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 10:31:14.333  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:14.334  5522  5522 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 10:31:14.334  5522  5522 D BtGatt.GattService: Received start request. Starting profile...
09-15 10:31:14.335  5522  5522 D BtGatt.GattService: start()
09-15 10:31:14.335  5522  5522 I bt_bluedroid: get_profile_interface gatt
09-15 10:31:14.335  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:14.335  5522  5522 D BtGatt.AdvertiseManager: advertise manager created
,09-15 10:31:14.339  5522  5522 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:31:14.340  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:14.340  5522  5522 V BluetoothAdapterState: isBleTurningOn()=true
09-15 10:31:14.340  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:14.340  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 10:31:14.341  5522  5534 I bt_bluedroid: bt_bluedroid
,09-15 10:31:14.341  5522  5535 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-15 10:31:14.341  5522  5535 I bt_hci  : start_up
,09-15 10:31:14.346  5522  5535 I bt_vendor: alloc value 0xf41b7871
,09-15 10:31:14.346  5522  5535 I bt_vendor: init
09-15 10:31:14.346  5522  5535 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 10:31:14.346  5522  5535 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 10:31:14.352  5489  5508 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 10:31:14.363   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@97ac4df:true
,09-15 10:31:14.452  5522  5535 D bt_hci  : start_up starting async portion
09-15 10:31:14.450  5545  5545 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:31:14.453  5522  5542 I bt_hci  : event_finish_startup
09-15 10:31:14.453  5522  5542 I bt_hci_h4: hal_open
09-15 10:31:14.453  5522  5542 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 10:31:14.454  5522  5542 I bt_userial_vendor: device fd = 54 open
,09-15 10:31:14.466  5522  5542 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 10:31:14.468  5522  5542 D bt_hwcfg: Chipset BCM4358A3
,09-15 10:31:14.468  5522  5542 D bt_hwcfg: Target name = [BCM4358A3]
09-15 10:31:14.468  5522  5542 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 10:31:14.735  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-15 10:31:14.875  5522  5542 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 10:31:14.875  5522  5542 D bt_hwcfg: Settlement delay -- 100 ms
09-15 10:31:14.875  5522  5542 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 10:31:14.999  5522  5542 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 10:31:14.999  5522  5542 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 10:31:15.002  5522  5542 I bt_hwcfg: vendor lib fwcfg completed
09-15 10:31:15.002  5522  5542 I bt_vendor: firmware callback
,09-15 10:31:15.003  5522  5542 I bt_hci  : firmware_config_callback
,09-15 10:31:15.011  5522  5547 I bt_btu  : btu_task pending for preload complete event
,09-15 10:31:15.011  5522  5547 I bt_btu_task: Bluetooth chip preload is complete
09-15 10:31:15.012  5522  5547 I bt_btu  : btu_task received preload complete event
,09-15 10:31:15.017  5522  5547 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 10:31:15.018  5522  5547 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 10:31:15.019  5522  5547 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 10:31:15.019  5522  5547 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 10:31:15.019  5522  5547 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 10:31:15.019  5522  5547 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 10:31:15.019  5522  5547 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 10:31:15.019  5522  5547 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 10:31:15.104  5522  5547 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4135549
,09-15 10:31:15.104  5522  5547 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4135549 
,09-15 10:31:15.123  5522  5538 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 10:31:15.124   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 10:31:15.124  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 10:31:15.125  5522  5538 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 10:31:15.127  5522  5538 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:31:15.130  5522  5538 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:31:15.130  5522  5538 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 10:31:15.131  5522  5538 D bt_hci  : do_postload posting postload work item
09-15 10:31:15.131  5522  5542 I bt_hci  : event_postload
09-15 10:31:15.131  5522  5542 I bt_vendor: sco_config_cb
09-15 10:31:15.131  5522  5542 I bt_hci  : sco_config_callback postload finished.
09-15 10:31:15.135  5522  5538 D bt_bte_conf: Device ID record 1 : primary
09-15 10:31:15.135  5522  5538 D bt_bte_conf:   vendorId            = 000f
09-15 10:31:15.135  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.135  5522  5538 D bt_bte_conf:   vendorIdSource      = 0001
09-15 10:31:15.135  5522  5538 D bt_bte_conf:   product             = 1200
09-15 10:31:15.136  5522  5538 D bt_bte_conf:   version             = 1436
09-15 10:31:15.136  5522  5538 D bt_bte_conf:   clientExecutableURL = 
09-15 10:31:15.136  5522  5538 D bt_bte_conf:   serviceDescription  = 
09-15 10:31:15.136  5522  5538 D bt_bte_conf:   documentationURL    = 
09-15 10:31:15.136  5522  5538 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 10:31:15.136  5522  5535 D bt_stack_manager: event_start_up_stack finished
,09-15 10:31:15.138  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.140  5522  5542 I bt_vendor: low_power_mode_cb
09-15 10:31:15.142  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.143  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 10:31:15.143  5522  5534 D BluetoothAdapterProperties: Setting state to 15
,09-15 10:31:15.143  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 10:31:15.144  5522  5534 I BluetoothAdapterState: Entering BleOnState
,09-15 10:31:15.147  5522  5534 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 10:31:15.147  5522  5534 D BluetoothAdapterProperties: Setting state to 11
,09-15 10:31:15.147  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 10:31:15.151  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:15.152  5522  5522 D HeadsetService: Received start request. Starting profile...
,09-15 10:31:15.153  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.154  5522  5522 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 10:31:15.155  5522  5522 D HeadsetStateMachine: make
09-15 10:31:15.155  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.157  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.163  5522  5534 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:31:15.165  5522  5522 D HeadsetStateMachine: max_hf_connections = 1
09-15 10:31:15.165  5522  5522 I bt_bluedroid: get_profile_interface handsfree
09-15 10:31:15.165  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 10:31:15.165  5522  5538 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 10:31:15.168  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:15.169  5522  5522 D A2dpService: Received start request. Starting profile...
,09-15 10:31:15.170  5522  5522 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 10:31:15.170  5522  5522 I bt_bluedroid: get_profile_interface avrcp
,09-15 10:31:15.174  5522  5522 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 10:31:15.175  5522  5522 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 10:31:15.175  5522  5522 D A2dpStateMachine: make
,09-15 10:31:15.176  5522  5522 I bt_bluedroid: get_profile_interface a2dp
09-15 10:31:15.176  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 10:31:15.179  5522  5555 D A2dpStateMachine: Enter Disconnected: -2
,09-15 10:31:15.180  5522  5522 I BluetoothHidServiceJni: classInitNative: succeeds
09-15 10:31:15.181  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:15.182  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:15.182  5522  5522 D HidService: Received start request. Starting profile...
,09-15 10:31:15.182  5522  5522 I bt_bluedroid: get_profile_interface hidhost
09-15 10:31:15.183  5522  5522 D HidService: setHidService(): set to: null
09-15 10:31:15.183  5522  5538 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf411656d
09-15 10:31:15.183  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 10:31:15.183  5522  5522 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 10:31:15.183  5477  5477 D BluetoothInputDevice: Proxy object connected
09-15 10:31:15.184  5477  5477 D HidProfile: Bluetooth service connected
09-15 10:31:15.184  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:15.184  5522  5522 D HealthService: Received start request. Starting profile...
,09-15 10:31:15.185  5522  5522 I bt_bluedroid: get_profile_interface health
,09-15 10:31:15.186  5522  5522 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 10:31:15.187  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:15.188  5522  5522 D PanService: Received start request. Starting profile...
,09-15 10:31:15.188  5477  5477 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:31:15.188  5522  5522 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 10:31:15.188  5522  5522 I bt_bluedroid: get_profile_interface pan
09-15 10:31:15.188  5477  5477 D PanProfile: Bluetooth service connected
09-15 10:31:15.188  5522  5538 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 10:31:15.192  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:15.193  5477  5477 D BluetoothMap: Proxy object connected
,09-15 10:31:15.193  5522  5522 D BluetoothMapService: Received start request. Starting profile...
09-15 10:31:15.193  5522  5522 D BluetoothMapService: start()
09-15 10:31:15.194  5477  5477 D MapProfile: Bluetooth service connected
09-15 10:31:15.194  5477  5477 D BluetoothMap: getConnectedDevices()
09-15 10:31:15.194  5477  5477 D BluetoothMap: Bluetooth is Not enabled
,09-15 10:31:15.195  5522  5522 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 10:31:15.196  5522  5522 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 10:31:15.196  5522  5522 D BluetoothMapAppObserver: createReceiver()
09-15 10:31:15.198  5522  5522 D BluetoothMapAppObserver: initObservers()
09-15 10:31:15.198  5522  5522 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 10:31:15.203  5522  5522 V SapService: SapBinder()
,09-15 10:31:15.203  5522  5522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:15.204  5522  5522 D SapService: Received start request. Starting profile...
09-15 10:31:15.204  5522  5522 V SapService: start()
,09-15 10:31:15.205  5522  5522 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:31:15.205  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.205  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.205  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.205  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.205  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.206  5522  5553 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:31:15.206  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.207  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.208  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.208  5522  5522 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:15.208  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.208  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.208  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 10:31:15.208  5522  5534 D BluetoothAdapterProperties: ScanMode =  20
09-15 10:31:15.208  5522  5534 D BluetoothAdapterProperties: State =  11
09-15 10:31:15.208  5522  5534 D BluetoothAdapterProperties: Setting state to 12
09-15 10:31:15.209  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 10:31:15.209  5522  5534 I BluetoothAdapterState: Entering OnState
09-15 10:31:15.209  5477  5487 D BluetoothMap: onBluetoothStateChange: up=true
09-15 10:31:15.210  5477  5488 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 10:31:15.210  5522  5538 D BluetoothAdapterProperties: Scan Mode:21
09-15 10:31:15.210  5522  5538 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 10:31:15.211  3087  3101 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 10:31:15.213   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 10:31:15.213   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:31:15.214  5371  5371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 10:31:15.214  3087  3087 D BluetoothA2dp: Proxy object connected
09-15 10:31:15.214   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:15.214   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:15.214   929   929 D BluetoothA2dp: Proxy object connected
09-15 10:31:15.214  3087  3683 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:31:15.216  3087  3104 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:15.216  3087  3683 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 10:31:15.217  3087  3087 D BluetoothPan: BluetoothPAN Proxy object connected
,09-15 10:31:15.217  3087  3087 D PanProfile: Bluetooth service connected
09-15 10:31:15.218  5371  5371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-15 10:31:15.219  5477  5487 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:31:15.220  3087  3101 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 10:31:15.222  5522  5522 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:15.223  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:15.223  5522  5522 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 10:31:15.223  3087  3087 D BluetoothInputDevice: Proxy object connected
09-15 10:31:15.223  3087  3087 D HidProfile: Bluetooth service connected
09-15 10:31:15.224  5522  5522 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:15.225  3478  3702 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:15.225  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:15.225  5477  5488 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 10:31:15.226  5522  5522 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:15.226  3087  3101 D BluetoothMap: onBluetoothStateChange: up=true
09-15 10:31:15.227  5522  5522 D ObexServerSockets: Succeed to create listening sockets 
,09-15 10:31:15.227  5522  5522 D ObexServerSockets0: startAccept()
09-15 10:31:15.227  5522  5522 D ObexServerSockets0: prepareForNewConnect()
,09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:15.229  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:15.229  3087  3087 D BluetoothMap: Proxy object connected
,09-15 10:31:15.229  3087  3087 D MapProfile: Bluetooth service connected
09-15 10:31:15.229  3087  3087 D BluetoothMap: getConnectedDevices()
,09-15 10:31:15.230  5522  5561 D ObexServerSockets0: Accepting socket connection...
09-15 10:31:15.230   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-15 10:31:15.233  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:15.233  5522  5522 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 10:31:15.233  5522  5522 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 10:31:15.233  5522  5563 D ObexServerSockets0: Accepting socket connection...
09-15 10:31:15.235  5522  5522 D BluetoothMapService: onReceive
09-15 10:31:15.235  5522  5522 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 10:31:15.235  5522  5522 D BluetoothMapService: STATE_ON
,09-15 10:31:15.236  5477  5477 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-15 10:31:15.237  5522  5565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:15.237  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:15.239  5522  5565 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 10:31:15.239  5522  5565 D BluetoothSdpJni: SDP Create record success - handle: 1
09-15 10:31:15.240  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:15.241  5371  5521 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.242  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.242  5371  5417 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:31:15.242  5477  5477 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-15 10:31:15.242  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:31:15.243  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.244  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.247  5522  5534 D BluetoothAdapterState: Current state: ON, message: 23
09-15 10:31:15.247  5522  5534 D BluetoothAdapterProperties: Setting state to 13
,09-15 10:31:15.247  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-15 10:31:15.248  5522  5534 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 10:31:15.249  5522  5534 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:31:15.249  5522  5522 D BluetoothMapService: onReceive
09-15 10:31:15.249  5522  5522 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 10:31:15.249  5522  5522 D BluetoothMapService: STATE_TURNING_OFF
09-15 10:31:15.250  5522  5522 D BluetoothMapService: MAP Service closeService in
09-15 10:31:15.250  5522  5522 D BluetoothMapMasInstance0: MAP Service shutdown
,09-15 10:31:15.250  5522  5522 D ObexServerSockets0: shutdown(block = true)
09-15 10:31:15.250  5522  5538 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:31:15.250  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 10:31:15.250  5522  5522 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:31:15.250  5522  5522 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 10:31:15.250  5522  5561 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 10:31:15.250  5522  5549 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-15 10:31:15.251  5522  5563 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 10:31:15.253  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:15.253  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:15.253  5522  5522 D HeadsetService: Received stop request...Stopping profile...
09-15 10:31:15.254  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 10:31:15.254  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:15.254  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:15.256  5477  5477 D BluetoothA2dp: Proxy object connected
,09-15 10:31:15.258  5522  5522 D A2dpService: Received stop request...Stopping profile...
09-15 10:31:15.258  5522  5555 D A2dpStateMachine: Exit Disconnected: -1
09-15 10:31:15.259   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 10:31:15.260  5522  5522 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:15.260  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.260  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:31:15.260  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.261  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:15.261  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:15.262  5371  5371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:31:15.262  3087  3087 D BluetoothA2dp: Proxy object disconnected
09-15 10:31:15.262  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:15.263  5477  5477 D DockEventReceiver: finishStartingService: stopping service
09-15 10:31:15.263  5522  5522 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-15 10:31:15.263  5522  5522 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 10:31:15.263  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 10:31:15.263  5522  5547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:15.263  5522  5547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:15.263  5522  5547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:15.263  5522  5538 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-15 10:31:15.264  5477  5477 D BluetoothA2dp: Proxy object disconnected
09-15 10:31:15.265  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.265  5522  5522 D HidService: Received stop request...Stopping profile...
09-15 10:31:15.265  5522  5522 D HidService: Stopping Bluetooth HidService
09-15 10:31:15.266  5477  5477 D BluetoothInputDevice: Proxy object disconnected
09-15 10:31:15.266  5477  5477 D HidProfile: Bluetooth service disconnected
09-15 10:31:15.266  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.266  5522  5522 D HealthService: Received stop request...Stopping profile...
09-15 10:31:15.267  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:15.268  5522  5522 V BluetoothAdapterState: isTurningOff()=true
,09-15 10:31:15.268  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.268  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.268  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.269  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 10:31:15.269  5522  5547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:15.269  5522  5522 D PanService: Received stop request...Stopping profile...
09-15 10:31:15.269  5522  5547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 10:31:15.270  5522  5547 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 10:31:15.270  5522  5547 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:31:15.270  5522  5547 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-15 10:31:15.270  5522  5547 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 10:31:15.270  5522  5522 D BluetoothMapService: Received stop request...Stopping profile...
09-15 10:31:15.270  5522  5522 D BluetoothMapService: stop()
09-15 10:31:15.271  5477  5477 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 10:31:15.271  5477  5477 D PanProfile: Bluetooth service disconnected
,09-15 10:31:15.271  5522  5522 D BluetoothMapAppObserver: deinitObservers()
,09-15 10:31:15.271  5522  5522 D BluetoothMapAppObserver: removeReceiver()
09-15 10:31:15.272  5477  5477 D BluetoothMap: Proxy object disconnected
09-15 10:31:15.272  5477  5477 D MapProfile: Bluetooth service disconnected
09-15 10:31:15.272  5522  5522 D SapService: Received stop request...Stopping profile...
09-15 10:31:15.272  5522  5522 V SapService: stop()
,09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isTurningOff()=true
,09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.281  5522  5522 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 10:31:15.281  5477  5477 D BluetoothPbap: Proxy object connected
09-15 10:31:15.281  5522  5522 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 10:31:15.281  5522  5538 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.281  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.282  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.282  5477  5477 D PbapServerProfile: Bluetooth service connected
09-15 10:31:15.282  5522  5522 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-15 10:31:15.282  5522  5538 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 10:31:15.282  3087  3087 D BluetoothInputDevice: Proxy object disconnected
09-15 10:31:15.282  3087  3087 D HidProfile: Bluetooth service disconnected
09-15 10:31:15.282  5522  5522 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-15 10:31:15.282  3087  3087 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 10:31:15.282  3087  3087 D PanProfile: Bluetooth service disconnected
09-15 10:31:15.282  5522  5522 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:15.282  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.282  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.282  3087  3087 D BluetoothMap: Proxy object disconnected
09-15 10:31:15.282  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:31:15.282  3087  3087 D MapProfile: Bluetooth service disconnected
09-15 10:31:15.283  3087  3087 D BluetoothPbap: Proxy object connected
09-15 10:31:15.283  5522  5522 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 10:31:15.283  3087  3087 D PbapServerProfile: Bluetooth service connected
09-15 10:31:15.283  5522  5522 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-15 10:31:15.288  5522  5522 D BluetoothMapService: MAP Service closeService in
,09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isTurningOff()=true
09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.288  5522  5522 D BluetoothMapService: cleanup()
09-15 10:31:15.288  5522  5522 D BluetoothMapService: MAP Service closeService in
09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isTurningOff()=true
,09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.288  5522  5522 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.288  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 10:31:15.289  5522  5534 D BluetoothAdapterProperties: Setting state to 15
09-15 10:31:15.289  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 10:31:15.289  5522  5534 I BluetoothAdapterState: Entering BleOnState
09-15 10:31:15.290  5477  5487 D BluetoothMap: onBluetoothStateChange: up=false
,09-15 10:31:15.291  5477  5488 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 10:31:15.292  3087  3683 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:31:15.293  5477  5487 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:15.293   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:15.293   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 10:31:15.293   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:15.293   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:15.293  3087  3101 D BluetoothPan: onBluetoothStateChange on: false
09-15 10:31:15.294  3087  3104 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 10:31:15.294  3087  3683 D BluetoothPbap: onBluetoothStateChange: up=false
,09-15 10:31:15.294  5477  5488 D BluetoothPan: onBluetoothStateChange on: false
09-15 10:31:15.295  3087  3101 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 10:31:15.295  5477  5487 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-15 10:31:15.296  3478  3502 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 10:31:15.297  5477  5488 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 10:31:15.297  3087  3104 D BluetoothMap: onBluetoothStateChange: up=false
09-15 10:31:15.298  5522  5534 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 10:31:15.298  5522  5534 D BluetoothAdapterProperties: Setting state to 16
09-15 10:31:15.298  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 10:31:15.299  5522  5534 D BluetoothAdapterProperties: onBleDisable
09-15 10:31:15.299  5522  5534 I BluetoothAdapterState: Entering PendingCommandState
09-15 10:31:15.301  5522  5535 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-15 10:31:15.301  5522  5538 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:31:15.302  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.303  5522  5547 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 10:31:15.303  5522  5547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-15 10:31:15.305  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:31:15.305  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.307  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:15.308  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.311  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:15.313  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:31:15.320  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:31:15.327  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:15.329  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:31:15.504  5522  5538 I bt_hci  : shut_down
,09-15 10:31:15.504  5522  5542 D bt_hwcfg: hw_epilog_process
,09-15 10:31:15.506  5522  5542 I bt_vendor: low_power_mode_cb
,09-15 10:31:15.509  5522  5542 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 10:31:15.509  5522  5542 I bt_vendor: epilog_cb
09-15 10:31:15.509  5522  5542 I bt_hci  : epilog_finished_callback
09-15 10:31:15.510  5522  5538 I bt_hci_h4: hal_close
,09-15 10:31:15.512  5522  5538 I bt_userial_vendor: device fd = 54 close
,09-15 10:31:15.639  5522  5535 D bt_stack_manager: event_shut_down_stack finished.
,09-15 10:31:15.640  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 10:31:15.644  5522  5534 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-15 10:31:15.644  5522  5522 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-15 10:31:15.645  5522  5522 D BtGatt.GattService: Received stop request...Stopping profile...
,09-15 10:31:15.647  5522  5522 D BtGatt.GattService: stop()
09-15 10:31:15.648  5522  5522 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 10:31:15.651  5522  5522 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:15.651  5522  5522 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.652  5522  5522 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:15.652  5522  5522 V BluetoothAdapterState: isBleTurningOff()=true
09-15 10:31:15.652  5522  5534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 10:31:15.653  5522  5534 D BluetoothAdapterProperties: Setting state to 10
,09-15 10:31:15.653  5522  5534 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 10:31:15.654  5522  5534 I BluetoothAdapterState: Entering OffState
,09-15 10:31:15.655   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 10:31:15.671  5522  5522 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 10:31:15.671  5522  5522 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 10:31:15.671  5522  5522 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-15 10:31:15.674  5522  5535 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 10:31:15.682  5522  5522 I art     : System.exit called, status: 0
,09-15 10:31:15.682  5522  5522 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 10:31:15.713   929   939 I ActivityManager: Process com.android.bluetooth (pid 5522) has died
,09-15 10:31:15.747  5371  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:15.748  5371  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:15.748  5371  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 10:31:15.748  5371  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:15.751  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:15.780   929   946 I ActivityManager: Start proc 5578:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 10:31:15.843  5578  5578 D AdapterServiceConfig: Adding HeadsetService
,09-15 10:31:15.843  5578  5578 D AdapterServiceConfig: Adding A2dpService
09-15 10:31:15.844  5578  5578 D AdapterServiceConfig: Adding HidService
09-15 10:31:15.844  5578  5578 D AdapterServiceConfig: Adding HealthService
,09-15 10:31:15.844  5578  5578 D AdapterServiceConfig: Adding PanService
09-15 10:31:15.844  5578  5578 D AdapterServiceConfig: Adding GattService
09-15 10:31:15.844  5578  5578 D AdapterServiceConfig: Adding BluetoothMapService
09-15 10:31:15.844  5578  5578 D AdapterServiceConfig: Adding SapService
,09-15 10:31:15.854   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76fe89f:true
,09-15 10:31:15.854  5578  5578 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 10:31:15.857  5578  5578 I bt_bluedroid: init
,09-15 10:31:15.857  5578  5590 I BluetoothAdapterState: Entering OffState
,09-15 10:31:15.859  5578  5591 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 10:31:15.860  5578  5591 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 10:31:15.860  5578  5591 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 10:31:15.860  5578  5591 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 10:31:15.860  5578  5578 I bt_bluedroid: get_profile_interface socket
,09-15 10:31:15.862  5578  5594 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 10:31:15.862  5578  5578 I bt_bluedroid: get_profile_interface sdp
09-15 10:31:15.863  5578  5594 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:31:15.867  5578  5589 I bt_bluedroid: config_hci_snoop_log
09-15 10:31:15.867   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 10:31:15.871  5578  5590 D BluetoothAdapterState: Current state: OFF, message: 0
,09-15 10:31:15.871  5578  5590 D BluetoothAdapterProperties: Setting state to 14
09-15 10:31:15.871  5578  5590 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-15 10:31:15.873  5578  5590 D BluetoothBondStateMachine: make
,09-15 10:31:15.874  5578  5595 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 10:31:15.877  5578  5590 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:31:15.877  5578  5578 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 10:31:15.879  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:15.880  5578  5578 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 10:31:15.880  5578  5578 D BtGatt.GattService: Received start request. Starting profile...
09-15 10:31:15.880  5578  5578 D BtGatt.GattService: start()
09-15 10:31:15.881  5578  5578 I bt_bluedroid: get_profile_interface gatt
09-15 10:31:15.881  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:15.881  5578  5578 D BtGatt.AdvertiseManager: advertise manager created
,09-15 10:31:15.886  5578  5578 V BluetoothAdapterState: isTurningOff()=false
,09-15 10:31:15.886  5578  5578 V BluetoothAdapterState: isTurningOn()=false
09-15 10:31:15.886  5578  5578 V BluetoothAdapterState: isBleTurningOn()=true
09-15 10:31:15.886  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:15.886  5578  5590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 10:31:15.888  5578  5590 I bt_bluedroid: bt_bluedroid
09-15 10:31:15.888  5578  5591 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 10:31:15.888  5578  5591 I bt_hci  : start_up
,09-15 10:31:15.893  5578  5591 I bt_vendor: alloc value 0xf41b7871
09-15 10:31:15.893  5578  5591 I bt_vendor: init
09-15 10:31:15.893  5578  5591 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 10:31:15.893  5578  5591 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 10:31:16.003  5578  5591 D bt_hci  : start_up starting async portion
,09-15 10:31:16.003  5578  5598 I bt_hci  : event_finish_startup
09-15 10:31:16.003  5578  5598 I bt_hci_h4: hal_open
09-15 10:31:16.004  5578  5598 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-15 10:31:16.007  5578  5598 I bt_userial_vendor: device fd = 54 open
,09-15 10:31:16.000  5599  5599 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:31:16.021  5578  5598 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 10:31:16.024  5578  5598 D bt_hwcfg: Chipset BCM4358A3
,09-15 10:31:16.024  5578  5598 D bt_hwcfg: Target name = [BCM4358A3]
09-15 10:31:16.024  5578  5598 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 10:31:16.262  5578  5590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-15 10:31:16.418  5578  5598 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 10:31:16.419  5578  5598 D bt_hwcfg: Settlement delay -- 100 ms
09-15 10:31:16.419  5578  5598 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 10:31:16.542  5578  5598 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 10:31:16.542  5578  5598 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 10:31:16.544  5578  5598 I bt_hwcfg: vendor lib fwcfg completed
09-15 10:31:16.544  5578  5598 I bt_vendor: firmware callback
,09-15 10:31:16.544  5578  5598 I bt_hci  : firmware_config_callback
,09-15 10:31:16.552  5578  5601 I bt_btu  : btu_task pending for preload complete event
,09-15 10:31:16.552  5578  5601 I bt_btu_task: Bluetooth chip preload is complete
09-15 10:31:16.552  5578  5601 I bt_btu  : btu_task received preload complete event
,09-15 10:31:16.558  5578  5601 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 10:31:16.559  5578  5601 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 10:31:16.559  5578  5601 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 10:31:16.559  5578  5601 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 10:31:16.559  5578  5601 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-15 10:31:16.559  5578  5601 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_GAP
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_SDP
,09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 10:31:16.560  5578  5601 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 10:31:16.639  5578  5601 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4135549
,09-15 10:31:16.640  5578  5601 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4135549 
,09-15 10:31:16.655  5578  5594 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 10:31:16.658  5578  5594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 10:31:16.658  5578  5594 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 10:31:16.662  5578  5594 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 10:31:16.664  5578  5594 D BluetoothAdapterProperties: Scan Mode:20
09-15 10:31:16.665  5578  5594 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 10:31:16.665  5578  5594 D bt_hci  : do_postload posting postload work item
09-15 10:31:16.665  5578  5598 I bt_hci  : event_postload
09-15 10:31:16.665  5578  5598 I bt_vendor: sco_config_cb
09-15 10:31:16.665  5578  5598 I bt_hci  : sco_config_callback postload finished.
09-15 10:31:16.670  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:16.673  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:16.674  5578  5594 D bt_bte_conf: Device ID record 1 : primary
09-15 10:31:16.674  5578  5594 D bt_bte_conf:   vendorId            = 000f
09-15 10:31:16.674  5578  5594 D bt_bte_conf:   vendorIdSource      = 0001
09-15 10:31:16.674  5578  5594 D bt_bte_conf:   product             = 1200
,09-15 10:31:16.675  5578  5594 D bt_bte_conf:   version             = 1436
09-15 10:31:16.675  5578  5594 D bt_bte_conf:   clientExecutableURL = 
09-15 10:31:16.675  5578  5594 D bt_bte_conf:   serviceDescription  = 
09-15 10:31:16.675  5578  5598 I bt_vendor: low_power_mode_cb
09-15 10:31:16.675  5578  5594 D bt_bte_conf:   documentationURL    = 
09-15 10:31:16.675  5578  5594 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 10:31:16.675  5578  5591 D bt_stack_manager: event_start_up_stack finished
09-15 10:31:16.677  5578  5590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 10:31:16.677  5578  5590 D BluetoothAdapterProperties: Setting state to 15
09-15 10:31:16.677  5578  5590 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 10:31:16.678  5578  5590 I BluetoothAdapterState: Entering BleOnState
,09-15 10:31:16.683  5578  5590 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 10:31:16.683  5578  5590 D BluetoothAdapterProperties: Setting state to 11
,09-15 10:31:16.683  5578  5590 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-15 10:31:16.688  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:16.691   929   929 D BluetoothHeadset: Proxy object connected
09-15 10:31:16.692  3087  3104 D BluetoothHeadset: Proxy object connected
09-15 10:31:16.692  5578  5578 D HeadsetService: Received start request. Starting profile...
,09-15 10:31:16.692  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:16.694  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:16.695  5578  5578 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 10:31:16.696  5578  5578 D HeadsetStateMachine: make
09-15 10:31:16.697  3478  3702 D BluetoothHeadset: Proxy object connected
,09-15 10:31:16.698   929   929 D BluetoothHeadset: Proxy object connected
,09-15 10:31:16.698   929   929 D BluetoothHeadset: Proxy object connected
09-15 10:31:16.698  5477  5488 D BluetoothHeadset: Proxy object connected
09-15 10:31:16.701  3087  3087 D HeadsetProfile: Bluetooth service connected
09-15 10:31:16.703  5477  5477 D HeadsetProfile: Bluetooth service connected
,09-15 10:31:16.706  5578  5590 I BluetoothAdapterState: Entering PendingCommandState
,09-15 10:31:16.707  5578  5578 D HeadsetStateMachine: max_hf_connections = 1
,09-15 10:31:16.708  5578  5578 I bt_bluedroid: get_profile_interface handsfree
09-15 10:31:16.708  5578  5594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 10:31:16.708  5578  5594 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-15 10:31:16.711  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:16.712  5578  5578 D A2dpService: Received start request. Starting profile...
,09-15 10:31:16.713  5578  5578 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 10:31:16.713  5578  5578 I bt_bluedroid: get_profile_interface avrcp
,09-15 10:31:16.719  5578  5578 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 10:31:16.720  5578  5578 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 10:31:16.720  5578  5578 D A2dpStateMachine: make
09-15 10:31:16.721  5578  5578 I bt_bluedroid: get_profile_interface a2dp
,09-15 10:31:16.721  5578  5594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 10:31:16.724  5578  5609 D A2dpStateMachine: Enter Disconnected: -2
,09-15 10:31:16.724  5578  5578 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 10:31:16.725  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:16.726  5578  5578 D HidService: Received start request. Starting profile...
09-15 10:31:16.726  5578  5578 I bt_bluedroid: get_profile_interface hidhost
09-15 10:31:16.726  5578  5594 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf411656d
,09-15 10:31:16.726  5578  5578 D HidService: setHidService(): set to: null
09-15 10:31:16.727  5578  5594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 10:31:16.728  5578  5578 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 10:31:16.729  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
09-15 10:31:16.730  5578  5578 D HealthService: Received start request. Starting profile...
09-15 10:31:16.730  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:16.731  5578  5578 I bt_bluedroid: get_profile_interface health
09-15 10:31:16.732  5578  5578 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 10:31:16.733  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:16.734  5578  5578 D PanService: Received start request. Starting profile...
09-15 10:31:16.734  5578  5578 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 10:31:16.734  5578  5578 I bt_bluedroid: get_profile_interface pan
,09-15 10:31:16.734  5472  5472 I wpa_supplicant: wlan0: Trying to associate with SSID 'RA-WINGS'
09-15 10:31:16.735  5578  5594 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 10:31:16.738  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:16.739  5578  5578 D BluetoothMapService: Received start request. Starting profile...
,09-15 10:31:16.739  5578  5578 D BluetoothMapService: start()
09-15 10:31:16.742  5578  5578 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-15 10:31:16.743  5578  5578 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 10:31:16.743  5578  5578 D BluetoothMapAppObserver: createReceiver()
09-15 10:31:16.745  5578  5578 D BluetoothMapAppObserver: initObservers()
09-15 10:31:16.745  5578  5578 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 10:31:16.753  5578  5578 V SapService: SapBinder()
,09-15 10:31:16.753  5578  5578 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:16.754  5578  5578 D SapService: Received start request. Starting profile...
09-15 10:31:16.754  5578  5578 V SapService: start()
,09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isTurningOn()=true
,09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:16.756  5578  5607 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isTurningOn()=true
,09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:16.756  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 10:31:16.757  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.757  5578  5578 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:16.757  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:16.757  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:16.757  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 10:31:16.758  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:16.759  5578  5578 V BluetoothAdapterState: isTurningOff()=false
09-15 10:31:16.759  5578  5578 V BluetoothAdapterState: isTurningOn()=true
09-15 10:31:16.759  5578  5578 V BluetoothAdapterState: isBleTurningOn()=false
09-15 10:31:16.759  5578  5578 V BluetoothAdapterState: isBleTurningOff()=false
09-15 10:31:16.759  5578  5590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 10:31:16.759  5578  5590 D BluetoothAdapterProperties: ScanMode =  20
09-15 10:31:16.759  5578  5590 D BluetoothAdapterProperties: State =  11
09-15 10:31:16.761  5578  5590 D BluetoothAdapterProperties: Setting state to 12
09-15 10:31:16.762  5578  5590 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 10:31:16.762  5578  5590 I BluetoothAdapterState: Entering OnState
09-15 10:31:16.762  5477  5487 D BluetoothMap: onBluetoothStateChange: up=true
09-15 10:31:16.763  5578  5594 D BluetoothAdapterProperties: Scan Mode:21
09-15 10:31:16.763  5371  5577 D BluetoothAdapter: enable(): BT is already enabled..!
09-15 10:31:16.763  5578  5594 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-15 10:31:16.764  5477  5488 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 10:31:16.766  5477  5477 D BluetoothMap: Proxy object connected
09-15 10:31:16.767  3087  3101 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:16.767  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:16.768  5477  5487 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:16.769   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:16.769   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 10:31:16.769  3087  3087 D BluetoothA2dp: Proxy object connected
,09-15 10:31:16.770  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:16.766  5477  5477 D MapProfile: Bluetooth service connected
,09-15 10:31:16.770  5477  5477 D BluetoothMap: getConnectedDevices()
09-15 10:31:16.771  5578  5578 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 10:31:16.771   929   929 D BluetoothA2dp: Proxy object connected
09-15 10:31:16.771  5578  5578 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 10:31:16.772   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:16.772   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:16.773  3087  3683 D BluetoothPan: onBluetoothStateChange on: true
09-15 10:31:16.773  5578  5578 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:16.774  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:16.774  3087  3101 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:16.775  3087  3104 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 10:31:16.776  5578  5578 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:16.777  5477  5488 D BluetoothPan: onBluetoothStateChange on: true
,09-15 10:31:16.777  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:16.777  5578  5578 D ObexServerSockets: Succeed to create listening sockets 
09-15 10:31:16.778  5578  5578 D ObexServerSockets0: startAccept()
09-15 10:31:16.778  5578  5578 D ObexServerSockets0: prepareForNewConnect()
,09-15 10:31:16.780  5578  5578 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-15 10:31:16.780  5578  5578 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 10:31:16.780  5578  5617 D ObexServerSockets0: Accepting socket connection...
09-15 10:31:16.780  5578  5618 D ObexServerSockets0: Accepting socket connection...
09-15 10:31:16.781  3087  3087 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:31:16.781  3087  3087 D PanProfile: Bluetooth service connected
09-15 10:31:16.781  5477  5477 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 10:31:16.781  5477  5477 D PanProfile: Bluetooth service connected
,09-15 10:31:16.782  3087  3101 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-15 10:31:16.785  5477  5614 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 10:31:16.785  3087  3087 D BluetoothInputDevice: Proxy object connected
09-15 10:31:16.786  3087  3087 D HidProfile: Bluetooth service connected
09-15 10:31:16.786  3478  3702 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 10:31:16.787  5477  5488 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 10:31:16.788  3087  3683 D BluetoothMap: onBluetoothStateChange: up=true
09-15 10:31:16.789  3087  3087 D BluetoothMap: Proxy object connected
09-15 10:31:16.789  3087  3087 D MapProfile: Bluetooth service connected
09-15 10:31:16.789  3087  3087 D BluetoothMap: getConnectedDevices()
09-15 10:31:16.790  5477  5477 D BluetoothA2dp: Proxy object connected
09-15 10:31:16.790   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 10:31:16.791  5578  5578 D BluetoothMapService: onReceive
09-15 10:31:16.791  5578  5578 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 10:31:16.791  5578  5578 D BluetoothMapService: STATE_ON
09-15 10:31:16.791   929   929 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-15 10:31:16.792  5477  5477 D BluetoothInputDevice: Proxy object connected
,09-15 10:31:16.792  5477  5477 D HidProfile: Bluetooth service connected
09-15 10:31:16.793  5578  5619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:16.793  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:16.794  5578  5619 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 10:31:16.794  5578  5619 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-15 10:31:16.795  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:16.798  5477  5477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 10:31:16.803  3557  3557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 10:31:16.803  5477  5477 D DockEventReceiver: finishStartingService: stopping service
,09-15 10:31:16.810  5477  5477 D BluetoothPbap: Proxy object connected
,09-15 10:31:16.810  5477  5477 D PbapServerProfile: Bluetooth service connected
,09-15 10:31:16.815  5578  5578 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 10:31:16.815  5578  5578 D ObexServerSockets0: prepareForNewConnect()
09-15 10:31:16.818  3087  3087 D BluetoothPbap: Proxy object connected
09-15 10:31:16.818  3087  3087 D PbapServerProfile: Bluetooth service connected
09-15 10:31:16.819  5578  5623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:31:16.830  5578  5627 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 10:31:16.832  5578  5627 I BtOppRfcommListener: Accept thread started.
,09-15 10:31:17.189  5472  5472 I wpa_supplicant: wlan0: Associated with 84:b2:61:1c:62:d3
,09-15 10:31:17.191  5472  5472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to 84:b2:61:1c:62:d3 completed [id=1 id_str=]
,09-15 10:31:17.197  5472  5472 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=COUNTRY_IE type=COUNTRY alpha2=CH
,09-15 10:31:17.207   929  2951 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "RA-WINGS", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 10:31:17.208   929  2951 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "RA-WINGS"NONE to any
09-15 10:31:17.208   929  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-15 10:31:17.226   929  2951 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "RA-WINGS"NONE to any
,09-15 10:31:17.239   507   923 D CommandListener: Setting iface cfg
,09-15 10:31:17.246   929  2951 D WifiStateMachine: Start Dhcp Watchdog 2
,09-15 10:31:17.252   929  2951 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-15 10:31:17.258   929  5631 D DhcpClient: Receive thread started
,09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:17.269  5371  5577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:17.272  5371  5577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:17.277  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:17.279   929  3732 D WifiService: setWifiEnabled: false pid=5371, uid=10077
09-15 10:31:17.279   929  3732 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:17.284   929  3550 D WifiService: setWifiEnabled: false pid=5371, uid=10077
,09-15 10:31:17.284   929  3550 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:17.353   929  2951 E native  : do suspend false
,09-15 10:31:17.372   929  2951 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{2}, ntable=[]
,09-15 10:31:17.373   929  5630 D DhcpClient: Broadcasting DHCPDISCOVER
,09-15 10:31:17.373   929  2951 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
09-15 10:31:17.373   929  2951 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "RA-WINGS"NONE to any
,09-15 10:31:17.385   929  2951 E native  : do suspend true
,09-15 10:31:17.410   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:31:17.418   929  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,09-15 10:31:17.418   929  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,09-15 10:31:17.426   929  5631 D DhcpClient: Receive thread stopped
,09-15 10:31:17.432   929  2964 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-15 10:31:17.432   929  2964 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-15 10:31:17.435   929   929 D RttService: SCAN_AVAILABLE : 1
09-15 10:31:17.435   929  3029 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 10:31:17.440   929  2951 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-15 10:31:17.451   929  2951 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 10:31:17.452   929  2951 E native  : do suspend true
,09-15 10:31:17.476   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:31:17.482   929  2951 D DhcpClient: doQuit
09-15 10:31:17.483   929  2951 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 10:31:17.483   929  5630 D DhcpClient: onQuitting
,09-15 10:31:17.485  5472  5472 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-15 10:31:17.503  5472  5472 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:17.505  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:17.508  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:17.508  5472  5472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=84:b2:61:1c:62:d3 reason=3 locally_generated=1
,09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:17.514  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:17.517  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:17.520  5472  5472 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 10:31:17.532  5472  5472 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 10:31:17.636   929  2951 D wifi    : In wifi stop Hal
,09-15 10:31:17.636  4251  4251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 10:31:17.636   929  2951 D wifi    : halHandle = 0x7f965f7700, mVM = 0x7fb1d4d140, mCls = 0x186a
,09-15 10:31:17.636   929  5471 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-15 10:31:17.637   929  5471 D WifiHAL : Got a signal to exit!!!
09-15 10:31:17.637   929  5471 I WifiHAL : Exit wifi_event_loop
09-15 10:31:17.639   929  2951 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-15 10:31:17.640   929  2951 E WifiHAL : Event processing terminated
09-15 10:31:17.641   929  2951 D wifi    : In wifi cleaned up handler
,09-15 10:31:17.641   929  2951 I WifiHAL : Internal cleanup completed
,09-15 10:31:17.646  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:17.651  3583  3991 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 10:31:17.652  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:17.657   929  5471 D wifi    : set interface wlan0 flags (DOWN)
,09-15 10:31:17.658   929  2951 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:17.795  5371  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:17.801  5371  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 10:31:17.809  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:17.811   929  3123 D WifiService: setWifiEnabled: true pid=5371, uid=10077
09-15 10:31:17.811   929  3123 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 10:31:17.816   929  3391 D WifiService: setWifiEnabled: true pid=5371, uid=10077
09-15 10:31:17.816   929  3391 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:17.865   929   946 D Tethering: InitialState.processMessage what=4
09-15 10:31:17.868   507   923 D SoftapController: Softap fwReload - Ok
09-15 10:31:17.869   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 10:31:17.871   507   923 D CommandListener: Setting iface cfg
,09-15 10:31:17.872   507   923 D CommandListener: Trying to bring down wlan0
09-15 10:31:17.873   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 10:31:17.877   929  2951 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 10:31:18.319   929   940 D WifiService: setWifiEnabled: true pid=5371, uid=10077
,09-15 10:31:18.323   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 10:31:18.483   929  2951 D wifi    : set interface wlan0 flags (UP)
,09-15 10:31:18.483   929  2951 I WifiHAL : Initializing wifi
,09-15 10:31:18.483   929  2951 I WifiHAL : Creating socket
,09-15 10:31:18.488   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 10:31:18.491   929  2951 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 10:31:18.491   929  2951 D wifi    : Did set static halHandle = 0x7f965f7700
09-15 10:31:18.491   929  2951 D wifi    : halHandle = 0x7f965f7700, mVM = 0x7fb1d4d140, mCls = 0x190a
09-15 10:31:18.492   929  2951 D wifi    : array field set
,09-15 10:31:18.492   929  2951 I WifiNative-HAL: interface[0] = wlan0
09-15 10:31:18.494   929  5638 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547983685376
,09-15 10:31:18.495   929  5638 D wifi    : waitForHalEvents called, vm = 0x7fb1d4d140, obj = 0x190a, env = 0x7f965d5180
,09-15 10:31:18.561  5639  5639 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 10:31:18.584  5639  5639 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:31:18.594  5639  5639 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 10:31:18.595  5639  5639 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 10:31:18.596   929  2951 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 10:31:18.608  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:18.610  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:18.616   929  2951 D WifiConfigStore: Loading config and enabling all networks 
,09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:18.620  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:18.621  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:18.625  5371  5371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 10:31:18.627  5371  5371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:18.631   929  2951 D WifiConfigStore: loaded 0 passpoint configs
,09-15 10:31:18.631   929  2951 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 10:31:18.632   929  2951 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 10:31:18.633   929  2951 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 10:31:18.634   929  2951 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-15 10:31:18.634   929  2951 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 10:31:18.634   929  2951 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 10:31:18.634   929  2951 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 10:31:18.638   929  2951 D WifiNative-HAL: Setting external_sim to 1
,09-15 10:31:18.639  4251  4251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 10:31:18.639   929  2951 D wifi    : setting dfs flag to true, 0x7f979ab360
09-15 10:31:18.640   929  2951 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 10:31:18.640   929  2951 D wifi    : setting scan oui 0x7f979ab360
,09-15 10:31:18.640   929  2951 D WifiHAL : Sending mac address OUI
,09-15 10:31:18.653   929  2951 E native  : do suspend true
,09-15 10:31:18.658   929  2951 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 10:31:18.659   929   929 D RttService: SCAN_AVAILABLE : 3
09-15 10:31:18.659   929  3029 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 10:31:18.659   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-15 10:31:18.660   507   923 D CommandListener: Setting iface cfg
,09-15 10:31:18.663   929  2950 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '80 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 80 Failed to set address (No such device)'
,09-15 10:31:18.663   929  2950 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 10:31:18.669   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=247593 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-15 10:31:18.670   929  2950 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 10:31:18.671   929  2950 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:18.827  5371  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:18.829  5371  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:18.832  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:18.833  5371  5417 D BluetoothAdapter: enable(): BT is already enabled..!
,09-15 10:31:18.833   929  3747 D WifiService: setWifiEnabled: true pid=5371, uid=10077
09-15 10:31:18.833   929  3747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-15 10:31:18.834  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 10:31:18.834  5371  5417 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 10:31:18.834  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:31:18.834  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 10:31:18.834  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e99d removed from the list
09-15 10:31:18.834  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:31:18.834  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a97e12 removed from the list
09-15 10:31:18.834  5371  5417 D io.jxcore.node.ConnectivityMonitor: stop
09-15 10:31:18.834  5371  5417 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 10:31:18.834  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 10:31:18.838  5371  5641 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-15 10:31:18.838  5371  5641 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 10:31:19.355  5371  5641 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-15 10:31:19.356  5371  5641 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 10:31:19.357  5371  5641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:31:19.357  5371  5643 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-15 10:31:19.357  5371  5643 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-15 10:31:19.357  5371  5643 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:31:19.357  5371  5641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:31:19.359  5371  5643 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 10:31:19.362  5371  5646 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 218, name: OutgoingSocketThread/Sender)
,09-15 10:31:19.362  5371  5643 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-15 10:31:19.362  5371  5641 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 10:31:19.364  5371  5647 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 219, name: IncomingSocketThread/Sender)
,09-15 10:31:19.365  5371  5649 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 220, name: OutgoingSocketThread/Receiver)
09-15 10:31:19.366  5371  5648 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 221, name: IncomingSocketThread/Receiver)
,09-15 10:31:19.367  5371  5649 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 220, thread name: OutgoingSocketThread/Receiver)
09-15 10:31:19.367  5371  5649 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 10:31:19.367  5371  5649 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 220, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-15 10:31:19.368  5371  5648 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 221, thread name: IncomingSocketThread/Receiver)
,09-15 10:31:19.368  5371  5648 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-15 10:31:19.368  5371  5648 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 221, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-15 10:31:19.855  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-15 10:31:19.857  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-15 10:31:19.864  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@939d087 Bundle[{}]
,09-15 10:31:19.865  5371  5417 I io.jxcore.node.LifeCycleMonitor: start: OK
09-15 10:31:19.865  5371  5417 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-15 10:31:19.867  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-15 10:31:19.870  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-15 10:31:19.870  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-15 10:31:19.871  5371  5417 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 10:31:19.879  5371  5650 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-15 10:31:19.880  5371  5650 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 10:31:20.391  5371  5650 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-15 10:31:20.391  5371  5652 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-15 10:31:20.391  5371  5650 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 10:31:20.391  5371  5652 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-15 10:31:20.392  5371  5650 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:31:20.392  5371  5652 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:31:20.393  5371  5650 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 10:31:20.393  5371  5652 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 10:31:20.395  5371  5654 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 232, name: OutgoingSocketThread/Sender)
,09-15 10:31:20.395  5371  5652 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-15 10:31:20.397  5371  5650 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 10:31:20.398  5371  5655 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 233, name: IncomingSocketThread/Sender)
,09-15 10:31:20.400  5371  5656 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 235, name: IncomingSocketThread/Receiver)
,09-15 10:31:20.401  5371  5657 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 234, name: OutgoingSocketThread/Receiver)
09-15 10:31:20.401  5371  5656 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 235, thread name: IncomingSocketThread/Receiver)
09-15 10:31:20.401  5371  5656 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-15 10:31:20.402  5371  5656 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 235, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-15 10:31:20.403  5371  5657 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 234, thread name: OutgoingSocketThread/Receiver)
09-15 10:31:20.403  5371  5657 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 10:31:20.403  5371  5657 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 234, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-15 10:31:20.898  5371  5417 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 244)
,09-15 10:31:20.899  5371  5417 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-15 10:31:20.899  5371  5417 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 245)
,09-15 10:31:20.904  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 10:31:20.905  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99b9fe0 added. We now have 3 listener(s)
,09-15 10:31:20.909  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 10:31:20.910  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 10:31:20.910  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 10:31:20.910  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 10:31:20.910  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9398299 added. We now have 3 listener(s)
09-15 10:31:20.911  5371  5417 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 10:31:20.912  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 10:31:20.920  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 10:31:20.924  5371  5417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 10:31:20.927  5371  5417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 10:31:20.927  5371  5417 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 10:31:20.930  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 10:31:20.932  5371  5371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 10:31:20.933  5371  5417 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-15 10:31:20.933  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-15 10:31:20.934  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-15 10:31:20.934  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 10:31:20.934  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 10:31:20.934  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:20.935  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 10:31:20.939  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:31:20.939  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-15 10:31:20.940  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 10:31:20.940  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 10:31:20.941  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-15 10:31:20.941  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:20.941  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 10:31:20.942  5371  5658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:20.940  5616  5616 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31684]" dev="sockfs" ino=31684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:31:20.940  5616  5616 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31684]" dev="sockfs" ino=31684 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:20.945  5371  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 10:31:20.946  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:31:20.946  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 10:31:20.949  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:31:20.950  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 10:31:20.950  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:31:20.952  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-15 10:31:20.952  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:31:20.953  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-15 10:31:20.953  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:20.953  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:20.953  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 10:31:20.954  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:20.957  5578  5615 D BtGatt.GattService: registerClient() - UUID=0a2d1a6d-4d0f-4a6f-af2c-633ae3d833d6
09-15 10:31:20.958  5578  5594 D BtGatt.GattService: onClientRegistered() - UUID=0a2d1a6d-4d0f-4a6f-af2c-633ae3d833d6, clientIf=5
,09-15 10:31:20.958  5371  5381 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 10:31:20.960  5578  5596 D BtGatt.AdvertiseManager: message : 0
09-15 10:31:20.963  5578  5596 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:31:20.973  5578  5594 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:31:20.979  5578  5594 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:31:20.980  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-15 10:31:20.980  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 10:31:20.981  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 10:31:20.982  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:20.982  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:31:20.983  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:31:20.983  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 10:31:20.983  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 10:31:20.983  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-15 10:31:20.985  5371  5371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:20.985  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:21.486  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 10:31:21.487  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:31:21.487  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:31:24.485  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-15 10:31:24.485  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 10:31:24.485  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 10:31:24.486  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:31:24.486  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-15 10:31:24.487  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:31:24.487  5371  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:31:24.487  5371  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:31:24.487  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 10:31:24.487  5371  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-15 10:31:24.487  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 10:31:24.487  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:31:24.487  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:31:24.487  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 10:31:24.487  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-15 10:31:24.489  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:31:24.491  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:24.491  5371  5417 D BluetoothLeScanner: could not find callback wrapper
09-15 10:31:24.491  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:31:24.492  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 10:31:24.494  5578  5596 D BtGatt.AdvertiseManager: message : 1
,09-15 10:31:24.495  5578  5596 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 10:31:24.509  5578  5594 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 10:31:24.510  5578  5594 D BtGatt.GattService: Client app is not null!
,09-15 10:31:24.511  5578  5588 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:31:24.512  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 10:31:24.512  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-15 10:31:24.512  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 10:31:24.512  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 10:31:24.512  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-15 10:31:24.514  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:24.514  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:31:24.514  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:31:24.515  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 10:31:24.517  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 10:31:24.517  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:31:24.517  5371  5371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:31:24.518  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:24.518  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:24.518  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:24.523  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 10:31:24.524  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 10:31:24.524  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 10:31:24.525  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 10:31:24.525  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:24.525  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 10:31:24.529  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 10:31:24.530  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 10:31:24.534  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 10:31:24.535  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 10:31:24.535  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 10:31:24.541  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 10:31:24.541  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:31:24.542  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 10:31:24.544  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:24.547  5578  5605 D BtGatt.GattService: registerClient() - UUID=8444ff98-74c1-421b-8d9c-1bdfcfc20b58
,09-15 10:31:24.548  5578  5594 D BtGatt.GattService: onClientRegistered() - UUID=8444ff98-74c1-421b-8d9c-1bdfcfc20b58, clientIf=5
,09-15 10:31:24.548  5371  5381 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:31:24.549  5578  5616 D BtGatt.GattService: start scan with filters
,09-15 10:31:24.555  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 10:31:24.555  5578  5597 D BtGatt.ScanManager: handling starting scan
09-15 10:31:24.555  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:31:24.555  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 10:31:24.556  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 10:31:24.557  5578  5597 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8b59708
,09-15 10:31:24.560  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:31:24.560  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 10:31:24.560  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 10:31:24.563  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:31:24.566  5578  5594 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 10:31:24.566  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:24.567  5578  5597 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 10:31:24.574  5578  5594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:31:24.574  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:24.574  5578  5597 D BtGatt.ScanManager: Starting BLE batch scan
09-15 10:31:24.575  5578  5597 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 10:31:24.587  5578  5594 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 10:31:24.587  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:24.593  5578  5594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 10:31:24.593  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:25.061  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 10:31:25.062  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:31:25.062  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:31:25.125   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:26.126   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:27.127   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:27.571  5371  5417 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-15 10:31:27.571  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,09-15 10:31:27.572  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 10:31:27.572  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 10:31:27.574  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:27.576  5578  5605 D BtGatt.GattService: stopScan() - queue size =1
09-15 10:31:27.584  5578  5616 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 10:31:27.585  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:31:27.585  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:31:27.585  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 10:31:27.587  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 10:31:27.587  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 10:31:27.587  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 10:31:27.588  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:27.591  5578  5578 D BtGatt.ScanManager: awakened up at time 256515
09-15 10:31:27.593  5578  5615 D BtGatt.GattService: registerClient() - UUID=6dca9377-b8c7-4b91-9eda-12a80b111aa1
09-15 10:31:27.595  5578  5594 D BtGatt.GattService: onClientRegistered() - UUID=6dca9377-b8c7-4b91-9eda-12a80b111aa1, clientIf=5
09-15 10:31:27.596  5371  5382 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 10:31:27.596  5578  5605 D BtGatt.GattService: start scan with filters
,09-15 10:31:27.597  5578  5594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 10:31:27.597  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.597  5578  5597 D BtGatt.ScanManager: stopping BLe Batch
,09-15 10:31:27.604  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 10:31:27.604  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 10:31:27.604  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:27.604  5578  5594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 10:31:27.604  5371  5417 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 10:31:27.605  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 10:31:27.605  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.605  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 10:31:27.605  5578  5597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:31:27.606  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-15 10:31:27.607  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 10:31:27.607  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 10:31:27.607  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 10:31:27.607  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-15 10:31:27.607  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 10:31:27.607  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 10:31:27.607  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 10:31:27.608  5371  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 10:31:27.608  5371  5417 D BluetoothAdapter: STATE_ON
09-15 10:31:27.609  5578  5615 D BtGatt.GattService: stopScan() - queue size =0
09-15 10:31:27.607  5616  5616 W Binder_5: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31696]" dev="sockfs" ino=31696 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 10:31:27.607  5616  5616 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31696]" dev="sockfs" ino=31696 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 10:31:27.610  5578  5605 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:31:27.610  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:31:27.610  5371  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-15 10:31:27.610  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 10:31:27.610  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 10:31:27.610  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 10:31:27.610  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 10:31:27.612  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:27.613  5371  5417 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 10:31:27.615  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-15 10:31:27.615  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 10:31:27.616  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-15 10:31:27.616  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:27.616  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 10:31:27.616  5371  5417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 10:31:27.617  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:27.620  5578  5616 D BtGatt.GattService: registerClient() - UUID=fa646886-806a-4894-9856-4dbc5d5178de
09-15 10:31:27.620  5578  5594 D BtGatt.GattService: onClientRegistered() - UUID=fa646886-806a-4894-9856-4dbc5d5178de, clientIf=5
,09-15 10:31:27.620  5371  5381 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-15 10:31:27.622  5578  5596 D BtGatt.AdvertiseManager: message : 0
,09-15 10:31:27.624  5578  5596 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 10:31:27.624  5578  5594 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-15 10:31:27.624  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.624  5578  5594 D BtGatt.GattService: current time is 256548761193
09-15 10:31:27.625  5578  5594 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -88, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -88, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -76, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 10:31:27.626  5578  5597 D BtGatt.ScanManager: handling starting scan
,09-15 10:31:27.627  5578  5594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-15 10:31:27.628  5578  5594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-15 10:31:27.628  5578  5594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 10:31:27.628  5578  5594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 10:31:27.629  5578  5594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 10:31:27.629  5578  5594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-15 10:31:27.639  5578  5594 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 10:31:27.644  5578  5594 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 10:31:27.644  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.644  5578  5597 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 10:31:27.648  5578  5594 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 10:31:27.649  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 10:31:27.649  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 10:31:27.651  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 10:31:27.652  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-15 10:31:27.652  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 10:31:27.652  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 10:31:27.652  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 10:31:27.652  5371  5371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 10:31:27.653  5371  5371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 10:31:27.653  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-15 10:31:27.654  5578  5594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 10:31:27.654  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.654  5578  5597 D BtGatt.ScanManager: Starting BLE batch scan
09-15 10:31:27.654  5578  5597 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 10:31:27.655  5371  5371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:27.655  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 10:31:27.664  5578  5594 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 10:31:27.664  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:27.669  5578  5594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 10:31:27.669  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:27.676  5578  5594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-15 10:31:27.676  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.676  5578  5597 D BtGatt.ScanManager: stopping BLe Batch
,09-15 10:31:27.681  5578  5594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 10:31:27.682  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 10:31:27.682  5578  5597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 10:31:27.687  5578  5594 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 10:31:27.687  5578  5594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 10:31:28.128   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:28.156  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 10:31:28.156  5371  5371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:31:28.157  5371  5371 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 10:31:29.129   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 10:31:30.129   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 10:31:31.157  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 10:31:31.157  5371  5417 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-15 10:31:31.157  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 10:31:31.157  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-15 10:31:31.158  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 10:31:31.158  5371  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 10:31:31.158  5371  5417 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 10:31:31.158  5371  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 10:31:31.158  5371  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 10:31:31.158  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 10:31:31.159  5371  5371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 10:31:31.159  5371  5417 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@99b9fe0 removed from the list
,09-15 10:31:31.159  5371  5371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 10:31:31.159  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 10:31:31.159  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 10:31:31.159  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 10:31:31.160  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 10:31:31.160  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 10:31:31.162  5371  5417 D BluetoothAdapter: STATE_ON
,09-15 10:31:31.162  5371  5417 D BluetoothLeScanner: could not find callback wrapper
09-15 10:31:31.163  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 10:31:31.163  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 10:31:31.164  5578  5596 D BtGatt.AdvertiseManager: message : 1
09-15 10:31:31.166  5578  5596 D BtGatt.AdvertiseManager: stop advertise for client 5
09-15 10:31:31.178  5578  5594 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-15 10:31:31.178  5578  5594 D BtGatt.GattService: Client app is not null!
,09-15 10:31:31.180  5578  5605 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 10:31:31.181  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 10:31:31.181  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 10:31:31.181  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 10:31:31.181  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 10:31:31.181  5371  5417 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-15 10:31:31.185  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:31.185  5371  5417 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 10:31:31.185  5371  5417 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 10:31:31.186  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 10:31:31.188  5371  5417 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9398299 removed from the list
09-15 10:31:31.188  5371  5417 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 10:31:31.188  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:31.188  5371  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 10:31:31.188  5371  5371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 10:31:31.189  5371  5371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 10:31:31.191  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-15 10:31:31.191  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-15 10:31:31.191  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 10:31:31.192  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 10:31:31.192  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 10:31:31.192  5371  5417 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 10:31:31.201  5371  5663 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 265, name: My test thread name)
,09-15 10:31:31.690  5371  5371 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 10:31:33.200  5371  5417 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 265
,09-15 10:31:33.201  5371  5417 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 265, name: My test thread name)
,09-15 10:31:33.206  5371  5664 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 266, name: My test thread name)
,09-15 10:31:33.207  5371  5664 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 266, thread name: My test thread name)
,09-15 10:31:33.207  5371  5664 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 266, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-15 10:31:33.211  5371  5417 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 10:31:33.218  5371  5665 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 270, name: My test thread name)
,09-15 10:31:33.219  5371  5665 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 270, thread name: My test thread name): Test exception.
09-15 10:31:33.219  5371  5665 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 270, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-15 10:31:33.225  5371  5417 I jxcore-log: *Native tests were executed*
09-15 10:31:33.225  5371  5417 I jxcore-log: 
,09-15 10:31:33.226  5371  5417 I jxcore-log: Total number of executed tests:  82
09-15 10:31:33.226  5371  5417 I jxcore-log: 
09-15 10:31:33.226  5371  5417 I jxcore-log: Number of passed tests:  82
09-15 10:31:33.226  5371  5417 I jxcore-log: 
,09-15 10:31:33.227  5371  5417 I jxcore-log: Number of failed tests:  0
09-15 10:31:33.227  5371  5417 I jxcore-log: 
09-15 10:31:33.227  5371  5417 I jxcore-log: Number of ignored tests:  0
09-15 10:31:33.227  5371  5417 I jxcore-log: 
,09-15 10:31:33.228  5371  5417 I jxcore-log: Total duration:  23951
09-15 10:31:33.228  5371  5417 I jxcore-log: 
,09-15 10:31:33.229  5371  5417 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-15 10:31:33.229  5371  5417 I jxcore-log: 
,09-15 10:31:33.235  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:31:33.235  5371  5417 I jxcore-log: 
09-15 10:31:33.242  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:31:33.242  5371  5417 I jxcore-log: 
09-15 10:31:33.244  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:31:33.244  5371  5417 I jxcore-log: 
09-15 10:31:33.247  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 10:31:33.247  5371  5417 I jxcore-log: 
,09-15 10:31:33.250  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 10:31:33.250  5371  5417 I jxcore-log: 
,09-15 10:31:33.253  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 10:31:33.253  5371  5417 I jxcore-log: 
,09-15 10:31:33.253  5371  5371 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 10:31:33.256  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 10:31:33.256  5371  5417 I jxcore-log: 
,09-15 10:31:33.259  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.259  5371  5417 I jxcore-log: 
,09-15 10:31:33.260  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:31:33.260  5371  5417 I jxcore-log: 
,09-15 10:31:33.261  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:31:33.261  5371  5417 I jxcore-log: 
,09-15 10:31:33.263  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:31:33.263  5371  5417 I jxcore-log: 
,09-15 10:31:33.264  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:31:33.264  5371  5417 I jxcore-log: 
,09-15 10:31:33.265  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.265  5371  5417 I jxcore-log: 
,09-15 10:31:33.267  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.267  5371  5417 I jxcore-log: 
,09-15 10:31:33.268  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.268  5371  5417 I jxcore-log: 
09-15 10:31:33.269  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.269  5371  5417 I jxcore-log: 
,09-15 10:31:33.270  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.270  5371  5417 I jxcore-log: 
,09-15 10:31:33.271  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.271  5371  5417 I jxcore-log: 
09-15 10:31:33.272  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.272  5371  5417 I jxcore-log: 
09-15 10:31:33.272  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.272  5371  5417 I jxcore-log: 
,09-15 10:31:33.273  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.273  5371  5417 I jxcore-log: 
,09-15 10:31:33.274  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.274  5371  5417 I jxcore-log: 
,09-15 10:31:33.275  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.275  5371  5417 I jxcore-log: 
,09-15 10:31:33.276  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.276  5371  5417 I jxcore-log: 
,09-15 10:31:33.277  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.277  5371  5417 I jxcore-log: 
,09-15 10:31:33.278  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.278  5371  5417 I jxcore-log: 
,09-15 10:31:33.279  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.279  5371  5417 I jxcore-log: 
,09-15 10:31:33.280  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:31:33.280  5371  5417 I jxcore-log: 
09-15 10:31:33.281  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:31:33.281  5371  5417 I jxcore-log: 
09-15 10:31:33.281  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 10:31:33.281  5371  5417 I jxcore-log: 
09-15 10:31:33.282  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.282  5371  5417 I jxcore-log: 
09-15 10:31:33.283  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.283  5371  5417 I jxcore-log: 
09-15 10:31:33.283  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.283  5371  5417 I jxcore-log: 
,09-15 10:31:33.284  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 10:31:33.284  5371  5417 I jxcore-log: 
,09-15 10:31:33.285  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 10:31:33.285  5371  5417 I jxcore-log: 
,09-15 10:31:33.287  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 10:31:33.287  5371  5417 I jxcore-log: 
,09-15 10:31:33.288  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 10:31:33.288  5371  5417 I jxcore-log: 
,09-15 10:31:33.289  5371  5417 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 10:31:33.289  5371  5417 I jxcore-log: 
,09-15 10:31:33.356  5371  5663 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 265, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-15 10:31:33.646  5666  5666 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-15 10:31:33.651  5666  5666 D AndroidRuntime: CheckJNI is OFF
,09-15 10:31:33.681  5666  5666 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-15 10:31:33.715  5666  5666 I Radio-JNI: register_android_hardware_Radio DONE
,09-15 10:31:33.733  5666  5666 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-15 10:31:33.744   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-15 10:31:33.745   929   942 I ActivityManager: Killing 5371:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-15 10:31:33.812   929  3131 D GraphicsStats: Buffer count: 2
09-15 10:31:33.812   929  3123 I WindowState: WIN DEATH: Window{e1c66e6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-15 10:31:33.812   929  2960 D WifiService: Client connection lost with reason: 4
,09-15 10:31:33.866   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-15 10:31:33.866   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-15 10:31:33.867   929   952 I art     : Starting a blocking GC Explicit
09-15 10:31:33.867   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-15 10:31:33.867   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 10:31:33.867   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:33.867   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:33.867   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 10:31:33.867   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-15 10:31:33.868   929   942 I ActivityManager:   Force finishing activity ActivityRecord{a429fe3 u0 com.test.thalitest/.MainActivity t2}
,09-15 10:31:33.878   929  3550 W ActivityManager: Spurious death for ProcessRecord{8c33841 0:com.test.thalitest/u0a77}, curProc for 5371: null
,09-15 10:31:33.947   929   952 I art     : Explicit concurrent mark sweep GC freed 30730(1964KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.582ms total 79.855ms
,09-15 10:31:33.965   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-15 10:31:33.968  5666  5666 I art     : System.exit called, status: 0
,09-15 10:31:33.968  5666  5666 I AndroidRuntime: VM exiting with result code 0.
,09-15 10:31:33.975   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-15 10:31:33.983   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-15 10:31:33.990  5578  5578 D BluetoothMapAppObserver: onReceive
09-15 10:31:33.990  5578  5578 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-15 10:31:33.993  3371  3371 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 10:31:33.997  3583  3926 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 10:31:34.004   929  2940 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-15 10:31:34.023  3371  5677 I Keyboard.Facilitator.DecoderInitializer: run()
,09-15 10:31:34.025  3393  5678 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-15 10:31:34.038  3371  5677 I Decoder : createOrResetDecoder
,09-15 10:31:34.050  3478  3478 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-15 10:31:34.051  3557  3557 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-15 10:31:34.052  3557  3557 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-15 10:31:34.066  3890  5683 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-15 10:31:34.066  3890  5683 D AccountUtils: Clearing selected account for com.test.thalitest
,09-15 10:31:34.071   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-15 10:31:34.098  3557  3557 I ConfigService: onCreate
,09-15 10:31:34.100    27    27 W kworker/2:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:31:34.104    27    27 W kworker/2:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:31:34.110    27    27 W kworker/2:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 10:31:34.132  3890  5683 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-15 10:31:34.137  3371  5677 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-15 10:31:34.155  3890  5683 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:34.155  3890  5683 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-15 10:31:34.155  3890  5683 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-15 10:31:34.157  3890  5683 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-15 10:31:34.200  3890  3890 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-15 10:31:34.200  3890  3890 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-15 10:31:34.203   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
