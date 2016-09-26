#### Test 86171191508789d_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-26 10:48:58.734   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 10:48:58.735   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-26 10:48:59.192  5675  5675 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-26 10:48:59.198  5675  5675 D AndroidRuntime: CheckJNI is OFF
09-26 10:48:59.227  5675  5675 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-26 10:48:59.262  5675  5675 I Radio-JNI: register_android_hardware_Radio DONE
09-26 10:48:59.279  5675  5675 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-26 10:48:59.285   929   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-26 10:48:59.328   929   940 I ActivityManager: Start proc 5684:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-26 10:48:59.355  5675  5675 D AndroidRuntime: Shutting down VM
,09-26 10:48:59.664   929  3601 I WindowManager: Screenshot max retries 4 of Token{52d5319 ActivityRecord{db26260 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{1ae1d78 u0 Starting com.test.thalitest} drawState=2
,09-26 10:48:59.746  5684  5684 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-26 10:48:59.783  5684  5684 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-26 10:48:59.805  5684  5684 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 614-632)
,09-26 10:48:59.805  5684  5684 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-26 10:48:59.825  5684  5684 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c00c6a}
,09-26 10:48:59.826  5684  5684 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-26 10:48:59.826  5684  5684 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-26 10:48:59.831  5684  5684 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-26 10:48:59.832  5684  5684 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-26 10:48:59.866  5684  5684 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-26 10:48:59.885  5684  5684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-26 10:48:59.886  5684  5684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-26 10:48:59.886  5684  5684 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-26 10:48:59.886  5684  5684 I Adreno  : Build Date                       : 12/06/15
09-26 10:48:59.886  5684  5684 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-26 10:48:59.886  5684  5684 I Adreno  : Local Branch                     : mybranch17112971
09-26 10:48:59.886  5684  5684 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-26 10:48:59.886  5684  5684 I Adreno  : Remote Branch                    : NONE
09-26 10:48:59.886  5684  5684 I Adreno  : Reconstruct Branch               : NOTHING
,09-26 10:48:59.934   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fba0caf:true,
,09-26 10:48:59.956   408   408 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34829]" dev="sockfs" ino=34829 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-26 10:48:59.956   408   408 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34829]" dev="sockfs" ino=34829 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 10:48:59.971  5684  5684 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-26 10:48:59.979  5684  5684 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-26 10:49:00.003  4182  4182 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31946]" dev="sockfs" ino=31946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 10:49:00.006  4182  4182 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31946]" dev="sockfs" ino=31946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-26 10:49:00.010  3640  3640 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34834]" dev="sockfs" ino=34834 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 10:49:00.010  3640  3640 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34834]" dev="sockfs" ino=34834 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-26 10:49:00.015  5684  5708 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-26 10:49:00.040  5684  5721 I OpenGLRenderer: Initialized EGL, version 1.4
,09-26 10:49:00.102   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +434ms (total +802ms)
,09-26 10:49:00.128  5684  5684 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5684
,09-26 10:49:00.212  5684  5684 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-26 10:49:00.331  5684  5724 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -584840912
,09-26 10:49:00.335  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-26 10:49:00.335  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-26 10:49:00.335  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-26 10:49:00.335  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-26 10:49:00.335  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-26 10:49:00.335  5684  5724 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c09bc93 added. We now have 1 listener(s)
,09-26 10:49:00.337  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-26 10:49:00.338  5684  5724 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 10:49:00.338  5684  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:49:00.338  5684  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-26 10:49:00.340  5684  5724 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4296fce added. We now have 1 listener(s)
09-26 10:49:00.340  5684  5724 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:49:00.346  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 10:49:00.346   929  3025 D WifiService: New client listening to asynchronous messages
09-26 10:49:00.346  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413,
09-26 10:49:00.346  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-26 10:49:00.346  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-26 10:49:00.346  5684  5724 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-26 10:49:00.348  5684  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:00.348  5684  5724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-26 10:49:00.353  5684  5724 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:00.353  5684  5724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:00.353  5684  5724 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-26 10:49:00.353  5684  5724 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:49:00.354  5684  5724 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-26 10:49:00.358  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:00.362  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:00.370  5684  5684 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-26 10:49:00.668  5684  5730 W jxcore-log: Initializing JXcore engine
09-26 10:49:00.668  5684  5730 W jxcore-log: JXcore engine is ready
,09-26 10:49:00.690  5730  5730 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11610 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-26 10:49:00.690  5730  5730 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[1815]" dev="sockfs" ino=1815 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-26 10:49:00.690  5730  5730 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-26 10:49:00.690  5730  5730 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33073]" dev="sockfs" ino=33073 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-26 10:49:00.700  5684  5730 W jxcore-log: Starting JXcore engine
,09-26 10:49:00.749  5684  5730 W jxcore-log: Platform android
09-26 10:49:00.749  5684  5730 W jxcore-log: 
,09-26 10:49:00.749  5684  5730 W jxcore-log: Process ARCH arm
09-26 10:49:00.749  5684  5730 W jxcore-log: 
,09-26 10:49:00.848  5684  5730 I jxcore-log: JXcore Cordova bridge is ready!
09-26 10:49:00.848  5684  5730 I jxcore-log: 
,09-26 10:49:00.848  5684  5730 W jxcore-log: JXcore engine is started
,09-26 10:49:00.859  5684  5724 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-26 10:49:00.865  5684  5684 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-26 10:49:01.298   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:49:02.980   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 10:49:08.736   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:09.737   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:10.713  5684  5730 I jxcore-log: 2016-09-26 14:49:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-26 10:49:10.713  5684  5730 I jxcore-log: 
,09-26 10:49:10.715  5684  5730 I jxcore-log: 2016-09-26 14:49:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-26 10:49:10.715  5684  5730 I jxcore-log: 
,09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:10.718  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:49:10.720  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:49:10.722  5684  5730 I jxcore-log: 2016-09-26 14:49:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-26 10:49:10.722  5684  5730 I jxcore-log: 
,09-26 10:49:10.724  5684  5730 I jxcore-log: 2016-09-26 14:49:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-26 10:49:10.724  5684  5730 I jxcore-log: 
,09-26 10:49:10.738   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:10.981  5684  5730 I jxcore-log: 2016-09-26 14:49:10 - DEBUG UnitTest_app: 'Running unit tests'
09-26 10:49:10.981  5684  5730 I jxcore-log: 
,09-26 10:49:10.982  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 10:49:10.982  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbdd10d added. We now have 2 listener(s)
,09-26 10:49:10.982  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 10:49:10.983  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:49:10.983  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 10:49:10.983  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:49:10.983  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9228c2 added. We now have 2 listener(s)
09-26 10:49:10.983  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 10:49:10.983  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 10:49:10.985  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:10.988  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:10.989  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:49:10.990  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:49:10.990  5684  5730 D executeNativeTests: Running unit tests
,09-26 10:49:10.998  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:11.003  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:11.027  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 10:49:11.027  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 added. We now have 3 listener(s)
09-26 10:49:11.028  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 10:49:11.028  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:49:11.028  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 10:49:11.028  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:49:11.028  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 added. We now have 3 listener(s)
09-26 10:49:11.028  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:49:11.028  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 10:49:11.030  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:11.032  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:49:11.034  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:11.034  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 10:49:11.035  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 10:49:11.035  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 10:49:11.035  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 10:49:11.035  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-26 10:49:11.036  5684  5730 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-26 10:49:11.036  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 10:49:11.036  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-26 10:49:11.036  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:11.036  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:11.036  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:11.036  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:11.036  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:11.036  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:11.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:11.037  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.037  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:49:11.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 10:49:11.037  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 removed from the list
09-26 10:49:11.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:11.037  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 removed from the list
09-26 10:49:11.039  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:11.045  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:11.045  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:11.045  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:11.046  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.046  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:11.046  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:11.046  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:11.046  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:11.046  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
,09-26 10:49:11.047  5684  5730 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-26 10:49:11.047  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:11.047  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:11.047  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:11.048  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:11.048  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.048  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:11.048  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:11.048  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:11.048  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:11.048  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:11.048  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.048  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:11.048  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.048  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:11.048  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:49:11.048  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:11.048  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:11.048  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 10:49:11.051  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 10:49:11.052  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 10:49:11.052  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 10:49:11.052  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 10:49:11.052  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 10:49:11.052  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:11.052  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:11.052  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:11.052  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:11.052  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.052  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:11.052  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:11.052  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:11.052  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:11.052  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:11.052  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.052  5684  5730 D org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:11.052  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:11.052  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:11.053  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:11.053  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:11.053  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:11.053  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:11.053  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 10:49:11.054  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:11.056  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:11.057  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:11.057  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:49:11.057  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:49:11.057  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 10:49:11.057  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 10:49:11.057  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:11.057  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:11.059  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:11.059  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 10:49:11.061  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:11.063  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 10:49:11.066  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:49:11.066  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:49:11.066  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:11.067  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-26 10:49:11.068  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-26 10:49:11.068  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 10:49:11.068  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 10:49:11.069  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 10:49:11.069  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:11.071  4653  4886 D BtGatt.GattService: registerClient() - UUID=8a1a2747-4d98-482b-b74f-69746e83d70b
09-26 10:49:11.072  4653  4728 D BtGatt.GattService: onClientRegistered() - UUID=8a1a2747-4d98-482b-b74f-69746e83d70b, clientIf=5
09-26 10:49:11.074  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 10:49:11.075  4653  4670 D BtGatt.GattService: start scan with filters
09-26 10:49:11.079  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 10:49:11.079  4653  4734 D BtGatt.ScanManager: handling starting scan
09-26 10:49:11.079  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 10:49:11.079  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 10:49:11.079  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-26 10:49:11.080  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:49:11.081  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 10:49:11.081  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:49:11.081  4653  4734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:49:11.081  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 10:49:11.082  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
09-26 10:49:11.088  4653  4728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 10:49:11.088  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:11.089  4653  4734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-26 10:49:11.094  4653  4728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 10:49:11.094  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:11.094  4653  4734 D BtGatt.ScanManager: Starting BLE batch scan
09-26 10:49:11.094  4653  4734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 10:49:11.103  4653  4728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 10:49:11.103  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:11.110  4653  4728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 10:49:11.110  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:49:11.582  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 10:49:11.583  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-26 10:49:11.583  5684  5684 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 10:49:11.739   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:12.058   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 10:49:12.061   929  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-26 10:49:12.740   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:13.741   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 10:49:15.084   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 10:49:15.089   929  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-26 10:49:16.086  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:49:16.086  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:16.087  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-26 10:49:16.087  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:16.087  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 10:49:16.087  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 10:49:16.087  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 10:49:16.087  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-26 10:49:16.087  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 10:49:16.088  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:49:16.088  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-26 10:49:16.089  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:16.090  4653  4887 D BtGatt.GattService: stopScan() - queue size =1
,09-26 10:49:16.091  4653  4878 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 10:49:16.092  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:16.092  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 10:49:16.092  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 10:49:16.093  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 10:49:16.093  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 10:49:16.096  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:49:16.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:16.097  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:49:16.097  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:16.098  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:16.099  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:16.099  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:16.100  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:16.100  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
,09-26 10:49:16.100  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:49:16.100  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:16.100  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 10:49:16.100  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:16.100  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:16.100  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:16.100  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:16.105  4653  4653 D BtGatt.ScanManager: awakened up at time 236932
,09-26 10:49:16.108  4653  4728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 10:49:16.108  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:16.109  4653  4734 D BtGatt.ScanManager: stopping BLe Batch
09-26 10:49:16.110  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:16.110  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 10:49:16.120  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:49:16.121  4653  4728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 10:49:16.121  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:16.121  4653  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 10:49:16.122  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 10:49:16.122  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 10:49:16.123  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:16.124  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:16.127  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:49:16.127  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:16.127  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:49:16.132  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:49:16.132  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:16.133  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:16.136  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 10:49:16.146  4653  4728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-26 10:49:16.147  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:16.147  4653  4728 D BtGatt.GattService: current time is 236975135841
09-26 10:49:16.147  4653  4728 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -70, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -77, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 10:49:16.149  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 10:49:16.150  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 10:49:16.151  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 10:49:16.151  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 10:49:16.151  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-26 10:49:16.151  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-26 10:49:16.638  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 10:49:18.742   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:19.744   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:20.745   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:21.102  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-26 10:49:21.108  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:21.119  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:49:21.124  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:49:21.125  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:49:21.125  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:49:21.125  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 10:49:21.125  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 10:49:21.125  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:21.126  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:21.131  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:21.133  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:49:21.139  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:21.142  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-26 10:49:21.143  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 10:49:21.143  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 10:49:21.144  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:49:21.148  4653  4887 D BtGatt.GattService: registerClient() - UUID=15655b49-4866-4dee-bfb1-6b593d5b378c
09-26 10:49:21.149  4653  4728 D BtGatt.GattService: onClientRegistered() - UUID=15655b49-4866-4dee-bfb1-6b593d5b378c, clientIf=5
,09-26 10:49:21.149  5684  5695 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 10:49:21.150  4653  4878 D BtGatt.GattService: start scan with filters
09-26 10:49:21.154  4653  4734 D BtGatt.ScanManager: handling starting scan
,09-26 10:49:21.155  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 10:49:21.155  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-26 10:49:21.156  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 10:49:21.156  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 10:49:21.160  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:49:21.160  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 10:49:21.161  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 10:49:21.164  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 10:49:21.166  4653  4728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 10:49:21.166  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.166  4653  4734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 10:49:21.169  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
,09-26 10:49:21.173  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:21.173  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-26 10:49:21.173  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:21.173  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-26 10:49:21.173  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:21.173  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 10:49:21.174  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 10:49:21.174  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 10:49:21.174  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 10:49:21.174  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 10:49:21.174  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:49:21.174  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 10:49:21.175  4653  4728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 10:49:21.175  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.175  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:21.175  4653  4734 D BtGatt.ScanManager: Starting BLE batch scan
09-26 10:49:21.175  4653  4734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-26 10:49:21.176  4653  4887 D BtGatt.GattService: stopScan() - queue size =1
09-26 10:49:21.177  4653  4674 D BtGatt.GattService: unregisterClient() - clientIf=5
09-26 10:49:21.178  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:21.178  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 10:49:21.178  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 10:49:21.178  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 10:49:21.178  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-26 10:49:21.190  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 10:49:21.190  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:21.190  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:49:21.190  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:21.191  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:21.191  4653  4728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 10:49:21.192  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:49:21.192  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:21.192  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:49:21.193  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:21.193  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:49:21.193  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:21.193  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 10:49:21.193  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:21.193  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:21.193  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:21.193  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:21.193  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:49:21.197  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:49:21.197  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 10:49:21.201  4653  4728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 10:49:21.201  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:49:21.204  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:49:21.205  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 10:49:21.205  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:49:21.205  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:21.206  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:21.210  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:49:21.210  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:21.210  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:21.213  4653  4728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 10:49:21.213  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:21.213  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.214  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:21.214  4653  4734 D BtGatt.ScanManager: stopping BLe Batch
09-26 10:49:21.214  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:21.217  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 10:49:21.217  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:21.217  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:21.218  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:21.218  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:21.219  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:21.219  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:21.220  5684  5730 D BluetoothLeScanner: could not find callback wrapper
,09-26 10:49:21.220  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:21.220  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:21.220  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:21.221  5684  5730 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-26 10:49:21.223  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:21.224  4653  4728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 10:49:21.225  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.225  4653  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:21.228  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:49:21.231  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:49:21.231  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:49:21.231  4653  4728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 10:49:21.232  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.231  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:49:21.232  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-26 10:49:21.232  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 10:49:21.232  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:21.232  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:49:21.234  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:21.237  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:21.239  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:21.243  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 10:49:21.244  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-26 10:49:21.244  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 10:49:21.244  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:21.246  4653  4674 D BtGatt.GattService: registerClient() - UUID=efa96189-96df-4f2c-97cf-4f8987e11469
09-26 10:49:21.247  4653  4728 D BtGatt.GattService: onClientRegistered() - UUID=efa96189-96df-4f2c-97cf-4f8987e11469, clientIf=5
09-26 10:49:21.247  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 10:49:21.247  4653  4670 D BtGatt.GattService: start scan with filters
,09-26 10:49:21.250  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 10:49:21.250  4653  4734 D BtGatt.ScanManager: handling starting scan
,09-26 10:49:21.250  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 10:49:21.250  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 10:49:21.250  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 10:49:21.253  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:49:21.253  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 10:49:21.253  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:49:21.254  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 10:49:21.257  4653  4728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-26 10:49:21.257  5684  5730 I io.jxcore.node.ConnectionHelper: start: OK
09-26 10:49:21.257  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.257  4653  4734 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 10:49:21.262  4653  4728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-26 10:49:21.262  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:21.262  4653  4734 D BtGatt.ScanManager: Starting BLE batch scan
09-26 10:49:21.263  4653  4734 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 10:49:21.272  4653  4728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 10:49:21.272  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:49:21.277  4653  4728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-26 10:49:21.277  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:49:21.746   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:21.754  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 10:49:21.754  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:49:21.755  5684  5684 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 10:49:22.747   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:23.747   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 10:49:26.257  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:49:26.258  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:26.258  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 10:49:26.258  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:26.258  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-26 10:49:26.258  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 10:49:26.258  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 10:49:26.259  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 10:49:26.259  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-26 10:49:26.259  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:49:26.259  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 10:49:26.261  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:26.263  4653  4886 D BtGatt.GattService: stopScan() - queue size =1
09-26 10:49:26.264  4653  4878 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 10:49:26.265  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:26.266  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 10:49:26.266  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 10:49:26.266  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 10:49:26.266  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 10:49:26.269  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:49:26.269  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:26.269  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:49:26.269  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:26.270  4653  4653 D BtGatt.ScanManager: awakened up at time 247097
09-26 10:49:26.273  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:26.276  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:49:26.276  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:26.276  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:26.278  4653  4728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 10:49:26.278  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:26.279  4653  4734 D BtGatt.ScanManager: stopping BLe Batch
09-26 10:49:26.280  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:26.280  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 10:49:26.285  4653  4728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-26 10:49:26.285  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:26.285  4653  4734 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 10:49:26.288  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:49:26.289  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:49:26.290  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:49:26.290  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:26.291  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:26.293  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:49:26.293  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:26.293  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:26.297  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:26.297  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:49:26.297  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:49:26.300  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 10:49:26.304  4653  4728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-26 10:49:26.304  4653  4728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:49:26.304  4653  4728 D BtGatt.GattService: current time is 247132156750
09-26 10:49:26.304  4653  4728 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -73, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -74, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -78, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 10:49:26.304  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-26 10:49:26.304  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 10:49:26.305  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 10:49:26.305  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 10:49:26.305  4653  4728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-26 10:49:26.801  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 10:49:26.802  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:26.802  5684  5684 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 10:49:31.277  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:49:31.278  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.278  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 10:49:31.278  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.278  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.279  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:31.279  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
,09-26 10:49:31.279  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.279  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.279  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.279  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.281  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:31.281  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.286  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.286  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.286  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:49:31.288  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.288  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.288  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 10:49:31.289  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.289  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
,09-26 10:49:31.290  5684  5730 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-26 10:49:31.292  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.292  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.292  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.293  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.293  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.293  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.293  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.293  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.293  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.294  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:49:31.294  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.294  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.294  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.294  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.297  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.298  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.298  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:49:31.298  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.299  5684  5730 D BluetoothLeScanner: could not find callback wrapper
,09-26 10:49:31.299  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.299  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.299  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.300  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-26 10:49:31.300  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.300  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.300  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.300  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.300  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.301  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:31.301  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.301  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.301  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.301  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.301  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.301  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.301  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.301  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.302  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.302  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.302  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:49:31.303  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.303  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.303  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.303  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.303  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.304  5684  5730 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-26 10:49:31.304  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.304  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.304  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.304  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 10:49:31.305  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.305  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.305  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.305  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.305  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.305  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.305  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.305  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.305  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.305  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:31.306  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:49:31.306  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.307  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.307  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:49:31.307  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.308  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.308  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.308  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.309  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-26 10:49:31.309  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.309  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.309  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 10:49:31.309  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 10:49:31.309  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:31.309  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:31.309  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.309  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.309  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.309  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.309  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.310  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.310  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.310  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.311  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.311  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.311  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.312  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.312  5684  5730 D BluetoothLeScanner: could not find callback wrapper
,09-26 10:49:31.312  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.312  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.312  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.313  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 10:49:31.313  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 10:49:31.313  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 10:49:31.313  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-26 10:49:31.313  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:31.313  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:31.314  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-26 10:49:31.314  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-26 10:49:31.314  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-26 10:49:31.314  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.314  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.314  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.314  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.314  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.314  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.314  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.314  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.314  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.314  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.314  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:31.314  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.315  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.315  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.316  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.316  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.316  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.317  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.317  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.317  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.317  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.317  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.317  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 10:49:31.318  5684  5730 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 10:49:31.318  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-26 10:49:31.320  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-26 10:49:31.320  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-26 10:49:31.321  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-26 10:49:31.322  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-26 10:49:31.322  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-26 10:49:31.323  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 10:49:31.323  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-26 10:49:31.323  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-26 10:49:31.323  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 10:49:31.323  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-26 10:49:31.323  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 10:49:31.323  5684  5730 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-26 10:49:31.323  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-26 10:49:31.326  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-26 10:49:31.327  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-26 10:49:31.327  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-26 10:49:31.328  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-26 10:49:31.328  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-26 10:49:31.328  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-26 10:49:31.328  5684  5730 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-26 10:49:31.328  5684  5730 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-26 10:49:31.328  5684  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-26 10:49:31.330  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.330  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.330  5684  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:49:31.330  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 10:49:31.332  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.332  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.332  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.332  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-26 10:49:31.333  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.333  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.333  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.333  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.334  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.334  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.330  4670  4670 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33846]" dev="sockfs" ino=33846 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 10:49:31.334  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.334  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.330  4670  4670 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33846]" dev="sockfs" ino=33846 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 10:49:31.335  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:49:31.336  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.336  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.336  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-26 10:49:31.336  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
,09-26 10:49:31.336  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.336  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.336  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.336  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.336  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.337  5684  5731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-26 10:49:31.337  5684  5732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-26 10:49:31.337  4653  4875 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-26 10:49:31.337  5684  5730 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-26 10:49:31.338  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:31.338  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.338  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.338  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.338  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.338  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.338  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.338  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.338  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.338  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:49:31.339  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.339  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.339  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.339  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.340  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.340  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.340  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.341  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.341  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.341  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.341  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.341  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.342  5684  5730 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-26 10:49:31.342  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:49:31.343  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.343  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.343  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.343  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.343  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.343  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.343  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.343  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.343  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:49:31.343  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.343  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.343  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.343  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.344  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.344  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.344  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.345  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.345  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.345  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 10:49:31.345  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.346  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.346  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-26 10:49:31.346  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-26 10:49:31.347  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 10:49:31.347  5684  5730 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-26 10:49:31.347  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 10:49:31.347  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-26 10:49:31.347  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 10:49:31.347  5684  5730 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-26 10:49:31.347  5684  5730 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-26 10:49:31.347  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-26 10:49:31.347  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 10:49:31.347  5684  5730 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-26 10:49:31.347  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:49:31.347  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:31.347  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:31.347  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.347  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.348  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.348  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.348  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.348  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.348  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:31.348  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:31.348  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.348  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.348  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.350  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:31.350  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:31.350  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:31.351  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:31.351  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:31.351  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:31.351  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.351  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.352  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:31.352  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.353  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:31.353  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:31.353  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:31.353  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:31.353  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:49:31.353  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:31.353  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:33.749   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:34.749   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:35.750   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:36.250   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 10:49:36.354  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:49:36.354  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
,09-26 10:49:36.354  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:36.354  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:36.354  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.355  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
,09-26 10:49:36.355  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:36.355  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:36.355  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 10:49:36.356  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:36.356  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.356  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:36.356  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:36.356  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.356  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.357  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:36.357  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.357  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.357  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:36.357  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.360  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:36.360  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:36.360  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:36.362  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:36.363  5684  5730 D BluetoothLeScanner: could not find callback wrapper
,09-26 10:49:36.363  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:36.363  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.363  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.366  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-26 10:49:36.367  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:36.368  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-26 10:49:36.370  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-26 10:49:36.370  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-26 10:49:36.370  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-26 10:49:36.371  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 10:49:36.371  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-26 10:49:36.371  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:36.371  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 10:49:36.372  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-26 10:49:36.372  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-26 10:49:36.372  5684  5733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:49:36.372  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.372  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 10:49:36.372  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:36.372  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.373  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-26 10:49:36.373  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 10:49:36.373  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 10:49:36.373  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:49:36.373  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-26 10:49:36.375  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:36.375  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:36.375  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:36.375  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:36.375  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:49:36.375  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:36.373  4878  4878 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33853]" dev="sockfs" ino=33853 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 10:49:36.375  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.378  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:49:36.378  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.378  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-26 10:49:36.378  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:36.378  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:36.378  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:36.378  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:36.378  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-26 10:49:36.373  4878  4878 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33853]" dev="sockfs" ino=33853 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 10:49:36.378  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:36.379  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.379  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:36.379  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:36.379  5684  5733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-26 10:49:36.379  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:49:36.379  5684  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-26 10:49:36.379  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.379  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:36.379  5684  5733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 10:49:36.379  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.379  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:36.384  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:49:36.384  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 10:49:36.392  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:49:36.393  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:49:36.394  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:49:36.394  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 10:49:36.395  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:36.398  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:36.398  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:36.400  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:36.401  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:36.401  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:36.401  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:36.401  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:36.402  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:36.402  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.402  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:49:36.402  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.402  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:49:36.402  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:49:36.403  5684  5730 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-26 10:49:36.403  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-26 10:49:36.403  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-26 10:49:36.404  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:36.404  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-26 10:49:36.404  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:36.404  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:36.404  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:36.404  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:36.404  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.404  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:49:36.404  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:36.404  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.404  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.404  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:36.404  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.404  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:49:36.408  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:49:36.408  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-26 10:49:36.409  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:36.412  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:36.412  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:49:36.413  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.413  5684  5684 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-26 10:49:36.414  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:49:36.414  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:36.414  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:36.415  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:36.415  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:36.415  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:36.415  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.415  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
,09-26 10:49:36.418  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:49:36.419  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:36.419  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:36.419  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:49:36.419  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.419  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.419  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:36.419  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.419  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.419  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:36.419  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.419  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:49:36.419  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.419  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.420  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:36.420  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:36.420  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:49:36.421  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:49:36.421  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:36.421  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:36.421  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.421  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.422  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:49:36.422  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:49:36.422  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:49:36.422  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 10:49:36.422  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.422  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.422  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578f40 not in the list
09-26 10:49:36.422  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.422  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.422  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:36.422  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:36.422  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.422  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:36.422  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:36.424  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:49:36.424  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:49:36.424  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:49:36.425  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:49:36.425  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:49:36.425  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:49:36.425  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:49:36.425  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6dae79 not in the list
09-26 10:49:36.426  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-26 10:49:36.426  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 10:49:36.426  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-26 10:49:36.426  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-26 10:49:36.426  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-26 10:49:36.426  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-26 10:49:36.429  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-26 10:49:36.429  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-26 10:49:36.429  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-26 10:49:36.429  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 10:49:36.430  5684  5730 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-26 10:49:36.430  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-26 10:49:36.430  5684  5730 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-26 10:49:36.430  5684  5730 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-26 10:49:36.430  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-26 10:49:36.430  5684  5730 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-26 10:49:36.431  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-26 10:49:36.431  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-26 10:49:36.431  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-26 10:49:36.431  5684  5730 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-26 10:49:36.433  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:49:36.433  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43d6107 added. We now have 3 listener(s)
09-26 10:49:36.433  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:49:36.435  5684  5730 D BluetoothAdapter: enable(): BT is already enabled..!
,09-26 10:49:36.436   929  3206 D WifiService: setWifiEnabled: true pid=5684, uid=10077
09-26 10:49:36.436   929  3206 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 10:49:36.460  4653  4834 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-26 10:49:36.460  4653  4834 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-26 10:49:36.751   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:36.913  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 10:49:37.752   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:38.753   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 10:49:39.278   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-26 10:49:41.301   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:49:41.441  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 10:49:41.441  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@41ca234 added. We now have 4 listener(s)
09-26 10:49:41.441  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 10:49:41.454  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:49:41.454  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@41ca234 removed from the list
,09-26 10:49:41.455  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:49:41.455  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:49:41.455  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:41.457  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 10:49:41.457  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d5185d added. We now have 4 listener(s)
09-26 10:49:41.457  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 10:49:41.460  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:49:41.460  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d5185d removed from the list
09-26 10:49:41.460  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:49:41.461  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:49:41.461  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:49:41.462  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:49:41.462  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a15e5d2 added. We now have 4 listener(s)
09-26 10:49:41.462  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 10:49:41.467   929  3837 D WifiService: setWifiEnabled: false pid=5684, uid=10077
09-26 10:49:41.467   929  3837 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 10:49:41.474   929  3024 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-26 10:49:41.475   929  3024 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 10:49:41.475   929  3024 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 10:49:41.475   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 10:49:41.481  4653  4723 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 10:49:41.481  4653  4723 D BluetoothAdapterProperties: Setting state to 13
,09-26 10:49:41.481  4653  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-26 10:49:41.482  4653  4723 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 10:49:41.483  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:49:41.484  4653  4723 I BluetoothAdapterState: Entering PendingCommandState
,09-26 10:49:41.489  4653  4653 D BluetoothMapService: onReceive
09-26 10:49:41.489  4653  4653 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-26 10:49:41.490  4653  4653 D BluetoothMapService: STATE_TURNING_OFF
09-26 10:49:41.490  4653  4653 D BluetoothMapService: MAP Service closeService in
09-26 10:49:41.490  4653  4653 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 10:49:41.490  4653  4653 D ObexServerSockets0: shutdown(block = true)
09-26 10:49:41.493  4653  4653 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 10:49:41.493  4653  4653 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 10:49:41.493  4653  4875 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-26 10:49:41.493  4653  4890 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 10:49:41.492  4653  4889 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-26 10:49:41.495  4653  4653 I BtOppRfcommListener: stopping Accept Thread
09-26 10:49:41.496  4653  5361 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 10:49:41.496  4653  5361 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-26 10:49:41.499  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:41.500  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:41.500  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.501  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:41.501  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 10:49:41.505  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.508   929  5431 D DhcpClient: Clearing IP address
09-26 10:49:41.509   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-26 10:49:41.510  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:41.514  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:41.514  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:41.516  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.516  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:41.519  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:41.519  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:41.520  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.520  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:41.521  3625  5485 V NativeCrypto: Read error: ssl=0x7f6e176c00: I/O error during system call, Connection timed out
,09-26 10:49:41.523   507   921 D CommandListener: Setting iface cfg
09-26 10:49:41.525  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:41.526  3625  5485 V NativeCrypto: SSL shutdown failed: ssl=0x7f6e176c00: I/O error during system call, Broken pipe
09-26 10:49:41.527   929  5432 D DhcpClient: Receive thread stopped
09-26 10:49:41.528   929  3814 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-26 10:49:41.528   929  5429 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-26 10:49:41.531   929   942 I ActivityManager: Start proc 5737:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-26 10:49:41.531  4653  4728 D BluetoothAdapterProperties: Scan Mode:20
09-26 10:49:41.532  4653  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-26 10:49:41.535  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:41.535  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:41.536   929  5429 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-26 10:49:41.537   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-26 10:49:41.537   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-26 10:49:41.539   929  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-26 10:49:41.539  4653  4653 D HeadsetService: Received stop request...Stopping profile...
09-26 10:49:41.541  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.541  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:41.541   533   533 E Parcel  : Reading a NULL string not supported here.
09-26 10:49:41.541   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-26 10:49:41.543   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-26 10:49:41.545  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.545  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:49:41.547  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.547  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:41.547   929   929 D RttService: SCAN_AVAILABLE : 1
,09-26 10:49:41.547   929  3133 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-26 10:49:41.548  3813  3845 D BluetoothHeadset: Proxy object disconnected
09-26 10:49:41.548   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 10:49:41.548  3168  3179 D BluetoothHeadset: Proxy object disconnected
09-26 10:49:41.548   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 10:49:41.548   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 10:49:41.550  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.550  4653  4653 D A2dpService: Received stop request...Stopping profile...
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.550  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:41.550  4653  4881 D A2dpStateMachine: Exit Disconnected: -1
09-26 10:49:41.551  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.551  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:41.552   929   929 D BluetoothA2dp: Proxy object disconnected
09-26 10:49:41.552  4653  4653 D HidService: Received stop request...Stopping profile...
09-26 10:49:41.553  4653  4653 D HidService: Stopping Bluetooth HidService
09-26 10:49:41.554  3168  3168 D HeadsetProfile: Bluetooth service disconnected
,09-26 10:49:41.554  4653  4653 D HealthService: Received stop request...Stopping profile...
09-26 10:49:41.554  3168  3168 D BluetoothA2dp: Proxy object disconnected
09-26 10:49:41.555  3168  3168 D BluetoothInputDevice: Proxy object disconnected
09-26 10:49:41.555  3168  3168 D HidProfile: Bluetooth service disconnected
,09-26 10:49:41.555  4653  4653 V BluetoothAdapterState: isTurningOff()=true
09-26 10:49:41.555  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.555  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.555  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.556   929  3026 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-26 10:49:41.556  4653  4653 D PanService: Received stop request...Stopping profile...
09-26 10:49:41.558  3776  3953 W QCNEJ   : |CORE| network lost: 100
09-26 10:49:41.559  3776  3953 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-26 10:49:41.561  4653  4653 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 10:49:41.561  4653  4653 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-26 10:49:41.561  4653  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:49:41.561  4653  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:49:41.561  4653  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:49:41.561  4653  4653 D BluetoothMapService: Received stop request...Stopping profile...
09-26 10:49:41.561  4653  4653 D BluetoothMapService: stop()
09-26 10:49:41.562  4653  4728 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 10:49:41.562  4653  4728 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-26 10:49:41.563  4653  4653 D BluetoothMapAppObserver: deinitObservers()
,09-26 10:49:41.563  4653  4653 D BluetoothMapAppObserver: removeReceiver()
09-26 10:49:41.568  4653  4653 D SapService: Received stop request...Stopping profile...
09-26 10:49:41.568  4653  4653 V SapService: stop()
09-26 10:49:41.569  4653  4653 V BluetoothAdapterState: isTurningOff()=true
,09-26 10:49:41.570  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.570  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.570  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.571  3168  3168 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 10:49:41.571  3168  3168 D PanProfile: Bluetooth service disconnected
09-26 10:49:41.572  4653  4728 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-26 10:49:41.572  4653  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:49:41.572  4653  4653 V BluetoothAdapterState: isTurningOff()=true
09-26 10:49:41.572  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.572  3168  3168 D BluetoothMap: Proxy object disconnected
09-26 10:49:41.572  4653  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:49:41.573  3168  3168 D MapProfile: Bluetooth service disconnected
09-26 10:49:41.573  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.573  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.573  4653  4834 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 10:49:41.573  4653  4834 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 10:49:41.573  4653  4834 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 10:49:41.573  4653  4834 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 10:49:41.573  4653  4653 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-26 10:49:41.573   929  3024 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-26 10:49:41.573  4653  4653 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 10:49:41.573  4653  4653 V BluetoothAdapterState: isTurningOff()=true
,09-26 10:49:41.573  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.573  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.573  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.573  4653  4728 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 10:49:41.573  4653  4653 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 10:49:41.574  4653  4728 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 10:49:41.574  4653  4653 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 10:49:41.574  4653  4653 V BluetoothAdapterState: isTurningOff()=true
09-26 10:49:41.574  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.574  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 10:49:41.574  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.575  4653  4653 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 10:49:41.575  4653  4653 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-26 10:49:41.576   929  3024 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 10:49:41.577  4653  4653 D BluetoothMapService: MAP Service closeService in
09-26 10:49:41.577  4653  4653 V BluetoothAdapterState: isTurningOff()=true
09-26 10:49:41.577  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.577  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.577  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.577  4653  4653 D BluetoothMapService: cleanup()
09-26 10:49:41.578  4653  4653 D BluetoothMapService: MAP Service closeService in
,09-26 10:49:41.578  4653  4653 V BluetoothAdapterState: isTurningOff()=true
09-26 10:49:41.578  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.578  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.578  4653  4653 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:41.578  4653  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-26 10:49:41.578  4653  4723 D BluetoothAdapterProperties: Setting state to 15
09-26 10:49:41.578  4653  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 10:49:41.583  4653  4723 I BluetoothAdapterState: Entering BleOnState
09-26 10:49:41.583   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-26 10:49:41.583  3168  4026 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:49:41.584  3168  3182 D BluetoothPan: onBluetoothStateChange on: false
09-26 10:49:41.585  3168  3179 D BluetoothPbap: onBluetoothStateChange: up=false
,09-26 10:49:41.585   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:49:41.586  3168  3182 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 10:49:41.586   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:49:41.586  3813  3853 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:49:41.587  3168  4026 D BluetoothMap: onBluetoothStateChange: up=false
09-26 10:49:41.587  3168  3179 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 10:49:41.588   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 10:49:41.588   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-26 10:49:41.588  4653  4723 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-26 10:49:41.588  4653  4723 D BluetoothAdapterProperties: Setting state to 16
,09-26 10:49:41.588  4653  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 10:49:41.589  4653  4723 D BluetoothAdapterProperties: onBleDisable
09-26 10:49:41.589  4653  4723 I BluetoothAdapterState: Entering PendingCommandState
09-26 10:49:41.589  4653  4724 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 10:49:41.590  4653  4728 D BluetoothAdapterProperties: Scan Mode:20
09-26 10:49:41.591  4653  4834 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 10:49:41.591  4653  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:49:41.591  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.592  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:49:41.595  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.596  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:49:41.599  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:41.599  5737  5737 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-26 10:49:41.600  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.601  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.603  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.613   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:49:41.613   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-26 10:49:41.613   929  3026 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-26 10:49:41.613  5737  5737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 10:49:41.613   929  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 10:49:41.614   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-26 10:49:41.621  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.623  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:41.624  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:41.625  5349  5349 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fa357f6 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-26 10:49:41.629  5101  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 10:49:41.629  5101  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 10:49:41.629  5101  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-26 10:49:41.629  5101  5120 E SarControlService: no key has been found,reset the power
09-26 10:49:41.629  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 10:49:41.629  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 10:49:41.629  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 10:49:41.630  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:49:41.630  5126  5126 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 10:49:41.631  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-26 10:49:41.631  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 10:49:41.631  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 10:49:41.632  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:49:41.632  5126  5126 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 10:49:41.635  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000ea03000000000000ffffffff]
09-26 10:49:41.635  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:49:41.635  5126  5140 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-26 10:49:41.636  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:49:41.636  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-26 10:49:41.642  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000eb03000000000000ffffffff]
,09-26 10:49:41.642  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-26 10:49:41.642  5126  5140 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-26 10:49:41.642  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:49:41.643  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 10:49:41.644   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9b635f:true
09-26 10:49:41.644  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 10:49:41.658   929   939 I ActivityManager: Start proc 5762:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-26 10:49:41.668   507   921 E Netd    : netlink response contains error (No such file or directory)
,09-26 10:49:41.670   929  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 10:49:41.670   507   921 D TetherController: Setting IP forward enable = 0
,09-26 10:49:41.673   929  3024 D DhcpClient: doQuit
,09-26 10:49:41.673   929  3024 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 10:49:41.673   929  5431 D DhcpClient: onQuitting
09-26 10:49:41.674  3501  3501 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 10:49:41.674  5737  5737 D LocalBluetoothProfileManager: Adding local MAP profile
,09-26 10:49:41.679  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.679  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:41.680  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.680  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:41.680  5737  5737 D BluetoothMap: Create BluetoothMap proxy object
09-26 10:49:41.682  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.682  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:41.682  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.682  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:49:41.683  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:41.683  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:41.684  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:41.684  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:49:41.690  3501  3501 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-26 10:49:41.693  3501  3501 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-26 10:49:41.696  5762  5762 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-26 10:49:41.699  5737  5737 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-26 10:49:41.707   507   921 D TetherController: Setting IP forward enable = 0
,09-26 10:49:41.710  5737  5737 D DockEventReceiver: finishStartingService: stopping service
,09-26 10:49:41.717   929  3601 I ActivityManager: Killing 5041:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-26 10:49:41.727  3501  3501 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-26 10:49:41.743  3501  3501 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 10:49:41.798  4653  4728 I bt_hci  : shut_down
,09-26 10:49:41.802  4653  4735 D bt_hwcfg: hw_epilog_process
,09-26 10:49:41.802  4653  4735 I bt_vendor: low_power_mode_cb
,09-26 10:49:41.804  4653  4735 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-26 10:49:41.805  4653  4735 I bt_vendor: epilog_cb
09-26 10:49:41.805  4653  4735 I bt_hci  : epilog_finished_callback
09-26 10:49:41.806  4653  4728 I bt_hci_h4: hal_close
,09-26 10:49:41.807  4653  4728 I bt_userial_vendor: device fd = 54 close
,09-26 10:49:41.845   929  3024 D wifi    : In wifi stop Hal
,09-26 10:49:41.845  5076  5076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 10:49:41.845   929  3024 D wifi    : halHandle = 0x7f6ca16900, mVM = 0x7f8904d140, mCls = 0x100a06
09-26 10:49:41.845   929  3500 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 10:49:41.845   929  3500 D WifiHAL : Got a signal to exit!!!
,09-26 10:49:41.845   929  3500 I WifiHAL : Exit wifi_event_loop
09-26 10:49:41.846   929  3024 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-26 10:49:41.846   929  3024 E WifiHAL : Event processing terminated
09-26 10:49:41.846   929  3024 D wifi    : In wifi cleaned up handler
09-26 10:49:41.846   929  3024 I WifiHAL : Internal cleanup completed
09-26 10:49:41.848  4148  4271 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-26 10:49:41.848  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.850  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.852  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:41.868   929  3500 D wifi    : set interface wlan0 flags (DOWN)
,09-26 10:49:41.868   929  3024 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 10:49:41.905  5762  5762 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-26 10:49:41.905  5762  5762 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.905  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.906  5762  5762 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.906  5762  5762 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.906  5762  5762 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.k.d(PG:583)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:170)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.906  5762  5762 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.906  5762  5762 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.File.exists(File.java:361)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.906  5762  5762 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-26 10:49:41.906  5762  5762 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-26 10:49:41.910  4653  4724 D bt_stack_manager: event_shut_down_stack finished.
09-26 10:49:41.911  4653  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-26 10:49:41.914  4653  4723 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 10:49:41.914  4653  4653 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 10:49:41.915  5737  5737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 10:49:41.915  4653  4653 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 10:49:41.915  4653  4653 D BtGatt.GattService: stop()
09-26 10:49:41.915  4653  4653 D BtGatt.AdvertiseManager: advertise clients cleared
09-26 10:49:41.917  4653  4653 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:41.917  4653  4653 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:41.917  4653  4653 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:41.917  4653  4653 V BluetoothAdapterState: isBleTurningOff()=true
09-26 10:49:41.917  4653  4723 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-26 10:49:41.917  4653  4723 D BluetoothAdapterProperties: Setting state to 10
09-26 10:49:41.917  4653  4723 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-26 10:49:41.918  4653  4723 I BluetoothAdapterState: Entering OffState
09-26 10:49:41.920  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 10:49:41.922   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-26 10:49:41.932  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 10:49:41.935  3937  3937 D SystemUpdateService: onCreate
09-26 10:49:41.935  4653  4653 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-26 10:49:41.936  4653  4653 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 10:49:41.936  4653  4653 I BluetoothServiceJni: cleanupNative: return from cleanup
09-26 10:49:41.936  4653  4724 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-26 10:49:41.942  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 10:49:41.950  4653  4724 D bt_stack_manager: event_clean_up_stack finished.
09-26 10:49:41.952  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-26 10:49:41.954  5737  5737 D DockEventReceiver: finishStartingService: stopping service
09-26 10:49:41.959  3937  5456 I iu.UploadsManager: num queued entries: 0
09-26 10:49:41.960  3937  5456 I iu.UploadsManager: num updated entries: 0
09-26 10:49:41.960  3937  5456 I iu.SyncManager: NEXT; no task
09-26 10:49:41.962  4653  4653 I art     : System.exit called, status: 0
09-26 10:49:41.962  4653  4653 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-26 10:49:41.978  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-26 10:49:41.979  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-26 10:49:41.981  5459  5459 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 10:49:41.985  5459  5459 D SprintDMHelper: simOperator: 
,09-26 10:49:41.985  5459  5459 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 10:49:41.997  3937  5800 I SystemUpdateService: active receiver: enabled
,09-26 10:49:42.003  5076  5802 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 10:49:42.007  3937  5800 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 10:49:42.009  3937  5800 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-26 10:49:42.009  3937  5800 I SystemUpdateService: now status is 0 (complete)
09-26 10:49:42.009  3937  5800 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 10:49:42.009  3937  5800 I SystemUpdateService: file has been verified
09-26 10:49:42.009  3937  5800 I SystemUpdateService: OTA package size = 21989297
,09-26 10:49:42.011   929  3206 I ActivityManager: Start proc 5803:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-26 10:49:42.015   929  3804 I ActivityManager: Process com.android.bluetooth (pid 4653) has died
,09-26 10:49:42.026  3937  5800 I SystemUpdateService: showing system update notification
,09-26 10:49:42.045  5803  5803 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-26 10:49:42.054   929   940 I ActivityManager: Killing 5349:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-26 10:49:42.071   929   946 D Tethering: InitialState.processMessage what=4
,09-26 10:49:42.086   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 10:49:42.102  3937  3937 D SystemUpdateService: onDestroy
,09-26 10:49:42.108   929  3855 I ActivityManager: Killing 4739:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-26 10:49:42.282  5762  5790 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-26 10:49:42.291   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10b3be0:true
,09-26 10:49:46.503   929  3850 D WifiService: setWifiEnabled: true pid=5684, uid=10077
09-26 10:49:46.504   929  3850 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 10:49:46.510   507   921 D SoftapController: Softap fwReload - Ok
,09-26 10:49:46.514   507   921 D CommandListener: Setting iface cfg
,09-26 10:49:46.515   507   921 D CommandListener: Trying to bring down wlan0
09-26 10:49:46.516   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-26 10:49:46.520   929  3024 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 10:49:47.098   929  3024 D wifi    : set interface wlan0 flags (UP)
,09-26 10:49:47.098   929  3024 I WifiHAL : Initializing wifi
09-26 10:49:47.098   929  3024 I WifiHAL : Creating socket
,09-26 10:49:47.101   929  3024 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-26 10:49:47.101   929  3024 D wifi    : Did set static halHandle = 0x7f6ca16900
09-26 10:49:47.101   929  3024 D wifi    : halHandle = 0x7f6ca16900, mVM = 0x7f8904d140, mCls = 0x20194e
09-26 10:49:47.101   929  3024 D wifi    : array field set
09-26 10:49:47.101   929  3024 I WifiNative-HAL: interface[0] = wlan0
09-26 10:49:47.103   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-26 10:49:47.103   929  5823 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547283364096
09-26 10:49:47.104   929  5823 D wifi    : waitForHalEvents called, vm = 0x7f8904d140, obj = 0x20194e, env = 0x7f6dec95c0
,09-26 10:49:47.167  5824  5824 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 10:49:47.183  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 10:49:47.189  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 10:49:47.189  5824  5824 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 10:49:47.204   929  3024 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 10:49:47.207  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:47.210  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:47.211  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:47.211  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:47.211  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:47.211  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:49:47.220   929  3024 D WifiConfigStore: Loading config and enabling all networks 
,09-26 10:49:47.221  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:47.221  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:47.221  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:47.221  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:47.223  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:47.223  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:47.223  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:47.223  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:47.224  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:47.231   929  3024 D WifiConfigStore: loaded 0 passpoint configs
,09-26 10:49:47.231   929  3024 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 10:49:47.232   929  3024 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 10:49:47.233   929  3024 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 10:49:47.234   929  3024 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-26 10:49:47.235   929  3024 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-26 10:49:47.235   929  3024 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 10:49:47.235   929  3024 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 10:49:47.238  5076  5076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 10:49:47.238   929  3024 D WifiNative-HAL: Setting external_sim to 1
09-26 10:49:47.238   929  3024 D wifi    : setting dfs flag to true, 0x7f7150e6e0
,09-26 10:49:47.239   929  3024 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 10:49:47.239   929  3024 D wifi    : setting scan oui 0x7f7150e6e0
09-26 10:49:47.239   929  3024 D WifiHAL : Sending mac address OUI
,09-26 10:49:47.243   929  3024 E native  : do suspend false
,09-26 10:49:47.251   929  3024 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-26 10:49:47.251   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-26 10:49:47.251   929   929 D RttService: SCAN_AVAILABLE : 3
09-26 10:49:47.251   929  3133 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-26 10:49:47.252   507   921 D CommandListener: Setting iface cfg
,09-26 10:49:47.256   929  3023 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-26 10:49:47.256   929  3023 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 10:49:47.264   929  3023 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 10:49:47.269   929  3023 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 10:49:47.269   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=268096 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-26 10:49:50.422  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:49:50.426  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:49:50.433  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:49:50.438  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:49:50.485   929  3024 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 10:49:50.486   929  3024 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-26 10:49:50.487   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 10:49:50.499   929  3024 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 10:49:50.532   929  3024 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 10:49:50.534  5824  5824 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 10:49:50.989  5824  5824 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 10:49:51.032  5824  5824 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-26 10:49:51.034  5824  5824 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 10:49:51.047   929  3024 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 10:49:51.047   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-26 10:49:51.048   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 10:49:51.065   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 10:49:51.080   507   921 D CommandListener: Setting iface cfg
,09-26 10:49:51.086   929  3024 D WifiStateMachine: Start Dhcp Watchdog 2
,09-26 10:49:51.093   929  5830 D DhcpClient: Receive thread started
,09-26 10:49:51.097   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-26 10:49:51.097   929  3024 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-26 10:49:51.097   929  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-26 10:49:51.179   929  3024 E native  : do suspend false
,09-26 10:49:51.190   929  5829 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 10:49:51.234   929  5830 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-26 10:49:51.234   929  5829 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-26 10:49:51.236   929  5829 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 10:49:51.251   929  5830 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 10:49:51.251   929  5829 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-26 10:49:51.254   507   921 D CommandListener: Setting iface cfg
,09-26 10:49:51.259   929  3024 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 10:49:51.263   929  5829 D DhcpClient: Scheduling renewal in 86399s
,09-26 10:49:51.271   929  3024 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 10:49:51.272   929  3024 D WifiConfigStore: No blacklist allowed without epno enabled
09-26 10:49:51.275   929  3024 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-26 10:49:51.275   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 10:49:51.279   929  3026 D ConnectivityService: Adding iface wlan0 to network 101
,09-26 10:49:51.330   929  3026 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-26 10:49:51.330   929  3026 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-26 10:49:51.339   929  3026 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-26 10:49:51.342   929  3026 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-26 10:49:51.345   929  3026 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-26 10:49:51.354   929  3026 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-26 10:49:51.358   929  3026 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-26 10:49:51.358   929  3026 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-26 10:49:51.358   929  3026 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-26 10:49:51.358   929  3026 D ConnectivityService:    accepting network in place of null
09-26 10:49:51.358   929  3024 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 10:49:51.358   929  3024 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 10:49:51.359   929  3026 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -60]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 10:49:51.382   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:49:51.386   929  5828 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272214, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 10:49:51.404   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:49:51.408   929  3026 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-26 10:49:51.408  3776  3953 W QCNEJ   : |CORE| network available: 101
09-26 10:49:51.408   929  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 10:49:51.409   929  3026 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-26 10:49:51.410  3776  3953 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-26 10:49:51.412   929   946 D Tethering: MasterInitialState.processMessage what=3
09-26 10:49:51.413  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:51.413  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:51.413  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.413  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:51.414  3776  3953 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-26 10:49:51.415  3776  3953 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-26 10:49:51.416  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:51.416  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:51.416  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.416  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetwork,Changed: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:51.419  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:49:51.419  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:49:51.419  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.419  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:49:51.423  5101  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-26 10:49:51.423  5101  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 10:49:51.423  5101  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 10:49:51.423  5101  5120 E SarControlService: no key has been found,reset the power
09-26 10:49:51.423  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 10:49:51.423  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 10:49:51.423  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 10:49:51.424  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:49:51.424  5126  5126 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-26 10:49:51.427  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-26 10:49:51.427  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 10:49:51.428  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 10:49:51.428  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:49:51.428  5126  5126 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 10:49:51.431  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-26 10:49:51.432  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000ec03000000000000ffffffff]
,09-26 10:49:51.432  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:49:51.432  5126  5140 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-26 10:49:51.435  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000ed03000000000000ffffffff]
09-26 10:49:51.435  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:49:51.435  5126  5140 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-26 10:49:51.435  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:49:51.436  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 10:49:51.436  3937  3937 D SystemUpdateService: onCreate
09-26 10:49:51.437  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-26 10:49:51.437  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-26 10:49:51.440  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 10:49:51.450  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-26 10:49:51.457  3937  5456 I iu.UploadsManager: num queued entries: 0
,09-26 10:49:51.457  3937  5456 I iu.UploadsManager: num updated entries: 0
09-26 10:49:51.458  3937  5456 I iu.SyncManager: NEXT; no task
,09-26 10:49:51.459  3937  5840 I SystemUpdateService: active receiver: enabled
,09-26 10:49:51.462  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-26 10:49:51.463  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 10:49:51.465  5459  5459 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 10:49:51.468  5459  5459 D SprintDMHelper: simOperator: 
09-26 10:49:51.468  5459  5459 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 10:49:51.472   929  5827 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-26 10:49:51.490  3937  5840 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 10:49:51.503  3937  5840 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-26 10:49:51.503  3937  5840 I SystemUpdateService: now status is 0 (complete)
09-26 10:49:51.503  3937  5840 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 10:49:51.503  3937  5840 I SystemUpdateService: file has been verified
09-26 10:49:51.503  3937  5840 I SystemUpdateService: OTA package size = 21989297
,09-26 10:49:51.508  3937  5840 I SystemUpdateService: showing system update notification
,09-26 10:49:51.508   929  3213 D WifiService: setWifiEnabled: false pid=5684, uid=10077
09-26 10:49:51.508   929  3213 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 10:49:51.509   929  3024 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-26 10:49:51.509   929  3024 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-26 10:49:51.509   929  3024 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 10:49:51.510   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 10:49:51.518   929  5829 D DhcpClient: Clearing IP address
09-26 10:49:51.518   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-26 10:49:51.519  3937  3937 D SystemUpdateService: onDestroy
09-26 10:49:51.520   507   921 D CommandListener: Setting iface cfg
,09-26 10:49:51.526   929  5827 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-26 10:49:51.526   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-26 10:49:51.531   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-26 10:49:51.531   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-26 10:49:51.534   533   533 E Parcel  : Reading a NULL string not supported here.
,09-26 10:49:51.535   929   929 D RttService: SCAN_AVAILABLE : 1
09-26 10:49:51.535   929  3133 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-26 10:49:51.537   929  3026 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-26 10:49:51.539  3776  3953 W QCNEJ   : |CORE| network lost: 101
09-26 10:49:51.539   929  3024 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-26 10:49:51.540  3776  3953 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-26 10:49:51.542   929  5830 D DhcpClient: Receive thread stopped
,09-26 10:49:51.543   929  3024 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-26 10:49:51.562   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:49:51.584   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:49:51.584   507   921 D CommandListener: Clearing all IP addresses on wlan0
09-26 10:49:51.584   929  3026 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-26 10:49:51.584   929  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-26 10:49:51.586   929   946 D Tethering: MasterInitialState.processMessage what=3
09-26 10:49:51.587   929  3024 D DhcpClient: doQuit
09-26 10:49:51.587   929  3024 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-26 10:49:51.588   929  5829 D DhcpClient: onQuitting
09-26 10:49:51.588  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:51.588  5824  5824 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:51.588  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:51.589  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.589  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:49:51.598  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:51.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:51.598  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.598  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:51.599  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:51.599  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:51.599  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.599  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:51.600  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:51.600  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:51.600  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Blu,etooth is disabled - will return stored value
09-26 10:49:51.600  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:51.601  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:51.602  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:51.603  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 10:49:51.605  5101  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-26 10:49:51.605  5101  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 10:49:51.605  5101  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-26 10:49:51.605  5101  5120 E SarControlService: no key has been found,reset the power
09-26 10:49:51.605  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 10:49:51.606  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 10:49:51.606  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 10:49:51.606  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:49:51.606  5126  5126 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 10:49:51.607  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 10:49:51.607  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 10:49:51.607  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 10:49:51.608  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:49:51.608  5126  5126 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-26 10:49:51.610  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-26 10:49:51.611  3937  3937 D SystemUpdateService: onCreate
,09-26 10:49:51.612  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000ee03000000000000ffffffff]
09-26 10:49:51.612  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:49:51.612  5126  5140 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-26 10:49:51.612  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:49:51.612  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 10:49:51.615  5824  5824 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-26 10:49:51.615  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000ef03000000000000ffffffff]
,09-26 10:49:51.615  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:49:51.615  5126  5140 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-26 10:49:51.617  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:49:51.618  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 10:49:51.618  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 10:49:51.625  3937  5858 I SystemUpdateService: active receiver: enabled
,09-26 10:49:51.626  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-26 10:49:51.632  3937  5456 I iu.UploadsManager: num queued entries: 0
,09-26 10:49:51.633  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 10:49:51.635  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 10:49:51.636  5459  5459 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-26 10:49:51.640  5459  5459 D SprintDMHelper: simOperator: 
,09-26 10:49:51.640  5459  5459 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 10:49:51.643   507   921 E Netd    : netlink response contains error (No such file or directory)
,09-26 10:49:51.644   929  3026 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-26 10:49:51.645   929  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-26 10:49:51.648  5824  5824 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-26 10:49:51.650  3937  5858 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 10:49:51.651  3937  5456 I iu.UploadsManager: num updated entries: 0
,09-26 10:49:51.654  3937  5456 I iu.SyncManager: NEXT; no task
,09-26 10:49:51.655  3937  5858 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-26 10:49:51.655  3937  5858 I SystemUpdateService: now status is 0 (complete)
09-26 10:49:51.655  3937  5858 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 10:49:51.655  3937  5858 I SystemUpdateService: file has been verified
09-26 10:49:51.655  3937  5858 I SystemUpdateService: OTA package size = 21989297
09-26 10:49:51.655  5824  5824 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-26 10:49:51.661   929  3024 D wifi    : In wifi stop Hal
,09-26 10:49:51.661   929  3024 D wifi    : halHandle = 0x7f6ca16900, mVM = 0x7f8904d140, mCls = 0x20194e
09-26 10:49:51.661   929  5823 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-26 10:49:51.661   929  5823 D WifiHAL : Got a signal to exit!!!
09-26 10:49:51.661   929  5823 I WifiHAL : Exit wifi_event_loop
09-26 10:49:51.662   929  3024 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-26 10:49:51.662   929  3024 E WifiHAL : Event processing terminated
09-26 10:49:51.662   929  3024 D wifi    : In wifi cleaned up handler
09-26 10:49:51.662   929  3024 I WifiHAL : Internal cleanup completed
09-26 10:49:51.662  5076  5076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 10:49:51.663  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:51.664  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:51.666  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:51.667  4148  4271 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 10:49:51.674  3937  5858 I SystemUpdateService: showing system update notification
,09-26 10:49:51.681  3937  3937 D SystemUpdateService: onDestroy
,09-26 10:49:51.685   929  5823 D wifi    : set interface wlan0 flags (DOWN)
,09-26 10:49:51.685   929  3024 D WifiNative-HAL: HAL event thread stopped successfully
,09-26 10:49:51.892   929   946 D Tethering: InitialState.processMessage what=4
,09-26 10:49:51.898   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-26 10:49:52.409   929  3026 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-26 10:49:53.754   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:54.755   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:55.756   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:56.499  5076  5845 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-26 10:49:56.499  5076  5845 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-26 10:49:56.503  5076  5845 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-26 10:49:56.536   929   946 I ActivityManager: Start proc 5863:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 10:49:56.613  5863  5863 D AdapterServiceConfig: Adding HeadsetService
,09-26 10:49:56.614  5863  5863 D AdapterServiceConfig: Adding A2dpService
09-26 10:49:56.614  5863  5863 D AdapterServiceConfig: Adding HidService
09-26 10:49:56.614  5863  5863 D AdapterServiceConfig: Adding HealthService
09-26 10:49:56.614  5863  5863 D AdapterServiceConfig: Adding PanService
09-26 10:49:56.614  5863  5863 D AdapterServiceConfig: Adding GattService
,09-26 10:49:56.614  5863  5863 D AdapterServiceConfig: Adding BluetoothMapService
09-26 10:49:56.615  5863  5863 D AdapterServiceConfig: Adding SapService
,09-26 10:49:56.625   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e93d91:true
,09-26 10:49:56.626  5863  5863 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 10:49:56.628  5863  5863 I bt_bluedroid: init
09-26 10:49:56.628  5863  5875 I BluetoothAdapterState: Entering OffState
,09-26 10:49:56.631  5863  5876 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 10:49:56.631  5863  5876 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 10:49:56.631  5863  5876 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-26 10:49:56.631  5863  5876 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-26 10:49:56.632  5863  5863 I bt_bluedroid: get_profile_interface socket
,09-26 10:49:56.633  5863  5879 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-26 10:49:56.634  5863  5863 I bt_bluedroid: get_profile_interface sdp
,09-26 10:49:56.635  5863  5879 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 10:49:56.640  5863  5874 I bt_bluedroid: config_hci_snoop_log
,09-26 10:49:56.641   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-26 10:49:56.644  5863  5875 D BluetoothAdapterState: Current state: OFF, message: 0
09-26 10:49:56.644  5863  5875 D BluetoothAdapterProperties: Setting state to 14
09-26 10:49:56.645  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-26 10:49:56.646  5863  5875 D BluetoothBondStateMachine: make
,09-26 10:49:56.649  5863  5880 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 10:49:56.651  5863  5875 I BluetoothAdapterState: Entering PendingCommandState
,09-26 10:49:56.652  5863  5863 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 10:49:56.655  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:56.655  5863  5863 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-26 10:49:56.656  5863  5863 D BtGatt.GattService: Received start request. Starting profile...
09-26 10:49:56.656  5863  5863 D BtGatt.GattService: start()
09-26 10:49:56.656  5863  5863 I bt_bluedroid: get_profile_interface gatt
,09-26 10:49:56.657  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:56.657  5863  5863 D BtGatt.AdvertiseManager: advertise manager created
,09-26 10:49:56.663  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:56.663  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:49:56.663  5863  5863 V BluetoothAdapterState: isBleTurningOn()=true
09-26 10:49:56.663  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:56.663  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 10:49:56.664  5863  5875 I bt_bluedroid: bt_bluedroid
,09-26 10:49:56.665  5863  5876 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-26 10:49:56.665  5863  5876 I bt_hci  : start_up
,09-26 10:49:56.671  5863  5876 I bt_vendor: alloc value 0xf3fed871
,09-26 10:49:56.671  5863  5876 I bt_vendor: init
09-26 10:49:56.671  5863  5876 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 10:49:56.671  5863  5876 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 10:49:56.757   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:56.779  5863  5876 D bt_hci  : start_up starting async portion
,09-26 10:49:56.779  5863  5883 I bt_hci  : event_finish_startup
,09-26 10:49:56.779  5863  5883 I bt_hci_h4: hal_open
09-26 10:49:56.779  5863  5883 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-26 10:49:56.776  5884  5884 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-26 10:49:56.781  5863  5883 I bt_userial_vendor: device fd = 54 open
,09-26 10:49:56.796  5863  5883 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 10:49:56.799  5863  5883 D bt_hwcfg: Chipset BCM4358A3
,09-26 10:49:56.799  5863  5883 D bt_hwcfg: Target name = [BCM4358A3]
09-26 10:49:56.799  5863  5883 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 10:49:57.189  5863  5883 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-26 10:49:57.190  5863  5883 D bt_hwcfg: Settlement delay -- 100 ms
09-26 10:49:57.190  5863  5883 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 10:49:57.325  5863  5883 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 10:49:57.326  5863  5883 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-26 10:49:57.329  5863  5883 I bt_hwcfg: vendor lib fwcfg completed
09-26 10:49:57.329  5863  5883 I bt_vendor: firmware callback
09-26 10:49:57.329  5863  5883 I bt_hci  : firmware_config_callback
,09-26 10:49:57.337  5863  5886 I bt_btu  : btu_task pending for preload complete event
,09-26 10:49:57.337  5863  5886 I bt_btu_task: Bluetooth chip preload is complete
09-26 10:49:57.337  5863  5886 I bt_btu  : btu_task received preload complete event
,09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_HCI
,09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_AVDT
09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_A2D
09-26 10:49:57.344  5863  5886 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_BTM
,09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_GAP
09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_SDP
09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_GATT
,09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_SMP
09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 10:49:57.345  5863  5886 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 10:49:57.427  5863  5886 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f6b549
09-26 10:49:57.428  5863  5886 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f6b549 
,09-26 10:49:57.437  5863  5879 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-26 10:49:57.438  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 10:49:57.439  5863  5879 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 10:49:57.441  5863  5879 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 10:49:57.444  5863  5879 D BluetoothAdapterProperties: Scan Mode:20
,09-26 10:49:57.445  5863  5879 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-26 10:49:57.445  5863  5879 D bt_hci  : do_postload posting postload work item
,09-26 10:49:57.447  5863  5883 I bt_hci  : event_postload
,09-26 10:49:57.447  5863  5883 I bt_vendor: sco_config_cb
09-26 10:49:57.447  5863  5883 I bt_hci  : sco_config_callback postload finished.
09-26 10:49:57.451  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:57.454  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:57.456  5863  5883 I bt_vendor: low_power_mode_cb
,09-26 10:49:57.458  5863  5879 D bt_bte_conf: Device ID record 1 : primary
09-26 10:49:57.459  5863  5879 D bt_bte_conf:   vendorId            = 000f
,09-26 10:49:57.459  5863  5879 D bt_bte_conf:   vendorIdSource      = 0001
09-26 10:49:57.459  5863  5879 D bt_bte_conf:   product             = 1200
09-26 10:49:57.459  5863  5879 D bt_bte_conf:   version             = 1436
09-26 10:49:57.459  5863  5879 D bt_bte_conf:   clientExecutableURL = 
09-26 10:49:57.459  5863  5879 D bt_bte_conf:   serviceDescription  = 
,09-26 10:49:57.459  5863  5879 D bt_bte_conf:   documentationURL    = 
09-26 10:49:57.459  5863  5879 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 10:49:57.459  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:57.460  5863  5876 D bt_stack_manager: event_start_up_stack finished
09-26 10:49:57.461  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 10:49:57.462  5863  5875 D BluetoothAdapterProperties: Setting state to 15
09-26 10:49:57.462  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-26 10:49:57.463  5863  5875 I BluetoothAdapterState: Entering BleOnState
,09-26 10:49:57.467  5863  5875 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-26 10:49:57.467  5863  5875 D BluetoothAdapterProperties: Setting state to 11
09-26 10:49:57.467  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 10:49:57.473  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:57.474  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:57.477  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:57.480  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:57.482  5863  5863 D HeadsetService: Received start request. Starting profile...
,09-26 10:49:57.484  5863  5863 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 10:49:57.485  5863  5863 D HeadsetStateMachine: make
,09-26 10:49:57.493  5863  5875 I BluetoothAdapterState: Entering PendingCommandState
,09-26 10:49:57.495  5863  5863 D HeadsetStateMachine: max_hf_connections = 1
,09-26 10:49:57.495  5863  5863 I bt_bluedroid: get_profile_interface handsfree
09-26 10:49:57.496  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 10:49:57.496  5863  5879 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-26 10:49:57.501  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:57.502  5863  5863 D A2dpService: Received start request. Starting profile...
09-26 10:49:57.502  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 10:49:57.502  5863  5863 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-26 10:49:57.503  5863  5863 I bt_bluedroid: get_profile_interface avrcp
,09-26 10:49:57.510  5863  5863 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-26 10:49:57.510  5863  5863 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-26 10:49:57.510  5863  5863 D A2dpStateMachine: make
,09-26 10:49:57.511  5863  5863 I bt_bluedroid: get_profile_interface a2dp
09-26 10:49:57.512  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-26 10:49:57.514  5863  5894 D A2dpStateMachine: Enter Disconnected: -2
,09-26 10:49:57.515  5863  5863 I BluetoothHidServiceJni: classInitNative: succeeds
,09-26 10:49:57.516  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:57.518  5863  5863 D HidService: Received start request. Starting profile...
,09-26 10:49:57.518  5863  5863 I bt_bluedroid: get_profile_interface hidhost
09-26 10:49:57.518  5863  5863 D HidService: setHidService(): set to: null
,09-26 10:49:57.518  5863  5879 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f4c56d
09-26 10:49:57.518  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 10:49:57.519  5863  5863 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-26 10:49:57.520  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:49:57.520  5863  5863 D HealthService: Received start request. Starting profile...
09-26 10:49:57.521  5737  5737 D BluetoothInputDevice: Proxy object connected
09-26 10:49:57.522  5863  5863 I bt_bluedroid: get_profile_interface health
,09-26 10:49:57.522  5737  5737 D HidProfile: Bluetooth service connected
09-26 10:49:57.523  5863  5863 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-26 10:49:57.524  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:57.526  5737  5737 D BluetoothPan: BluetoothPAN Proxy object connected
,09-26 10:49:57.526  5737  5737 D PanProfile: Bluetooth service connected
09-26 10:49:57.527  5863  5863 D PanService: Received start request. Starting profile...
09-26 10:49:57.527  5863  5863 D BluetoothPanServiceJni: initializeNative(L110): pan
09-26 10:49:57.527  5863  5863 I bt_bluedroid: get_profile_interface pan
09-26 10:49:57.528  5863  5879 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-26 10:49:57.530  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:49:57.531  5737  5737 D BluetoothMap: Proxy object connected
09-26 10:49:57.531  5863  5863 D BluetoothMapService: Received start request. Starting profile...
09-26 10:49:57.531  5863  5863 D BluetoothMapService: start()
09-26 10:49:57.531  5737  5737 D MapProfile: Bluetooth service connected
09-26 10:49:57.532  5737  5737 D BluetoothMap: getConnectedDevices()
09-26 10:49:57.532  5737  5737 D BluetoothMap: Bluetooth is Not enabled
09-26 10:49:57.534  5863  5863 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-26 10:49:57.535  5863  5863 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 10:49:57.535  5863  5863 D BluetoothMapAppObserver: createReceiver()
,09-26 10:49:57.537  5863  5863 D BluetoothMapAppObserver: initObservers()
09-26 10:49:57.537  5863  5863 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 10:49:57.545  5863  5863 V SapService: SapBinder()
,09-26 10:49:57.545  5863  5863 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:49:57.546  5863  5863 D SapService: Received start request. Starting profile...
09-26 10:49:57.546  5863  5863 V SapService: start()
,09-26 10:49:57.548  5863  5863 V BluetoothAdapterState: isTurningOff()=false
,09-26 10:49:57.548  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.548  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:57.548  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:57.548  5863  5892 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:57.549  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:49:57.550  5863  5863 V BluetoothAdapterState: isTurningOff()=false
09-26 10:49:57.551  5863  5863 V BluetoothAdapterState: isTurningOn()=true
09-26 10:49:57.551  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:49:57.551  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 10:49:57.551  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 10:49:57.551  5863  5875 D BluetoothAdapterProperties: ScanMode =  20
09-26 10:49:57.551  5863  5875 D BluetoothAdapterProperties: State =  11
09-26 10:49:57.551  5863  5875 D BluetoothAdapterProperties: Setting state to 12
09-26 10:49:57.551  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-26 10:49:57.552  3168  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:49:57.553  5737  5749 D BluetoothPan: onBluetoothStateChange on: true
09-26 10:49:57.553  5863  5875 I BluetoothAdapterState: Entering OnState
09-26 10:49:57.553  3168  3179 D BluetoothPan: onBluetoothStateChange on: true
09-26 10:49:57.554  5863  5879 D BluetoothAdapterProperties: Scan Mode:21
09-26 10:49:57.554  5863  5879 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-26 10:49:57.557  3168  3168 D BluetoothPan: BluetoothPAN Proxy object connected
,09-26 10:49:57.557  3168  3168 D PanProfile: Bluetooth service connected
09-26 10:49:57.557  3168  4026 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:57.558  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:49:57.559  5737  5746 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 10:49:57.561   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-26 10:49:57.561  3168  3182 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 10:49:57.561  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:57.562  5863  5863 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 10:49:57.563  3168  3168 D BluetoothInputDevice: Proxy object connected
09-26 10:49:57.563  5737  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 10:49:57.563  3168  3168 D HidProfile: Bluetooth service connected
09-26 10:49:57.563  5863  5863 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-26 10:49:57.563   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:49:57.563  3813  4059 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:49:57.564  3168  4026 D BluetoothMap: onBluetoothStateChange: up=true
09-26 10:49:57.565  5863  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:49:57.566  3168  4026 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 10:49:57.566  3168  3168 D BluetoothMap: Proxy object connected
09-26 10:49:57.566  3168  3168 D MapProfile: Bluetooth service connected
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:57.566  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:49:57.566  3168  3168 D BluetoothMap: getConnectedDevices()
09-26 10:49:57.568  5737  5746 D BluetoothMap: onBluetoothStateChange: up=true
09-26 10:49:57.568   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 10:49:57.568  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:49:57.568  5863  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:49:57.569   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:49:57.569   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-26 10:49:57.572  5863  5863 D ObexServerSockets: Succeed to create listening sockets 
09-26 10:49:57.572  5863  5863 D ObexServerSockets0: startAccept()
09-26 10:49:57.572  5863  5863 D ObexServerSockets0: prepareForNewConnect()
,09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:49:57.574  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:49:57.575  5863  5863 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 10:49:57.575  5863  5863 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-26 10:49:57.577  5863  5900 D ObexServerSockets0: Accepting socket connection...
09-26 10:49:57.577  5863  5901 D ObexServerSockets0: Accepting socket connection...
,09-26 10:49:57.577  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:49:57.577   929   929 D BluetoothA2dp: Proxy object connected
09-26 10:49:57.578  3168  3168 D BluetoothA2dp: Proxy object connected
09-26 10:49:57.578  5863  5863 D BluetoothMapService: onReceive
09-26 10:49:57.578  5863  5863 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 10:49:57.578  5863  5863 D BluetoothMapService: STATE_ON
09-26 10:49:57.578  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:57.580  5863  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:49:57.580  5737  5737 D LocalBluetoothProfileManager: Adding local A2DP profile
09-26 10:49:57.580  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:49:57.581  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:49:57.582  5863  5902 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 10:49:57.582  5863  5902 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-26 10:49:57.583  5737  5737 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-26 10:49:57.590  5737  5737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-26 10:49:57.592  5737  5737 D BluetoothA2dp: Proxy object connected
,09-26 10:49:57.596  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 10:49:57.598  5737  5737 D DockEventReceiver: finishStartingService: stopping service
,09-26 10:49:57.603  3168  3168 D BluetoothPbap: Proxy object connected
09-26 10:49:57.604  3168  3168 D PbapServerProfile: Bluetooth service connected
,09-26 10:49:57.604  5737  5737 D BluetoothPbap: Proxy object connected
09-26 10:49:57.604  5863  5863 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 10:49:57.604  5863  5863 D ObexServerSockets0: prepareForNewConnect()
09-26 10:49:57.604  5737  5737 D PbapServerProfile: Bluetooth service connected
,09-26 10:49:57.611  5863  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 10:49:57.625  5863  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 10:49:57.627  5863  5910 I BtOppRfcommListener: Accept thread started.
,09-26 10:49:57.654  3813  3845 D BluetoothHeadset: Proxy object connected
09-26 10:49:57.654   929   929 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.655  3168  4026 D BluetoothHeadset: Proxy object connected
09-26 10:49:57.655  3168  3168 D HeadsetProfile: Bluetooth service connected
09-26 10:49:57.655   929   929 D BluetoothHeadset: Proxy object connected
09-26 10:49:57.655   929   929 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.661   929   946 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.664   929   946 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.664  3813  3853 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.668   929   946 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.687  5737  5746 D BluetoothHeadset: Proxy object connected
,09-26 10:49:57.688  5737  5737 D HeadsetProfile: Bluetooth service connected
,09-26 10:49:57.757   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:49:58.758   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 10:49:59.366   929  3026 D ConnectivityService: handlePromptUnvalidated 101
,09-26 10:50:01.520  5863  5875 D BluetoothAdapterState: Current state: ON, message: 23
,09-26 10:50:01.521  5863  5875 D BluetoothAdapterProperties: Setting state to 13
09-26 10:50:01.521  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-26 10:50:01.522  5863  5875 D BluetoothAdapterProperties: onBluetoothDisable()
09-26 10:50:01.527  5863  5863 D BluetoothMapService: onReceive
09-26 10:50:01.527  5863  5863 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 10:50:01.527  5863  5863 D BluetoothMapService: STATE_TURNING_OFF
09-26 10:50:01.528  5863  5863 D BluetoothMapService: MAP Service closeService in
09-26 10:50:01.528  5863  5863 D BluetoothMapMasInstance0: MAP Service shutdown
09-26 10:50:01.529  5863  5863 D ObexServerSockets0: shutdown(block = true)
09-26 10:50:01.529  5863  5900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-26 10:50:01.530  5863  5875 I BluetoothAdapterState: Entering PendingCommandState
09-26 10:50:01.532  5863  5879 D BluetoothAdapterProperties: Scan Mode:20
09-26 10:50:01.533  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-26 10:50:01.534  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:01.534  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:50:01.534  5737  5737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 10:50:01.535  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:50:01.535  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:50:01.537  5863  5863 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-26 10:50:01.537  5863  5863 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-26 10:50:01.537  5863  5888 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-26 10:50:01.537  5863  5901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-26 10:50:01.539  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:01.540  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:50:01.542  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:50:01.542  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:50:01.545  5737  5737 D DockEventReceiver: finishStartingService: stopping service
09-26 10:50:01.546  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:01.547  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:50:01.547  5684  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-26 10:50:01.548  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:50:01.552  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:01.554  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:01.555  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:01.555  5863  5863 I BtOppRfcommListener: stopping Accept Thread
09-26 10:50:01.556  5863  5910 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-26 10:50:01.556  5863  5910 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-26 10:50:01.557  5863  5863 D HeadsetService: Received stop request...Stopping profile...
,09-26 10:50:01.560  3813  4059 D BluetoothHeadset: Proxy object disconnected
,09-26 10:50:01.560   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 10:50:01.560  3168  3182 D BluetoothHeadset: Proxy object disconnected
09-26 10:50:01.560  3168  3168 D HeadsetProfile: Bluetooth service disconnected
09-26 10:50:01.560  5737  5746 D BluetoothHeadset: Proxy object disconnected
09-26 10:50:01.561   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 10:50:01.561   929   929 D BluetoothHeadset: Proxy object disconnected
09-26 10:50:01.563  5863  5863 D A2dpService: Received stop request...Stopping profile...
09-26 10:50:01.563  5863  5894 D A2dpStateMachine: Exit Disconnected: -1
09-26 10:50:01.564  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 10:50:01.564   929   929 D BluetoothA2dp: Proxy object disconnected
09-26 10:50:01.565  3168  3168 D BluetoothA2dp: Proxy object disconnected
09-26 10:50:01.565  5863  5863 D HidService: Received stop request...Stopping profile...
09-26 10:50:01.565  5863  5863 D HidService: Stopping Bluetooth HidService
09-26 10:50:01.566  5737  5737 D HeadsetProfile: Bluetooth service disconnected
09-26 10:50:01.566  5737  5737 D BluetoothA2dp: Proxy object disconnected
,09-26 10:50:01.566  5737  5737 D BluetoothInputDevice: Proxy object disconnected
09-26 10:50:01.566  5737  5737 D HidProfile: Bluetooth service disconnected
09-26 10:50:01.567  5863  5863 D HealthService: Received stop request...Stopping profile...
09-26 10:50:01.567  3168  3168 D BluetoothInputDevice: Proxy object disconnected
09-26 10:50:01.567  3168  3168 D HidProfile: Bluetooth service disconnected
,09-26 10:50:01.569  5863  5863 D PanService: Received stop request...Stopping profile...
,09-26 10:50:01.570  3168  3168 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 10:50:01.570  5737  5737 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-26 10:50:01.570  3168  3168 D PanProfile: Bluetooth service disconnected
09-26 10:50:01.570  5737  5737 D PanProfile: Bluetooth service disconnected
09-26 10:50:01.571  5863  5863 D BluetoothMapService: Received stop request...Stopping profile...
09-26 10:50:01.571  5863  5863 D BluetoothMapService: stop()
09-26 10:50:01.571  5863  5863 D BluetoothMapAppObserver: deinitObservers()
,09-26 10:50:01.571  5863  5863 D BluetoothMapAppObserver: removeReceiver()
09-26 10:50:01.572  3168  3168 D BluetoothMap: Proxy object disconnected
09-26 10:50:01.572  3168  3168 D MapProfile: Bluetooth service disconnected
09-26 10:50:01.573  5737  5737 D BluetoothMap: Proxy object disconnected
09-26 10:50:01.573  5737  5737 D MapProfile: Bluetooth service disconnected
09-26 10:50:01.573  5863  5863 D SapService: Received stop request...Stopping profile...
09-26 10:50:01.573  5863  5863 V SapService: stop()
,09-26 10:50:01.575  5863  5863 V BluetoothAdapterState: isTurningOff()=true
,09-26 10:50:01.575  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.575  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.575  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:01.577  5863  5863 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-26 10:50:01.577  5863  5863 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-26 10:50:01.577  5863  5886 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:50:01.577  5863  5886 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:50:01.577  5863  5886 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:50:01.577  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-26 10:50:01.578  5863  5879 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-26 10:50:01.579  5863  5863 V BluetoothAdapterState: isTurningOff()=true
09-26 10:50:01.579  3168  3168 D BluetoothPbap: Proxy object disconnected
09-26 10:50:01.579  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.579  3168  3168 D PbapServerProfile: Bluetooth service disconnected
09-26 10:50:01.579  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.579  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:01.580  5863  5886 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:50:01.580  5863  5863 V BluetoothAdapterState: isTurningOff()=true
09-26 10:50:01.580  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.580  5863  5886 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-26 10:50:01.580  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.580  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:01.580  5863  5886 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 10:50:01.581  5863  5886 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 10:50:01.581  5863  5886 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-26 10:50:01.581  5863  5863 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-26 10:50:01.581  5863  5886 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-26 10:50:01.581  5863  5863 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-26 10:50:01.581  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-26 10:50:01.581  5863  5863 V BluetoothAdapterState: isTurningOff()=true
09-26 10:50:01.581  5863  5863 V BluetoothAdapterState: isTurningOn()=false
,09-26 10:50:01.581  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.581  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:01.581  5863  5863 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-26 10:50:01.581  5863  5879 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-26 10:50:01.581  5863  5879 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-26 10:50:01.582  5863  5863 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-26 10:50:01.582  5737  5737 D BluetoothPbap: Proxy object disconnected
09-26 10:50:01.582  5863  5863 V BluetoothAdapterState: isTurningOff()=true
09-26 10:50:01.582  5737  5737 D PbapServerProfile: Bluetooth service disconnected
09-26 10:50:01.582  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.582  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.582  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:01.583  5863  5863 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-26 10:50:01.583  5863  5863 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-26 10:50:01.584  5863  5863 D BluetoothMapService: MAP Service closeService in
,09-26 10:50:01.584  5863  5863 V BluetoothAdapterState: isTurningOff()=true
09-26 10:50:01.584  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.584  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.584  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:01.585  5863  5863 D BluetoothMapService: cleanup()
09-26 10:50:01.585  5863  5863 D BluetoothMapService: MAP Service closeService in
09-26 10:50:01.585  5863  5863 V BluetoothAdapterState: isTurningOff()=true
09-26 10:50:01.585  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.585  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
,09-26 10:50:01.585  5863  5863 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 10:50:01.585  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-26 10:50:01.595  5863  5875 D BluetoothAdapterProperties: Setting state to 15
09-26 10:50:01.595  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-26 10:50:01.596  5863  5875 I BluetoothAdapterState: Entering BleOnState
,09-26 10:50:01.596  3168  3182 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-26 10:50:01.599  5737  5749 D BluetoothPan: onBluetoothStateChange on: false
,09-26 10:50:01.609  3168  3179 D BluetoothPan: onBluetoothStateChange on: false
09-26 10:50:01.610  3168  4026 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 10:50:01.610  5737  5746 D BluetoothPbap: onBluetoothStateChange: up=false
09-26 10:50:01.611  5737  5749 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:50:01.611   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:50:01.611  3168  3182 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-26 10:50:01.612  5737  5746 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-26 10:50:01.612   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:50:01.612  3813  3845 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:50:01.612  3168  3179 D BluetoothMap: onBluetoothStateChange: up=false
09-26 10:50:01.613  5737  5749 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 10:50:01.613  3168  4026 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 10:50:01.614  5737  5746 D BluetoothMap: onBluetoothStateChange: up=false
09-26 10:50:01.614   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-26 10:50:01.615   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-26 10:50:01.615  5863  5875 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-26 10:50:01.615  5863  5875 D BluetoothAdapterProperties: Setting state to 16
09-26 10:50:01.615  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-26 10:50:01.615  5863  5875 D BluetoothAdapterProperties: onBleDisable
09-26 10:50:01.616  5863  5875 I BluetoothAdapterState: Entering PendingCommandState
09-26 10:50:01.616  5863  5876 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-26 10:50:01.617  5863  5879 D BluetoothAdapterProperties: Scan Mode:20
09-26 10:50:01.618  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:01.618  5737  5737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 10:50:01.619  5863  5886 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-26 10:50:01.619  5863  5886 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-26 10:50:01.623  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:01.625  5737  5737 D DockEventReceiver: finishStartingService: stopping service
,09-26 10:50:01.625  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:01.627  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:01.628  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:01.629  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:01.629  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 10:50:01.829  5863  5879 I bt_hci  : shut_down
,09-26 10:50:01.834  5863  5883 D bt_hwcfg: hw_epilog_process
,09-26 10:50:01.835  5863  5883 I bt_vendor: low_power_mode_cb
,09-26 10:50:01.837  5863  5883 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-26 10:50:01.837  5863  5883 I bt_vendor: epilog_cb
09-26 10:50:01.837  5863  5883 I bt_hci  : epilog_finished_callback
,09-26 10:50:01.841  5863  5879 I bt_hci_h4: hal_close
,09-26 10:50:01.841  5863  5879 I bt_userial_vendor: device fd = 54 close
,09-26 10:50:01.948  5863  5876 D bt_stack_manager: event_shut_down_stack finished.
,09-26 10:50:01.948  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-26 10:50:01.951  5863  5875 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-26 10:50:01.951  5863  5863 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 10:50:01.952  5863  5863 D BtGatt.GattService: Received stop request...Stopping profile...
09-26 10:50:01.952  5863  5863 D BtGatt.GattService: stop()
09-26 10:50:01.952  5863  5863 D BtGatt.AdvertiseManager: advertise clients cleared
,09-26 10:50:01.955  5863  5863 V BluetoothAdapterState: isTurningOff()=false
,09-26 10:50:01.956  5863  5863 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:01.956  5863  5863 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:01.956  5863  5863 V BluetoothAdapterState: isBleTurningOff()=true
,09-26 10:50:01.956  5863  5875 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-26 10:50:01.956  5863  5875 D BluetoothAdapterProperties: Setting state to 10
,09-26 10:50:01.956  5863  5875 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-26 10:50:01.957  5863  5875 I BluetoothAdapterState: Entering OffState
09-26 10:50:01.958   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-26 10:50:01.967  5863  5863 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-26 10:50:01.967  5863  5863 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-26 10:50:01.967  5863  5863 I BluetoothServiceJni: cleanupNative: return from cleanup
09-26 10:50:01.968  5863  5876 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-26 10:50:01.973  5863  5863 I art     : System.exit called, status: 0
,09-26 10:50:01.973  5863  5863 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-26 10:50:01.995   929  3841 I ActivityManager: Process com.android.bluetooth (pid 5863) has died
,09-26 10:50:06.518  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:06.519  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:06.523  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:50:06.524  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a15e5d2 removed from the list
09-26 10:50:06.524  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:06.524  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:06.524  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:06.526  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:50:06.527  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fbada0 added. We now have 4 listener(s)
09-26 10:50:06.527  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:50:06.529  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:50:06.529  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fbada0 removed from the list
09-26 10:50:06.529  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:50:06.529  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:06.530  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:06.531  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:50:06.531  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cfdd59 added. We now have 4 listener(s)
,09-26 10:50:06.532  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 10:50:11.542  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:11.577   929   946 I ActivityManager: Start proc 5919:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-26 10:50:11.683  5919  5919 D AdapterServiceConfig: Adding HeadsetService
,09-26 10:50:11.684  5919  5919 D AdapterServiceConfig: Adding A2dpService
09-26 10:50:11.684  5919  5919 D AdapterServiceConfig: Adding HidService
09-26 10:50:11.684  5919  5919 D AdapterServiceConfig: Adding HealthService
09-26 10:50:11.685  5919  5919 D AdapterServiceConfig: Adding PanService
09-26 10:50:11.685  5919  5919 D AdapterServiceConfig: Adding GattService
09-26 10:50:11.685  5919  5919 D AdapterServiceConfig: Adding BluetoothMapService
09-26 10:50:11.685  5919  5919 D AdapterServiceConfig: Adding SapService
,09-26 10:50:11.699   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38627b6:true
,09-26 10:50:11.699  5919  5919 D BluetoothAdapterState: make() - Creating AdapterState
,09-26 10:50:11.703  5919  5919 I bt_bluedroid: init
09-26 10:50:11.703  5919  5931 I BluetoothAdapterState: Entering OffState
,09-26 10:50:11.705  5919  5932 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-26 10:50:11.705  5919  5932 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-26 10:50:11.705  5919  5932 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-26 10:50:11.706  5919  5932 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-26 10:50:11.707  5919  5919 I bt_bluedroid: get_profile_interface socket
,09-26 10:50:11.708  5919  5935 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 10:50:11.709  5919  5919 I bt_bluedroid: get_profile_interface sdp
09-26 10:50:11.710  5919  5935 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 10:50:11.715  5919  5930 I bt_bluedroid: config_hci_snoop_log
,09-26 10:50:11.717   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-26 10:50:11.722  5919  5931 D BluetoothAdapterState: Current state: OFF, message: 0
,09-26 10:50:11.722  5919  5931 D BluetoothAdapterProperties: Setting state to 14
09-26 10:50:11.722  5919  5931 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-26 10:50:11.724  5919  5931 D BluetoothBondStateMachine: make
,09-26 10:50:11.726  5919  5937 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-26 10:50:11.730  5919  5931 I BluetoothAdapterState: Entering PendingCommandState
,09-26 10:50:11.731  5919  5919 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-26 10:50:11.733  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:50:11.734  5919  5919 D BtGatt.DebugUtils: handleDebugAction() action=null
09-26 10:50:11.734  5919  5919 D BtGatt.GattService: Received start request. Starting profile...
09-26 10:50:11.734  5919  5919 D BtGatt.GattService: start()
09-26 10:50:11.734  5919  5919 I bt_bluedroid: get_profile_interface gatt
09-26 10:50:11.736  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:50:11.736  5919  5919 D BtGatt.AdvertiseManager: advertise manager created
,09-26 10:50:11.742  5919  5919 V BluetoothAdapterState: isTurningOff()=false
,09-26 10:50:11.742  5919  5919 V BluetoothAdapterState: isTurningOn()=false
09-26 10:50:11.742  5919  5919 V BluetoothAdapterState: isBleTurningOn()=true
09-26 10:50:11.742  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:11.742  5919  5931 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-26 10:50:11.744  5919  5931 I bt_bluedroid: bt_bluedroid
09-26 10:50:11.744  5919  5932 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-26 10:50:11.745  5919  5932 I bt_hci  : start_up
,09-26 10:50:11.752  5919  5932 I bt_vendor: alloc value 0xf3fed871
09-26 10:50:11.752  5919  5932 I bt_vendor: init
09-26 10:50:11.752  5919  5932 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-26 10:50:11.753  5919  5932 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-26 10:50:11.862  5919  5932 D bt_hci  : start_up starting async portion
,09-26 10:50:11.863  5919  5940 I bt_hci  : event_finish_startup
09-26 10:50:11.863  5919  5940 I bt_hci_h4: hal_open
09-26 10:50:11.863  5919  5940 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-26 10:50:11.860  5941  5941 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-26 10:50:11.865  5919  5940 I bt_userial_vendor: device fd = 54 open
,09-26 10:50:11.882  5919  5940 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 10:50:11.886  5919  5940 D bt_hwcfg: Chipset BCM4358A3
,09-26 10:50:11.886  5919  5940 D bt_hwcfg: Target name = [BCM4358A3]
09-26 10:50:11.886  5919  5940 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-26 10:50:12.392  5919  5940 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-26 10:50:12.392  5919  5940 D bt_hwcfg: Settlement delay -- 100 ms
09-26 10:50:12.392  5919  5940 I bt_hwcfg: Setting fw settlement delay to 100 
,09-26 10:50:12.530  5919  5940 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-26 10:50:12.531  5919  5940 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-26 10:50:12.533  5919  5940 I bt_hwcfg: vendor lib fwcfg completed
09-26 10:50:12.533  5919  5940 I bt_vendor: firmware callback
09-26 10:50:12.533  5919  5940 I bt_hci  : firmware_config_callback
,09-26 10:50:12.543  5919  5943 I bt_btu  : btu_task pending for preload complete event
09-26 10:50:12.543  5919  5943 I bt_btu_task: Bluetooth chip preload is complete
,09-26 10:50:12.544  5919  5943 I bt_btu  : btu_task received preload complete event
,09-26 10:50:12.550  5919  5943 I         : BTE_InitTraceLevels -- TRC_HCI
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_AVDT
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_AVRC
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_A2D
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_BNEP
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_BTM
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_GAP
09-26 10:50:12.551  5919  5943 I         : BTE_InitTraceLevels -- TRC_PAN
09-26 10:50:12.552  5919  5943 I         : BTE_InitTraceLevels -- TRC_SDP
09-26 10:50:12.552  5919  5943 I         : BTE_InitTraceLevels -- TRC_GATT
09-26 10:50:12.552  5919  5943 I         : BTE_InitTraceLevels -- TRC_SMP
,09-26 10:50:12.552  5919  5943 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-26 10:50:12.552  5919  5943 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-26 10:50:12.651  5919  5943 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f6b549
,09-26 10:50:12.652  5919  5943 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f6b549 
,09-26 10:50:12.667  5919  5935 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,09-26 10:50:12.669  5919  5935 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-26 10:50:12.670  5919  5935 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-26 10:50:12.673  5919  5935 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-26 10:50:12.677  5919  5935 D BluetoothAdapterProperties: Scan Mode:20
,09-26 10:50:12.677  5919  5935 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 10:50:12.677  5919  5935 D bt_hci  : do_postload posting postload work item
09-26 10:50:12.678  5919  5940 I bt_hci  : event_postload
09-26 10:50:12.678  5919  5940 I bt_vendor: sco_config_cb
09-26 10:50:12.678  5919  5940 I bt_hci  : sco_config_callback postload finished.
,09-26 10:50:12.683  5919  5935 D bt_bte_conf: Device ID record 1 : primary
,09-26 10:50:12.683  5919  5935 D bt_bte_conf:   vendorId            = 000f
09-26 10:50:12.684  5919  5935 D bt_bte_conf:   vendorIdSource      = 0001
09-26 10:50:12.684  5919  5935 D bt_bte_conf:   product             = 1200
09-26 10:50:12.684  5919  5935 D bt_bte_conf:   version             = 1436
09-26 10:50:12.684  5919  5935 D bt_bte_conf:   clientExecutableURL = 
09-26 10:50:12.684  5919  5935 D bt_bte_conf:   serviceDescription  = 
,09-26 10:50:12.684  5919  5935 D bt_bte_conf:   documentationURL    = 
,09-26 10:50:12.684  5919  5935 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-26 10:50:12.684  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:12.685  5919  5932 D bt_stack_manager: event_start_up_stack finished
09-26 10:50:12.687  5919  5931 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-26 10:50:12.687  5919  5931 D BluetoothAdapterProperties: Setting state to 15
09-26 10:50:12.688  5919  5931 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-26 10:50:12.688  5919  5931 I BluetoothAdapterState: Entering BleOnState
09-26 10:50:12.690  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:12.690  5919  5940 I bt_vendor: low_power_mode_cb
,09-26 10:50:12.692  5919  5931 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-26 10:50:12.693  5919  5931 D BluetoothAdapterProperties: Setting state to 11
09-26 10:50:12.693  5919  5931 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-26 10:50:12.698  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:50:12.699  5919  5919 D HeadsetService: Received start request. Starting profile...
09-26 10:50:12.703  5919  5919 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-26 10:50:12.704  5919  5919 D HeadsetStateMachine: make
09-26 10:50:12.704  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:12.707  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:12.714  5919  5931 I BluetoothAdapterState: Entering PendingCommandState
,09-26 10:50:12.716  5919  5919 D HeadsetStateMachine: max_hf_connections = 1
09-26 10:50:12.716  5919  5919 I bt_bluedroid: get_profile_interface handsfree
,09-26 10:50:12.716  5919  5935 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-26 10:50:12.717  5919  5935 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-26 10:50:12.720  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:50:12.721  5919  5919 D A2dpService: Received start request. Starting profile...
,09-26 10:50:12.722  5919  5919 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-26 10:50:12.722  5919  5919 I bt_bluedroid: get_profile_interface avrcp
,09-26 10:50:12.730  5919  5919 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-26 10:50:12.731  5919  5919 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-26 10:50:12.731  5919  5919 D A2dpStateMachine: make
09-26 10:50:12.732  5919  5919 I bt_bluedroid: get_profile_interface a2dp
,09-26 10:50:12.733  5919  5935 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-26 10:50:12.734  5919  5950 D A2dpStateMachine: Enter Disconnected: -2
09-26 10:50:12.735  5919  5919 I BluetoothHidServiceJni: classInitNative: succeeds
09-26 10:50:12.735  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:50:12.736  5919  5919 D HidService: Received start request. Starting profile...
09-26 10:50:12.736  5919  5919 I bt_bluedroid: get_profile_interface hidhost
09-26 10:50:12.736  5919  5919 D HidService: setHidService(): set to: null
,09-26 10:50:12.737  5919  5935 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f4c56d
09-26 10:50:12.737  5919  5935 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-26 10:50:12.738  5919  5919 I BluetoothHealthServiceJni: classInitNative: succeeds
09-26 10:50:12.740  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:50:12.740  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-26 10:50:12.741  5919  5919 D HealthService: Received start request. Starting profile...
09-26 10:50:12.742  5919  5919 I bt_bluedroid: get_profile_interface health
09-26 10:50:12.743  5919  5919 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-26 10:50:12.744  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:50:12.744  5919  5919 D PanService: Received start request. Starting profile...
09-26 10:50:12.745  5919  5919 D BluetoothPanServiceJni: initializeNative(L110): pan
09-26 10:50:12.745  5919  5919 I bt_bluedroid: get_profile_interface pan
09-26 10:50:12.745  5919  5935 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-26 10:50:12.747  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:50:12.748  5919  5919 D BluetoothMapService: Received start request. Starting profile...
09-26 10:50:12.748  5919  5919 D BluetoothMapService: start()
09-26 10:50:12.751  5919  5919 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-26 10:50:12.752  5919  5919 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-26 10:50:12.752  5919  5919 D BluetoothMapAppObserver: createReceiver()
,09-26 10:50:12.753  5919  5919 D BluetoothMapAppObserver: initObservers()
09-26 10:50:12.753  5919  5919 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-26 10:50:12.761  5919  5919 V SapService: SapBinder()
,09-26 10:50:12.761  5919  5919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
09-26 10:50:12.761  5919  5919 D SapService: Received start request. Starting profile...
09-26 10:50:12.761  5919  5919 V SapService: start()
,09-26 10:50:12.763  5919  5919 V BluetoothAdapterState: isTurningOff()=false
,09-26 10:50:12.763  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.763  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.763  5919  5948 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-26 10:50:12.763  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isTurningOff()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isTurningOff()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
,09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isTurningOff()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.764  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isTurningOff()=false
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isTurningOff()=false
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.765  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:12.766  5919  5919 V BluetoothAdapterState: isTurningOff()=false
,09-26 10:50:12.766  5919  5919 V BluetoothAdapterState: isTurningOn()=true
09-26 10:50:12.766  5919  5919 V BluetoothAdapterState: isBleTurningOn()=false
09-26 10:50:12.766  5919  5919 V BluetoothAdapterState: isBleTurningOff()=false
09-26 10:50:12.766  5919  5931 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-26 10:50:12.766  5919  5931 D BluetoothAdapterProperties: ScanMode =  20
09-26 10:50:12.766  5919  5931 D BluetoothAdapterProperties: State =  11
09-26 10:50:12.766  5919  5931 D BluetoothAdapterProperties: Setting state to 12
09-26 10:50:12.766  5919  5931 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-26 10:50:12.767  3168  4026 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:50:12.767  5919  5935 D BluetoothAdapterProperties: Scan Mode:21
09-26 10:50:12.767  5919  5931 I BluetoothAdapterState: Entering OnState
09-26 10:50:12.767  5737  5746 D BluetoothPan: onBluetoothStateChange on: true
09-26 10:50:12.768  5919  5935 D BluetoothAdapterProperties: Discoverable Timeout:120
09-26 10:50:12.769  3168  3182 D BluetoothPan: onBluetoothStateChange on: true
09-26 10:50:12.771  3168  3179 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:12.771  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:50:12.773  5737  5737 D BluetoothPan: BluetoothPAN Proxy object connected
,09-26 10:50:12.773  3168  3168 D BluetoothPan: BluetoothPAN Proxy object connected
09-26 10:50:12.773  5737  5737 D PanProfile: Bluetooth service connected
09-26 10:50:12.773  3168  3168 D PanProfile: Bluetooth service connected
09-26 10:50:12.773  5737  5746 D BluetoothPbap: onBluetoothStateChange: up=true
09-26 10:50:12.774  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:50:12.775  5737  5749 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:50:12.775   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:50:12.775  3168  3182 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 10:50:12.777  5737  5746 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:12.778  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:50:12.779  5919  5919 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-26 10:50:12.779  5919  5919 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-26 10:50:12.780   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:50:12.780  3813  3845 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:50:12.780  3168  4026 D BluetoothMap: onBluetoothStateChange: up=true
09-26 10:50:12.780  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:50:12.781  5919  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:50:12.782  5737  5749 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 10:50:12.784  3168  3179 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 10:50:12.784  5919  5919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:50:12.785  5737  5746 D BluetoothMap: onBluetoothStateChange: up=true
09-26 10:50:12.785  5919  5919 D ObexServerSockets: Succeed to create listening sockets 
09-26 10:50:12.785  5919  5919 D ObexServerSockets0: startAccept()
09-26 10:50:12.786  5919  5919 D ObexServerSockets0: prepareForNewConnect()
,09-26 10:50:12.787  5919  5919 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-26 10:50:12.788  5919  5919 D BluetoothSdpJni: SDP Create record success - handle: 0
09-26 10:50:12.788   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-26 10:50:12.788   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-26 10:50:12.788  5919  5956 D ObexServerSockets0: Accepting socket connection...
09-26 10:50:12.789  5919  5955 D ObexServerSockets0: Accepting socket connection...
09-26 10:50:12.789  5737  5737 D BluetoothInputDevice: Proxy object connected
09-26 10:50:12.789  5737  5737 D HidProfile: Bluetooth service connected
,09-26 10:50:12.790  3168  3168 D BluetoothInputDevice: Proxy object connected
09-26 10:50:12.790  3168  3168 D HidProfile: Bluetooth service connected
09-26 10:50:12.790   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-26 10:50:12.793   929   929 D BluetoothA2dp: Proxy object connected
,09-26 10:50:12.793  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:12.793  3168  3168 D BluetoothMap: Proxy object connected
09-26 10:50:12.794  3168  3168 D MapProfile: Bluetooth service connected
,09-26 10:50:12.794  3168  3168 D BluetoothMap: getConnectedDevices()
09-26 10:50:12.794  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:12.794  5919  5919 D BluetoothMapService: onReceive
09-26 10:50:12.795  5919  5919 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-26 10:50:12.795  5919  5919 D BluetoothMapService: STATE_ON
09-26 10:50:12.797  5919  5959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:50:12.798  3168  3168 D BluetoothA2dp: Proxy object connected
09-26 10:50:12.799  5737  5737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-26 10:50:12.799  5919  5959 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-26 10:50:12.799  5919  5959 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-26 10:50:12.801  5737  5737 D BluetoothMap: Proxy object connected
,09-26 10:50:12.802  5737  5737 D MapProfile: Bluetooth service connected
09-26 10:50:12.802  5737  5737 D BluetoothMap: getConnectedDevices()
09-26 10:50:12.803  5737  5737 D BluetoothA2dp: Proxy object connected
09-26 10:50:12.806  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-26 10:50:12.808  5737  5737 D DockEventReceiver: finishStartingService: stopping service
,09-26 10:50:12.813  5737  5737 D BluetoothPbap: Proxy object connected
,09-26 10:50:12.814  5737  5737 D PbapServerProfile: Bluetooth service connected
,09-26 10:50:12.818  5919  5919 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-26 10:50:12.819  5919  5919 D ObexServerSockets0: prepareForNewConnect()
09-26 10:50:12.820  5919  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 10:50:12.828  3168  3168 D BluetoothPbap: Proxy object connected
,09-26 10:50:12.829  3168  3168 D PbapServerProfile: Bluetooth service connected
,09-26 10:50:12.837  5919  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-26 10:50:12.838  5919  5967 I BtOppRfcommListener: Accept thread started.
,09-26 10:50:12.869  3813  3853 D BluetoothHeadset: Proxy object connected
,09-26 10:50:12.870   929   929 D BluetoothHeadset: Proxy object connected
09-26 10:50:12.870  3168  4026 D BluetoothHeadset: Proxy object connected
09-26 10:50:12.870  3168  3168 D HeadsetProfile: Bluetooth service connected
09-26 10:50:12.870  5737  5746 D BluetoothHeadset: Proxy object connected
,09-26 10:50:12.870   929   929 D BluetoothHeadset: Proxy object connected
09-26 10:50:12.870   929   929 D BluetoothHeadset: Proxy object connected
,09-26 10:50:12.871  5737  5737 D HeadsetProfile: Bluetooth service connected
,09-26 10:50:12.875  5737  5749 D BluetoothHeadset: Proxy object connected
,09-26 10:50:12.876   929   946 D BluetoothHeadset: Proxy object connected
09-26 10:50:12.876  5737  5737 D HeadsetProfile: Bluetooth service connected
,09-26 10:50:12.881   929   946 D BluetoothHeadset: Proxy object connected
,09-26 10:50:12.881  3813  4059 D BluetoothHeadset: Proxy object connected
,09-26 10:50:12.889   929   946 D BluetoothHeadset: Proxy object connected
,09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:16.557  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:50:16.562  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:50:16.563  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:16.564  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4cfdd59 removed from the list
09-26 10:50:16.564  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:16.564  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:16.564  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:16.567  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:50:16.567  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc88d1e added. We now have 4 listener(s)
09-26 10:50:16.567  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-26 10:50:16.571   929  3639 D WifiService: setWifiEnabled: false pid=5684, uid=10077
,09-26 10:50:16.571   929  3639 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 10:50:18.759   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:50:19.760   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:50:20.762   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:50:21.580  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:21.581   929  3206 D WifiService: setWifiEnabled: true pid=5684, uid=10077
09-26 10:50:21.582   929  3206 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-26 10:50:21.591   507   921 D SoftapController: Softap fwReload - Ok
,09-26 10:50:21.598   507   921 D CommandListener: Setting iface cfg
,09-26 10:50:21.598   507   921 D CommandListener: Trying to bring down wlan0
09-26 10:50:21.600   507   921 D CommandListener: Clearing all IP addresses on wlan0
,09-26 10:50:21.605   929  3024 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-26 10:50:21.763   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:50:22.291   929  3024 D wifi    : set interface wlan0 flags (UP)
,09-26 10:50:22.291   929  3024 I WifiHAL : Initializing wifi
09-26 10:50:22.291   929  3024 I WifiHAL : Creating socket
,09-26 10:50:22.298   929  3024 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-26 10:50:22.299   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-26 10:50:22.299   929  3024 D wifi    : Did set static halHandle = 0x7f6ca16900
09-26 10:50:22.299   929  3024 D wifi    : halHandle = 0x7f6ca16900, mVM = 0x7f8904d140, mCls = 0x201562
09-26 10:50:22.300   929  3024 D wifi    : array field set
09-26 10:50:22.300   929  3024 I WifiNative-HAL: interface[0] = wlan0
,09-26 10:50:22.302   929  5972 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547283364096
09-26 10:50:22.302   929  5972 D wifi    : waitForHalEvents called, vm = 0x7f8904d140, obj = 0x201562, env = 0x7f6decad00
,09-26 10:50:22.352  5973  5973 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-26 10:50:22.374  5973  5973 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 10:50:22.384  5973  5973 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-26 10:50:22.384  5973  5973 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-26 10:50:22.405   929  3024 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-26 10:50:22.415  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:22.418   929  3024 D WifiConfigStore: Loading config and enabling all networks 
,09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:22.424  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-26 10:50:22.427  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-26 10:50:22.430   929  3024 D WifiConfigStore: loaded 0 passpoint configs
09-26 10:50:22.431   929  3024 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-26 10:50:22.431  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-26 10:50:22.431   929  3024 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-26 10:50:22.432   929  3024 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-26 10:50:22.433   929  3024 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-26 10:50:22.433  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-26 10:50:22.433   929  3024 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-26 10:50:22.433   929  3024 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-26 10:50:22.433   929  3024 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-26 10:50:22.435  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:22.437   929  3024 D WifiNative-HAL: Setting external_sim to 1
09-26 10:50:22.437  5076  5076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-26 10:50:22.438   929  3024 D wifi    : setting dfs flag to true, 0x7f70cafe80
,09-26 10:50:22.439   929  3024 D WifiStateMachine: Setting OUI to DA-A1-19
09-26 10:50:22.439   929  3024 D wifi    : setting scan oui 0x7f70cafe80
09-26 10:50:22.439   929  3024 D WifiHAL : Sending mac address OUI
,09-26 10:50:22.444   929  3024 E native  : do suspend false
,09-26 10:50:22.453   929  3024 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-26 10:50:22.453   929   929 D RttService: SCAN_AVAILABLE : 3
09-26 10:50:22.453   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-26 10:50:22.453   929  3133 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-26 10:50:22.454   507   921 D CommandListener: Setting iface cfg
,09-26 10:50:22.458   929  3023 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-26 10:50:22.458   929  3023 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-26 10:50:22.468   929  3023 D WifiNative-HAL: p2pGetDeviceAddress
,09-26 10:50:22.469   929  3023 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-26 10:50:22.475   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303303 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,09-26 10:50:22.764   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:50:23.765   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 10:50:25.633  5973  5973 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:50:25.639  5973  5973 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:50:25.644  5973  5973 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:50:25.649  5973  5973 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-26 10:50:25.711   929  3024 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-26 10:50:25.713   929  3024 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-26 10:50:25.713   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 10:50:25.725   929  3024 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-26 10:50:25.759   929  3024 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-26 10:50:25.760  5973  5973 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-26 10:50:26.198  5973  5973 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-26 10:50:26.234  5973  5973 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-26 10:50:26.235  5973  5973 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-26 10:50:26.245   929  3024 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-26 10:50:26.245   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-26 10:50:26.245   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-26 10:50:26.260   929  3024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-26 10:50:26.272   507   921 D CommandListener: Setting iface cfg
,09-26 10:50:26.278   929  3024 D WifiStateMachine: Start Dhcp Watchdog 3
,09-26 10:50:26.284   929  5978 D DhcpClient: Receive thread started
,09-26 10:50:26.287   929  3024 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-26 10:50:26.288   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-26 10:50:26.288   929  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-26 10:50:26.370   929  3024 E native  : do suspend false
,09-26 10:50:26.384   929  5977 D DhcpClient: Broadcasting DHCPDISCOVER
,09-26 10:50:26.403   929  5978 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-26 10:50:26.403   929  5977 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-26 10:50:26.405   929  5977 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-26 10:50:26.432   929  5978 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-26 10:50:26.433   929  5977 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-26 10:50:26.436   507   921 D CommandListener: Setting iface cfg
,09-26 10:50:26.442   929  3024 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-26 10:50:26.448   929  5977 D DhcpClient: Scheduling renewal in 86399s
,09-26 10:50:26.457   929  3024 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-26 10:50:26.458   929  3024 D WifiConfigStore: No blacklist allowed without epno enabled
,09-26 10:50:26.460   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-26 10:50:26.461   929  3026 D ConnectivityService: Adding iface wlan0 to network 102
,09-26 10:50:26.464   929  3024 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-26 10:50:26.515   929  3026 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-26 10:50:26.515   929  3026 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-26 10:50:26.519   929  3026 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-26 10:50:26.523   929  3026 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-26 10:50:26.525   929  3026 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-26 10:50:26.534   929  3026 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:50:26.538   929  3026 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-26 10:50:26.538   929  3026 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-26 10:50:26.538   929  3026 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-26 10:50:26.538   929  3024 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-26 10:50:26.538   929  3026 D ConnectivityService:    accepting network in place of null
09-26 10:50:26.539   929  3024 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-26 10:50:26.539   929  3026 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-26 10:50:26.559   929  5976 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307387, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 10:50:26.562   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:50:26.583   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-26 10:50:26.587   929  3026 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-26 10:50:26.587  3776  3953 W QCNEJ   : |CORE| network available: 102
,09-26 10:50:26.587   929  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-26 10:50:26.589   929  3026 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-26 10:50:26.589  3776  3953 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-26 10:50:26.590   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-26 10:50:26.593  3776  3953 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-26 10:50:26.594  3776  3953 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:26.598  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:50:26.603  5101  5120 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-26 10:50:26.604  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:26.605  5101  5120 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-26 10:50:26.605  5101  5120 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-26 10:50:26.605  5101  5120 E SarControlService: no key has been found,reset the power
09-26 10:50:26.605  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-26 10:50:26.605  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-26 10:50:26.605  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-26 10:50:26.606  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:50:26.606  5126  5126 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-26 10:50:26.607  5101  5135 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-26 10:50:26.607  5101  5135 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-26 10:50:26.607  5101  5135 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-26 10:50:26.608  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-26 10:50:26.608  5126  5126 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:26.608  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:26.610  5684  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:50:26.610  3937  3937 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-26 10:50:26.612  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:26.613  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:26.613  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc88d1e removed from the list
09-26 10:50:26.613  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:26.613  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:26.613  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:26.613  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000f003000000000000ffffffff]
09-26 10:50:26.613  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:50:26.613  5126  5140 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-26 10:50:26.614  3937  3937 D SystemUpdateService: onCreate
09-26 10:50:26.614  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:50:26.614  5684  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:26.615  5101  5112 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-26 10:50:26.615  5126  5140 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cedd10c HexData = [00000000f103000000000000ffffffff]
,09-26 10:50:26.615  5126  5140 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-26 10:50:26.615  5126  5140 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-26 10:50:26.616  5126  5126 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-26 10:50:26.616  5101  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-26 10:50:26.617  5684  5988 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-26 10:50:26.617  5684  5988 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-26 10:50:26.619  3937  3937 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-26 10:50:26.629  3937  3937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-26 10:50:26.634  3937  5989 I SystemUpdateService: active receiver: enabled
,09-26 10:50:26.636  3937  5456 I iu.UploadsManager: num queued entries: 0
09-26 10:50:26.636  3937  5456 I iu.UploadsManager: num updated entries: 0
,09-26 10:50:26.637  3937  5456 I iu.SyncManager: NEXT; no task
,09-26 10:50:26.639  3937  3937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-26 10:50:26.640  3937  3937 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-26 10:50:26.642  5459  5459 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-26 10:50:26.644   929  5975 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-26 10:50:26.646  5459  5459 D SprintDMHelper: simOperator: 
,09-26 10:50:26.646  5459  5459 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-26 10:50:26.666  3937  5989 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-26 10:50:26.679  3937  5989 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-26 10:50:26.679  3937  5989 I SystemUpdateService: now status is 0 (complete)
09-26 10:50:26.679  3937  5989 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-26 10:50:26.679  3937  5989 I SystemUpdateService: file has been verified
09-26 10:50:26.679  3937  5989 I SystemUpdateService: OTA package size = 21989297
,09-26 10:50:26.684  3937  5989 I SystemUpdateService: showing system update notification
,09-26 10:50:26.693  3937  3937 D SystemUpdateService: onDestroy
,09-26 10:50:26.722   929  5975 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 26 Sep 2016 14:50:26 GMT], X-Android-Received-Millis=[1474901426721], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474901426693]}
,09-26 10:50:26.722   929  3026 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-26 10:50:26.723   929  3026 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-26 10:50:26.723   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-26 10:50:26.724   929  3026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-26 10:50:26.783  5076  5993 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-26 10:50:29.309   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:50:29.650  5684  6001 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-26 10:50:29.650  5684  5988 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-26 10:50:29.652  5684  6001 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-26 10:50:29.653  5684  6001 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 10:50:29.652  5684  5988 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 10:50:29.654  5684  5988 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 10:50:29.654  5684  6001 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 10:50:29.655  5684  5988 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 10:50:29.658  5684  6003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Sender)
,09-26 10:50:29.658  5684  6001 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-26 10:50:29.659  5684  5988 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 10:50:29.662  5684  6004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender)
,09-26 10:50:29.663  5684  6005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Receiver)
,09-26 10:50:29.663  5684  6006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver)
09-26 10:50:29.665  5684  6006 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver)
09-26 10:50:29.665  5684  6005 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: IncomingSocketThread/Receiver)
09-26 10:50:29.665  5684  6006 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-26 10:50:29.665  5684  6005 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-26 10:50:29.665  5684  6006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-26 10:50:29.665  5684  6005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-26 10:50:32.626  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-26 10:50:32.628  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-26 10:50:32.635  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fc80810 Bundle[{}]
,09-26 10:50:32.637  5684  5730 I io.jxcore.node.LifeCycleMonitor: start: OK
09-26 10:50:32.637  5684  5730 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-26 10:50:32.638  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-26 10:50:32.639  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-26 10:50:32.640  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-26 10:50:32.641  5684  5730 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-26 10:50:32.648  5684  5730 I System.out: Running OutgoingSocketThread
,09-26 10:50:32.651  5684  6007 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-26 10:50:32.651  5684  6007 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-26 10:50:34.544   929  3026 D ConnectivityService: handlePromptUnvalidated 102
,09-26 10:50:35.661  5684  6007 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-26 10:50:35.661  5684  6007 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-26 10:50:35.661  5684  6007 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 10:50:35.662  5684  6007 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 10:50:35.663  5684  6007 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-26 10:50:35.663  5684  6008 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-26 10:50:35.664  5684  6008 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-26 10:50:35.665  5684  6010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Sender)
09-26 10:50:35.666  5684  6008 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-26 10:50:35.666  5684  6011 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Receiver)
,09-26 10:50:35.668  5684  6008 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 10:50:35.669  5684  6011 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: OutgoingSocketThread/Receiver)
09-26 10:50:35.669  5684  6012 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender)
09-26 10:50:35.669  5684  6011 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-26 10:50:35.670  5684  6011 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-26 10:50:35.670  5684  6008 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-26 10:50:35.673  5684  6013 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Receiver)
,09-26 10:50:35.675  5684  6013 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: IncomingSocketThread/Receiver)
,09-26 10:50:35.676  5684  6013 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-26 10:50:35.676  5684  6013 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-26 10:50:37.470   929  3024 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-26 10:50:38.660  5684  5730 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,09-26 10:50:38.661  5684  5730 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-26 10:50:38.661  5684  5730 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-26 10:50:38.669  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 10:50:38.669  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9769ff added. We now have 3 listener(s)
09-26 10:50:38.671  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 10:50:38.672  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:50:38.672  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-26 10:50:38.672  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 10:50:38.672  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fe03cc added. We now have 4 listener(s)
09-26 10:50:38.673  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:50:38.674  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 10:50:38.679  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:38.686  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:50:38.688  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:38.688  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:50:38.689  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:50:38.689  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:50:38.689  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:50:38.689  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:38.689  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:38.689  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:38.689  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 10:50:38.689  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9769ff removed from the list
09-26 10:50:38.689  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:38.689  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fe03cc removed from the list
,09-26 10:50:38.692  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:38.692  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:38.692  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:38.693  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:38.693  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:38.695  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:50:38.695  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:38.695  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:50:38.695  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:38.695  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fe03cc not in the list
,09-26 10:50:38.696  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:38.696  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:38.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:50:38.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:50:38.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:38.697  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fe03cc not in the list
09-26 10:50:38.697  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:38.697  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:38.697  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:38.697  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9769ff not in the list
,09-26 10:50:38.698  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-26 10:50:38.698  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16c5d2a added. We now have 3 listener(s)
09-26 10:50:38.699  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 10:50:38.700  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:50:38.700  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 10:50:38.700  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:50:38.700  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@802a71b added. We now have 4 listener(s)
09-26 10:50:38.700  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:50:38.700  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 10:50:38.703  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:38.708  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-26 10:50:38.709  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:50:38.710  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:50:38.710  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:50:38.710  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-26 10:50:38.710  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 10:50:38.710  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:38.710  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:50:38.713  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:38.714  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:38.714  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 10:50:38.716  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:38.718  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:50:38.719  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:50:38.719  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 10:50:38.722  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-26 10:50:38.722  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 10:50:38.722  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-26 10:50:38.723  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:38.726  5919  5958 D BtGatt.GattService: registerClient() - UUID=c87cf565-b580-47ef-92bc-9e48b6dd0dac
,09-26 10:50:38.727  5919  5935 D BtGatt.GattService: onClientRegistered() - UUID=c87cf565-b580-47ef-92bc-9e48b6dd0dac, clientIf=5
,09-26 10:50:38.727  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-26 10:50:38.728  5919  5936 D BtGatt.GattService: start scan with filters
,09-26 10:50:38.731  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 10:50:38.732  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-26 10:50:38.732  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 10:50:38.732  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 10:50:38.732  5919  5939 D BtGatt.ScanManager: handling starting scan
09-26 10:50:38.733  5919  5939 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65ff0d
,09-26 10:50:38.734  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:50:38.734  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 10:50:38.734  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 10:50:38.736  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 10:50:38.739  5684  5730 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-26 10:50:38.739  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-26 10:50:38.739  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 10:50:38.739  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:38.739  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 10:50:38.739  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 10:50:38.739  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 10:50:38.739  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 10:50:38.740  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 10:50:38.740  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:50:38.740  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 10:50:38.741  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:38.741  5919  5935 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 10:50:38.741  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:38.741  5919  5958 D BtGatt.GattService: stopScan() - queue size =1
09-26 10:50:38.741  5919  5939 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 10:50:38.742  5919  5936 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 10:50:38.743  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 10:50:38.743  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 10:50:38.743  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-26 10:50:38.743  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 10:50:38.743  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 10:50:38.745  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:50:38.745  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:38.745  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:50:38.745  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:38.745  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:38.746  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:50:38.746  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:38.746  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:50:38.748  5919  5935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-26 10:50:38.748  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:38.748  5919  5939 D BtGatt.ScanManager: Starting BLE batch scan
09-26 10:50:38.748  5919  5939 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 10:50:38.750  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:38.750  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 10:50:38.754  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 10:50:38.755  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:50:38.755  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:50:38.755  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:38.755  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:38.757  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:50:38.757  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:38.757  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:50:38.759  5919  5935 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-26 10:50:38.759  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:38.759  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:50:38.760  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:38.761  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:50:38.763  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:50:38.763  5919  5935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 10:50:38.764  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:50:38.770  5919  5935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 10:50:38.770  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:38.770  5919  5939 D BtGatt.ScanManager: stopping BLe Batch
,09-26 10:50:38.776  5919  5935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-26 10:50:38.776  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:38.777  5919  5939 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-26 10:50:38.782  5919  5935 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-26 10:50:38.782  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:50:39.264  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-26 10:50:39.265  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-26 10:50:39.265  5684  5684 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 10:50:41.747  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:50:41.747  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:50:41.747  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:50:41.748  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:41.748  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:41.748  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:41.748  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 10:50:41.748  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16c5d2a removed from the list
09-26 10:50:41.749  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:41.749  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@802a71b removed from the list
09-26 10:50:41.749  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
,09-26 10:50:41.749  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:41.751  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:41.751  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:41.755  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:50:41.755  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:41.755  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:50:41.757  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:41.757  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:41.757  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:41.757  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:50:41.757  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@802a71b not in the list
09-26 10:50:41.758  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:41.758  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:41.761  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:50:41.762  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:50:41.763  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:41.763  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:41.763  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:50:41.763  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-26 10:50:41.763  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-26 10:50:41.764  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@802a71b not in the list
09-26 10:50:41.764  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:41.764  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:41.764  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:41.764  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16c5d2a not in the list
09-26 10:50:41.766  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 10:50:41.766  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5bed0 added. We now have 3 listener(s)
09-26 10:50:41.769  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-26 10:50:41.769  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:50:41.769  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 10:50:41.769  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-26 10:50:41.770  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95cec9 added. We now have 4 listener(s)
09-26 10:50:41.770  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:50:41.770  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 10:50:41.774  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:41.781  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:50:41.785  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:50:41.786  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:50:41.787  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 10:50:41.787  5684  5730 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-26 10:50:41.790  5930  5930 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32194]" dev="sockfs" ino=32194 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 10:50:41.790  5930  5930 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32194]" dev="sockfs" ino=32194 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-26 10:50:41.788  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-26 10:50:41.788  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-26 10:50:41.788  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-26 10:50:41.788  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-26 10:50:41.788  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:41.789  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-26 10:50:41.790  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-26 10:50:41.790  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:41.790  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-26 10:50:41.790  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-26 10:50:41.791  5684  6014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-26 10:50:41.791  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-26 10:50:41.791  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:41.791  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:50:41.794  5684  6014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-26 10:50:41.795  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:41.795  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-26 10:50:41.798  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-26 10:50:41.798  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 10:50:41.802  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:50:41.803  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:50:41.803  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 10:50:41.806  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-26 10:50:41.806  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 10:50:41.807  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-26 10:50:41.807  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-26 10:50:41.808  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-26 10:50:41.808  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-26 10:50:41.808  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:41.813  5919  5957 D BtGatt.GattService: registerClient() - UUID=2854281c-97f7-48f2-b2ed-5effc6cc49c3
09-26 10:50:41.813  5919  5935 D BtGatt.GattService: onClientRegistered() - UUID=2854281c-97f7-48f2-b2ed-5effc6cc49c3, clientIf=5
,09-26 10:50:41.814  5684  5695 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-26 10:50:41.816  5919  5938 D BtGatt.AdvertiseManager: message : 0
,09-26 10:50:41.818  5919  5938 D BtGatt.AdvertiseManager: starting multi advertising
,09-26 10:50:41.829  5919  5935 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-26 10:50:41.836  5919  5935 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-26 10:50:41.836  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-26 10:50:41.837  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-26 10:50:41.838  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-26 10:50:41.840  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-26 10:50:41.840  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-26 10:50:41.840  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-26 10:50:41.840  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-26 10:50:41.840  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-26 10:50:41.840  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-26 10:50:41.842  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 10:50:41.843  5684  5684 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-26 10:50:41.843  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-26 10:50:42.344  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-26 10:50:42.345  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-26 10:50:42.345  5684  5684 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 10:50:44.843  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:50:44.844  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-26 10:50:44.844  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-26 10:50:44.844  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-26 10:50:44.844  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-26 10:50:44.844  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-26 10:50:44.845  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 10:50:44.845  5684  5730 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-26 10:50:44.845  5684  6014 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-26 10:50:44.845  5684  6014 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-26 10:50:44.845  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-26 10:50:44.846  5684  6014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-26 10:50:44.846  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-26 10:50:44.846  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 10:50:44.846  5684  5684 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-26 10:50:44.846  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-26 10:50:44.846  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:50:44.848  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:44.849  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:44.850  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:44.850  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-26 10:50:44.853  5919  5938 D BtGatt.AdvertiseManager: message : 1
09-26 10:50:44.854  5919  5938 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-26 10:50:44.872  5919  5935 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-26 10:50:44.873  5919  5935 D BtGatt.GattService: Client app is not null!
09-26 10:50:44.874  5919  5930 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 10:50:44.875  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:44.875  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-26 10:50:44.875  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-26 10:50:44.875  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-26 10:50:44.875  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-26 10:50:44.878  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 10:50:44.879  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:50:44.879  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:44.880  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:50:44.882  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:44.882  5684  5684 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-26 10:50:44.882  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:44.882  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:44.882  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 10:50:44.882  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:50:44.882  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5bed0 removed from the list
,09-26 10:50:44.882  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:44.882  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:44.882  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:50:44.882  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95cec9 removed from the list
09-26 10:50:44.883  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:44.883  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-26 10:50:44.888  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:44.888  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-26 10:50:44.895  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 10:50:44.896  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-26 10:50:44.896  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:50:44.896  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:44.897  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:44.901  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:44.901  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:44.903  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:50:44.903  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:44.903  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:50:44.904  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:50:44.904  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:44.904  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-26 10:50:44.904  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:44.904  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95cec9 not in the list
09-26 10:50:44.904  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:50:44.904  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:44.904  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:50:44.909  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:44.909  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:44.910  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:44.912  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:44.912  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:50:44.913  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:44.914  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:50:44.915  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:44.915  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:44.915  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:44.915  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:50:44.916  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:44.916  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:44.916  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f95cec9 not in the list
09-26 10:50:44.916  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:44.916  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:44.916  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:44.916  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5bed0 not in the list
09-26 10:50:44.917  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 10:50:44.917  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85df4a6 added. We now have 3 listener(s)
,09-26 10:50:44.919  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 10:50:44.919  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:50:44.920  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 10:50:44.920  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 10:50:44.920  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefeee7 added. We now have 4 listener(s)
09-26 10:50:44.920  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:50:44.921  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-26 10:50:44.925  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:44.931  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:50:44.933  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:50:44.934  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-26 10:50:44.934  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:50:44.934  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-26 10:50:44.934  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-26 10:50:44.934  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:44.934  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:50:44.938  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:44.940  5684  5730 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:44.940  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 10:50:44.943  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:44.947  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-26 10:50:44.948  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:50:44.948  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-26 10:50:44.951  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-26 10:50:44.952  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-26 10:50:44.952  5684  5730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-26 10:50:44.953  5684  5730 D BluetoothAdapter: STATE_ON
,09-26 10:50:44.955  5919  5957 D BtGatt.GattService: registerClient() - UUID=ff243d90-135c-43ce-bf42-50db827cefee
,09-26 10:50:44.956  5919  5935 D BtGatt.GattService: onClientRegistered() - UUID=ff243d90-135c-43ce-bf42-50db827cefee, clientIf=5
,09-26 10:50:44.956  5684  5694 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-26 10:50:44.957  5919  5958 D BtGatt.GattService: start scan with filters
09-26 10:50:44.959  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-26 10:50:44.959  5919  5939 D BtGatt.ScanManager: handling starting scan
,09-26 10:50:44.959  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-26 10:50:44.960  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-26 10:50:44.960  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-26 10:50:44.962  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-26 10:50:44.963  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-26 10:50:44.963  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-26 10:50:44.964  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-26 10:50:44.967  5919  5935 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-26 10:50:44.967  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:44.967  5919  5939 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-26 10:50:44.972  5919  5935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-26 10:50:44.973  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:44.973  5919  5939 D BtGatt.ScanManager: Starting BLE batch scan
09-26 10:50:44.973  5919  5939 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-26 10:50:44.982  5919  5935 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-26 10:50:44.983  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:50:44.988  5919  5935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-26 10:50:44.988  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:50:45.413  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 10:50:45.464  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-26 10:50:45.464  5684  5684 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:50:45.464  5684  5684 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-26 10:50:47.452   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:50:47.459   929  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 56
,09-26 10:50:47.973  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-26 10:50:47.974  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-26 10:50:47.974  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-26 10:50:47.974  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:47.974  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-26 10:50:47.974  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-26 10:50:47.975  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-26 10:50:47.975  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-26 10:50:47.975  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-26 10:50:47.975  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-26 10:50:47.976  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-26 10:50:47.978  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:50:47.979  5919  5930 D BtGatt.GattService: stopScan() - queue size =1
,09-26 10:50:47.982  5919  5957 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-26 10:50:47.982  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:47.983  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-26 10:50:47.983  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-26 10:50:47.983  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-26 10:50:47.983  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-26 10:50:47.986  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-26 10:50:47.986  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:47.987  5684  5730 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-26 10:50:47.987  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:47.987  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:47.990  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-26 10:50:47.990  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:50:47.990  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:50:47.990  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-26 10:50:47.990  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:47.990  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-26 10:50:47.990  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-26 10:50:47.990  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85df4a6 removed from the list
09-26 10:50:47.990  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:47.990  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefeee7 removed from the list
09-26 10:50:47.990  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:47.990  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:47.990  5919  5919 D BtGatt.ScanManager: awakened up at time 328818
09-26 10:50:47.996  5919  5935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-26 10:50:47.996  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:47.997  5919  5939 D BtGatt.ScanManager: stopping BLe Batch
,09-26 10:50:47.999  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:47.999  5684  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-26 10:50:48.006  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-26 10:50:48.007  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-26 10:50:48.007  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-26 10:50:48.007  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:48.007  5919  5935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-26 10:50:48.008  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-26 10:50:48.008  5919  5939 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-26 10:50:48.008  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.011  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:48.011  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.012  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:50:48.012  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:48.012  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:50:48.013  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:50:48.013  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:48.013  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:48.013  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:48.013  5684  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-26 10:50:48.013  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefeee7 not in the list
09-26 10:50:48.013  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-26 10:50:48.013  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-26 10:50:48.017  5684  5684 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-26 10:50:48.017  5684  5684 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-26 10:50:48.019  5684  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:48.022  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:48.022  5684  5684 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-26 10:50:48.022  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.023  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:50:48.023  5684  5730 D BluetoothAdapter: STATE_ON
09-26 10:50:48.023  5684  5730 D BluetoothLeScanner: could not find callback wrapper
09-26 10:50:48.024  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-26 10:50:48.024  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-26 10:50:48.024  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-26 10:50:48.024  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:48.024  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eefeee7 not in the list
09-26 10:50:48.024  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:48.024  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:48.024  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.024  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85df4a6 not in the list
09-26 10:50:48.025  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-26 10:50:48.025  5919  5935 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-26 10:50:48.025  5919  5935 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-26 10:50:48.025  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71f582c added. We now have 3 listener(s)
09-26 10:50:48.025  5919  5935 D BtGatt.GattService: current time is 328853141985
09-26 10:50:48.025  5919  5935 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -71, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -87, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -79, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 10:50:48.026  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-26 10:50:48.026  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-26 10:50:48.026  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-26 10:50:48.026  5919  5935 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-26 10:50:48.027  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-26 10:50:48.027  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e22f5 added. We now have 4 listener(s)
09-26 10:50:48.027  5684  5730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-26 10:50:48.027  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-26 10:50:48.027  5919  5935 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-26 10:50:48.027  5919  5935 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-26 10:50:48.028  5919  5935 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-26 10:50:48.028  5919  5935 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-26 10:50:48.030  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-26 10:50:48.034  5684  5730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-26 10:50:48.036  5684  5730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-26 10:50:48.036  5684  5730 D io.jxcore.node.ConnectivityMonitor: start: OK
09-26 10:50:48.036  5684  5730 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-26 10:50:48.037  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-26 10:50:48.037  5684  5730 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-26 10:50:48.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:48.037  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:48.037  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-26 10:50:48.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-26 10:50:48.037  5684  5730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71f582c removed from the list
09-26 10:50:48.037  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:48.037  5684  5730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e22f5 removed from the list
09-26 10:50:48.038  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-26 10:50:48.039  5684  5730 D io.jxcore.node.ConnectivityMonitor: stop
09-26 10:50:48.039  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.039  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-26 10:50:48.039  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.040  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:50:48.040  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-26 10:50:48.040  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:48.040  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e22f5 not in the list
09-26 10:50:48.041  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:48.041  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-26 10:50:48.043  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-26 10:50:48.044  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-26 10:50:48.044  5684  5730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-26 10:50:48.044  5684  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-26 10:50:48.044  5684  5730 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e22f5 not in the list
09-26 10:50:48.044  5684  5730 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-26 10:50:48.044  5684  5730 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-26 10:50:48.044  5684  5730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-26 10:50:48.044  5684  5730 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71f582c not in the list
09-26 10:50:48.044  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-26 10:50:48.045  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-26 10:50:48.045  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-26 10:50:48.045  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-26 10:50:48.045  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-26 10:50:48.045  5684  5730 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-26 10:50:48.523  5684  5684 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-26 10:50:48.765   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 10:50:48.766   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 10:50:50.056  5684  6017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: My test thread name)
,09-26 10:50:50.482   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-26 10:50:50.490   929  3026 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-26 10:50:52.054  5684  5730 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 190
,09-26 10:50:52.055  5684  5730 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 190, name: My test thread name)
,09-26 10:50:52.060  5684  6018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-26 10:50:52.061  5684  6018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: My test thread name)
,09-26 10:50:52.061  5684  6018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-26 10:50:52.064  5684  5730 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-26 10:50:52.072  5684  6019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name)
,09-26 10:50:52.072  5684  6019 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 195, thread name: My test thread name): Test exception.
09-26 10:50:52.073  5684  6019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-26 10:50:52.084  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-26 10:50:52.084  5684  5730 I jxcore-log: 
,09-26 10:50:52.085  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-26 10:50:52.085  5684  5730 I jxcore-log: 
,09-26 10:50:52.087  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-26 10:50:52.087  5684  5730 I jxcore-log: 
09-26 10:50:52.089  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-26 10:50:52.089  5684  5730 I jxcore-log: 
,09-26 10:50:52.092  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Total duration:  101048'
09-26 10:50:52.092  5684  5730 I jxcore-log: 
,09-26 10:50:52.099  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-26 10:50:52.099  5684  5730 I jxcore-log: 
,09-26 10:50:52.112  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.112  5684  5730 I jxcore-log: 
,09-26 10:50:52.115  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.115  5684  5730 I jxcore-log: 
,09-26 10:50:52.116  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.116  5684  5730 I jxcore-log: 
,09-26 10:50:52.117  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.117  5684  5730 I jxcore-log: 
,09-26 10:50:52.119  5684  5684 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-26 10:50:52.119  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 10:50:52.119  5684  5730 I jxcore-log: 
,09-26 10:50:52.121  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 10:50:52.121  5684  5730 I jxcore-log: 
,09-26 10:50:52.122  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.122  5684  5730 I jxcore-log: 
,09-26 10:50:52.123  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.123  5684  5730 I jxcore-log: 
,09-26 10:50:52.124  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 10:50:52.124  5684  5730 I jxcore-log: 
,09-26 10:50:52.125  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 10:50:52.125  5684  5730 I jxcore-log: 
,09-26 10:50:52.126  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 10:50:52.126  5684  5730 I jxcore-log: 
09-26 10:50:52.127  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.127  5684  5730 I jxcore-log: 
09-26 10:50:52.128  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.128  5684  5730 I jxcore-log: 
09-26 10:50:52.129  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.129  5684  5730 I jxcore-log: 
,09-26 10:50:52.130  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.130  5684  5730 I jxcore-log: 
,09-26 10:50:52.131  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.131  5684  5730 I jxcore-log: 
,09-26 10:50:52.133  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.133  5684  5730 I jxcore-log: 
,09-26 10:50:52.133  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.133  5684  5730 I jxcore-log: 
09-26 10:50:52.135  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.135  5684  5730 I jxcore-log: 
,09-26 10:50:52.136  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.136  5684  5730 I jxcore-log: 
,09-26 10:50:52.137  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.137  5684  5730 I jxcore-log: 
,09-26 10:50:52.138  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.138  5684  5730 I jxcore-log: 
,09-26 10:50:52.139  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.139  5684  5730 I jxcore-log: 
,09-26 10:50:52.142  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.142  5684  5730 I jxcore-log: 
,09-26 10:50:52.143  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.143  5684  5730 I jxcore-log: 
09-26 10:50:52.144  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.144  5684  5730 I jxcore-log: 
,09-26 10:50:52.145  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.145  5684  5730 I jxcore-log: 
,09-26 10:50:52.146  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.146  5684  5730 I jxcore-log: 
09-26 10:50:52.146  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.146  5684  5730 I jxcore-log: 
,09-26 10:50:52.147  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.147  5684  5730 I jxcore-log: 
,09-26 10:50:52.148  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.148  5684  5730 I jxcore-log: 
,09-26 10:50:52.148  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.148  5684  5730 I jxcore-log: 
09-26 10:50:52.149  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.149  5684  5730 I jxcore-log: 
,09-26 10:50:52.149  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.149  5684  5730 I jxcore-log: 
,09-26 10:50:52.150  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.150  5684  5730 I jxcore-log: 
,09-26 10:50:52.151  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.151  5684  5730 I jxcore-log: 
,09-26 10:50:52.151  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.151  5684  5730 I jxcore-log: 
,09-26 10:50:52.152  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.152  5684  5730 I jxcore-log: 
,09-26 10:50:52.153  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-26 10:50:52.153  5684  5730 I jxcore-log: 
,09-26 10:50:52.153  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.153  5684  5730 I jxcore-log: 
,09-26 10:50:52.154  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-26 10:50:52.154  5684  5730 I jxcore-log: 
,09-26 10:50:52.154  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.154  5684  5730 I jxcore-log: 
,09-26 10:50:52.155  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.155  5684  5730 I jxcore-log: 
,09-26 10:50:52.156  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.156  5684  5730 I jxcore-log: 
,09-26 10:50:52.157  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.157  5684  5730 I jxcore-log: 
,09-26 10:50:52.157  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.157  5684  5730 I jxcore-log: 
,09-26 10:50:52.158  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 10:50:52.158  5684  5730 I jxcore-log: 
,09-26 10:50:52.159  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.159  5684  5730 I jxcore-log: 
,09-26 10:50:52.159  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-26 10:50:52.159  5684  5730 I jxcore-log: 
,09-26 10:50:52.160  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.160  5684  5730 I jxcore-log: 
,09-26 10:50:52.160  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 10:50:52.160  5684  5730 I jxcore-log: 
,09-26 10:50:52.161  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-26 10:50:52.161  5684  5730 I jxcore-log: 
,09-26 10:50:52.162  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-26 10:50:52.162  5684  5730 I jxcore-log: 
,09-26 10:50:52.162  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-26 10:50:52.162  5684  5730 I jxcore-log: 
,09-26 10:50:52.164  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-26 10:50:52.164  5684  5730 I jxcore-log: 
,09-26 10:50:52.165  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - WARN testUtils: 'myNameCallback not set!'
09-26 10:50:52.165  5684  5730 I jxcore-log: 
,09-26 10:50:52.166  5684  5730 I jxcore-log: 2016-09-26 14:50:52 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-26 10:50:52.166  5684  5730 I jxcore-log: 
,09-26 10:50:52.190  5684  6017 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-26 10:50:53.509   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:50:53.696   929  5976 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334523, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-26 10:50:54.182  5684  5730 I jxcore-log: 2016-09-26 14:50:54 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-26 10:50:54.182  5684  5730 I jxcore-log: 
,09-26 10:50:54.512  5684  5730 I jxcore-log: 2016-09-26 14:50:54 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-26 10:50:54.512  5684  5730 I jxcore-log: 
,09-26 10:50:54.526  5684  5730 I jxcore-log: 2016-09-26 14:50:54 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-26 10:50:54.526  5684  5730 I jxcore-log: 
,09-26 10:50:55.648  5684  5730 I jxcore-log: 2016-09-26 14:50:55 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-26 10:50:55.648  5684  5730 I jxcore-log: 
,09-26 10:50:55.799  5684  5730 I jxcore-log: 2016-09-26 14:50:55 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-26 10:50:55.799  5684  5730 I jxcore-log: 
,09-26 10:50:55.805  5684  5730 I jxcore-log: 2016-09-26 14:50:55 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-26 10:50:55.805  5684  5730 I jxcore-log: 
,09-26 10:50:55.809  5684  5730 I jxcore-log: 2016-09-26 14:50:55 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-26 10:50:55.809  5684  5730 I jxcore-log: 
,09-26 10:50:56.346  5684  5730 I jxcore-log: 2016-09-26 14:50:56 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-26 10:50:56.346  5684  5730 I jxcore-log: 
,09-26 10:50:56.399  5684  5730 I jxcore-log: 2016-09-26 14:50:56 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-26 10:50:56.399  5684  5730 I jxcore-log: 
,09-26 10:50:56.412  5684  5730 I jxcore-log: 2016-09-26 14:50:56 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-26 10:50:56.412  5684  5730 I jxcore-log: 
,09-26 10:50:56.423  5684  5730 I jxcore-log: 2016-09-26 14:50:56 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-26 10:50:56.423  5684  5730 I jxcore-log: 
,09-26 10:50:56.686  5684  5730 I jxcore-log: 2016-09-26 14:50:56 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-26 10:50:56.686  5684  5730 I jxcore-log: 
,09-26 10:50:56.809  5684  5730 I jxcore-log: 2016-09-26 14:50:56 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-26 10:50:56.809  5684  5730 I jxcore-log: 
,09-26 10:50:57.041  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-26 10:50:57.041  5684  5730 I jxcore-log: 
,09-26 10:50:57.052  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-26 10:50:57.052  5684  5730 I jxcore-log: 
,09-26 10:50:57.058  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-26 10:50:57.058  5684  5730 I jxcore-log: 
,09-26 10:50:57.064  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-26 10:50:57.064  5684  5730 I jxcore-log: 
,09-26 10:50:57.094  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-26 10:50:57.094  5684  5730 I jxcore-log: 
,09-26 10:50:57.131  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-26 10:50:57.131  5684  5730 I jxcore-log: 
,09-26 10:50:57.138  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-26 10:50:57.138  5684  5730 I jxcore-log: 
,09-26 10:50:57.145  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-26 10:50:57.145  5684  5730 I jxcore-log: 
,09-26 10:50:57.160  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-26 10:50:57.160  5684  5730 I jxcore-log: 
,09-26 10:50:57.165  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-26 10:50:57.165  5684  5730 I jxcore-log: 
,09-26 10:50:57.171  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-26 10:50:57.171  5684  5730 I jxcore-log: 
,09-26 10:50:57.184  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-26 10:50:57.184  5684  5730 I jxcore-log: 
,09-26 10:50:57.206  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-26 10:50:57.206  5684  5730 I jxcore-log: 
,09-26 10:50:57.215  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-26 10:50:57.215  5684  5730 I jxcore-log: 
,09-26 10:50:57.226  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-26 10:50:57.226  5684  5730 I jxcore-log: 
,09-26 10:50:57.235  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-26 10:50:57.235  5684  5730 I jxcore-log: 
,09-26 10:50:57.247  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-26 10:50:57.247  5684  5730 I jxcore-log: 
,09-26 10:50:57.257  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-26 10:50:57.257  5684  5730 I jxcore-log: 
,09-26 10:50:57.262  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-26 10:50:57.262  5684  5730 I jxcore-log: 
,09-26 10:50:57.281  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js'
09-26 10:50:57.281  5684  5730 I jxcore-log: 
,09-26 10:50:57.290  5684  5730 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-26 10:50:57.291  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - INFO testUtils: 'BLE multiple advertisement supported'
09-26 10:50:57.291  5684  5730 I jxcore-log: 
,09-26 10:50:57.569  5684  5730 I jxcore-log: 2016-09-26 14:50:57 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:50:57.569  5684  5730 I jxcore-log: 
,09-26 10:51:02.356   929  5976 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-26 10:51:03.767   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:04.768   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:05.769   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:06.516   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:51:06.770   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:07.772   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:08.772   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 10:51:13.774   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:14.775   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:15.776   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:16.778   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:17.779   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:18.780   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 10:51:28.781   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:29.783   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:30.784   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:31.785   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:32.787   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:33.787   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 10:51:46.518   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:51:48.788   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:49.789   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:50.791   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:51.792   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:52.793   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:51:53.794   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 10:52:06.519   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:52:13.795   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:52:14.796   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:52:15.798   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:52:16.799   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:52:17.801   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:52:18.801   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-26 10:52:43.802   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-26 10:52:43.803   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-26 10:52:45.410   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:52:46.524   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:52:48.444   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:00.562   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:03.592   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:03.804   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:04.805   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:05.807   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:06.525   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:53:06.808   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:07.809   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:08.809   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-26 10:53:09.642   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:12.674   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:13.811   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:14.812   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:15.813   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:16.814   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:17.816   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:18.817   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-26 10:53:26.528   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:53:28.818   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:29.819   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:30.821   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:31.822   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:32.823   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:33.824   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-26 10:53:39.908   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:45.969   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:48.826   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:48.989   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:49.827   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:50.828   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:51.830   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:52.027   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:53:52.831   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:53:53.832   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-26 10:53:59.664  5684  5730 I jxcore-log: 2016-09-26 14:53:59 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-26 10:53:59.664  5684  5730 I jxcore-log: 
,09-26 10:53:59.854  5684  5730 I jxcore-log: 2016-09-26 14:53:59 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:53:59.854  5684  5730 I jxcore-log: 
,09-26 10:53:59.862  5684  5730 I jxcore-log: 2016-09-26 14:53:59 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:53:59.862  5684  5730 I jxcore-log: 
,09-26 10:54:00.125  5684  5730 I jxcore-log: 2016-09-26 14:54:00 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:00.125  5684  5730 I jxcore-log: 
,09-26 10:54:00.133  5684  5730 I jxcore-log: 2016-09-26 14:54:00 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:00.133  5684  5730 I jxcore-log: 
,09-26 10:54:00.638  5684  5730 I jxcore-log: 2016-09-26 14:54:00 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:00.638  5684  5730 I jxcore-log: 
,09-26 10:54:00.646  5684  5730 I jxcore-log: 2016-09-26 14:54:00 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:00.646  5684  5730 I jxcore-log: 
,09-26 10:54:01.115   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:54:01.694  5684  5730 I jxcore-log: 2016-09-26 14:54:01 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:01.694  5684  5730 I jxcore-log: 
,09-26 10:54:01.704  5684  5730 I jxcore-log: 2016-09-26 14:54:01 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:01.704  5684  5730 I jxcore-log: 
,09-26 10:54:02.738  5684  5730 I jxcore-log: 2016-09-26 14:54:02 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:02.738  5684  5730 I jxcore-log: 
,09-26 10:54:02.743  5684  5730 I jxcore-log: 2016-09-26 14:54:02 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:02.743  5684  5730 I jxcore-log: 
,09-26 10:54:03.783  5684  5730 I jxcore-log: 2016-09-26 14:54:03 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:03.783  5684  5730 I jxcore-log: 
,09-26 10:54:03.790  5684  5730 I jxcore-log: 2016-09-26 14:54:03 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:03.790  5684  5730 I jxcore-log: 
,09-26 10:54:04.143   929  3026 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-26 10:54:04.826  5684  5730 I jxcore-log: 2016-09-26 14:54:04 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:04.826  5684  5730 I jxcore-log: 
,09-26 10:54:04.836  5684  5730 I jxcore-log: 2016-09-26 14:54:04 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:04.836  5684  5730 I jxcore-log: 
,09-26 10:54:06.494  5684  5730 I jxcore-log: 2016-09-26 14:54:06 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:06.494  5684  5730 I jxcore-log: 
,09-26 10:54:06.503  5684  5730 I jxcore-log: 2016-09-26 14:54:06 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:06.503  5684  5730 I jxcore-log: 
,09-26 10:54:06.530   929  3024 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-26 10:54:07.556  5684  5730 I jxcore-log: 2016-09-26 14:54:07 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:07.556  5684  5730 I jxcore-log: 
,09-26 10:54:07.564  5684  5730 I jxcore-log: 2016-09-26 14:54:07 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:07.564  5684  5730 I jxcore-log: 
,09-26 10:54:08.630  5684  5730 I jxcore-log: 2016-09-26 14:54:08 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:08.630  5684  5730 I jxcore-log: 
,09-26 10:54:08.639  5684  5730 I jxcore-log: 2016-09-26 14:54:08 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:08.639  5684  5730 I jxcore-log: 
,09-26 10:54:09.682  5684  5730 I jxcore-log: 2016-09-26 14:54:09 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:09.682  5684  5730 I jxcore-log: 
,09-26 10:54:09.692  5684  5730 I jxcore-log: 2016-09-26 14:54:09 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:09.692  5684  5730 I jxcore-log: 
,09-26 10:54:10.727  5684  5730 I jxcore-log: 2016-09-26 14:54:10 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:10.727  5684  5730 I jxcore-log: 
,09-26 10:54:10.737  5684  5730 I jxcore-log: 2016-09-26 14:54:10 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:10.737  5684  5730 I jxcore-log: 
,09-26 10:54:11.771  5684  5730 I jxcore-log: 2016-09-26 14:54:11 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:11.771  5684  5730 I jxcore-log: 
,09-26 10:54:11.778  5684  5730 I jxcore-log: 2016-09-26 14:54:11 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:11.778  5684  5730 I jxcore-log: 
,09-26 10:54:12.815  5684  5730 I jxcore-log: 2016-09-26 14:54:12 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:12.815  5684  5730 I jxcore-log: 
,09-26 10:54:12.833  5684  5730 I jxcore-log: 2016-09-26 14:54:12 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:12.833  5684  5730 I jxcore-log: 
,09-26 10:54:13.833   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:54:13.879  5684  5730 I jxcore-log: 2016-09-26 14:54:13 - DEBUG CoordinatedClient: 'connected to the test server'
09-26 10:54:13.879  5684  5730 I jxcore-log: 
,09-26 10:54:13.891  5684  5730 I jxcore-log: 2016-09-26 14:54:13 - DEBUG CoordinatedClient: 'reconnected to the test server'
09-26 10:54:13.891  5684  5730 I jxcore-log: 
,09-26 10:54:14.835   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:54:15.836   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:54:16.837   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-26 10:54:17.838   535   535 I ServiceManager: Waiting for service AtCmdFwd...

```
