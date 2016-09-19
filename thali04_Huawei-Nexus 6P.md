#### Test 85202518a9487e3_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-19 07:38:35.266   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:35.958  5560  5560 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 07:38:35.963  5560  5560 D AndroidRuntime: CheckJNI is OFF
09-19 07:38:35.990  5560  5560 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 07:38:36.031  5560  5560 I Radio-JNI: register_android_hardware_Radio DONE
09-19 07:38:36.046  5560  5560 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-19 07:38:36.049   927  3751 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-19 07:38:36.091   927  3751 I ActivityManager: Start proc 5569:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-19 07:38:36.096  5560  5560 D AndroidRuntime: Shutting down VM
09-19 07:38:36.125   927   937 I ActivityManager: Killing 3509:com.google.android.gm/u0a68 (adj 15): empty #17
09-19 07:38:36.225  5569  5569 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-19 07:38:36.258  5569  5569 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-19 07:38:36.266   537   537 I ServiceManager: Waiting for service AtCmdFwd...
09-19 07:38:36.284  5569  5569 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 5186-5204)
09-19 07:38:36.284  5569  5569 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-19 07:38:36.304  5569  5569 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56da455}
09-19 07:38:36.305  5569  5569 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-19 07:38:36.305  5569  5569 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-19 07:38:36.310  5569  5569 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-19 07:38:36.312  5569  5569 E SysUtils: ApplicationContext is null in ApplicationStatus
09-19 07:38:36.359  5569  5569 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-19 07:38:36.372  5569  5569 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 07:38:36.373  5569  5569 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 07:38:36.373  5569  5569 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-19 07:38:36.373  5569  5569 I Adreno  : Build Date                       : 12/06/15
09-19 07:38:36.373  5569  5569 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-19 07:38:36.373  5569  5569 I Adreno  : Local Branch                     : mybranch17112971
09-19 07:38:36.373  5569  5569 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-19 07:38:36.373  5569  5569 I Adreno  : Remote Branch                    : NONE
09-19 07:38:36.373  5569  5569 I Adreno  : Reconstruct Branch               : NOTHING
09-19 07:38:36.424   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa1ab71:true
09-19 07:38:36.453   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34078]" dev="sockfs" ino=34078 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 07:38:36.453   403   403 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34078]" dev="sockfs" ino=34078 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 07:38:36.470  5569  5569 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-19 07:38:36.480  5569  5569 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
09-19 07:38:36.507   403   403 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32652]" dev="sockfs" ino=32652 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 07:38:36.507   403   403 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32652]" dev="sockfs" ino=32652 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 07:38:36.512  5569  5606 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-19 07:38:36.513  3804  3804 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[34089]" dev="sockfs" ino=34089 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:38:36.513  3804  3804 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[34089]" dev="sockfs" ino=34089 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:38:36.521  5569  5593 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-19 07:38:36.560  5569  5606 I OpenGLRenderer: Initialized EGL, version 1.4
09-19 07:38:36.648   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +470ms (total +586ms)
09-19 07:38:36.661  5569  5569 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5569
09-19 07:38:36.752  5569  5569 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-19 07:38:36.956  5569  5607 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -562562768
09-19 07:38:36.962  5569  5607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-19 07:38:36.962  5569  5607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-19 07:38:36.962  5569  5607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-19 07:38:36.962  5569  5607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-19 07:38:36.962  5569  5607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-19 07:38:36.962  5569  5607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5143f82 added. We now have 1 listener(s)
09-19 07:38:36.966  5569  5607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-19 07:38:36.967  5569  5607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 07:38:36.967  5569  5607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:38:36.967  5569  5607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-19 07:38:36.972  5569  5607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7286c9 added. We now have 1 listener(s)
09-19 07:38:36.972  5569  5607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:38:36.977   927  2950 D WifiService: New client listening to asynchronous messages
09-19 07:38:36.977  5569  5607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 07:38:36.978  5569  5607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-19 07:38:36.978  5569  5607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-19 07:38:36.978  5569  5607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-19 07:38:36.978  5569  5607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-19 07:38:36.980  5569  5607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:36.981  5569  5607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-19 07:38:36.986  5569  5607 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:38:36.986  5569  5607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:38:36.987  5569  5607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-19 07:38:36.987  5569  5607 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:38:36.987  5569  5607 I io.jxcore.node.LifeCycleMonitor: start: OK
09-19 07:38:36.989  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:36.992  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:37.014  5569  5569 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-19 07:38:37.267   537   537 I ServiceManager: Waiting for service AtCmdFwd...
09-19 07:38:37.506  5569  5578 I art     : Background sticky concurrent mark sweep GC freed 76627(7MB) AllocSpace objects, 17(1872KB) LOS objects, 28% free, 23MB/32MB, paused 2.615ms total 273.458ms
,09-19 07:38:38.131  5569  5615 W jxcore-log: Initializing JXcore engine
09-19 07:38:38.131  5569  5615 W jxcore-log: JXcore engine is ready
,09-19 07:38:38.187  5615  5615 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11811 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-19 07:38:38.187  5615  5615 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16392]" dev="sockfs" ino=16392 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-19 07:38:38.187  5615  5615 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-19 07:38:38.187  5615  5615 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31549]" dev="sockfs" ino=31549 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-19 07:38:38.203  5569  5615 W jxcore-log: Starting JXcore engine
,09-19 07:38:38.263  5569  5615 W jxcore-log: Platform android
09-19 07:38:38.263  5569  5615 W jxcore-log: 
,09-19 07:38:38.263  5569  5615 W jxcore-log: Process ARCH arm
09-19 07:38:38.263  5569  5615 W jxcore-log: 
,09-19 07:38:38.268   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:38.360  5569  5615 I jxcore-log: JXcore Cordova bridge is ready!
09-19 07:38:38.360  5569  5615 I jxcore-log: 
,09-19 07:38:38.360  5569  5615 W jxcore-log: JXcore engine is started
,09-19 07:38:38.374  5569  5607 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-19 07:38:38.380  5569  5569 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-19 07:38:39.270   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:40.270   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:38:46.901  3545  5617 I VacuumService: Vacuum at: now=1474285126901 tag=VacuumService
,09-19 07:38:46.940  3545  5620 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-19 07:38:46.980  3545  5618 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-19 07:38:46.983  3545  5618 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-19 07:38:47.007  3545  5620 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.252  3545  5618 W Uploader:  no longer exists, so no auth token.
,09-19 07:38:47.260  3545  5622 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.320  3545  5620 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.443  3545  5622 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.608  3545  5620 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.689  3545  5618 W Uploader:  no longer exists, so no auth token.
,09-19 07:38:47.701  3545  5622 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.783  3545  5620 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-19 07:38:47.784  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-19 07:38:47.784  5569  5615 I jxcore-log: 
09-19 07:38:47.786  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-19 07:38:47.786  5569  5615 I jxcore-log: 
,09-19 07:38:47.787  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:38:47.787  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:38:47.788  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:47.788  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:47.789  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-19 07:38:47.789  5569  5615 I jxcore-log: 
09-19 07:38:47.790  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-19 07:38:47.790  5569  5615 I jxcore-log: 
,09-19 07:38:48.018  5569  5615 I jxcore-log: Running unit tests
09-19 07:38:48.018  5569  5615 I jxcore-log: 
09-19 07:38:48.018  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 07:38:48.019  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cec02 added. We now have 2 listener(s)
09-19 07:38:48.020  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 07:38:48.020  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:38:48.020  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 07:38:48.020  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:38:48.020  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a054913 added. We now have 2 listener(s)
09-19 07:38:48.020  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:38:48.021  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 07:38:48.022  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:48.023  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:38:48.023  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:38:48.023  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:48.023  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:48.023  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-19 07:38:48.023  5569  5615 D executeNativeTests: Running unit tests
,09-19 07:38:48.027  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:38:48.031  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:38:48.060  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 07:38:48.061  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 added. We now have 3 listener(s)
09-19 07:38:48.061  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 07:38:48.061  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:38:48.061  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 07:38:48.061  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:38:48.061  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe added. We now have 3 listener(s)
09-19 07:38:48.061  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:38:48.062  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 07:38:48.063  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:48.064  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:38:48.064  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:38:48.064  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:38:48.064  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:48.064  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:38:48.065  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-19 07:38:48.066  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:38:48.066  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:38:48.066  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-19 07:38:48.066  5569  5615 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-19 07:38:48.066  5569  5615 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-19 07:38:48.066  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 07:38:48.067  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-19 07:38:48.067  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:38:48.067  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:38:48.067  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:38:48.067  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:38:48.067  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:38:48.067  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:38:48.067  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.067  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:38:48.067  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-19 07:38:48.067  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 removed from the list
09-19 07:38:48.067  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:48.067  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe removed from the list
,09-19 07:38:48.068  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:48.072  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:48.073  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:38:48.073  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.074  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.074  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.074  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:38:48.074  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:38:48.074  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:48.074  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:48.075  5569  5615 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-19 07:38:48.075  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:38:48.075  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:38:48.075  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:38:48.075  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:38:48.075  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.075  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.075  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:38:48.075  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:48.075  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:48.075  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:38:48.075  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.075  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.075  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.075  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.076  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:38:48.076  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:38:48.076  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:48.076  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-19 07:38:48.078  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-19 07:38:48.079  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:38:48.079  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:38:48.079  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:38:48.079  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:38:48.079  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.079  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.079  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:38:48.079  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:48.079  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:48.079  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:38:48.079  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.079  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.079  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:48.079  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:48.080  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:38:48.080  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:38:48.080  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:48.080  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:48.080  5569  5615 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-19 07:38:48.081  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:48.082  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:38:48.082  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:38:48.082  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:48.082  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:48.082  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:38:48.082  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 07:38:48.082  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 07:38:48.082  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 07:38:48.082  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:48.082  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 07:38:48.084  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-19 07:38:48.084  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:48.085  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:48.085  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-19 07:38:48.085  5569  5615 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-19 07:38:48.086  5569  5615 I io.jxcore.node.ConnectionHelper: start: OK
09-19 07:38:48.086  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-19 07:38:48.588  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 07:38:52.037   927  5279 D NetlinkSocketObserver: NeighborEvent{elapsedMs=160957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-19 07:38:53.087  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:38:53.088  5569  5615 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-19 07:38:53.090  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:38:53.090  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:38:53.090  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 07:38:53.090  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:53.090  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-19 07:38:53.090  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 07:38:53.090  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-19 07:38:53.091  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 07:38:53.091  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 07:38:53.091  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 07:38:53.092  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 07:38:53.093  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:38:53.093  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:38:53.093  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:38:53.093  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:53.093  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:38:53.094  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
,09-19 07:38:53.093  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:38:53.094  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:53.094  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:53.094  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-19 07:38:53.094  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:38:53.094  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:53.094  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:53.095  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:38:53.095  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:38:53.095  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 07:38:53.095  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:38:53.095  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:38:53.096  5569  5615 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-19 07:38:53.098  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:53.100  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:38:53.100  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 07:38:53.101  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:38:53.101  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:38:53.101  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:38:53.101  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 07:38:53.101  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-19 07:38:53.101  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 07:38:53.101  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:38:53.101  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 07:38:53.104  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-19 07:38:53.104  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-19 07:38:53.104  5569  5615 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-19 07:38:53.104  5569  5615 I io.jxcore.node.ConnectionHelper: start: OK
09-19 07:38:53.105  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:38:53.108  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:38:53.108  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-19 07:38:53.610  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 07:38:55.271   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:56.273   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:57.274   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:58.105  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:38:58.106  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:38:58.106  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 07:38:58.106  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:38:58.106  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-19 07:38:58.106  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 07:38:58.106  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 07:38:58.106  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 07:38:58.106  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-19 07:38:58.107  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 07:38:58.107  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:38:58.108  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:38:58.108  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:38:58.109  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:38:58.109  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-19 07:38:58.275   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:38:58.609  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 07:38:58.610  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:38:58.610  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-19 07:38:59.277   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:39:00.277   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:39:03.110  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:39:03.110  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:39:03.110  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 07:39:03.111  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 07:39:03.111  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.111  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 07:39:03.111  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.111  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.111  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.111  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.112  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.113  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.114  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:03.115  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.115  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.115  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:03.115  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.119  5569  5615 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-19 07:39:03.120  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.121  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.121  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 07:39:03.121  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.121  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.121  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.122  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.122  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.122  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.122  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.122  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.122  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.122  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.123  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.123  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.124  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.124  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.124  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.126  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-19 07:39:03.126  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.127  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.127  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:03.127  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.127  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.127  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.127  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.128  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.128  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.128  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.128  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.128  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.128  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.128  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.130  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.131  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.131  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.131  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.131  5569  5615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-19 07:39:03.132  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.132  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.132  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:03.132  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.132  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.132  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.132  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.132  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.132  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.132  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.133  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.133  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.133  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.133  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.134  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.134  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.134  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.134  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.134  5569  5615 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-19 07:39:03.135  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.135  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.135  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:03.135  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.135  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:39:03.135  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.135  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.135  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.135  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.135  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.135  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.135  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.135  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.135  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.136  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 07:39:03.136  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.136  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.136  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.137  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-19 07:39:03.137  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:39:03.137  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:39:03.137  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 07:39:03.138  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:39:03.138  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:39:03.138  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-19 07:39:03.138  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:39:03.138  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:39:03.138  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.138  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.138  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 07:39:03.138  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.138  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.138  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.138  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.138  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.139  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.139  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.139  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.139  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.139  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.139  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.140  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.140  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 07:39:03.141  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.141  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.143  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 07:39:03.143  5569  5615 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-19 07:39:03.144  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-19 07:39:03.150  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-19 07:39:03.151  5569  5615 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-19 07:39:03.151  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-19 07:39:03.151  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-19 07:39:03.152  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-19 07:39:03.153  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-19 07:39:03.154  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-19 07:39:03.155  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-19 07:39:03.155  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-19 07:39:03.156  5569  5615 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-19 07:39:03.156  5569  5615 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-19 07:39:03.156  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 07:39:03.156  5569  5615 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-19 07:39:03.156  5569  5615 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-19 07:39:03.156  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 07:39:03.156  5569  5615 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-19 07:39:03.156  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-19 07:39:03.158  5569  5615 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-19 07:39:03.158  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-19 07:39:03.161  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-19 07:39:03.161  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-19 07:39:03.163  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-19 07:39:03.163  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-19 07:39:03.163  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-19 07:39:03.163  5569  5615 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-19 07:39:03.164  5569  5615 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-19 07:39:03.164  5569  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-19 07:39:03.164  5569  5627 E BluetoothDevice: Bluetooth is not enabled
09-19 07:39:03.164  5569  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 121)
09-19 07:39:03.164  5569  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 121)
09-19 07:39:03.164  5569  5627 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 121)
09-19 07:39:03.164  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.164  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.164  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:03.164  5569  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 121
09-19 07:39:03.164  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.165  5569  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 121
09-19 07:39:03.165  5569  5569 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-19 07:39:03.165  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.165  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.165  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.165  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.165  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.165  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.166  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.166  5569  5569 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-19 07:39:03.166  5569  5569 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 07:39:03.166  5569  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-19 07:39:03.166  5569  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-19 07:39:03.166  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.166  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.166  5569  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:39:03.166  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.166  5569  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:39:03.166  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.166  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.166  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:03.167  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
,09-19 07:39:03.167  5569  5615 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-19 07:39:03.168  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:39:03.168  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.168  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:03.168  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.168  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.168  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.168  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.168  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.168  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.168  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:39:03.168  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.169  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.169  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.169  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.169  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.169  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.169  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.169  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.170  5569  5615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-19 07:39:03.170  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.170  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:39:03.170  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:03.170  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.170  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.171  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.171  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.171  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.171  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.171  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:39:03.171  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.171  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.171  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.171  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.171  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.171  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.171  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.171  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.172  5569  5615 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-19 07:39:03.172  5569  5615 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-19 07:39:03.172  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-19 07:39:03.172  5569  5615 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-19 07:39:03.173  5569  5615 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-19 07:39:03.173  5569  5615 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-19 07:39:03.173  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-19 07:39:03.173  5569  5615 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-19 07:39:03.173  5569  5615 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-19 07:39:03.173  5569  5615 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-19 07:39:03.173  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-19 07:39:03.173  5569  5615 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-19 07:39:03.173  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:03.173  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:03.173  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-19 07:39:03.173  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:03.173  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.173  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.173  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.173  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.173  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.174  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.174  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.174  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.174  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.174  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.174  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:03.174  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:03.174  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.174  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.175  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 07:39:03.175  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.175  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:03.175  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:03.175  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:03.175  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:03.175  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:03.175  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:03.175  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:08.176  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:08.176  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.176  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.176  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.176  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:08.176  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.176  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:08.176  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:08.177  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:08.177  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.177  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.177  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.177  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.177  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:08.177  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.177  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:08.177  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.177  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.178  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.178  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:08.179  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:08.179  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:08.179  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.180  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.181  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-19 07:39:08.182  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:39:08.182  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-19 07:39:08.182  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-19 07:39:08.182  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 07:39:08.182  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-19 07:39:08.182  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.183  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-19 07:39:08.183  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.183  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-19 07:39:08.183  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.183  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-19 07:39:08.183  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:08.183  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 07:39:08.183  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 07:39:08.183  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 07:39:08.183  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:39:08.183  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.184  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:39:08.184  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.184  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:39:08.184  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:08.184  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-19 07:39:08.184  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:39:08.184  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:08.184  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:08.184  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.184  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.184  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.185  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.185  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.185  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.185  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:39:08.185  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.185  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.185  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.185  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:08.185  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:08.185  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:08.185  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.186  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.186  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-19 07:39:08.187  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:39:08.187  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-19 07:39:08.187  5569  5615 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-19 07:39:08.187  5569  5615 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-19 07:39:08.187  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-19 07:39:08.187  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:39:08.187  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-19 07:39:08.187  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:08.187  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:08.187  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:08.187  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.188  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.188  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.188  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.188  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.188  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.188  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:08.188  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.188  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.188  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:39:08.188  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.189  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:08.189  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:08.189  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.189  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.191  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:08.191  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:08.191  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:08.191  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.191  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.191  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.192  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.192  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.192  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.192  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:08.192  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.192  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.192  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.192  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.192  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:08.193  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:08.193  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.193  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.194  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:39:08.194  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:39:08.194  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:39:08.194  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:39:08.194  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the li,st - probably already removed
09-19 07:39:08.194  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.194  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7684ab9 not in the list
09-19 07:39:08.194  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.194  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.194  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:08.194  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.194  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.194  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:08.194  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:08.195  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:39:08.195  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:39:08.195  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:08.195  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2425efe not in the list
09-19 07:39:08.196  5569  5615 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-19 07:39:08.196  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-19 07:39:08.197  5569  5615 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-19 07:39:08.197  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-19 07:39:08.197  5569  5615 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-19 07:39:08.197  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-19 07:39:08.199  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-19 07:39:08.200  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-19 07:39:08.200  5569  5615 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-19 07:39:08.200  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-19 07:39:08.201  5569  5615 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-19 07:39:08.201  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-19 07:39:08.201  5569  5615 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-19 07:39:08.201  5569  5615 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-19 07:39:08.201  5569  5615 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-19 07:39,:08.201  5569  5615 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-19 07:39:08.202  5569  5615 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-19 07:39:08.202  5569  5615 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-19 07:39:08.202  5569  5615 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-19 07:39:08.202  5569  5615 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-19 07:39:08.203  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:39:08.203  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3dd398 added. We now have 3 listener(s)
09-19 07:39:08.204  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:39:08.205   927   938 D WifiService: setWifiEnabled: true pid=5569, uid=10077
09-19 07:39:08.205   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 07:39:08.221   927   944 I ActivityManager: Start proc 5630:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-19 07:39:08.331  5630  5630 D AdapterServiceConfig: Adding HeadsetService
,09-19 07:39:08.331  5630  5630 D AdapterServiceConfig: Adding A2dpService
09-19 07:39:08.331  5630  5630 D AdapterServiceConfig: Adding HidService
09-19 07:39:08.331  5630  5630 D AdapterServiceConfig: Adding HealthService
09-19 07:39:08.332  5630  5630 D AdapterServiceConfig: Adding PanService
09-19 07:39:08.332  5630  5630 D AdapterServiceConfig: Adding GattService
09-19 07:39:08.332  5630  5630 D AdapterServiceConfig: Adding BluetoothMapService
09-19 07:39:08.332  5630  5630 D AdapterServiceConfig: Adding SapService
,09-19 07:39:08.353   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79689d8:true
,09-19 07:39:08.354  5630  5630 D BluetoothAdapterState: make() - Creating AdapterState
,09-19 07:39:08.356  5630  5630 I bt_bluedroid: init
,09-19 07:39:08.357  5630  5642 I BluetoothAdapterState: Entering OffState
,09-19 07:39:08.360  5630  5643 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-19 07:39:08.362  5630  5643 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-19 07:39:08.362  5630  5643 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-19 07:39:08.362  5630  5643 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-19 07:39:08.364  5630  5630 I bt_bluedroid: get_profile_interface socket
,09-19 07:39:08.365  5630  5646 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-19 07:39:08.365  5630  5630 I bt_bluedroid: get_profile_interface sdp
,09-19 07:39:08.367  5630  5646 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 07:39:08.371  5630  5641 I bt_bluedroid: config_hci_snoop_log
09-19 07:39:08.372   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-19 07:39:08.375  5630  5642 D BluetoothAdapterState: Current state: OFF, message: 0
,09-19 07:39:08.375  5630  5642 D BluetoothAdapterProperties: Setting state to 14
09-19 07:39:08.376  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-19 07:39:08.377  5630  5642 D BluetoothBondStateMachine: make
,09-19 07:39:08.379  5630  5647 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-19 07:39:08.381  5630  5642 I BluetoothAdapterState: Entering PendingCommandState
,09-19 07:39:08.382  5630  5630 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-19 07:39:08.384  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:08.385  5630  5630 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-19 07:39:08.385  5630  5630 D BtGatt.GattService: Received start request. Starting profile...
09-19 07:39:08.386  5630  5630 D BtGatt.GattService: start()
09-19 07:39:08.386  5630  5630 I bt_bluedroid: get_profile_interface gatt
,09-19 07:39:08.387  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:08.387  5630  5630 D BtGatt.AdvertiseManager: advertise manager created
,09-19 07:39:08.392  5630  5630 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:08.392  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:08.392  5630  5630 V BluetoothAdapterState: isBleTurningOn()=true
09-19 07:39:08.392  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:08.392  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-19 07:39:08.394  5630  5642 I bt_bluedroid: bt_bluedroid
09-19 07:39:08.394  5630  5643 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-19 07:39:08.394  5630  5643 I bt_hci  : start_up
,09-19 07:39:08.400  5630  5643 I bt_vendor: alloc value 0xf3d4d871
,09-19 07:39:08.401  5630  5643 I bt_vendor: init
09-19 07:39:08.401  5630  5643 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-19 07:39:08.401  5630  5643 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-19 07:39:08.513  5630  5643 D bt_hci  : start_up starting async portion
,09-19 07:39:08.513  5630  5650 I bt_hci  : event_finish_startup
09-19 07:39:08.513  5630  5650 I bt_hci_h4: hal_open
09-19 07:39:08.514  5630  5650 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-19 07:39:08.510  5651  5651 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 07:39:08.516  5630  5650 I bt_userial_vendor: device fd = 54 open
,09-19 07:39:08.530  5630  5650 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 07:39:08.533  5630  5650 D bt_hwcfg: Chipset BCM4358A3
,09-19 07:39:08.533  5630  5650 D bt_hwcfg: Target name = [BCM4358A3]
09-19 07:39:08.534  5630  5650 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-19 07:39:08.686  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 07:39:08.934  5630  5650 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-19 07:39:08.935  5630  5650 D bt_hwcfg: Settlement delay -- 100 ms
09-19 07:39:08.935  5630  5650 I bt_hwcfg: Setting fw settlement delay to 100 
,09-19 07:39:09.059  5630  5650 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 07:39:09.060  5630  5650 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-19 07:39:09.061  5630  5650 I bt_hwcfg: vendor lib fwcfg completed
09-19 07:39:09.061  5630  5650 I bt_vendor: firmware callback
09-19 07:39:09.061  5630  5650 I bt_hci  : firmware_config_callback
,09-19 07:39:09.070  5630  5653 I bt_btu  : btu_task pending for preload complete event
09-19 07:39:09.070  5630  5653 I bt_btu_task: Bluetooth chip preload is complete
09-19 07:39:09.070  5630  5653 I bt_btu  : btu_task received preload complete event
,09-19 07:39:09.077  5630  5653 I         : BTE_InitTraceLevels -- TRC_HCI
,09-19 07:39:09.077  5630  5653 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_AVDT
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_A2D
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_BNEP
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_BTM
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_GAP
09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_PAN
,09-19 07:39:09.078  5630  5653 I         : BTE_InitTraceLevels -- TRC_SDP
09-19 07:39:09.079  5630  5653 I         : BTE_InitTraceLevels -- TRC_GATT
09-19 07:39:09.079  5630  5653 I         : BTE_InitTraceLevels -- TRC_SMP
09-19 07:39:09.079  5630  5653 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-19 07:39:09.079  5630  5653 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-19 07:39:09.162  5630  5653 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ccb549
09-19 07:39:09.163  5630  5653 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ccb549 
,09-19 07:39:09.180  5630  5646 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-19 07:39:09.182  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-19 07:39:09.182  5630  5646 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-19 07:39:09.184  5630  5646 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 07:39:09.188  5630  5646 D BluetoothAdapterProperties: Scan Mode:20
,09-19 07:39:09.188  5630  5646 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 07:39:09.188  5630  5646 D bt_hci  : do_postload posting postload work item
09-19 07:39:09.188  5630  5650 I bt_hci  : event_postload
09-19 07:39:09.189  5630  5650 I bt_vendor: sco_config_cb
09-19 07:39:09.189  5630  5650 I bt_hci  : sco_config_callback postload finished.
,09-19 07:39:09.197  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:09.199  5630  5646 D bt_bte_conf: Device ID record 1 : primary
09-19 07:39:09.199  5630  5646 D bt_bte_conf:   vendorId            = 000f
09-19 07:39:09.199  5630  5646 D bt_bte_conf:   vendorIdSource      = 0001
09-19 07:39:09.200  5630  5646 D bt_bte_conf:   product             = 1200
,09-19 07:39:09.200  5630  5646 D bt_bte_conf:   version             = 1436
09-19 07:39:09.200  5630  5646 D bt_bte_conf:   clientExecutableURL = 
09-19 07:39:09.200  5630  5646 D bt_bte_conf:   serviceDescription  = 
09-19 07:39:09.200  5630  5646 D bt_bte_conf:   documentationURL    = 
09-19 07:39:09.200  5630  5646 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-19 07:39:09.200  5630  5650 I bt_vendor: low_power_mode_cb
09-19 07:39:09.200  5630  5643 D bt_stack_manager: event_start_up_stack finished
09-19 07:39:09.201  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-19 07:39:09.201  5630  5642 D BluetoothAdapterProperties: Setting state to 15
09-19 07:39:09.201  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-19 07:39:09.202  5630  5642 I BluetoothAdapterState: Entering BleOnState
09-19 07:39:09.205  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:09.207  5630  5642 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-19 07:39:09.207  5630  5642 D BluetoothAdapterProperties: Setting state to 11
09-19 07:39:09.207  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-19 07:39:09.211  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:09.212  5630  5630 D HeadsetService: Received start request. Starting profile...
,09-19 07:39:09.215  5630  5630 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-19 07:39:09.215  5630  5630 D HeadsetStateMachine: make
,09-19 07:39:09.219  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:09.222  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:09.230   927   940 I ActivityManager: Start proc 5660:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-19 07:39:09.236  5630  5630 D HeadsetStateMachine: max_hf_connections = 1
,09-19 07:39:09.236  5630  5630 I bt_bluedroid: get_profile_interface handsfree
09-19 07:39:09.237  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-19 07:39:09.238  5630  5646 E bt_btif : btif_hf_upstreams_evt: Invalid index 250
,09-19 07:39:09.244  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:09.245  5630  5642 I BluetoothAdapterState: Entering PendingCommandState
09-19 07:39:09.246   927   927 D BluetoothA2dp: Proxy object connected
,09-19 07:39:09.246  5630  5630 D A2dpService: Received start request. Starting profile...
09-19 07:39:09.247  5630  5630 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-19 07:39:09.247  5630  5630 I bt_bluedroid: get_profile_interface avrcp
,09-19 07:39:09.255  5630  5630 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-19 07:39:09.255  5630  5630 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-19 07:39:09.255  5630  5630 D A2dpStateMachine: make
09-19 07:39:09.256  5630  5630 I bt_bluedroid: get_profile_interface a2dp
,09-19 07:39:09.257  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-19 07:39:09.260  5630  5673 D A2dpStateMachine: Enter Disconnected: -2
,09-19 07:39:09.263  5630  5630 I BluetoothHidServiceJni: classInitNative: succeeds
,09-19 07:39:09.263  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:09.265  3092  3092 D BluetoothInputDevice: Proxy object connected
,09-19 07:39:09.266  3092  3092 D HidProfile: Bluetooth service connected
,09-19 07:39:09.266  5630  5630 D HidService: Received start request. Starting profile...
09-19 07:39:09.267  5630  5630 I bt_bluedroid: get_profile_interface hidhost
09-19 07:39:09.267  5630  5630 D HidService: setHidService(): set to: null
09-19 07:39:09.267  5630  5646 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cac56d
09-19 07:39:09.267  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-19 07:39:09.268  5630  5630 I BluetoothHealthServiceJni: classInitNative: succeeds
09-19 07:39:09.269  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:09.269  5630  5630 D HealthService: Received start request. Starting profile...
,09-19 07:39:09.271  5630  5630 I bt_bluedroid: get_profile_interface health
,09-19 07:39:09.271  5630  5630 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:09.271  5630  5630 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:09.271  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.271  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.272  5630  5630 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-19 07:39:09.273  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:09.271  5660  5660 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-19 07:39:09.277  3092  3092 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 07:39:09.277  5630  5630 D PanService: Received start request. Starting profile...
09-19 07:39:09.277  3092  3092 D PanProfile: Bluetooth service connected
,09-19 07:39:09.277  5630  5630 D BluetoothPanServiceJni: initializeNative(L110): pan
09-19 07:39:09.278  5630  5630 I bt_bluedroid: get_profile_interface pan
,09-19 07:39:09.279  5630  5646 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-19 07:39:09.280  5630  5659 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-19 07:39:09.280  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:09.282  3092  3092 D BluetoothMap: Proxy object connected
09-19 07:39:09.283  5630  5630 D BluetoothMapService: Received start request. Starting profile...
09-19 07:39:09.282  3092  3092 D MapProfile: Bluetooth service connected
09-19 07:39:09.283  5630  5630 D BluetoothMapService: start()
09-19 07:39:09.283  3092  3092 D BluetoothMap: getConnectedDevices()
09-19 07:39:09.284  3092  3092 D BluetoothMap: Bluetooth is Not enabled
,09-19 07:39:09.286  5630  5630 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-19 07:39:09.289  5630  5630 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-19 07:39:09.290  5630  5630 D BluetoothMapAppObserver: createReceiver()
,09-19 07:39:09.292  5630  5630 D BluetoothMapAppObserver: initObservers()
,09-19 07:39:09.292  5630  5630 D BluetoothMapAppObserver: getEnabledAccountItems()
09-19 07:39:09.299  5630  5630 V SapService: SapBinder()
09-19 07:39:09.299  5630  5630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:09.300  5630  5630 D SapService: Received start request. Starting profile...
09-19 07:39:09.300  5630  5630 V SapService: start()
09-19 07:39:09.301   927   938 I ActivityManager: Killing 4759:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isTurningOn()=true
,09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.318  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:09.319  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.320  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.320  5630  5630 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:09.320  5630  5630 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:09.320  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.320  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.322  5630  5630 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:09.322  5630  5630 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:09.322  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:09.322  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:09.323  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-19 07:39:09.323  5630  5642 D BluetoothAdapterProperties: ScanMode =  20
09-19 07:39:09.323  5630  5642 D BluetoothAdapterProperties: State =  11
09-19 07:39:09.323  5630  5642 D BluetoothAdapterProperties: Setting state to 12
,09-19 07:39:09.323  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-19 07:39:09.323  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 07:39:09.324  5630  5642 I BluetoothAdapterState: Entering OnState
09-19 07:39:09.325  5630  5646 D BluetoothAdapterProperties: Scan Mode:21
09-19 07:39:09.325  3792  4055 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:09.325  5630  5646 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-19 07:39:09.327   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 07:39:09.328  3092  3904 D BluetoothMap: onBluetoothStateChange: up=true
09-19 07:39:09.328   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:09.328  5569  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-19 07:39:09.328  3092  3104 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 07:39:09.328  3092  3114 D BluetoothPan: onBluetoothStateChange on: true
09-19 07:39:09.329  3092  3904 D BluetoothPbap: onBluetoothStateChange: up=true
,09-19 07:39:09.330  5569  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-19 07:39:09.335  5569  5569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:09.340  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 07:39:09.341   927  3131 I ActivityManager: Start proc 5681:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-19 07:39:09.341   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 07:39:09.342   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:09.342  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:09.343  5630  5630 D BluetoothMapService: onReceive
,09-19 07:39:09.343  5630  5630 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 07:39:09.343   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-19 07:39:09.343  5630  5630 D BluetoothMapService: STATE_ON
,09-19 07:39:09.346  3092  3347 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:09.348  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 07:39:09.349  5630  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:09.350  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:09.350  5630  5686 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-19 07:39:09.350  5630  5686 D BluetoothSdpJni: SDP Create record success - handle: 0
09-19 07:39:09.352  3092  3092 D BluetoothA2dp: Proxy object connected
09-19 07:39:09.352  3092  3347 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-19 07:39:09.353  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:09.358  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:09.365  5630  5630 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-19 07:39:09.366  5630  5630 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-19 07:39:09.367  5630  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:09.371  5630  5630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:09.373  5630  5630 D ObexServerSockets: Succeed to create listening sockets 
09-19 07:39:09.373  5630  5630 D ObexServerSockets0: startAccept()
,09-19 07:39:09.373  5630  5630 D ObexServerSockets0: prepareForNewConnect()
09-19 07:39:09.375  5630  5630 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-19 07:39:09.375  5630  5630 D BluetoothSdpJni: SDP Create record success - handle: 1
09-19 07:39:09.375  5630  5695 D ObexServerSockets0: Accepting socket connection...
,09-19 07:39:09.376  5630  5694 D ObexServerSockets0: Accepting socket connection...
,09-19 07:39:09.384  5681  5681 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-19 07:39:09.425   927  3575 D ConnectivityService: Returning blocked NetworkInfo to uid=10058
,09-19 07:39:09.427  3792  3820 D BluetoothHeadset: Proxy object connected
,09-19 07:39:09.428   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:09.428   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:09.441   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:09.457  3092  3104 D BluetoothHeadset: Proxy object connected
,09-19 07:39:09.458  3092  3092 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:09.538  5681  5681 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at java.io.File.exists(File.java:361)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-19 07:39:09.538  5681  5681 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.538  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.539  5681  5681 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.539  5681  5681 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:170)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.539  5681  5681 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.k.d(PG:583)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:170)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.539  5681  5681 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.File.exists(File.java:361)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.539  5681  5681 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.File.exists(File.java:361)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.539  5681  5681 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-19 07:39:09.539  5681  5681 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-19 07:39:09.544  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-19 07:39:09.550   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79c7ebd:true
09-19 07:39:09.552  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 07:39:09.558  5660  5660 D LocalBluetoothProfileManager: Adding local A2DP profile
09-19 07:39:09.560  3092  3092 D BluetoothPbap: Proxy object connected
09-19 07:39:09.560  3092  3092 D PbapServerProfile: Bluetooth service connected
09-19 07:39:09.563  5660  5660 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-19 07:39:09.569  5630  5710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:09.585  5630  5714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:09.587  5630  5714 I BtOppRfcommListener: Accept thread started.
09-19 07:39:09.589  5660  5660 D LocalBluetoothProfileManager: Adding local MAP profile
09-19 07:39:09.590  5660  5660 D BluetoothMap: Create BluetoothMap proxy object
09-19 07:39:09.596  5660  5660 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-19 07:39:09.601  5660  5660 D DockEventReceiver: finishStartingService: stopping service
09-19 07:39:09.602  5660  5660 D BluetoothA2dp: Proxy object connected
09-19 07:39:09.604  5660  5660 D BluetoothInputDevice: Proxy object connected
09-19 07:39:09.605  5660  5660 D HidProfile: Bluetooth service connected
09-19 07:39:09.607  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 07:39:09.607  5660  5660 D PanProfile: Bluetooth service connected
09-19 07:39:09.607  5660  5660 D BluetoothMap: Proxy object connected
09-19 07:39:09.608  5660  5660 D MapProfile: Bluetooth service connected
09-19 07:39:09.608  5660  5660 D BluetoothMap: getConnectedDevices()
09-19 07:39:09.610  5660  5660 D BluetoothPbap: Proxy object connected
09-19 07:39:09.610  5660  5660 D PbapServerProfile: Bluetooth service connected
09-19 07:39:09.611   927  3865 I ActivityManager: Killing 5200:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-19 07:39:09.669  5660  5670 D BluetoothHeadset: Proxy object connected
,09-19 07:39:09.670  5660  5660 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:09.811  5681  5698 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-19 07:39:09.826   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c96fe61:true
,09-19 07:39:13.211  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 07:39:13.212  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35b97f1 added. We now have 4 listener(s)
09-19 07:39:13.212  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:39:13.216   389   389 I MSM-irqbalance: Discovered a new IRQ: 146
,09-19 07:39:13.222   389   389 I MSM-irqbalance: Discovered a new IRQ: 271
,09-19 07:39:13.225  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:13.226  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35b97f1 removed from the list
09-19 07:39:13.226  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:13.226  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:13.226  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:13.227  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:39:13.227  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb14fd6 added. We now have 4 listener(s)
,09-19 07:39:13.227  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:39:13.229  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:13.230  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb14fd6 removed from the list
09-19 07:39:13.230  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:39:13.230  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:13.230  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:13.231  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 07:39:13.231  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6566257 added. We now have 4 listener(s)
09-19 07:39:13.231  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:39:13.233   927  3865 D WifiService: setWifiEnabled: false pid=5569, uid=10077
09-19 07:39:13.234   927  3865 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 07:39:13.235   927  2940 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-19 07:39:13.235   927  2940 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-19 07:39:13.236   927  2940 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-19 07:39:13.236   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:39:13.239  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:39:13.239  5630  5642 D BluetoothAdapterState: Current state: ON, message: 23
09-19 07:39:13.240  5630  5642 D BluetoothAdapterProperties: Setting state to 13
09-19 07:39:13.240  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-19 07:39:13.240  5630  5642 D BluetoothAdapterProperties: onBluetoothDisable()
09-19 07:39:13.241  5630  5642 I BluetoothAdapterState: Entering PendingCommandState
09-19 07:39:13.245  5630  5630 D BluetoothMapService: onReceive
,09-19 07:39:13.245  5630  5630 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 07:39:13.245  5630  5630 D BluetoothMapService: STATE_TURNING_OFF
09-19 07:39:13.245  5630  5646 D BluetoothAdapterProperties: Scan Mode:20
09-19 07:39:13.245  5630  5630 D BluetoothMapService: MAP Service closeService in
09-19 07:39:13.245  5630  5630 D BluetoothMapMasInstance0: MAP Service shutdown
09-19 07:39:13.245  5630  5630 D ObexServerSockets0: shutdown(block = true)
,09-19 07:39:13.247  5630  5630 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 07:39:13.247  5630  5655 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-19 07:39:13.247  5630  5695 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-19 07:39:13.247  5630  5630 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 07:39:13.248  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.248  5630  5694 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:13.248  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:13.249  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.249  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 07:39:13.249  5630  5630 I BtOppRfcommListener: stopping Accept Thread
09-19 07:39:13.249  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-19 07:39:13.249  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-19 07:39:13.249  5630  5714 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-19 07:39:13.249   927  2940 E native  : do suspend true
09-19 07:39:13.251  5630  5714 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-19 07:39:13.252  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-19 07:39:13.252  5630  5630 D HeadsetService: Received stop request...Stopping profile...
09-19 07:39:13.253  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.256  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.256   927   927 D BluetoothHeadset: Proxy object disconnected
,09-19 07:39:13.256  5660  5671 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:13.257  3092  3104 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:13.258   927   927 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:13.258   927   927 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:13.258  3792  4501 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:13.260  5630  5630 D A2dpService: Received stop request...Stopping profile...
,09-19 07:39:13.260  5630  5673 D A2dpStateMachine: Exit Disconnected: -1
09-19 07:39:13.262  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:13.263  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:13.263  5660  5660 D DockEventReceiver: finishStartingService: stopping service
09-19 07:39:13.264   927   927 D BluetoothA2dp: Proxy object disconnected
09-19 07:39:13.265  5630  5630 D HidService: Received stop request...Stopping profile...
09-19 07:39:13.265  5630  5630 D HidService: Stopping Bluetooth HidService
09-19 07:39:13.266  5630  5630 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:13.266  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.266  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.266  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:13.267  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.267  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:13.267  5660  5660 D HeadsetProfile: Bluetooth service disconnected
,09-19 07:39:13.268  5660  5660 D BluetoothA2dp: Proxy object disconnected
09-19 07:39:13.268  5660  5660 D BluetoothInputDevice: Proxy object disconnected
09-19 07:39:13.268  5660  5660 D HidProfile: Bluetooth service disconnected
09-19 07:39:13.270  5630  5630 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-19 07:39:13.270  5630  5630 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-19 07:39:13.270  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-19 07:39:13.270  5630  5653 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:13.270  5630  5653 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:13.270  5630  5653 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:13.271  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:13.271  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:13.272  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.273  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 07:39:13.270  5630  5646 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-19 07:39:13.275  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.275  5630  5630 D HealthService: Received stop request...Stopping profile...
09-19 07:39:13.276  3092  3092 D HeadsetProfile: Bluetooth service disconnected
09-19 07:39:13.276  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 07:39:13.276  3092  3092 D BluetoothA2dp: Proxy object disconnected
09-19 07:39:13.276  3092  3092 D BluetoothInputDevice: Proxy object disconnected
,09-19 07:39:13.276  3092  3092 D HidProfile: Bluetooth service disconnected
09-19 07:39:13.278  5630  5630 D PanService: Received stop request...Stopping profile...
09-19 07:39:13.278  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.279  5660  5660 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 07:39:13.279  5660  5660 D PanProfile: Bluetooth service disconnected
09-19 07:39:13.279  3092  3092 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 07:39:13.279  3092  3092 D PanProfile: Bluetooth service disconnected
09-19 07:39:13.279   927  5280 D DhcpClient: Clearing IP address
09-19 07:39:13.279   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-19 07:39:13.280  5630  5630 D BluetoothMapService: Received stop request...Stopping profile...
,09-19 07:39:13.280  5630  5630 D BluetoothMapService: stop()
09-19 07:39:13.280  5630  5630 D BluetoothMapAppObserver: deinitObservers()
09-19 07:39:13.280  5630  5630 D BluetoothMapAppObserver: removeReceiver()
09-19 07:39:13.281  3092  3092 D BluetoothMap: Proxy object disconnected
09-19 07:39:13.282  3092  3092 D MapProfile: Bluetooth service disconnected
09-19 07:39:13.282  5660  5660 D BluetoothMap: Proxy object disconnected
09-19 07:39:13.282  5660  5660 D MapProfile: Bluetooth service disconnected
09-19 07:39:13.282  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.282  5630  5630 D SapService: Received stop request...Stopping profile...
09-19 07:39:13.282  5630  5630 V SapService: stop()
,09-19 07:39:13.284  5630  5630 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:13.284  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.284  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.284  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 07:39:13.285  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-19 07:39:13.285  5630  5653 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:13.285  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.285  5630  5630 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:13.285  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.285  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.285  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:13.285  5630  5653 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:13.285  5630  5653 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 07:39:13.285  5630  5630 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-19 07:39:13.285  5630  5653 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 07:39:13.285  5630  5653 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 07:39:13.285  5630  5630 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-19 07:39:13.285  5630  5646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-19 07:39:13.285  5630  5653 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-19 07:39:13.287   509   921 D CommandListener: Setting iface cfg
09-19 07:39:13.287  5660  5660 D BluetoothPbap: Proxy object disconnected
09-19 07:39:13.287  5660  5660 D PbapServerProfile: Bluetooth service disconnected
09-19 07:39:13.287  5630  5630 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:13.287  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.287  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.287  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:13.288  5630  5630 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-19 07:39:13.288  5630  5646 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-19 07:39:13.288  5630  5630 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-19 07:39:13.288  5630  5630 V BluetoothAdapterState: isTurningOff()=true
,09-19 07:39:13.288  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.288  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.288  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:13.289  5630  5630 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-19 07:39:13.289  5630  5630 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-19 07:39:13.290  5630  5630 D BluetoothMapService: MAP Service closeService in
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 07:39:13.290  5630  5630 D BluetoothMapService: cleanup()
09-19 07:39:13.290  5630  5630 D BluetoothMapService: MAP Service closeService in
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.290  5630  5630 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:13.290  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-19 07:39:13.290  5630  5642 D BluetoothAdapterProperties: Setting state to 15
09-19 07:39:13.290  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-19 07:39:13.296  3545  5337 V NativeCrypto: Read error: ssl=0x7f9749d000: I/O error during system call, Connection timed out
09-19 07:39:13.296  3792  3824 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:13.297   927  5281 D DhcpClient: Receive thread stopped
09-19 07:39:13.297  5630  5642 I BluetoothAdapterState: Entering BleOnState
09-19 07:39:13.297   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:13.298  3092  3904 D BluetoothMap: onBluetoothStateChange: up=false
,09-19 07:39:13.298  3545  5337 V NativeCrypto: SSL shutdown failed: ssl=0x7f9749d000: I/O error during system call, Broken pipe
09-19 07:39:13.298  3092  3092 D BluetoothPbap: Proxy object disconnected
09-19 07:39:13.298  3092  3092 D PbapServerProfile: Bluetooth service disconnected
,09-19 07:39:13.299  5660  5670 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:13.299   927  3575 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-19 07:39:13.299  5660  5671 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 07:39:13.300   927  5278 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-19 07:39:13.300   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:13.300  5660  5670 D BluetoothMap: onBluetoothStateChange: up=false
09-19 07:39:13.301  3092  3114 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-19 07:39:13.301  5660  5671 D BluetoothPbap: onBluetoothStateChange: up=false
09-19 07:39:13.302   927  5278 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-19 07:39:13.302  5660  5670 D BluetoothPan: onBluetoothStateChange on: false
09-19 07:39:13.302   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-19 07:39:13.302   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-19 07:39:13.303  3092  3104 D BluetoothPan: onBluetoothStateChange on: false
09-19 07:39:13.303  3092  3904 D BluetoothPbap: onBluetoothStateChange: up=false
09-19 07:39:13.303   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-19 07:39:13.304   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-19 07:39:13.310   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-19 07:39:13.310  3092  3904 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:13.310   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-19 07:39:13.311  3092  3104 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 07:39:13.312   535   535 E Parcel  : Reading a NULL string not supported here.
09-19 07:39:13.314   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:13.314  5660  5671 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-19 07:39:13.315  5630  5642 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-19 07:39:13.315  5630  5642 D BluetoothAdapterProperties: Setting state to 16
09-19 07:39:13.315  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-19 07:39:13.316  5630  5642 D BluetoothAdapterProperties: onBleDisable
09-19 07:39:13.316  5630  5642 I BluetoothAdapterState: Entering PendingCommandState
09-19 07:39:13.316  5630  5643 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-19 07:39:13.318   927   927 D RttService: SCAN_AVAILABLE : 1
09-19 07:39:13.318   927  3044 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-19 07:39:13.318  5630  5653 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-19 07:39:13.318  5630  5653 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:13.319   927  2951 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-19 07:39:13.320  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.320  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:13.321  3743  3893 W QCNEJ   : |CORE| network lost: 100
,09-19 07:39:13.321  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 07:39:13.321  3743  3893 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-19 07:39:13.322  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.322  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:13.323  5630  5646 D BluetoothAdapterProperties: Scan Mode:20
09-19 07:39:13.326  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.326  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:13.327  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 07:39:13.327  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.327  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:13.331  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.331  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:13.333  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.333  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:13.335   927  2940 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-19 07:39:13.336  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.336  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:13.338  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.339  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.342  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-19 07:39:13.359   927  2940 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-19 07:39:13.359   927  2940 E native  : do suspend true
,09-19 07:39:13.364   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:39:13.383   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:39:13.384   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-19 07:39:13.384   927  2951 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-19 07:39:13.385   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-19 07:39:13.386   927   944 D Tethering: MasterInitialState.processMessage what=3
09-19 07:39:13.389   927  2940 D DhcpClient: doQuit
,09-19 07:39:13.390   927  2940 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-19 07:39:13.391   927  5280 D DhcpClient: onQuitting
09-19 07:39:13.391  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.391  3412  3412 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-19 07:39:13.392  3914  3914 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-19 07:39:13.394  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.394  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:13.395  4876  4900 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-19 07:39:13.395  4876  4900 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-19 07:39:13.395  4876  4900 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-19 07:39:13.395  4876  4900 E SarControlService: no key has been found,reset the power
09-19 07:39:13.396  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.396  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:13.396  4876  4914 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-19 07:39:13.397  4876  4914 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-19 07:39:13.397  4876  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-19 07:39:13.398  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-19 07:39:13.398  4902  4902 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-19 07:39:13.398  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.398  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:13.399  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.399  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:13.400  4876  4914 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-19 07:39:13.400  4876  4914 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-19 07:39:13.400  4876  4914 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-19 07:39:13.401  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-19 07:39:13.401  4902  4902 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-19 07:39:13.402  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:13.402  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:13.403  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:13.403  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:13.405  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:13.406  3671  3671 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-19 07:39:13.407  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.411  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6a35e3f HexData = [00000000ea03000000000000ffffffff]
,09-19 07:39:13.411  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-19 07:39:13.411  4902  4916 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-19 07:39:13.411  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-19 07:39:13.412  4876  4886 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-19 07:39:13.412  4902  4916 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6a35e3f HexData = [00000000eb03000000000000ffffffff]
09-19 07:39:13.412  4902  4916 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-19 07:39:13.412  4902  4916 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-19 07:39:13.413  3412  3412 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-19 07:39:13.413  4902  4902 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-19 07:39:13.414  4876  4887 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-19 07:39:13.416  3412  3412 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-19 07:39:13.419  3671  5304 I iu.UploadsManager: num queued entries: 0
,09-19 07:39:13.420  3671  5304 I iu.UploadsManager: num updated entries: 0
09-19 07:39:13.421  3671  5304 I iu.SyncManager: NEXT; no task
,09-19 07:39:13.422  3671  3671 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-19 07:39:13.423  3671  3671 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-19 07:39:13.425  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-19 07:39:13.430  5308  5308 D SprintDMHelper: simOperator: 
09-19 07:39:13.430  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-19 07:39:13.439   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-19 07:39:13.440   927  2951 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-19 07:39:13.440   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-19 07:39:13.441  3412  3412 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-19 07:39:13.445  4850  5739 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-19 07:39:13.447  3412  3412 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-19 07:39:13.458   927  3775 I ActivityManager: Start proc 5740:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-19 07:39:13.459   927  2940 D wifi    : In wifi stop Hal
09-19 07:39:13.459   927  2940 D wifi    : halHandle = 0x7f8c026040, mVM = 0x7fa200d140, mCls = 0x100a12
09-19 07:39:13.460   927  3411 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-19 07:39:13.460   927  3411 D WifiHAL : Got a signal to exit!!!
09-19 07:39:13.460   927  3411 I WifiHAL : Exit wifi_event_loop
09-19 07:39:13.461   927  2940 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-19 07:39:13.461   927  2940 E WifiHAL : Event processing terminated
09-19 07:39:13.461   927  2940 D wifi    : In wifi cleaned up handler
09-19 07:39:13.461   927  2940 I WifiHAL : Internal cleanup completed
,09-19 07:39:13.462  4850  4850 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 07:39:13.463  4047  4225 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-19 07:39:13.464  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.465  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.467  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:13.481   927  3411 D wifi    : set interface wlan0 flags (DOWN)
,09-19 07:39:13.481   927  2940 D WifiNative-HAL: HAL event thread stopped successfully
,09-19 07:39:13.494  5740  5740 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-19 07:39:13.500   927   937 I ActivityManager: Killing 4507:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-19 07:39:13.527  5630  5646 I bt_hci  : shut_down
,09-19 07:39:13.530  5630  5650 D bt_hwcfg: hw_epilog_process
,09-19 07:39:13.530  5630  5650 I bt_vendor: low_power_mode_cb
,09-19 07:39:13.533  5630  5650 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-19 07:39:13.533  5630  5650 I bt_vendor: epilog_cb
09-19 07:39:13.533  5630  5650 I bt_hci  : epilog_finished_callback
,09-19 07:39:13.535  5630  5646 I bt_hci_h4: hal_close
,09-19 07:39:13.536  5630  5646 I bt_userial_vendor: device fd = 54 close
,09-19 07:39:13.545   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-19 07:39:13.645  5630  5643 D bt_stack_manager: event_shut_down_stack finished.
,09-19 07:39:13.646  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-19 07:39:13.649  5630  5642 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-19 07:39:13.649  5630  5630 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-19 07:39:13.650  5630  5630 D BtGatt.GattService: Received stop request...Stopping profile...
09-19 07:39:13.650  5630  5630 D BtGatt.GattService: stop()
,09-19 07:39:13.650  5630  5630 D BtGatt.AdvertiseManager: advertise clients cleared
,09-19 07:39:13.653  5630  5630 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:13.653  5630  5630 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:13.653  5630  5630 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:13.654  5630  5630 V BluetoothAdapterState: isBleTurningOff()=true
09-19 07:39:13.654  5630  5642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-19 07:39:13.654  5630  5642 D BluetoothAdapterProperties: Setting state to 10
09-19 07:39:13.654  5630  5642 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-19 07:39:13.655  5630  5642 I BluetoothAdapterState: Entering OffState
,09-19 07:39:13.657   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-19 07:39:13.666  5630  5630 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-19 07:39:13.666  5630  5630 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-19 07:39:13.666  5630  5630 I BluetoothServiceJni: cleanupNative: return from cleanup
09-19 07:39:13.668  5630  5643 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-19 07:39:13.671  5630  5630 I art     : System.exit called, status: 0
09-19 07:39:13.671  5630  5630 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-19 07:39:13.684   927   944 D Tethering: InitialState.processMessage what=4
,09-19 07:39:13.686   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-19 07:39:13.700   927  3131 I ActivityManager: Process com.android.bluetooth (pid 5630) has died
,09-19 07:39:18.252   927  3865 D WifiService: setWifiEnabled: true pid=5569, uid=10077
,09-19 07:39:18.253   927  3865 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 07:39:18.262   509   921 D SoftapController: Softap fwReload - Ok
,09-19 07:39:18.267   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:18.267   509   921 D CommandListener: Trying to bring down wlan0
,09-19 07:39:18.269   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-19 07:39:18.274   927  2940 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-19 07:39:18.870   927  2940 D wifi    : set interface wlan0 flags (UP)
,09-19 07:39:18.873   927  2940 I WifiHAL : Initializing wifi
,09-19 07:39:18.873   927  2940 I WifiHAL : Creating socket
,09-19 07:39:18.877   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-19 07:39:18.885   927  2940 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-19 07:39:18.886   927  2940 D wifi    : Did set static halHandle = 0x7f8c026040
,09-19 07:39:18.886   927  2940 D wifi    : halHandle = 0x7f8c026040, mVM = 0x7fa200d140, mCls = 0x10174a
09-19 07:39:18.886   927  2940 D wifi    : array field set
09-19 07:39:18.887   927  2940 I WifiNative-HAL: interface[0] = wlan0
09-19 07:39:18.889   927  5763 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547809812544
09-19 07:39:18.889   927  5763 D wifi    : waitForHalEvents called, vm = 0x7fa200d140, obj = 0x10174a, env = 0x7f861e5a80
,09-19 07:39:18.953  5764  5764 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-19 07:39:18.973  5764  5764 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 07:39:18.989   927  2940 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-19 07:39:18.992  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:18.993  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:18.994  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:19.011  5764  5764 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 07:39:19.011  5764  5764 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-19 07:39:19.026  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:19.026  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:19.027  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:19.027   927  2940 D WifiConfigStore: Loading config and enabling all networks 
09-19 07:39:19.027  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:19.028  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:19.028  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:19.028  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:19.028  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:19.030  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:19.030  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:19.030  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:19.030  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:19.040   927  2940 D WifiConfigStore: loaded 0 passpoint configs
,09-19 07:39:19.041   927  2940 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-19 07:39:19.041   927  2940 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-19 07:39:19.042   927  2940 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-19 07:39:19.043   927  2940 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-19 07:39:19.044   927  2940 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-19 07:39:19.044   927  2940 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-19 07:39:19.044   927  2940 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-19 07:39:19.048   927  2940 D WifiNative-HAL: Setting external_sim to 1
,09-19 07:39:19.048  4850  4850 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 07:39:19.048   927  2940 D wifi    : setting dfs flag to true, 0x7f8be97900
,09-19 07:39:19.049   927  2940 D WifiStateMachine: Setting OUI to DA-A1-19
09-19 07:39:19.049   927  2940 D wifi    : setting scan oui 0x7f8be97900
09-19 07:39:19.049   927  2940 D WifiHAL : Sending mac address OUI
,09-19 07:39:19.064   927  2940 E native  : do suspend true
,09-19 07:39:19.071   927  2940 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-19 07:39:19.071   927   927 D RttService: SCAN_AVAILABLE : 3
09-19 07:39:19.071   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-19 07:39:19.071   927  3044 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-19 07:39:19.072   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:19.076   927  2922 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '139 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 139 Failed to set address (No such device)'
09-19 07:39:19.077   927  2922 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-19 07:39:19.082   927  2922 D WifiNative-HAL: p2pGetDeviceAddress
,09-19 07:39:19.087   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=188007 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
09-19 07:39:19.087   927  2922 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-19 07:39:20.279   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:39:21.280   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:39:22.219  5764  5764 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-19 07:39:22.254   927  2940 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-19 07:39:22.260   927  2940 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,09-19 07:39:22.260   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:39:22.273   927  2940 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-19 07:39:22.280   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:39:22.312   927  2940 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-19 07:39:22.655  5764  5764 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-19 07:39:22.684  5764  5764 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-19 07:39:22.684  5764  5764 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-19 07:39:22.694   927  2940 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-19 07:39:22.694   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:39:22.694   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-19 07:39:22.708   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:39:22.718   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:22.723   927  2940 D WifiStateMachine: Start Dhcp Watchdog 2
,09-19 07:39:22.726   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-19 07:39:22.731   927  5781 D DhcpClient: Receive thread started
,09-19 07:39:22.812   927  2940 E native  : do suspend false
,09-19 07:39:22.825   927  5780 D DhcpClient: Broadcasting DHCPDISCOVER
,09-19 07:39:22.838   927  5781 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172650, domain null
,09-19 07:39:22.839   927  5780 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172650 seconds
,09-19 07:39:22.841   927  5780 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-19 07:39:22.867   927  5781 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-19 07:39:22.868   927  5780 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-19 07:39:22.870   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:22.877   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-19 07:39:22.879   927  2940 E native  : do suspend true
09-19 07:39:22.880   927  5780 D DhcpClient: Scheduling renewal in 86399s
,09-19 07:39:22.899   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-19 07:39:22.899   927  2940 D WifiConfigStore: No blacklist allowed without epno enabled
,09-19 07:39:22.900   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-19 07:39:22.901   927  2951 D ConnectivityService: Adding iface wlan0 to network 101
09-19 07:39:22.905   927  2940 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-19 07:39:22.933   927  2951 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-19 07:39:22.933   927  2951 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-19 07:39:22.936   927  2951 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-19 07:39:22.939   927  2951 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-19 07:39:22.940   927  2951 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-19 07:39:22.947   927  2951 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-19 07:39:22.952   927  2951 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-19 07:39:22.952   927  2951 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-19 07:39:22.952   927  2951 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-19 07:39:22.952   927  2951 D ConnectivityService:    accepting network in place of null
09-19 07:39:22.952   927  2940 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-19 07:39:22.952   927  2940 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-19 07:39:22.953   927  2951 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-19 07:39:22.977   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:39:22.995   927  5779 D NetlinkSocketObserver: NeighborEvent{elapsedMs=191915, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-19 07:39:22.999   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:39:23.002   927  2951 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-19 07:39:23.002   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-19 07:39:23.003  3743  3893 W QCNEJ   : |CORE| network available: 101
09-19 07:39:23.004   927  2951 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-19 07:39:23.005   927   944 D Tethering: MasterInitialState.processMessage what=3
09-19 07:39:23.005  3743  3893 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-19 07:39:23.008  3743  3893 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-19 07:39:23.008  3743  3893 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-19 07:39:23.009  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:23.009  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:23.010  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.010  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:23.014  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:23.014  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:23.014  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.015  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 07:39:23.017  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:39:23.017  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-19 07:39:23.018  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.018  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:39:23.019   927  3804 D ConnectivityService: Returning blocked NetworkInfo to uid=10062
,09-19 07:39:23.024  3914  3914 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-19 07:39:23.036  3671  3671 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-19 07:39:23.043  3671  5304 I iu.UploadsManager: num queued entries: 0
,09-19 07:39:23.043  3671  5304 I iu.UploadsManager: num updated entries: 0
09-19 07:39:23.044  3671  5304 I iu.SyncManager: NEXT; no task
,09-19 07:39:23.045  3671  3671 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-19 07:39:23.047  3671  3671 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-19 07:39:23.048  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-19 07:39:23.052  5308  5308 D SprintDMHelper: simOperator: 
09-19 07:39:23.052  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-19 07:39:23.073   927  5778 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-19 07:39:23.131   927  5778 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 19 Sep 2016 11:39:23 GMT], X-Android-Received-Millis=[1474285163131], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474285163105]}
,09-19 07:39:23.132   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-19 07:39:23.132   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-19 07:39:23.132   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-19 07:39:23.133   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-19 07:39:23.262   927  3804 D WifiService: setWifiEnabled: false pid=5569, uid=10077
,09-19 07:39:23.263   927  3804 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-19 07:39:23.267   927  2940 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-19 07:39:23.267   927  2940 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-19 07:39:23.268   927  2940 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-19 07:39:23.268   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:39:23.281   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:39:23.285   927  2940 E native  : do suspend true
,09-19 07:39:23.294   927  5780 D DhcpClient: Clearing IP address
,09-19 07:39:23.295   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-19 07:39:23.297   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:23.309   927  5781 D DhcpClient: Receive thread stopped
,09-19 07:39:23.311  3545  5796 V NativeCrypto: Read error: ssl=0x7f86302380: I/O error during system call, Connection timed out
09-19 07:39:23.313  3545  5796 V NativeCrypto: SSL shutdown failed: ssl=0x7f86302380: I/O error during system call, Broken pipe
,09-19 07:39:23.320   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-19 07:39:23.320   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-19 07:39:23.321   535   535 E Parcel  : Reading a NULL string not supported here.
09-19 07:39:23.326   927   927 D RttService: SCAN_AVAILABLE : 1
09-19 07:39:23.326   927  3044 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-19 07:39:23.334   927  2951 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-19 07:39:23.334   927  2940 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-19 07:39:23.337  3743  3893 W QCNEJ   : |CORE| network lost: 101
09-19 07:39:23.338   927  2940 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-19 07:39:23.338   927  2940 E native  : do suspend true
09-19 07:39:23.338  3743  3893 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-19 07:39:23.360   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:39:23.380   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:39:23.380   509   921 D CommandListener: Clearing all IP addresses on wlan0
09-19 07:39:23.381   927  2951 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-19 07:39:23.381   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-19 07:39:23.382   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-19 07:39:23.384   927  2940 D DhcpClient: doQuit
09-19 07:39:23.384   927  2940 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-19 07:39:23.384   927  5780 D DhcpClient: onQuitting
09-19 07:39:23.385  5764  5764 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-19 07:39:23.385  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:23.385  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:23.386  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.386  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:23.387  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:23.387  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:39:23.387  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.387  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:23.388  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:23.388  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:23.388  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.389  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:23.390  3914  3914 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-19 07:39:23.390  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:23.390  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:23.390  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:23.390  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:23.391  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:23.392  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:23.394  5764  5764 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-19 07:39:23.397  5764  5764 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-19 07:39:23.415  3671  3671 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-19 07:39:23.421  3671  5304 I iu.UploadsManager: num queued entries: 0
,09-19 07:39:23.421  3671  5304 I iu.UploadsManager: num updated entries: 0
09-19 07:39:23.421  3671  5304 I iu.SyncManager: NEXT; no task
,09-19 07:39:23.423  3671  3671 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-19 07:39:23.423  5764  5764 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-19 07:39:23.424  3671  3671 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-19 07:39:23.426  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-19 07:39:23.430  5308  5308 D SprintDMHelper: simOperator: 
09-19 07:39:23.430  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-19 07:39:23.438   509   921 E Netd    : netlink response contains error (No such file or directory)
09-19 07:39:23.439   927  2951 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-19 07:39:23.443  5764  5764 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-19 07:39:23.547  4850  4850 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 07:39:23.547   927  2940 D wifi    : In wifi stop Hal
09-19 07:39:23.548   927  2940 D wifi    : halHandle = 0x7f8c026040, mVM = 0x7fa200d140, mCls = 0x10174a
09-19 07:39:23.548   927  5763 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-19 07:39:23.548   927  5763 D WifiHAL : Got a signal to exit!!!
09-19 07:39:23.549   927  5763 I WifiHAL : Exit wifi_event_loop
09-19 07:39:23.551   927  2940 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-19 07:39:23.551   927  2940 E WifiHAL : Event processing terminated
09-19 07:39:23.551   927  2940 D wifi    : In wifi cleaned up handler
09-19 07:39:23.551   927  2940 I WifiHAL : Internal cleanup completed
,09-19 07:39:23.552  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:23.554  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:23.555  4047  4225 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 07:39:23.556  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:23.580   927  5763 D wifi    : set interface wlan0 flags (DOWN)
,09-19 07:39:23.580   927  2940 D WifiNative-HAL: HAL event thread stopped successfully
,09-19 07:39:23.644   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-19 07:39:23.788   927   944 D Tethering: InitialState.processMessage what=4
,09-19 07:39:23.795   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-19 07:39:24.003   927  2951 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-19 07:39:24.282   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:39:25.282   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:39:26.303   927   927 E WifiNative-wlan0: set PNO failure
,09-19 07:39:28.306   927   944 I ActivityManager: Start proc 5816:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-19 07:39:28.393  5816  5816 D AdapterServiceConfig: Adding HeadsetService
,09-19 07:39:28.393  5816  5816 D AdapterServiceConfig: Adding A2dpService
09-19 07:39:28.393  5816  5816 D AdapterServiceConfig: Adding HidService
09-19 07:39:28.393  5816  5816 D AdapterServiceConfig: Adding HealthService
09-19 07:39:28.393  5816  5816 D AdapterServiceConfig: Adding PanService
,09-19 07:39:28.394  5816  5816 D AdapterServiceConfig: Adding GattService
09-19 07:39:28.394  5816  5816 D AdapterServiceConfig: Adding BluetoothMapService
09-19 07:39:28.394  5816  5816 D AdapterServiceConfig: Adding SapService
,09-19 07:39:28.405   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68abaff:true
,09-19 07:39:28.406  5816  5816 D BluetoothAdapterState: make() - Creating AdapterState
,09-19 07:39:28.409  5816  5816 I bt_bluedroid: init
09-19 07:39:28.409  5816  5828 I BluetoothAdapterState: Entering OffState
,09-19 07:39:28.411  5816  5829 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-19 07:39:28.411  5816  5829 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-19 07:39:28.411  5816  5829 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-19 07:39:28.411  5816  5829 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-19 07:39:28.412  5816  5816 I bt_bluedroid: get_profile_interface socket
,09-19 07:39:28.414  5816  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-19 07:39:28.414  5816  5816 I bt_bluedroid: get_profile_interface sdp
,09-19 07:39:28.416  5816  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 07:39:28.420  5816  5827 I bt_bluedroid: config_hci_snoop_log
,09-19 07:39:28.421   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-19 07:39:28.425  5816  5828 D BluetoothAdapterState: Current state: OFF, message: 0
,09-19 07:39:28.425  5816  5828 D BluetoothAdapterProperties: Setting state to 14
09-19 07:39:28.425  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-19 07:39:28.427  5816  5828 D BluetoothBondStateMachine: make
,09-19 07:39:28.428  5816  5833 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-19 07:39:28.431  5816  5828 I BluetoothAdapterState: Entering PendingCommandState
,09-19 07:39:28.433  5816  5816 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-19 07:39:28.435  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:28.436  5816  5816 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-19 07:39:28.437  5816  5816 D BtGatt.GattService: Received start request. Starting profile...
,09-19 07:39:28.437  5816  5816 D BtGatt.GattService: start()
09-19 07:39:28.437  5816  5816 I bt_bluedroid: get_profile_interface gatt
,09-19 07:39:28.439  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:28.439  5816  5816 D BtGatt.AdvertiseManager: advertise manager created
,09-19 07:39:28.445  5816  5816 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:28.445  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:28.445  5816  5816 V BluetoothAdapterState: isBleTurningOn()=true
09-19 07:39:28.445  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:28.445  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-19 07:39:28.447  5816  5828 I bt_bluedroid: bt_bluedroid
09-19 07:39:28.447  5816  5829 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-19 07:39:28.447  5816  5829 I bt_hci  : start_up
,09-19 07:39:28.454  5816  5829 I bt_vendor: alloc value 0xf3d4d871
,09-19 07:39:28.454  5816  5829 I bt_vendor: init
09-19 07:39:28.454  5816  5829 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-19 07:39:28.454  5816  5829 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-19 07:39:28.565  5816  5829 D bt_hci  : start_up starting async portion
,09-19 07:39:28.565  5816  5836 I bt_hci  : event_finish_startup
09-19 07:39:28.565  5816  5836 I bt_hci_h4: hal_open
09-19 07:39:28.565  5816  5836 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-19 07:39:28.568  5816  5836 I bt_userial_vendor: device fd = 54 open
,09-19 07:39:28.563  5837  5837 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 07:39:28.582  5816  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 07:39:28.585  5816  5836 D bt_hwcfg: Chipset BCM4358A3
,09-19 07:39:28.585  5816  5836 D bt_hwcfg: Target name = [BCM4358A3]
09-19 07:39:28.585  5816  5836 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-19 07:39:28.963  5816  5836 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-19 07:39:28.964  5816  5836 D bt_hwcfg: Settlement delay -- 100 ms
,09-19 07:39:28.964  5816  5836 I bt_hwcfg: Setting fw settlement delay to 100 
,09-19 07:39:29.097  5816  5836 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 07:39:29.097  5816  5836 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-19 07:39:29.098  5816  5836 I bt_hwcfg: vendor lib fwcfg completed
09-19 07:39:29.098  5816  5836 I bt_vendor: firmware callback
09-19 07:39:29.099  5816  5836 I bt_hci  : firmware_config_callback
,09-19 07:39:29.107  5816  5839 I bt_btu  : btu_task pending for preload complete event
,09-19 07:39:29.107  5816  5839 I bt_btu_task: Bluetooth chip preload is complete
09-19 07:39:29.107  5816  5839 I bt_btu  : btu_task received preload complete event
,09-19 07:39:29.115  5816  5839 I         : BTE_InitTraceLevels -- TRC_HCI
,09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_AVDT
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_AVRC
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_A2D
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_BTM
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_GAP
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_PAN
09-19 07:39:29.117  5816  5839 I         : BTE_InitTraceLevels -- TRC_SDP
09-19 07:39:29.118  5816  5839 I         : BTE_InitTraceLevels -- TRC_GATT
09-19 07:39:29.118  5816  5839 I         : BTE_InitTraceLevels -- TRC_SMP
,09-19 07:39:29.118  5816  5839 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-19 07:39:29.118  5816  5839 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-19 07:39:29.202  5816  5839 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ccb549
,09-19 07:39:29.202  5816  5839 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ccb549 
,09-19 07:39:29.227  5816  5832 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-19 07:39:29.228  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-19 07:39:29.228  5816  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-19 07:39:29.231  5816  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 07:39:29.234  5816  5832 D BluetoothAdapterProperties: Scan Mode:20
,09-19 07:39:29.235  5816  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-19 07:39:29.235  5816  5832 D bt_hci  : do_postload posting postload work item
,09-19 07:39:29.235  5816  5836 I bt_hci  : event_postload
09-19 07:39:29.235  5816  5836 I bt_vendor: sco_config_cb
,09-19 07:39:29.235  5816  5836 I bt_hci  : sco_config_callback postload finished.
,09-19 07:39:29.241  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:29.243  5816  5832 D bt_bte_conf: Device ID record 1 : primary
09-19 07:39:29.243  5816  5832 D bt_bte_conf:   vendorId            = 000f
09-19 07:39:29.243  5816  5832 D bt_bte_conf:   vendorIdSource      = 0001
09-19 07:39:29.243  5816  5832 D bt_bte_conf:   product             = 1200
09-19 07:39:29.243  5816  5832 D bt_bte_conf:   version             = 1436
,09-19 07:39:29.243  5816  5832 D bt_bte_conf:   clientExecutableURL = 
09-19 07:39:29.243  5816  5832 D bt_bte_conf:   serviceDescription  = 
09-19 07:39:29.243  5816  5832 D bt_bte_conf:   documentationURL    = 
09-19 07:39:29.243  5816  5832 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-19 07:39:29.244  5816  5829 D bt_stack_manager: event_start_up_stack finished
09-19 07:39:29.244  5816  5836 I bt_vendor: low_power_mode_cb
09-19 07:39:29.244  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-19 07:39:29.244  5816  5828 D BluetoothAdapterProperties: Setting state to 15
,09-19 07:39:29.244  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-19 07:39:29.245  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.248  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.247  5816  5828 I BluetoothAdapterState: Entering BleOnState
,09-19 07:39:29.249  5816  5828 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-19 07:39:29.249  5816  5828 D BluetoothAdapterProperties: Setting state to 11
09-19 07:39:29.249  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-19 07:39:29.253  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:29.254  5816  5816 D HeadsetService: Received start request. Starting profile...
,09-19 07:39:29.257  5816  5816 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-19 07:39:29.257  5816  5816 D HeadsetStateMachine: make
,09-19 07:39:29.261  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.262  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.265  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.265  5816  5828 I BluetoothAdapterState: Entering PendingCommandState
,09-19 07:39:29.269  5816  5816 D HeadsetStateMachine: max_hf_connections = 1
,09-19 07:39:29.269  5816  5816 I bt_bluedroid: get_profile_interface handsfree
09-19 07:39:29.269  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-19 07:39:29.269  5816  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-19 07:39:29.272  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:29.272  5816  5816 D A2dpService: Received start request. Starting profile...
,09-19 07:39:29.273  5816  5816 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-19 07:39:29.273  5816  5816 I bt_bluedroid: get_profile_interface avrcp
,09-19 07:39:29.278  5816  5816 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-19 07:39:29.279  5816  5816 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-19 07:39:29.279  5816  5816 D A2dpStateMachine: make
09-19 07:39:29.280  5816  5816 I bt_bluedroid: get_profile_interface a2dp
,09-19 07:39:29.280  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-19 07:39:29.281  5816  5848 D A2dpStateMachine: Enter Disconnected: -2
09-19 07:39:29.282  5816  5816 I BluetoothHidServiceJni: classInitNative: succeeds
09-19 07:39:29.283  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:29.283  5816  5816 D HidService: Received start request. Starting profile...
,09-19 07:39:29.283  5816  5816 I bt_bluedroid: get_profile_interface hidhost
09-19 07:39:29.283  5816  5816 D HidService: setHidService(): set to: null
09-19 07:39:29.283  5816  5832 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cac56d
09-19 07:39:29.283  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-19 07:39:29.284  5816  5816 I BluetoothHealthServiceJni: classInitNative: succeeds
09-19 07:39:29.285  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:29.285  5816  5816 D HealthService: Received start request. Starting profile...
,09-19 07:39:29.286  5816  5816 I bt_bluedroid: get_profile_interface health
,09-19 07:39:29.287  5816  5816 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-19 07:39:29.288  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:29.288  5816  5816 D PanService: Received start request. Starting profile...
09-19 07:39:29.288  5816  5816 D BluetoothPanServiceJni: initializeNative(L110): pan
09-19 07:39:29.288  5816  5816 I bt_bluedroid: get_profile_interface pan
09-19 07:39:29.289  5816  5832 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-19 07:39:29.291  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:29.291  5816  5816 D BluetoothMapService: Received start request. Starting profile...
,09-19 07:39:29.291  5816  5816 D BluetoothMapService: start()
,09-19 07:39:29.294  5816  5816 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-19 07:39:29.295  5816  5816 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-19 07:39:29.295  5816  5816 D BluetoothMapAppObserver: createReceiver()
,09-19 07:39:29.296  5816  5816 D BluetoothMapAppObserver: initObservers()
,09-19 07:39:29.296  5816  5816 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-19 07:39:29.303  5816  5816 V SapService: SapBinder()
,09-19 07:39:29.303  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:29.304  5816  5816 D SapService: Received start request. Starting profile...
09-19 07:39:29.304  5816  5816 V SapService: start()
,09-19 07:39:29.306  5816  5816 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:29.306  5816  5816 V BluetoothAdapterState: isTurningOn()=true
,09-19 07:39:29.306  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.306  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.306  5816  5816 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.307  5816  5845 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.307  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.307  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.308  5816  5816 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:29.308  5816  5816 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:29.308  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:29.308  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:29.308  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-19 07:39:29.308  5816  5828 D BluetoothAdapterProperties: ScanMode =  20
09-19 07:39:29.308  5816  5828 D BluetoothAdapterProperties: State =  11
09-19 07:39:29.311  5816  5832 D BluetoothAdapterProperties: Scan Mode:21
09-19 07:39:29.311  5816  5828 D BluetoothAdapterProperties: Setting state to 12
,09-19 07:39:29.311  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-19 07:39:29.311  5816  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 07:39:29.311  3792  3820 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:29.312   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:29.312  3092  3114 D BluetoothMap: onBluetoothStateChange: up=true
09-19 07:39:29.312  5816  5828 I BluetoothAdapterState: Entering OnState
09-19 07:39:29.314  5660  5670 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:29.314  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:29.315  5660  5671 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 07:39:29.315  3092  3092 D BluetoothMap: Proxy object connected
,09-19 07:39:29.315  3092  3092 D MapProfile: Bluetooth service connected
09-19 07:39:29.315  3092  3092 D BluetoothMap: getConnectedDevices()
,09-19 07:39:29.317   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:29.317  5660  5670 D BluetoothMap: onBluetoothStateChange: up=true
,09-19 07:39:29.318  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:29.319  3092  3904 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-19 07:39:29.321  5816  5816 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-19 07:39:29.321  5660  5670 D BluetoothPbap: onBluetoothStateChange: up=true
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:29.321  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:39:29.321  5816  5816 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-19 07:39:29.322  5660  5660 D BluetoothA2dp: Proxy object connected
09-19 07:39:29.323  5816  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:29.323  5660  5671 D BluetoothPan: onBluetoothStateChange on: true
09-19 07:39:29.323  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:29.324  5816  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:29.325  3092  3114 D BluetoothPan: onBluetoothStateChange on: true
09-19 07:39:29.325  5816  5816 D ObexServerSockets: Succeed to create listening sockets 
09-19 07:39:29.325  5816  5816 D ObexServerSockets0: startAccept()
09-19 07:39:29.325  5816  5816 D ObexServerSockets0: prepareForNewConnect()
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:29.327  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:29.327  3092  3104 D BluetoothPbap: onBluetoothStateChange: up=true
,09-19 07:39:29.327  5816  5816 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-19 07:39:29.327  5816  5816 D BluetoothSdpJni: SDP Create record success - handle: 0
09-19 07:39:29.328  5816  5854 D ObexServerSockets0: Accepting socket connection...
09-19 07:39:29.328  5816  5855 D ObexServerSockets0: Accepting socket connection...
09-19 07:39:29.329  3092  3092 D BluetoothInputDevice: Proxy object connected
09-19 07:39:29.329  3092  3092 D HidProfile: Bluetooth service connected
09-19 07:39:29.330  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:29.331   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 07:39:29.332   927   927 D BluetoothA2dp: Proxy object connected
09-19 07:39:29.332  3092  3904 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:29.332  3092  3092 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 07:39:29.332  3092  3092 D PanProfile: Bluetooth service connected
09-19 07:39:29.333  3092  3104 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-19 07:39:29.333  5660  5660 D BluetoothMap: Proxy object connected
09-19 07:39:29.334  5660  5660 D MapProfile: Bluetooth service connected
,09-19 07:39:29.334  5660  5660 D BluetoothMap: getConnectedDevices()
09-19 07:39:29.335  3092  3092 D BluetoothA2dp: Proxy object connected
09-19 07:39:29.335   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:29.335  5660  5671 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 07:39:29.335  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 07:39:29.335  5660  5660 D PanProfile: Bluetooth service connected
,09-19 07:39:29.338  5660  5660 D BluetoothInputDevice: Proxy object connected
09-19 07:39:29.338  5660  5660 D HidProfile: Bluetooth service connected
09-19 07:39:29.338   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-19 07:39:29.338  5816  5816 D BluetoothMapService: onReceive
09-19 07:39:29.338  5816  5816 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 07:39:29.338  5816  5816 D BluetoothMapService: STATE_ON
09-19 07:39:29.339  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:29.342  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.342  5816  5857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:29.343  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:29.344  5816  5857 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-19 07:39:29.344  5816  5857 D BluetoothSdpJni: SDP Create record success - handle: 1
09-19 07:39:29.345  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 07:39:29.351  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 07:39:29.351  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-19 07:39:29.359  5660  5660 D BluetoothPbap: Proxy object connected
,09-19 07:39:29.359  5660  5660 D PbapServerProfile: Bluetooth service connected
,09-19 07:39:29.364  5816  5816 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-19 07:39:29.364  5816  5816 D ObexServerSockets0: prepareForNewConnect()
09-19 07:39:29.365  5816  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:29.367  3092  3092 D BluetoothPbap: Proxy object connected
09-19 07:39:29.367  3092  3092 D PbapServerProfile: Bluetooth service connected
,09-19 07:39:29.379  5816  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:29.380  5816  5865 I BtOppRfcommListener: Accept thread started.
,09-19 07:39:29.413   927   927 D BluetoothHeadset: Proxy object connected
,09-19 07:39:29.414  5660  5670 D BluetoothHeadset: Proxy object connected
09-19 07:39:29.414  3092  3904 D BluetoothHeadset: Proxy object connected
09-19 07:39:29.414  3092  3092 D HeadsetProfile: Bluetooth service connected
09-19 07:39:29.414   927   927 D BluetoothHeadset: Proxy object connected
09-19 07:39:29.414   927   927 D BluetoothHeadset: Proxy object connected
09-19 07:39:29.414  5660  5853 D BluetoothHeadset: Proxy object connected
,09-19 07:39:29.415  3792  3824 D BluetoothHeadset: Proxy object connected
09-19 07:39:29.415  5660  5660 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:29.417  5660  5660 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:29.417   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:29.433  3092  3104 D BluetoothHeadset: Proxy object connected
,09-19 07:39:29.433  3092  3092 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:29.435   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:30.959   927  2951 D ConnectivityService: handlePromptUnvalidated 101
,09-19 07:39:33.285  5816  5828 D BluetoothAdapterState: Current state: ON, message: 23
,09-19 07:39:33.286  5816  5828 D BluetoothAdapterProperties: Setting state to 13
,09-19 07:39:33.286  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-19 07:39:33.287  5816  5828 D BluetoothAdapterProperties: onBluetoothDisable()
,09-19 07:39:33.289  5816  5828 I BluetoothAdapterState: Entering PendingCommandState
,09-19 07:39:33.295  5816  5816 D BluetoothMapService: onReceive
09-19 07:39:33.296  5816  5816 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 07:39:33.296  5816  5816 D BluetoothMapService: STATE_TURNING_OFF
09-19 07:39:33.296  5816  5816 D BluetoothMapService: MAP Service closeService in
09-19 07:39:33.297  5816  5816 D BluetoothMapMasInstance0: MAP Service shutdown
09-19 07:39:33.297  5816  5816 D ObexServerSockets0: shutdown(block = true)
09-19 07:39:33.298  5816  5816 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-19 07:39:33.298  5816  5841 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-19 07:39:33.298  5816  5816 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-19 07:39:33.298  5816  5854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-19 07:39:33.298  5816  5855 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-19 07:39:33.299  5816  5832 D BluetoothAdapterProperties: Scan Mode:20
09-19 07:39:33.300  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-19 07:39:33.304  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:33.304  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:33.305  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:33.305  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:33.306  5816  5816 I BtOppRfcommListener: stopping Accept Thread
09-19 07:39:33.307  5816  5865 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-19 07:39:33.308  5816  5865 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-19 07:39:33.308  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 07:39:33.311  5816  5816 D HeadsetService: Received stop request...Stopping profile...
,09-19 07:39:33.313  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:33.313  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:39:33.314  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:33.314  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:33.317  5660  5660 D DockEventReceiver: finishStartingService: stopping service
09-19 07:39:33.317   927   927 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:33.318  5660  5671 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:33.318  5816  5816 D A2dpService: Received stop request...Stopping profile...
09-19 07:39:33.318  3092  3904 D BluetoothHeadset: Proxy object disconnected
,09-19 07:39:33.318  5816  5848 D A2dpStateMachine: Exit Disconnected: -1
09-19 07:39:33.318  3092  3092 D HeadsetProfile: Bluetooth service disconnected
09-19 07:39:33.318   927   927 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:33.318  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-19 07:39:33.318   927   927 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:33.319  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:33.319  3792  4501 D BluetoothHeadset: Proxy object disconnected
09-19 07:39:33.320   927   927 D BluetoothA2dp: Proxy object disconnected
09-19 07:39:33.320  5569  5569 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-19 07:39:33.320  3092  3092 D BluetoothA2dp: Proxy object disconnected
09-19 07:39:33.320  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:33.320  5660  5660 D HeadsetProfile: Bluetooth service disconnected
09-19 07:39:33.320  5660  5660 D BluetoothA2dp: Proxy object disconnected
09-19 07:39:33.321  5816  5816 D HidService: Received stop request...Stopping profile...
09-19 07:39:33.321  5816  5816 D HidService: Stopping Bluetooth HidService
09-19 07:39:33.322  3092  3092 D BluetoothInputDevice: Proxy object disconnected
09-19 07:39:33.322  5660  5660 D BluetoothInputDevice: Proxy object disconnected
09-19 07:39:33.322  3092  3092 D HidProfile: Bluetooth service disconnected
09-19 07:39:33.322  5660  5660 D HidProfile: Bluetooth service disconnected
09-19 07:39:33.323  5816  5816 D HealthService: Received stop request...Stopping profile...
,09-19 07:39:33.323  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:33.324  5816  5816 D PanService: Received stop request...Stopping profile...
09-19 07:39:33.324  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:33.325  3092  3092 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 07:39:33.325  3092  3092 D PanProfile: Bluetooth service disconnected
09-19 07:39:33.326  5660  5660 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-19 07:39:33.326  5660  5660 D PanProfile: Bluetooth service disconnected
09-19 07:39:33.326  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isTurningOff()=true
,09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.327  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.328  5816  5816 D BluetoothMapService: Received stop request...Stopping profile...
09-19 07:39:33.328  5816  5816 D BluetoothMapService: stop()
09-19 07:39:33.329  5816  5816 D BluetoothMapAppObserver: deinitObservers()
09-19 07:39:33.329  5816  5816 D BluetoothMapAppObserver: removeReceiver()
09-19 07:39:33.331  5660  5660 D BluetoothMap: Proxy object disconnected
,09-19 07:39:33.331  5660  5660 D MapProfile: Bluetooth service disconnected
09-19 07:39:33.331  3092  3092 D BluetoothMap: Proxy object disconnected
09-19 07:39:33.331  3092  3092 D MapProfile: Bluetooth service disconnected
09-19 07:39:33.332  5816  5816 D SapService: Received stop request...Stopping profile...
09-19 07:39:33.332  5816  5816 V SapService: stop()
09-19 07:39:33.334  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 07:39:33.337  5816  5816 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-19 07:39:33.337  5816  5816 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-19 07:39:33.337  5816  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:33.337  5816  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:33.337  5816  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:33.337  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-19 07:39:33.337  5816  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-19 07:39:33.338  5816  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:33.338  5816  5816 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:33.338  5816  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:33.338  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.338  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.338  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.338  5816  5816 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-19 07:39:33.338  5816  5816 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-19 07:39:33.339  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-19 07:39:33.339  5816  5839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 07:39:33.339  5816  5839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 07:39:33.339  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-19 07:39:33.339  5816  5839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-19 07:39:33.339  5816  5816 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:33.339  5816  5839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-19 07:39:33.339  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.339  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.339  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.339  5816  5816 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-19 07:39:33.339  5816  5832 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-19 07:39:33.340  5816  5816 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-19 07:39:33.340  5816  5816 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:33.340  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.340  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.340  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.340  5816  5816 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-19 07:39:33.340  5816  5816 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-19 07:39:33.341  5816  5816 D BluetoothMapService: MAP Service closeService in
09-19 07:39:33.341  5816  5816 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:33.341  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.341  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.341  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.342  5816  5816 D BluetoothMapService: cleanup()
09-19 07:39:33.342  5816  5816 D BluetoothMapService: MAP Service closeService in
09-19 07:39:33.344  3092  3092 D BluetoothPbap: Proxy object disconnected
09-19 07:39:33.344  3092  3092 D PbapServerProfile: Bluetooth service disconnected
09-19 07:39:33.344  5816  5816 V BluetoothAdapterState: isTurningOff()=true
09-19 07:39:33.344  5816  5816 V BluetoothAdapterState: isTurningOn()=false
,09-19 07:39:33.344  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.344  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:33.344  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-19 07:39:33.344  5816  5828 D BluetoothAdapterProperties: Setting state to 15
09-19 07:39:33.345  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-19 07:39:33.346  5816  5828 I BluetoothAdapterState: Entering BleOnState
09-19 07:39:33.346  5660  5660 D BluetoothPbap: Proxy object disconnected
09-19 07:39:33.346  5660  5660 D PbapServerProfile: Bluetooth service disconnected
,09-19 07:39:33.347  3792  4055 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:33.348   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:33.348  3092  3104 D BluetoothMap: onBluetoothStateChange: up=false
,09-19 07:39:33.350  5660  5671 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:33.351  5660  5853 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 07:39:33.351   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:33.351  5660  5866 D BluetoothMap: onBluetoothStateChange: up=false
09-19 07:39:33.352  3092  3904 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-19 07:39:33.352  5660  5670 D BluetoothPbap: onBluetoothStateChange: up=false
09-19 07:39:33.353  5660  5671 D BluetoothPan: onBluetoothStateChange on: false
09-19 07:39:33.354  3092  3114 D BluetoothPan: onBluetoothStateChange on: false
09-19 07:39:33.354  3092  3104 D BluetoothPbap: onBluetoothStateChange: up=false
,09-19 07:39:33.355   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 07:39:33.355  3092  3904 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:33.355  3092  3114 D BluetoothA2dp: onBluetoothStateChange: up=false
09-19 07:39:33.355   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-19 07:39:33.356  5660  5853 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-19 07:39:33.356  5816  5828 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-19 07:39:33.356  5816  5828 D BluetoothAdapterProperties: Setting state to 16
09-19 07:39:33.356  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-19 07:39:33.357  5816  5828 D BluetoothAdapterProperties: onBleDisable
09-19 07:39:33.357  5816  5828 I BluetoothAdapterState: Entering PendingCommandState
09-19 07:39:33.357  5816  5829 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-19 07:39:33.359  5816  5832 D BluetoothAdapterProperties: Scan Mode:20
09-19 07:39:33.359  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:33.360  5816  5839 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-19 07:39:33.360  5816  5839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-19 07:39:33.360  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:33.361  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-19 07:39:33.362  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:33.365  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 07:39:33.367  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:33.368  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:33.369  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:33.372  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-19 07:39:33.564  5816  5832 I bt_hci  : shut_down
,09-19 07:39:33.569  5816  5836 D bt_hwcfg: hw_epilog_process
,09-19 07:39:33.570  5816  5836 I bt_vendor: low_power_mode_cb
,09-19 07:39:33.572  5816  5836 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-19 07:39:33.572  5816  5836 I bt_vendor: epilog_cb
09-19 07:39:33.572  5816  5836 I bt_hci  : epilog_finished_callback
,09-19 07:39:33.574  5816  5832 I bt_hci_h4: hal_close
,09-19 07:39:33.574  5816  5832 I bt_userial_vendor: device fd = 54 close
,09-19 07:39:33.678  5816  5829 D bt_stack_manager: event_shut_down_stack finished.
,09-19 07:39:33.679  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-19 07:39:33.681  5816  5828 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-19 07:39:33.682  5816  5816 D BtGatt.DebugUtils: handleDebugAction() action=null
09-19 07:39:33.683  5816  5816 D BtGatt.GattService: Received stop request...Stopping profile...
09-19 07:39:33.683  5816  5816 D BtGatt.GattService: stop()
09-19 07:39:33.683  5816  5816 D BtGatt.AdvertiseManager: advertise clients cleared
,09-19 07:39:33.686  5816  5816 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:33.686  5816  5816 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:33.686  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:33.686  5816  5816 V BluetoothAdapterState: isBleTurningOff()=true
09-19 07:39:33.686  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-19 07:39:33.687  5816  5828 D BluetoothAdapterProperties: Setting state to 10
09-19 07:39:33.687  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-19 07:39:33.687  5816  5828 I BluetoothAdapterState: Entering OffState
,09-19 07:39:33.688   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-19 07:39:33.697  5816  5816 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-19 07:39:33.697  5816  5816 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-19 07:39:33.697  5816  5816 I BluetoothServiceJni: cleanupNative: return from cleanup
09-19 07:39:33.699  5816  5829 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-19 07:39:33.704  5816  5816 I art     : System.exit called, status: 0
,09-19 07:39:33.704  5816  5816 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-19 07:39:33.727   927   938 I ActivityManager: Process com.android.bluetooth (pid 5816) has died
,09-19 07:39:38.281  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:38.282  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:38.287  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:39:38.287  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6566257 removed from the list
,09-19 07:39:38.288  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:38.288  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:38.288  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:38.290  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 07:39:38.290  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d80c22d added. We now have 4 listener(s)
,09-19 07:39:38.291  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 07:39:38.294  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:38.295  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d80c22d removed from the list
,09-19 07:39:38.295  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:38.296  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:39:38.296  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:38.298  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 07:39:38.298  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ca9362 added. We now have 4 listener(s)
09-19 07:39:38.298  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 07:39:43.310  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:43.345   927   944 I ActivityManager: Start proc 5874:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-19 07:39:43.434  5874  5874 D AdapterServiceConfig: Adding HeadsetService
,09-19 07:39:43.434  5874  5874 D AdapterServiceConfig: Adding A2dpService
09-19 07:39:43.435  5874  5874 D AdapterServiceConfig: Adding HidService
09-19 07:39:43.435  5874  5874 D AdapterServiceConfig: Adding HealthService
09-19 07:39:43.435  5874  5874 D AdapterServiceConfig: Adding PanService
09-19 07:39:43.435  5874  5874 D AdapterServiceConfig: Adding GattService
09-19 07:39:43.435  5874  5874 D AdapterServiceConfig: Adding BluetoothMapService
09-19 07:39:43.435  5874  5874 D AdapterServiceConfig: Adding SapService
,09-19 07:39:43.446   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bd60278:true
,09-19 07:39:43.446  5874  5874 D BluetoothAdapterState: make() - Creating AdapterState
,09-19 07:39:43.449  5874  5874 I bt_bluedroid: init
,09-19 07:39:43.449  5874  5886 I BluetoothAdapterState: Entering OffState
,09-19 07:39:43.451  5874  5887 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-19 07:39:43.451  5874  5887 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-19 07:39:43.451  5874  5887 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-19 07:39:43.451  5874  5887 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-19 07:39:43.452  5874  5874 I bt_bluedroid: get_profile_interface socket
,09-19 07:39:43.454  5874  5890 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-19 07:39:43.454  5874  5874 I bt_bluedroid: get_profile_interface sdp
,09-19 07:39:43.455  5874  5890 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-19 07:39:43.460  5874  5885 I bt_bluedroid: config_hci_snoop_log
09-19 07:39:43.461   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-19 07:39:43.465  5874  5886 D BluetoothAdapterState: Current state: OFF, message: 0
09-19 07:39:43.465  5874  5886 D BluetoothAdapterProperties: Setting state to 14
09-19 07:39:43.465  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-19 07:39:43.467  5874  5886 D BluetoothBondStateMachine: make
,09-19 07:39:43.469  5874  5891 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-19 07:39:43.471  5874  5886 I BluetoothAdapterState: Entering PendingCommandState
,09-19 07:39:43.473  5874  5874 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-19 07:39:43.475  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:43.475  5874  5874 D BtGatt.DebugUtils: handleDebugAction() action=null
09-19 07:39:43.476  5874  5874 D BtGatt.GattService: Received start request. Starting profile...
09-19 07:39:43.476  5874  5874 D BtGatt.GattService: start()
09-19 07:39:43.476  5874  5874 I bt_bluedroid: get_profile_interface gatt
09-19 07:39:43.477  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:43.477  5874  5874 D BtGatt.AdvertiseManager: advertise manager created
,09-19 07:39:43.483  5874  5874 V BluetoothAdapterState: isTurningOff()=false
,09-19 07:39:43.483  5874  5874 V BluetoothAdapterState: isTurningOn()=false
09-19 07:39:43.483  5874  5874 V BluetoothAdapterState: isBleTurningOn()=true
09-19 07:39:43.483  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:43.484  5874  5886 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-19 07:39:43.485  5874  5886 I bt_bluedroid: bt_bluedroid
09-19 07:39:43.485  5874  5887 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-19 07:39:43.486  5874  5887 I bt_hci  : start_up
,09-19 07:39:43.491  5874  5887 I bt_vendor: alloc value 0xf3d4d871
,09-19 07:39:43.491  5874  5887 I bt_vendor: init
09-19 07:39:43.491  5874  5887 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-19 07:39:43.491  5874  5887 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-19 07:39:43.603  5874  5887 D bt_hci  : start_up starting async portion
,09-19 07:39:43.604  5874  5894 I bt_hci  : event_finish_startup
09-19 07:39:43.604  5874  5894 I bt_hci_h4: hal_open
09-19 07:39:43.604  5874  5894 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-19 07:39:43.603  5895  5895 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 07:39:43.608  5874  5894 I bt_userial_vendor: device fd = 54 open
,09-19 07:39:43.625  5874  5894 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 07:39:43.629  5874  5894 D bt_hwcfg: Chipset BCM4358A3
,09-19 07:39:43.629  5874  5894 D bt_hwcfg: Target name = [BCM4358A3]
09-19 07:39:43.629  5874  5894 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-19 07:39:44.023  5874  5894 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-19 07:39:44.023  5874  5894 D bt_hwcfg: Settlement delay -- 100 ms
09-19 07:39:44.024  5874  5894 I bt_hwcfg: Setting fw settlement delay to 100 
,09-19 07:39:44.156  5874  5894 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-19 07:39:44.156  5874  5894 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-19 07:39:44.159  5874  5894 I bt_hwcfg: vendor lib fwcfg completed
09-19 07:39:44.159  5874  5894 I bt_vendor: firmware callback
09-19 07:39:44.159  5874  5894 I bt_hci  : firmware_config_callback
,09-19 07:39:44.168  5874  5897 I bt_btu  : btu_task pending for preload complete event
,09-19 07:39:44.168  5874  5897 I bt_btu_task: Bluetooth chip preload is complete
,09-19 07:39:44.168  5874  5897 I bt_btu  : btu_task received preload complete event
,09-19 07:39:44.176  5874  5897 I         : BTE_InitTraceLevels -- TRC_HCI
,09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_AVDT
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_AVRC
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_A2D
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_BTM
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_GAP
09-19 07:39:44.177  5874  5897 I         : BTE_InitTraceLevels -- TRC_PAN
09-19 07:39:44.178  5874  5897 I         : BTE_InitTraceLevels -- TRC_SDP
09-19 07:39:44.178  5874  5897 I         : BTE_InitTraceLevels -- TRC_GATT
09-19 07:39:44.178  5874  5897 I         : BTE_InitTraceLevels -- TRC_SMP
,09-19 07:39:44.178  5874  5897 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-19 07:39:44.178  5874  5897 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-19 07:39:44.261  5874  5897 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ccb549
09-19 07:39:44.262  5874  5897 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ccb549 
,09-19 07:39:44.272  5874  5890 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-19 07:39:44.273  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-19 07:39:44.274  5874  5890 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-19 07:39:44.276  5874  5890 D BluetoothAdapterProperties: Name is: Nexus 6P
09-19 07:39:44.279  5874  5890 D BluetoothAdapterProperties: Scan Mode:20
09-19 07:39:44.280  5874  5890 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 07:39:44.280  5874  5890 D bt_hci  : do_postload posting postload work item
09-19 07:39:44.280  5874  5894 I bt_hci  : event_postload
,09-19 07:39:44.280  5874  5894 I bt_vendor: sco_config_cb
09-19 07:39:44.280  5874  5894 I bt_hci  : sco_config_callback postload finished.
09-19 07:39:44.283  5874  5890 D bt_bte_conf: Device ID record 1 : primary
09-19 07:39:44.283  5874  5890 D bt_bte_conf:   vendorId            = 000f
09-19 07:39:44.284  5874  5890 D bt_bte_conf:   vendorIdSource      = 0001
09-19 07:39:44.284  5874  5890 D bt_bte_conf:   product             = 1200
,09-19 07:39:44.284  5874  5890 D bt_bte_conf:   version             = 1436
09-19 07:39:44.284  5874  5890 D bt_bte_conf:   clientExecutableURL = 
09-19 07:39:44.284  5874  5890 D bt_bte_conf:   serviceDescription  = 
09-19 07:39:44.284  5874  5890 D bt_bte_conf:   documentationURL    = 
09-19 07:39:44.284  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:44.284  5874  5890 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-19 07:39:44.284  5874  5887 D bt_stack_manager: event_start_up_stack finished
09-19 07:39:44.288  5874  5886 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-19 07:39:44.288  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:44.288  5874  5886 D BluetoothAdapterProperties: Setting state to 15
09-19 07:39:44.289  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-19 07:39:44.290  5874  5894 I bt_vendor: low_power_mode_cb
,09-19 07:39:44.291  5874  5886 I BluetoothAdapterState: Entering BleOnState
09-19 07:39:44.295  5874  5886 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-19 07:39:44.295  5874  5886 D BluetoothAdapterProperties: Setting state to 11
09-19 07:39:44.295  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-19 07:39:44.303  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:44.304  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:44.306  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:44.307  5874  5874 D HeadsetService: Received start request. Starting profile...
09-19 07:39:44.310  5874  5874 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-19 07:39:44.310  5874  5874 D HeadsetStateMachine: make
,09-19 07:39:44.318  5874  5886 I BluetoothAdapterState: Entering PendingCommandState
,09-19 07:39:44.321  5874  5874 D HeadsetStateMachine: max_hf_connections = 1
,09-19 07:39:44.321  5874  5874 I bt_bluedroid: get_profile_interface handsfree
09-19 07:39:44.322  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-19 07:39:44.322  5874  5890 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-19 07:39:44.324  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:44.325  5874  5874 D A2dpService: Received start request. Starting profile...
09-19 07:39:44.326  5874  5874 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-19 07:39:44.326  5874  5874 I bt_bluedroid: get_profile_interface avrcp
,09-19 07:39:44.332  5874  5874 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-19 07:39:44.332  5874  5874 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-19 07:39:44.332  5874  5874 D A2dpStateMachine: make
09-19 07:39:44.333  5874  5874 I bt_bluedroid: get_profile_interface a2dp
,09-19 07:39:44.335  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-19 07:39:44.335  5874  5905 D A2dpStateMachine: Enter Disconnected: -2
09-19 07:39:44.336  5874  5874 I BluetoothHidServiceJni: classInitNative: succeeds
,09-19 07:39:44.337  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:44.337  5874  5874 D HidService: Received start request. Starting profile...
09-19 07:39:44.338  5874  5874 I bt_bluedroid: get_profile_interface hidhost
09-19 07:39:44.338  5874  5890 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cac56d
09-19 07:39:44.338  5874  5874 D HidService: setHidService(): set to: null
,09-19 07:39:44.338  5874  5890 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-19 07:39:44.338  5874  5874 I BluetoothHealthServiceJni: classInitNative: succeeds
09-19 07:39:44.339  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:44.340  5874  5874 D HealthService: Received start request. Starting profile...
,09-19 07:39:44.341  5874  5874 I bt_bluedroid: get_profile_interface health
,09-19 07:39:44.342  5874  5874 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-19 07:39:44.342  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:44.343  5874  5874 D PanService: Received start request. Starting profile...
09-19 07:39:44.343  5874  5874 D BluetoothPanServiceJni: initializeNative(L110): pan
09-19 07:39:44.343  5874  5874 I bt_bluedroid: get_profile_interface pan
09-19 07:39:44.344  5874  5890 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-19 07:39:44.346  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:39:44.347  5874  5874 D BluetoothMapService: Received start request. Starting profile...
09-19 07:39:44.347  5874  5874 D BluetoothMapService: start()
09-19 07:39:44.347  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 07:39:44.350  5874  5874 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-19 07:39:44.351  5874  5874 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-19 07:39:44.351  5874  5874 D BluetoothMapAppObserver: createReceiver()
09-19 07:39:44.353  5874  5874 D BluetoothMapAppObserver: initObservers()
09-19 07:39:44.353  5874  5874 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-19 07:39:44.360  5874  5874 V SapService: SapBinder()
,09-19 07:39:44.360  5874  5874 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
09-19 07:39:44.361  5874  5874 D SapService: Received start request. Starting profile...
09-19 07:39:44.361  5874  5874 V SapService: start()
,09-19 07:39:44.362  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.362  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.362  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.362  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 07:39:44.363  5874  5903 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.363  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.364  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
,09-19 07:39:44.364  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.364  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.364  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.364  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:44.365  5874  5874 V BluetoothAdapterState: isTurningOff()=false
09-19 07:39:44.365  5874  5874 V BluetoothAdapterState: isTurningOn()=true
09-19 07:39:44.365  5874  5874 V BluetoothAdapterState: isBleTurningOn()=false
09-19 07:39:44.365  5874  5874 V BluetoothAdapterState: isBleTurningOff()=false
09-19 07:39:44.365  5874  5886 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-19 07:39:44.366  5874  5886 D BluetoothAdapterProperties: ScanMode =  20
09-19 07:39:44.366  5874  5886 D BluetoothAdapterProperties: State =  11
,09-19 07:39:44.366  5874  5886 D BluetoothAdapterProperties: Setting state to 12
,09-19 07:39:44.366  5874  5886 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-19 07:39:44.367  3792  4055 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:44.368   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:44.368  3092  3904 D BluetoothMap: onBluetoothStateChange: up=true
09-19 07:39:44.370  5874  5886 I BluetoothAdapterState: Entering OnState
09-19 07:39:44.370  5874  5890 D BluetoothAdapterProperties: Scan Mode:21
09-19 07:39:44.370  5874  5890 D BluetoothAdapterProperties: Discoverable Timeout:120
09-19 07:39:44.370  5660  5853 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:44.371  5660  5866 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 07:39:44.371  3092  3092 D BluetoothMap: Proxy object connected
09-19 07:39:44.371  3092  3092 D MapProfile: Bluetooth service connected
09-19 07:39:44.371  3092  3092 D BluetoothMap: getConnectedDevices()
,09-19 07:39:44.373   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 07:39:44.373  5660  5670 D BluetoothMap: onBluetoothStateChange: up=true
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:44.375  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:44.375  3092  3114 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 07:39:44.376  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:44.377  5660  5671 D BluetoothPbap: onBluetoothStateChange: up=true
,09-19 07:39:44.378  5660  5660 D BluetoothA2dp: Proxy object connected
09-19 07:39:44.379  3092  3092 D BluetoothInputDevice: Proxy object connected
09-19 07:39:44.379  3092  3092 D HidProfile: Bluetooth service connected
09-19 07:39:44.379  5660  5853 D BluetoothPan: onBluetoothStateChange on: true
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:44.381  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:44.381  3092  3104 D BluetoothPan: onBluetoothStateChange on: true
09-19 07:39:44.381  5874  5874 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-19 07:39:44.382  5874  5874 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-19 07:39:44.383  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:44.383  3092  3114 D BluetoothPbap: onBluetoothStateChange: up=true
09-19 07:39:44.384  5874  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:44.385   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 07:39:44.385   927   927 D BluetoothA2dp: Proxy object connected
,09-19 07:39:44.385  3092  3904 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-19 07:39:44.385  5874  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:44.386  3092  3104 D BluetoothA2dp: onBluetoothStateChange: up=true
09-19 07:39:44.386  5874  5874 D ObexServerSockets: Succeed to create listening sockets 
09-19 07:39:44.387  5874  5874 D ObexServerSockets0: startAccept()
09-19 07:39:44.387  5874  5874 D ObexServerSockets0: prepareForNewConnect()
09-19 07:39:44.387  3092  3092 D BluetoothA2dp: Proxy object connected
09-19 07:39:44.387   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-19 07:39:44.387  5660  5866 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-19 07:39:44.389  5874  5874 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-19 07:39:44.389  5874  5874 D BluetoothSdpJni: SDP Create record success - handle: 0
09-19 07:39:44.390  5874  5912 D ObexServerSockets0: Accepting socket connection...
09-19 07:39:44.390  5874  5913 D ObexServerSockets0: Accepting socket connection...
09-19 07:39:44.391  5660  5660 D BluetoothMap: Proxy object connected
,09-19 07:39:44.391  5660  5660 D MapProfile: Bluetooth service connected
09-19 07:39:44.391  5660  5660 D BluetoothMap: getConnectedDevices()
09-19 07:39:44.391   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-19 07:39:44.392  3092  3092 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 07:39:44.392  3092  3092 D PanProfile: Bluetooth service connected
09-19 07:39:44.393  5874  5874 D BluetoothMapService: onReceive
09-19 07:39:44.393  5874  5874 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-19 07:39:44.393  5874  5874 D BluetoothMapService: STATE_ON
09-19 07:39:44.393  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:44.394  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:44.394  5874  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:39:44.395  5660  5660 D BluetoothInputDevice: Proxy object connected
09-19 07:39:44.395  5660  5660 D HidProfile: Bluetooth service connected
09-19 07:39:44.395  5874  5914 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-19 07:39:44.395  5874  5914 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-19 07:39:44.400  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-19 07:39:44.402  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
09-19 07:39:44.402  5660  5660 D PanProfile: Bluetooth service connected
,09-19 07:39:44.406  3545  3545 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-19 07:39:44.408  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-19 07:39:44.413  5660  5660 D BluetoothPbap: Proxy object connected
,09-19 07:39:44.413  5660  5660 D PbapServerProfile: Bluetooth service connected
,09-19 07:39:44.417  5874  5874 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-19 07:39:44.417  5874  5874 D ObexServerSockets0: prepareForNewConnect()
09-19 07:39:44.419  5874  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:44.425  3092  3092 D BluetoothPbap: Proxy object connected
09-19 07:39:44.425  3092  3092 D PbapServerProfile: Bluetooth service connected
,09-19 07:39:44.433  5874  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-19 07:39:44.434  5874  5922 I BtOppRfcommListener: Accept thread started.
,09-19 07:39:44.469   927   927 D BluetoothHeadset: Proxy object connected
,09-19 07:39:44.469  5660  5866 D BluetoothHeadset: Proxy object connected
,09-19 07:39:44.469  3092  3104 D BluetoothHeadset: Proxy object connected
09-19 07:39:44.470  3092  3092 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:44.470   927   927 D BluetoothHeadset: Proxy object connected
09-19 07:39:44.470   927   927 D BluetoothHeadset: Proxy object connected
09-19 07:39:44.470  3792  3820 D BluetoothHeadset: Proxy object connected
09-19 07:39:44.471  5660  5671 D BluetoothHeadset: Proxy object connected
09-19 07:39:44.472  5660  5660 D HeadsetProfile: Bluetooth service connected
09-19 07:39:44.473  5660  5660 D HeadsetProfile: Bluetooth service connected
09-19 07:39:44.474   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:44.485  3092  3114 D BluetoothHeadset: Proxy object connected
,09-19 07:39:44.486  3092  3092 D HeadsetProfile: Bluetooth service connected
,09-19 07:39:44.488   927   944 D BluetoothHeadset: Proxy object connected
,09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:48.327  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:39:48.332  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:48.333  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:48.333  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ca9362 removed from the list
09-19 07:39:48.333  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:39:48.334  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:39:48.334  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:39:48.335  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:39:48.336  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf4ccf3 added. We now have 4 listener(s)
09-19 07:39:48.336  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:39:48.338   927  3775 D WifiService: setWifiEnabled: false pid=5569, uid=10077
09-19 07:39:48.338   927  3775 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-19 07:39:50.283   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:39:50.283   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:39:53.348  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:53.349   927  3865 D WifiService: setWifiEnabled: true pid=5569, uid=10077
,09-19 07:39:53.349   927  3865 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-19 07:39:53.355   509   921 D SoftapController: Softap fwReload - Ok
,09-19 07:39:53.361   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:53.361   509   921 D CommandListener: Trying to bring down wlan0
,09-19 07:39:53.364   509   921 D CommandListener: Clearing all IP addresses on wlan0
,09-19 07:39:53.369   927  2940 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-19 07:39:54.022   927  2940 D wifi    : set interface wlan0 flags (UP)
,09-19 07:39:54.028   927  2940 I WifiHAL : Initializing wifi
,09-19 07:39:54.028   927  2940 I WifiHAL : Creating socket
,09-19 07:39:54.034   927  2940 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-19 07:39:54.034   927  2940 D wifi    : Did set static halHandle = 0x7f8c026040
,09-19 07:39:54.034   927  2940 D wifi    : halHandle = 0x7f8c026040, mVM = 0x7fa200d140, mCls = 0x100ec6
09-19 07:39:54.035   927  2940 D wifi    : array field set
09-19 07:39:54.035   927  2940 I WifiNative-HAL: interface[0] = wlan0
09-19 07:39:54.036   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-19 07:39:54.038   927  5928 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547809812544
09-19 07:39:54.038   927  5928 D wifi    : waitForHalEvents called, vm = 0x7fa200d140, obj = 0x100ec6, env = 0x7f861e7280
,09-19 07:39:54.087  5929  5929 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-19 07:39:54.107  5929  5929 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-19 07:39:54.144   927  2940 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-19 07:39:54.144  5929  5929 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-19 07:39:54.144  5929  5929 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-19 07:39:54.147  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:39:54.149  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:39:54.162   927  2940 D WifiConfigStore: Loading config and enabling all networks 
,09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:54.165  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:54.167  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:54.171  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-19 07:39:54.173  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:39:54.175   927  2940 D WifiConfigStore: loaded 0 passpoint configs
09-19 07:39:54.175   927  2940 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-19 07:39:54.175   927  2940 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-19 07:39:54.177   927  2940 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-19 07:39:54.178   927  2940 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-19 07:39:54.178   927  2940 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-19 07:39:54.178   927  2940 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-19 07:39:54.178   927  2940 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-19 07:39:54.182   927  2940 D WifiNative-HAL: Setting external_sim to 1
,09-19 07:39:54.182  4850  4850 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-19 07:39:54.183   927  2940 D wifi    : setting dfs flag to true, 0x7f8a8ffce0
09-19 07:39:54.183   927  2940 D WifiStateMachine: Setting OUI to DA-A1-19
,09-19 07:39:54.183   927  2940 D wifi    : setting scan oui 0x7f8a8ffce0
09-19 07:39:54.183   927  2940 D WifiHAL : Sending mac address OUI
,09-19 07:39:54.199   927  2940 E native  : do suspend true
,09-19 07:39:54.206   927  2940 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-19 07:39:54.206   927   927 D RttService: SCAN_AVAILABLE : 3
09-19 07:39:54.206   509   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-19 07:39:54.206   927  3044 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-19 07:39:54.207   509   921 D CommandListener: Setting iface cfg
,09-19 07:39:54.212   927  2922 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '172 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 172 Failed to set address (No such device)'
,09-19 07:39:54.212   927  2922 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-19 07:39:54.215   927  2922 D WifiNative-HAL: p2pGetDeviceAddress
,09-19 07:39:54.219   927  2922 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-19 07:39:54.220   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=223140 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
,09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:39:58.368  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:39:58.375  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:39:58.376  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:39:58.376  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf4ccf3 removed from the list
09-19 07:39:58.377  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:39:58.378  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:39:58.378  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:39:58.385  5569  5940 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-19 07:39:58.386  5569  5940 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-19 07:40:00.285   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:01.286   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:01.397  5569  5941 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-19 07:40:01.397  5569  5940 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-19 07:40:01.398  5569  5941 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-19 07:40:01.398  5569  5940 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-19 07:40:01.399  5569  5941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-19 07:40:01.399  5569  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-19 07:40:01.401  5569  5941 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-19 07:40:01.401  5569  5940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-19 07:40:01.405  5569  5943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: IncomingSocketThread/Sender)
,09-19 07:40:01.407  5569  5941 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-19 07:40:01.407  5569  5940 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-19 07:40:01.411  5569  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender)
,09-19 07:40:01.412  5569  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Receiver)
,09-19 07:40:01.415  5569  5945 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: IncomingSocketThread/Receiver)
,09-19 07:40:01.416  5569  5945 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-19 07:40:01.416  5569  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-19 07:40:01.416  5569  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
09-19 07:40:01.418  5569  5946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
09-19 07:40:01.418  5569  5946 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-19 07:40:01.419  5569  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-19 07:40:02.288   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:03.290   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:04.291   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:04.393  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-19 07:40:04.394  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-19 07:40:04.401  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f2a9ed3 Bundle[{}]
,09-19 07:40:04.402  5569  5615 I io.jxcore.node.LifeCycleMonitor: start: OK
09-19 07:40:04.404  5569  5615 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-19 07:40:04.405  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-19 07:40:04.406  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-19 07:40:04.407  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-19 07:40:04.409  5569  5615 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-19 07:40:04.415  5569  5615 I System.out: Running OutgoingSocketThread
,09-19 07:40:04.417  5569  5947 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-19 07:40:04.417  5569  5947 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-19 07:40:05.292   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:40:06.990  5952  5952 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-19 07:40:06.995  5952  5952 D AndroidRuntime: CheckJNI is OFF
,09-19 07:40:07.023  5952  5952 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-19 07:40:07.062  5952  5952 I Radio-JNI: register_android_hardware_Radio DONE
,09-19 07:40:07.080  5952  5952 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-19 07:40:07.111  5952  5952 I art     : System.exit called, status: 0
09-19 07:40:07.111  5952  5952 I AndroidRuntime: VM exiting with result code 0.
,09-19 07:40:07.429  5569  5947 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-19 07:40:07.429  5569  5947 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-19 07:40:07.429  5569  5947 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-19 07:40:07.430  5569  5962 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-19 07:40:07.430  5569  5962 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-19 07:40:07.430  5569  5962 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-19 07:40:07.430  5569  5947 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-19 07:40:07.432  5569  5962 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-19 07:40:07.432  5569  5947 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-19 07:40:07.438  5569  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
,09-19 07:40:07.438  5569  5962 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-19 07:40:07.440  5569  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
,09-19 07:40:07.441  5569  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,09-19 07:40:07.441  5569  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
,09-19 07:40:07.441  5569  5966 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-19 07:40:07.441  5569  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-19 07:40:07.442  5569  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender)
09-19 07:40:07.442  5569  5967 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
09-19 07:40:07.442  5569  5967 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-19 07:40:07.442  5569  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-19 07:40:10.293   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:10.426  5569  5615 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-19 07:40:10.428  5569  5615 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-19 07:40:10.428  5569  5615 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-19 07:40:10.435  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 07:40:10.435  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f7db0 added. We now have 3 listener(s)
,09-19 07:40:10.438  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 07:40:10.439  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:40:10.439  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-19 07:40:10.439  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:40:10.440  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f545429 added. We now have 4 listener(s)
,09-19 07:40:10.440  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:40:10.441  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 07:40:10.447  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:40:10.452  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:40:10.457  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:40:10.457  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:40:10.458  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:40:10.458  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:40:10.458  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:40:10.459  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:10.459  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:10.459  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:10.459  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 07:40:10.459  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f7db0 removed from the list
09-19 07:40:10.459  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:10.459  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f545429 removed from the list
,09-19 07:40:10.460  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:40:10.460  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:40:10.460  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:10.461  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:10.461  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:10.463  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:10.463  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:10.463  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:10.463  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f545429 not in the list
09-19 07:40:10.463  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:10.463  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:10.466  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 07:40:10.466  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:10.466  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:10.466  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f545429 not in the list
09-19 07:40:10.466  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:10.466  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:10.467  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:10.467  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f7db0 not in the list
09-19 07:40:10.467  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:40:10.468  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 07:40:10.468  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c05454f added. We now have 3 listener(s)
09-19 07:40:10.470  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 07:40:10.470  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:40:10.470  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 07:40:10.470  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:40:10.470  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376c4dc added. We now have 4 listener(s)
09-19 07:40:10.471  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 07:40:10.471  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 07:40:10.475  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:40:10.480  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:40:10.483  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:40:10.483  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:40:10.484  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 07:40:10.484  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 07:40:10.484  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 07:40:10.484  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:40:10.484  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 07:40:10.486  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:40:10.490  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:40:10.490  5569  5615 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 07:40:10.490  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 07:40:10.496  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 07:40:10.498  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-19 07:40:10.499  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-19 07:40:10.503  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-19 07:40:10.503  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 07:40:10.504  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-19 07:40:10.505  5569  5615 D BluetoothAdapter: STATE_ON
,09-19 07:40:10.511  5874  5911 D BtGatt.GattService: registerClient() - UUID=375bac2c-f643-4a04-b54c-364dae43c50e
,09-19 07:40:10.512  5874  5890 D BtGatt.GattService: onClientRegistered() - UUID=375bac2c-f643-4a04-b54c-364dae43c50e, clientIf=5
,09-19 07:40:10.512  5569  5580 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-19 07:40:10.514  5874  5902 D BtGatt.GattService: start scan with filters
,09-19 07:40:10.517  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 07:40:10.518  5874  5893 D BtGatt.ScanManager: handling starting scan
09-19 07:40:10.518  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-19 07:40:10.518  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-19 07:40:10.518  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-19 07:40:10.520  5874  5893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b227a4
,09-19 07:40:10.521  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 07:40:10.521  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-19 07:40:10.521  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 07:40:10.523  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-19 07:40:10.526  5569  5615 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-19 07:40:10.526  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:40:10.526  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 07:40:10.526  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:10.526  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-19 07:40:10.526  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 07:40:10.526  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 07:40:10.526  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 07:40:10.526  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 07:40:10.527  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 07:40:10.527  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 07:40:10.527  5874  5890 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 07:40:10.527  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:10.528  5569  5615 D BluetoothAdapter: STATE_ON
09-19 07:40:10.528  5874  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-19 07:40:10.528  5874  5911 D BtGatt.GattService: stopScan() - queue size =1
09-19 07:40:10.530  5874  5902 D BtGatt.GattService: unregisterClient() - clientIf=5
09-19 07:40:10.530  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 07:40:10.530  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-19 07:40:10.530  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 07:40:10.530  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-19 07:40:10.530  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 07:40:10.531  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:40:10.532  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 07:40:10.532  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 07:40:10.532  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 07:40:10.533  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:10.533  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:40:10.534  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:40:10.534  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:40:10.534  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-19 07:40:10.534  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:10.535  5874  5893 D BtGatt.ScanManager: Starting BLE batch scan
09-19 07:40:10.535  5874  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-19 07:40:10.544  5874  5890 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-19 07:40:10.544  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 07:40:10.549  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-19 07:40:10.549  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 07:40:10.556  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-19 07:40:10.556  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:10.556  5874  5893 D BtGatt.ScanManager: stopping BLe Batch
,09-19 07:40:10.561  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-19 07:40:10.561  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:10.561  5874  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-19 07:40:10.566  5874  5890 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-19 07:40:10.566  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 07:40:11.034  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-19 07:40:11.034  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:40:11.034  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-19 07:40:11.294   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:12.295   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:13.296   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:13.534  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:40:13.535  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:40:13.535  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:40:13.535  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:13.535  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:13.535  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:13.536  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-19 07:40:13.536  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c05454f removed from the list
,09-19 07:40:13.536  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:40:13.536  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376c4dc removed from the list
,09-19 07:40:13.536  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
,09-19 07:40:13.537  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:13.538  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:13.538  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:13.541  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:13.541  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-19 07:40:13.542  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:13.542  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376c4dc not in the list
09-19 07:40:13.542  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:13.542  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:13.546  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:13.546  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:13.546  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:40:13.547  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376c4dc not in the list
09-19 07:40:13.547  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:13.547  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:13.547  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:13.547  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c05454f not in the list
,09-19 07:40:13.549  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 07:40:13.549  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab15f61 added. We now have 3 listener(s)
09-19 07:40:13.554  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 07:40:13.555  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:40:13.555  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-19 07:40:13.555  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:40:13.555  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9b5a86 added. We now have 4 listener(s)
09-19 07:40:13.555  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:40:13.556  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-19 07:40:13.561  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:40:13.565  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:40:13.568  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-19 07:40:13.569  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:40:13.569  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-19 07:40:13.570  5569  5615 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-19 07:40:13.570  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-19 07:40:13.571  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-19 07:40:13.571  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-19 07:40:13.571  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-19 07:40:13.571  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:13.572  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:40:13.575  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-19 07:40:13.576  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:40:13.576  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-19 07:40:13.577  5885  5885 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[38541]" dev="sockfs" ino=38541 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-19 07:40:13.577  5885  5885 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[38541]" dev="sockfs" ino=38541 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-19 07:40:13.576  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-19 07:40:13.576  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-19 07:40:13.576  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-19 07:40:13.576  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:13.576  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 07:40:13.576  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-19 07:40:13.578  5569  5968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-19 07:40:13.580  5569  5615 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-19 07:40:13.580  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-19 07:40:13.582  5569  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-19 07:40:13.584  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 07:40:13.585  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 07:40:13.585  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-19 07:40:13.587  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-19 07:40:13.588  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 07:40:13.588  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-19 07:40:13.589  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-19 07:40:13.589  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-19 07:40:13.589  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-19 07:40:13.590  5569  5615 D BluetoothAdapter: STATE_ON
,09-19 07:40:13.594  5874  5884 D BtGatt.GattService: registerClient() - UUID=fec76ab3-a925-4d4f-9aa4-8f6981d24133
09-19 07:40:13.595  5874  5890 D BtGatt.GattService: onClientRegistered() - UUID=fec76ab3-a925-4d4f-9aa4-8f6981d24133, clientIf=5
,09-19 07:40:13.595  5569  5579 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-19 07:40:13.597  5874  5892 D BtGatt.AdvertiseManager: message : 0
,09-19 07:40:13.600  5874  5892 D BtGatt.AdvertiseManager: starting multi advertising
,09-19 07:40:13.611  5874  5890 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-19 07:40:13.617  5874  5890 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-19 07:40:13.618  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-19 07:40:13.618  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 07:40:13.619  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 07:40:13.621  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-19 07:40:13.621  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-19 07:40:13.621  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-19 07:40:13.621  5569  5569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-19 07:40:13.621  5569  5569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-19 07:40:13.621  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-19 07:40:13.624  5569  5569 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-19 07:40:13.624  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-19 07:40:13.624  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-19 07:40:13.624  5569  5615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-19 07:40:14.124  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-19 07:40:14.297   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:15.298   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:40:16.626  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:40:16.626  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-19 07:40:16.626  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-19 07:40:16.627  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-19 07:40:16.627  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-19 07:40:16.627  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-19 07:40:16.628  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-19 07:40:16.628  5569  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-19 07:40:16.628  5569  5615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-19 07:40:16.628  5569  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-19 07:40:16.628  5569  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-19 07:40:16.628  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-19 07:40:16.628  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 07:40:16.628  5569  5569 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-19 07:40:16.628  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-19 07:40:16.629  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 07:40:16.629  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-19 07:40:16.632  5569  5615 D BluetoothAdapter: STATE_ON
09-19 07:40:16.632  5569  5615 D BluetoothLeScanner: could not find callback wrapper
09-19 07:40:16.633  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-19 07:40:16.633  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-19 07:40:16.634  5874  5892 D BtGatt.AdvertiseManager: message : 1
09-19 07:40:16.636  5874  5892 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-19 07:40:16.649  5874  5890 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-19 07:40:16.649  5874  5890 D BtGatt.GattService: Client app is not null!
,09-19 07:40:16.650  5874  5910 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-19 07:40:16.651  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-19 07:40:16.651  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-19 07:40:16.652  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-19 07:40:16.652  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-19 07:40:16.652  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-19 07:40:16.654  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:40:16.655  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 07:40:16.655  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 07:40:16.656  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:16.657  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:16.658  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-19 07:40:16.658  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:16.658  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:16.658  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:40:16.658  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 07:40:16.658  5569  5569 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-19 07:40:16.658  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab15f61 removed from the list
,09-19 07:40:16.658  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:40:16.658  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:16.658  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9b5a86 removed from the list
,09-19 07:40:16.658  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:40:16.658  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:16.660  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:16.660  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:16.662  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-19 07:40:16.663  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:16.663  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:16.663  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9b5a86 not in the list
09-19 07:40:16.663  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:16.663  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:16.665  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:16.665  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:16.665  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:16.665  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9b5a86 not in the list
,09-19 07:40:16.665  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:16.665  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:16.665  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:16.666  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab15f61 not in the list
09-19 07:40:16.667  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-19 07:40:16.667  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ad8e3 added. We now have 3 listener(s)
,09-19 07:40:16.669  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-19 07:40:16.669  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:40:16.669  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 07:40:16.669  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-19 07:40:16.669  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b2e0 added. We now have 4 listener(s)
09-19 07:40:16.670  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 07:40:16.670  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 07:40:16.674  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:40:16.678  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:40:16.681  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:40:16.681  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:40:16.681  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 07:40:16.681  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-19 07:40:16.681  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-19 07:40:16.681  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 07:40:16.681  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-19 07:40:16.683  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:40:16.686  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 07:40:16.687  5569  5615 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-19 07:40:16.687  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-19 07:40:16.691  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-19 07:40:16.691  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-19 07:40:16.691  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-19 07:40:16.694  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-19 07:40:16.694  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-19 07:40:16.694  5569  5615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-19 07:40:16.695  5569  5615 D BluetoothAdapter: STATE_ON
,09-19 07:40:16.697  5874  5885 D BtGatt.GattService: registerClient() - UUID=df4dae69-2f81-407b-8e31-97873716a903
09-19 07:40:16.698  5874  5890 D BtGatt.GattService: onClientRegistered() - UUID=df4dae69-2f81-407b-8e31-97873716a903, clientIf=5
,09-19 07:40:16.698  5569  5678 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-19 07:40:16.699  5874  5910 D BtGatt.GattService: start scan with filters
,09-19 07:40:16.702  5874  5893 D BtGatt.ScanManager: handling starting scan
,09-19 07:40:16.703  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-19 07:40:16.703  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-19 07:40:16.703  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-19 07:40:16.703  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-19 07:40:16.705  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-19 07:40:16.706  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-19 07:40:16.706  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-19 07:40:16.707  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-19 07:40:16.709  5874  5890 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-19 07:40:16.709  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:16.709  5874  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-19 07:40:16.715  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-19 07:40:16.715  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:16.716  5874  5893 D BtGatt.ScanManager: Starting BLE batch scan
,09-19 07:40:16.717  5874  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-19 07:40:16.727  5874  5890 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-19 07:40:16.727  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 07:40:16.732  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-19 07:40:16.732  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-19 07:40:17.160  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 07:40:17.206  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-19 07:40:17.206  5569  5569 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 07:40:17.206  5569  5569 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-19 07:40:19.718  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-19 07:40:19.718  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-19 07:40:19.718  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-19 07:40:19.719  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.719  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-19 07:40:19.719  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-19 07:40:19.719  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-19 07:40:19.720  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-19 07:40:19.720  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-19 07:40:19.720  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-19 07:40:19.720  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-19 07:40:19.723  5569  5615 D BluetoothAdapter: STATE_ON
09-19 07:40:19.726  5874  5884 D BtGatt.GattService: stopScan() - queue size =1
,09-19 07:40:19.731  5874  5911 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-19 07:40:19.731  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-19 07:40:19.732  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-19 07:40:19.732  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-19 07:40:19.732  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-19 07:40:19.732  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-19 07:40:19.735  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:40:19.736  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-19 07:40:19.736  5569  5615 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-19 07:40:19.736  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-19 07:40:19.741  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-19 07:40:19.746  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:19.746  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:40:19.746  5874  5874 D BtGatt.ScanManager: awakened up at time 248667
,09-19 07:40:19.746  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.746  5569  5569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-19 07:40:19.747  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:19.747  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 07:40:19.747  5569  5569 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-19 07:40:19.747  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ad8e3 removed from the list
09-19 07:40:19.747  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-19 07:40:19.747  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b2e0 removed from the list
09-19 07:40:19.747  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:40:19.747  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:19.749  5874  5890 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-19 07:40:19.750  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:19.750  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.750  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:19.750  5874  5893 D BtGatt.ScanManager: stopping BLe Batch
09-19 07:40:19.752  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:19.752  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:19.752  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:19.752  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b2e0 not in the list
09-19 07:40:19.752  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:19.753  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:19.756  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:19.756  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:19.757  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:19.757  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b2e0 not in the list
09-19 07:40:19.757  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 07:40:19.757  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.757  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:19.757  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ad8e3 not in the list
09-19 07:40:19.758  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-19 07:40:19.758  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd53655 added. We now have 3 listener(s)
09-19 07:40:19.762  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 07:40:19.762  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 07:40:19.762  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 07:40:19.762  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-19 07:40:19.762  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f14386a added. We now have 4 listener(s)
09-19 07:40:19.762  5569  5615 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-19 07:40:19.763  5874  5890 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-19 07:40:19.763  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 07:40:19.763  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:19.764  5874  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-19 07:40:19.772  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-19 07:40:19.776  5569  5615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-19 07:40:19.778  5569  5615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-19 07:40:19.779  5569  5615 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 07:40:19.780  5569  5615 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-19 07:40:19.781  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:40:19.781  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-19 07:40:19.781  5569  5615 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-19 07:40:19.781  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-19 07:40:19.781  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-19 07:40:19.781  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-19 07:40:19.781  5569  5615 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-19 07:40:19.781  5569  5615 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd53655 removed from the list
09-19 07:40:19.781  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:19.781  5569  5615 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f14386a removed from the list
09-19 07:40:19.783  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-19 07:40:19.783  5569  5615 D io.jxcore.node.ConnectivityMonitor: stop
09-19 07:40:19.784  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:19.784  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.784  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:19.786  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:19.786  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:19.786  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:19.786  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f14386a not in the list
09-19 07:40:19.786  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.786  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-19 07:40:19.789  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-19 07:40:19.789  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-19 07:40:19.789  5569  5615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-19 07:40:19.790  5569  5615 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f14386a not in the list
09-19 07:40:19.790  5569  5615 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-19 07:40:19.790  5569  5615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-19 07:40:19.790  5569  5615 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-19 07:40:19.790  5569  5615 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd53655 not in the list
09-19 07:40:19.791  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-19 07:40:19.791  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-19 07:40:19.791  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-19 07:40:19.791  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-19 07:40:19.791  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-19 07:40:19.791  5569  5615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-19 07:40:19.795  5874  5890 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=10
09-19 07:40:19.795  5874  5890 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-19 07:40:19.795  5874  5890 D BtGatt.GattService: current time is 248716507572
,09-19 07:40:19.796  5874  5890 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -93, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -87, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -87, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -4, -84, 59, 127, 94, 121, 1, -128, -67, 41, 0, 0, 0, -4, -84, 59, 127, 94, 121, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -88, -127, -107, -23, 95, 111, 0, 54, 109, 9, 126, 102, 87, 1, -128, -66, 32, 0, 0, 0, 54, 109, 9, 126, 102, 87, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62, 0]
,09-19 07:40:19.798  5874  5890 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-19 07:40:19.799  5874  5890 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-19 07:40:19.799  5874  5890 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-19 07:40:19.799  5874  5890 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-19 07:40:19.799  5874  5890 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-19 07:40:19.799  5874  5890 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-19 07:40:19.799  5874  5890 D BtGatt.GattService: ScanRecord : []
09-19 07:40:19.800  5874  5890 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, -88, -127, -107, -23, 95, 111]
09-19 07:40:19.800  5874  5890 D BtGatt.GattService: ScanRecord : []
,09-19 07:40:19.800  5874  5890 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62]
,09-19 07:40:20.247  5569  5569 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-19 07:40:21.803  5569  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-19 07:40:23.803  5569  5615 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
09-19 07:40:23.803  5569  5615 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-19 07:40:23.809  5569  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
09-19 07:40:23.809  5569  5970 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
09-19 07:40:23.809  5569  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-19 07:40:23.814  5569  5615 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-19 07:40:23.821  5569  5971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
09-19 07:40:23.821  5569  5971 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-19 07:40:23.822  5569  5971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-19 07:40:23.831  5569  5615 I jxcore-log: Total number of executed tests:  82
09-19 07:40:23.831  5569  5615 I jxcore-log: 
,09-19 07:40:23.832  5569  5615 I jxcore-log: Number of passed tests:  81
09-19 07:40:23.832  5569  5615 I jxcore-log: 
09-19 07:40:23.832  5569  5615 I jxcore-log: Number of failed tests:  1
09-19 07:40:23.832  5569  5615 I jxcore-log: 
09-19 07:40:23.833  5569  5615 I jxcore-log: Number of ignored tests:  0
09-19 07:40:23.833  5569  5615 I jxcore-log: 
09-19 07:40:23.833  5569  5615 I jxcore-log: Total duration:  95765
09-19 07:40:23.833  5569  5615 I jxcore-log: 
,09-19 07:40:23.835  5569  5615 I jxcore-log: Failures: 
09-19 07:40:23.835  5569  5615 I jxcore-log:  DiscoveryManager1 isRunning should return true
09-19 07:40:23.835  5569  5615 I jxcore-log: Expected: is <true>
09-19 07:40:23.835  5569  5615 I jxcore-log:      but: was <false>
09-19 07:40:23.835  5569  5615 I jxcore-log: 
09-19 07:40:23.835  5569  5615 I jxcore-log: 
,09-19 07:40:23.836  5569  5615 I jxcore-log: Failed to execute UT.
09-19 07:40:23.836  5569  5615 I jxcore-log: 
,09-19 07:40:23.843  5569  5615 I jxcore-log: Unit Test app is loaded
09-19 07:40:23.843  5569  5615 I jxcore-log: 
,09-19 07:40:23.858  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.858  5569  5615 I jxcore-log: 
,09-19 07:40:23.868  5569  5569 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-19 07:40:23.868  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.868  5569  5615 I jxcore-log: 
,09-19 07:40:23.870  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.870  5569  5615 I jxcore-log: 
,09-19 07:40:23.873  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.873  5569  5615 I jxcore-log: 
,09-19 07:40:23.876  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.876  5569  5615 I jxcore-log: 
,09-19 07:40:23.879  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.879  5569  5615 I jxcore-log: 
,09-19 07:40:23.882  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.882  5569  5615 I jxcore-log: 
,09-19 07:40:23.884  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.884  5569  5615 I jxcore-log: 
,09-19 07:40:23.885  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.885  5569  5615 I jxcore-log: 
09-19 07:40:23.886  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.886  5569  5615 I jxcore-log: 
,09-19 07:40:23.888  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.888  5569  5615 I jxcore-log: 
,09-19 07:40:23.890  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.890  5569  5615 I jxcore-log: 
,09-19 07:40:23.891  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.891  5569  5615 I jxcore-log: 
,09-19 07:40:23.893  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.893  5569  5615 I jxcore-log: 
,09-19 07:40:23.894  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.894  5569  5615 I jxcore-log: 
,09-19 07:40:23.896  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.896  5569  5615 I jxcore-log: 
,09-19 07:40:23.898  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.898  5569  5615 I jxcore-log: 
,09-19 07:40:23.899  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.899  5569  5615 I jxcore-log: 
,09-19 07:40:23.901  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.901  5569  5615 I jxcore-log: 
09-19 07:40:23.902  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.902  5569  5615 I jxcore-log: 
09-19 07:40:23.903  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.903  5569  5615 I jxcore-log: 
09-19 07:40:23.904  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.904  5569  5615 I jxcore-log: 
09-19 07:40:23.904  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.904  5569  5615 I jxcore-log: 
09-19 07:40:23.904  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.904  5569  5615 I jxcore-log: 
,09-19 07:40:23.905  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.905  5569  5615 I jxcore-log: 
09-19 07:40:23.905  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:40:23.905  5569  5615 I jxcore-log: 
,09-19 07:40:23.907  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.907  5569  5615 I jxcore-log: 
,09-19 07:40:23.909  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.909  5569  5615 I jxcore-log: 
,09-19 07:40:23.910  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.910  5569  5615 I jxcore-log: 
,09-19 07:40:23.911  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.911  5569  5615 I jxcore-log: 
09-19 07:40:23.912  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.912  5569  5615 I jxcore-log: 
09-19 07:40:23.913  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.913  5569  5615 I jxcore-log: 
,09-19 07:40:23.914  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.914  5569  5615 I jxcore-log: 
,09-19 07:40:23.915  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.915  5569  5615 I jxcore-log: 
09-19 07:40:23.916  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.916  5569  5615 I jxcore-log: 
,09-19 07:40:23.917  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.917  5569  5615 I jxcore-log: 
09-19 07:40:23.919  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.919  5569  5615 I jxcore-log: 
,09-19 07:40:23.920  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.920  5569  5615 I jxcore-log: 
,09-19 07:40:23.921  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-19 07:40:23.921  5569  5615 I jxcore-log: 
09-19 07:40:23.922  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.922  5569  5615 I jxcore-log: 
,09-19 07:40:23.923  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.923  5569  5615 I jxcore-log: 
09-19 07:40:23.924  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.924  5569  5615 I jxcore-log: 
,09-19 07:40:23.924  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.924  5569  5615 I jxcore-log: 
09-19 07:40:23.925  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.925  5569  5615 I jxcore-log: 
,09-19 07:40:23.926  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.926  5569  5615 I jxcore-log: 
09-19 07:40:23.927  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.927  5569  5615 I jxcore-log: 
,09-19 07:40:23.927  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-19 07:40:23.927  5569  5615 I jxcore-log: 
09-19 07:40:23.928  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.928  5569  5615 I jxcore-log: 
,09-19 07:40:23.929  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.929  5569  5615 I jxcore-log: 
09-19 07:40:23.930  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-19 07:40:23.930  5569  5615 I jxcore-log: 
,09-19 07:40:23.930  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-19 07:40:23.930  5569  5615 I jxcore-log: 
09-19 07:40:23.931  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-19 07:40:23.931  5569  5615 I jxcore-log: 
,09-19 07:40:23.937  5569  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
09-19 07:40:23.937  5569  5615 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'off',
09-19 07:40:23.937  5569  5615 I jxcore-log:   bluetooth: 'off',
09-19 07:40:23.937  5569  5615 I jxcore-log:   wifi: 'on',
09-19 07:40:23.937  5569  5615 I jxcore-log:   cellular: 'doNotCare',
09-19 07:40:23.937  5569  5615 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-19 07:40:23.937  5569  5615 I jxcore-log: 
09-19 07:40:23.937  5569  5615 I jxcore-log: Toggling BLUETOOTH ON
09-19 07:40:23.937  5569  5615 I jxcore-log: 
,09-19 07:40:23.940  5569  5615 D BluetoothAdapter: enable(): BT is already enabled..!
,09-19 07:40:23.946  5569  5615 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-19 07:40:23.946  5569  5615 I jxcore-log:   bluetooth: 'on',
09-19 07:40:23.946  5569  5615 I jxcore-log:   wifi: 'on',
09-19 07:40:23.946  5569  5615 I jxcore-log:   cellular: 'doNotCare' }
09-19 07:40:23.946  5569  5615 I jxcore-log: 
09-19 07:40:23.947  5569  5615 I jxcore-log: My device name is: Huawei-Nexus 6P
09-19 07:40:23.947  5569  5615 I jxcore-log: 
09-19 07:40:23.947  5569  5615 I jxcore-log: WARN testUtils: myNameCallback not set!
09-19 07:40:23.947  5569  5615 I jxcore-log: 
09-19 07:40:23.947  5569  5615 I jxcore-log: Running for WIFI network type
09-19 07:40:23.947  5569  5615 I jxcore-log: 
,09-19 07:40:25.299   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:25.727  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-19 07:40:25.727  5569  5615 I jxcore-log: 
,09-19 07:40:26.032  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-19 07:40:26.032  5569  5615 I jxcore-log: 
,09-19 07:40:26.049  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-19 07:40:26.049  5569  5615 I jxcore-log: 
,09-19 07:40:26.052  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-19 07:40:26.052  5569  5615 I jxcore-log: 
,09-19 07:40:26.058  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-19 07:40:26.058  5569  5615 I jxcore-log: 
,09-19 07:40:26.097  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-19 07:40:26.097  5569  5615 I jxcore-log: 
,09-19 07:40:26.108  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-19 07:40:26.108  5569  5615 I jxcore-log: 
,09-19 07:40:26.111  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-19 07:40:26.111  5569  5615 I jxcore-log: 
,09-19 07:40:26.300   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:26.623  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-19 07:40:26.623  5569  5615 I jxcore-log: 
,09-19 07:40:26.630  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-19 07:40:26.630  5569  5615 I jxcore-log: 
,09-19 07:40:26.636  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-19 07:40:26.636  5569  5615 I jxcore-log: 
,09-19 07:40:26.797  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-19 07:40:26.797  5569  5615 I jxcore-log: 
,09-19 07:40:27.301   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:27.824  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-19 07:40:27.824  5569  5615 I jxcore-log: 
,09-19 07:40:27.857  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-19 07:40:27.857  5569  5615 I jxcore-log: 
,09-19 07:40:27.863  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-19 07:40:27.863  5569  5615 I jxcore-log: 
,09-19 07:40:27.950  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-19 07:40:27.950  5569  5615 I jxcore-log: 
,09-19 07:40:27.965  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-19 07:40:27.965  5569  5615 I jxcore-log: 
,09-19 07:40:27.968  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-19 07:40:27.968  5569  5615 I jxcore-log: 
,09-19 07:40:27.973  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-19 07:40:27.973  5569  5615 I jxcore-log: 
,09-19 07:40:27.985  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-19 07:40:27.985  5569  5615 I jxcore-log: 
,09-19 07:40:28.045  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-19 07:40:28.045  5569  5615 I jxcore-log: 
,09-19 07:40:28.049  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-19 07:40:28.049  5569  5615 I jxcore-log: 
,09-19 07:40:28.068  5569  5615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-19 07:40:28.068  5569  5615 I jxcore-log: 
,09-19 07:40:28.077  5569  5615 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-19 07:40:28.078  5569  5615 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-19 07:40:28.078  5569  5615 I jxcore-log: 
,09-19 07:40:28.079  5569  5615 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-19 07:40:28.079  5569  5615 I jxcore-log: 
09-19 07:40:28.079  5569  5615 I jxcore-log: ThaliTape :: Started ThaliTape
09-19 07:40:28.079  5569  5615 I jxcore-log: 
,09-19 07:40:28.083  5569  5615 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-19 07:40:28.083  5569  5615 I jxcore-log: 
,09-19 07:40:28.114  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:28.114  5569  5615 I jxcore-log: 
,09-19 07:40:28.114  5569  5615 I jxcore-log: websocket error
09-19 07:40:28.114  5569  5615 I jxcore-log: 
09-19 07:40:28.114  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:28.114  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:28.114  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:28.114  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:28.114  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:28.114  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:28.114  5569  5615 I jxcore-log: 
09-19 07:40:28.114  5569  5615 I jxcore-log: WARN testUtils: logCallback not set!
09-19 07:40:28.114  5569  5615 I jxcore-log: 
,09-19 07:40:28.302   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:29.303   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:29.514  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:29.514  5569  5615 I jxcore-log: 
,09-19 07:40:29.515  5569  5615 I jxcore-log: websocket error
09-19 07:40:29.515  5569  5615 I jxcore-log: 
,09-19 07:40:29.515  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:29.515  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:29.515  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:29.515  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:29.515  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:29.515  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:29.515  5569  5615 I jxcore-log: 
,09-19 07:40:30.303   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:40:32.101  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:32.101  5569  5615 I jxcore-log: 
,09-19 07:40:32.101  5569  5615 I jxcore-log: websocket error
09-19 07:40:32.101  5569  5615 I jxcore-log: 
,09-19 07:40:32.101  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:32.101  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:32.101  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:32.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:32.101  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:32.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:32.101  5569  5615 I jxcore-log: 
,09-19 07:40:37.131  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:37.131  5569  5615 I jxcore-log: 
,09-19 07:40:37.131  5569  5615 I jxcore-log: websocket error
09-19 07:40:37.131  5569  5615 I jxcore-log: 
09-19 07:40:37.132  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:37.132  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:37.132  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:37.132  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:37.132  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:37.132  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:37.132  5569  5615 I jxcore-log: 
,09-19 07:40:42.157  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:42.157  5569  5615 I jxcore-log: 
,09-19 07:40:42.157  5569  5615 I jxcore-log: websocket error
09-19 07:40:42.157  5569  5615 I jxcore-log: 
09-19 07:40:42.157  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:42.157  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:42.157  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:42.157  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:42.157  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:42.157  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:42.157  5569  5615 I jxcore-log: 
,09-19 07:40:45.304   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:46.305   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:47.194  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:47.194  5569  5615 I jxcore-log: 
,09-19 07:40:47.194  5569  5615 I jxcore-log: websocket error
09-19 07:40:47.194  5569  5615 I jxcore-log: 
09-19 07:40:47.194  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:47.194  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:47.194  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:47.194  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:47.194  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:47.194  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:47.194  5569  5615 I jxcore-log: 
,09-19 07:40:47.307   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:48.308   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:49.310   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:40:50.310   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:40:52.225  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:52.225  5569  5615 I jxcore-log: 
,09-19 07:40:52.225  5569  5615 I jxcore-log: websocket error
09-19 07:40:52.225  5569  5615 I jxcore-log: 
09-19 07:40:52.225  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:52.225  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:52.225  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:52.225  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:52.225  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:52.225  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:52.225  5569  5615 I jxcore-log: 
,09-19 07:40:57.256  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:40:57.256  5569  5615 I jxcore-log: 
,09-19 07:40:57.256  5569  5615 I jxcore-log: websocket error
09-19 07:40:57.256  5569  5615 I jxcore-log: 
09-19 07:40:57.257  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:40:57.257  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:40:57.257  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:40:57.257  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:57.257  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:40:57.257  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:40:57.257  5569  5615 I jxcore-log: 
,09-19 07:41:02.284  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:02.284  5569  5615 I jxcore-log: 
,09-19 07:41:02.284  5569  5615 I jxcore-log: websocket error
09-19 07:41:02.284  5569  5615 I jxcore-log: 
09-19 07:41:02.285  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:02.285  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:02.285  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:02.285  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:02.285  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:02.285  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:02.285  5569  5615 I jxcore-log: 
,09-19 07:41:07.314  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:07.314  5569  5615 I jxcore-log: 
09-19 07:41:07.314  5569  5615 I jxcore-log: websocket error
09-19 07:41:07.314  5569  5615 I jxcore-log: 
09-19 07:41:07.314  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:07.314  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:07.314  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:07.314  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:07.314  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:07.314  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:07.314  5569  5615 I jxcore-log: 
,09-19 07:41:10.311   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:11.313   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:12.314   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:12.372  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:12.372  5569  5615 I jxcore-log: 
09-19 07:41:12.372  5569  5615 I jxcore-log: websocket error
09-19 07:41:12.372  5569  5615 I jxcore-log: 
09-19 07:41:12.373  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:12.373  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:12.373  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:12.373  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:12.373  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:12.373  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:12.373  5569  5615 I jxcore-log: 
,09-19 07:41:13.315   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:14.030   927  2908 I PowerManagerService: Waking up from dozing (uid 1000)...
,09-19 07:41:14.031   927   927 V KeyguardServiceDelegate: onStartedWakingUp()
,09-19 07:41:14.052   927   947 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
09-19 07:41:14.052   927   947 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@74eef75)
,09-19 07:41:14.057   927   927 I sensors : batch
09-19 07:41:14.058   927   927 I sensors : activate
09-19 07:41:14.058   927   947 I sensors : batch
,09-19 07:41:14.058   927   947 I sensors : activate
09-19 07:41:14.058   514  3009 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-19 07:41:14.057  5976  5976 W mdss_fb0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 07:41:14.060   383   383 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7f9d3c3c00
09-19 07:41:14.060   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-19 07:41:14.066   927  2677 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
09-19 07:41:14.067   927  2940 E native  : do suspend false
09-19 07:41:14.068   927  2677 I hubconnection: sensorhub said: 'activate 31 enable:1'
09-19 07:41:14.069   927  2677 I hubconnection: sensorhub said: 'batch 7 flags:0, sampling_rate_Hz:4.00, max_report_latency_us:0'
,09-19 07:41:14.071   927  2677 I hubconnection: sensorhub said: 'activate 7 enable:1'
,09-19 07:41:14.073   927   937 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,09-19 07:41:14.088   927  2940 D WifiConfigStore: No blacklist allowed without epno enabled
,09-19 07:41:14.092  3092  3092 W PathParser: Points are too far apart 4.030360828967057
,09-19 07:41:14.092  3092  3092 W PathParser: Points are too far apart 4.030360538880159
,09-19 07:41:14.127   927   947 I DisplayPowerController: Unblocked screen on after 76 ms
,09-19 07:41:14.128   927   947 V KeyguardServiceDelegate: onScreenTurnedOn()
,09-19 07:41:14.128   927   947 I DreamManagerService: Gently waking up from dream.
,09-19 07:41:14.130   927  3742 I DreamManagerService: Leaving dreamland.
09-19 07:41:14.130   927   942 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-19 07:41:14.132   927  3128 I sensors : activate
,09-19 07:41:14.135   927  2677 I hubconnection: sensorhub said: 'activate 21 enable:0'
,09-19 07:41:14.146  3792  4521 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,09-19 07:41:14.146  3792  4521 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-19 07:41:14.147  3792  4521 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-19 07:41:14.147   527  1052 D         : oem-qmi: Connection accepted
09-19 07:41:14.147   527  1052 D         : oem-qmi: Waiting to accept connection
,09-19 07:41:14.153  3792  4521 D         : oem_qmi_lib:output 0
,09-19 07:41:14.154  3792  4521 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-19 07:41:14.156  3092  3092 W PathParser: Points are too far apart 4.030360828967057
09-19 07:41:14.156  3092  3092 W PathParser: Points are too far apart 4.030360538880159
,09-19 07:41:14.219   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,09-19 07:41:14.217  5982  5982 W irq/504-synapti: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 07:41:14.223   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,09-19 07:41:14.223   927  3061 D SurfaceControl: Excessive delay in setPowerMode(): 164ms
,09-19 07:41:14.316   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:15.317   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:41:15.712  3092  3092 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME RECENT clock SEARCH quick_settings >
,09-19 07:41:15.720  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-19 07:41:15.721  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-19 07:41:15.723  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-19 07:41:15.723  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-19 07:41:15.828   514  2961 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-19 07:41:15.830  3092  3092 D PhoneStatusBar: disable: < expand icons* alerts system_info* back HOME RECENT clock SEARCH quick_settings >
,09-19 07:41:15.843   514  2961 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
09-19 07:41:15.845   514  2961 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
,09-19 07:41:15.848   514  2961 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-19 07:41:15.850  3742  3742 W Binder_7: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[21973]" dev="sockfs" ino=21973 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:41:15.850  3742  3742 W Binder_7: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[21973]" dev="sockfs" ino=21973 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:41:15.857  3865  3865 W Binder_C: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:41:15.857  3865  3865 W Binder_C: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:41:15.866   514  2961 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-19 07:41:15.866  4047  4047 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,09-19 07:41:15.868   514  2961 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-19 07:41:15.868  3092  3092 D PhoneStatusBar: disable: < expand icons alerts system_info back home* recent* clock search* quick_settings >
,09-19 07:41:16.597   514  2961 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-19 07:41:16.598   514  2961 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-19 07:41:16.607   514  2961 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-19 07:41:17.392  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:17.392  5569  5615 I jxcore-log: 
09-19 07:41:17.393  5569  5615 I jxcore-log: websocket error
09-19 07:41:17.393  5569  5615 I jxcore-log: 
09-19 07:41:17.393  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:17.393  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:17.393  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:17.393  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:17.393  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:17.393  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:17.393  5569  5615 I jxcore-log: 
,09-19 07:41:17.813  5929  5929 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-19 07:41:17.830  5929  5929 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-19 07:41:17.838  5929  5929 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-19 07:41:17.847  5929  5929 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-19 07:41:17.884   927  2940 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-19 07:41:17.886   927  2940 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-19 07:41:17.886   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:41:17.898   927  2940 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-19 07:41:17.929   927  2940 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-19 07:41:17.932  5929  5929 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-19 07:41:18.403  5929  5929 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-19 07:41:18.463  5929  5929 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-19 07:41:18.464  5929  5929 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-19 07:41:18.477   927  2940 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-19 07:41:18.478   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:41:18.478   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-19 07:41:18.493   927  2940 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-19 07:41:18.506   509   921 D CommandListener: Setting iface cfg
,09-19 07:41:18.510   927  2940 D WifiStateMachine: Start Dhcp Watchdog 3
,09-19 07:41:18.519   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:41:18.519   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-19 07:41:18.519   927  2951 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-19 07:41:18.521   927  5996 D DhcpClient: Receive thread started
,09-19 07:41:18.602   927  2940 E native  : do suspend false
,09-19 07:41:18.616   927  5995 D DhcpClient: Broadcasting DHCPDISCOVER
,09-19 07:41:18.643   927  5996 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,09-19 07:41:18.643   927  5995 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,09-19 07:41:18.644   927  5995 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-19 07:41:18.663   927  5996 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-19 07:41:18.663   927  5995 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-19 07:41:18.666   509   921 D CommandListener: Setting iface cfg
,09-19 07:41:18.670   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-19 07:41:18.677   927  5995 D DhcpClient: Scheduling renewal in 86399s
,09-19 07:41:18.686   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-19 07:41:18.686   927  2940 D WifiConfigStore: No blacklist allowed without epno enabled
,09-19 07:41:18.687   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-19 07:41:18.690   927  2951 D ConnectivityService: Adding iface wlan0 to network 102
09-19 07:41:18.693   927  2940 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-19 07:41:18.725   927  2951 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-19 07:41:18.725   927  2951 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-19 07:41:18.729   927  2951 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-19 07:41:18.731   927  2951 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-19 07:41:18.734   927  2951 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-19 07:41:18.743   927  2951 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:41:18.748   927  2951 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-19 07:41:18.748   927  2951 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-19 07:41:18.748   927  2951 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-19 07:41:18.748   927  2951 D ConnectivityService:    accepting network in place of null
09-19 07:41:18.748   927  2940 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-19 07:41:18.749   927  2940 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-19 07:41:18.751   927  2951 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -63]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-19 07:41:18.766   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307686, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-19 07:41:18.776   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:41:18.799   509   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-19 07:41:18.805   927  2951 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-19 07:41:18.805   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-19 07:41:18.805  3743  3893 W QCNEJ   : |CORE| network available: 102
,09-19 07:41:18.807   927  2951 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-19 07:41:18.808   927   944 D Tethering: MasterInitialState.processMessage what=3
09-19 07:41:18.809  3743  3893 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-19 07:41:18.811  3743  3893 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-19 07:41:18.811  3743  3893 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:41:18.819  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 07:41:18.820  3914  3914 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-19 07:41:18.821  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-19 07:41:18.824  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:41:18.824  5569  5615 I jxcore-log: 
,09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 07:41:18.826  5569  5569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 07:41:18.828  5569  5569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 07:41:18.831  5569  5615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 07:41:18.831  5569  5615 I jxcore-log: 
,09-19 07:41:18.836  3671  3671 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-19 07:41:18.840   927  5993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:802::200e
,09-19 07:41:18.844  3671  5304 I iu.UploadsManager: num queued entries: 0
09-19 07:41:18.844  3671  5304 I iu.UploadsManager: num updated entries: 0
,09-19 07:41:18.845  3671  5304 I iu.SyncManager: NEXT; no task
,09-19 07:41:18.847  3671  3671 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-19 07:41:18.849  3671  3671 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-19 07:41:18.850  5308  5308 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-19 07:41:18.854  5308  5308 D SprintDMHelper: simOperator: 
09-19 07:41:18.854  5308  5308 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-19 07:41:18.886   927  5993 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 19 Sep 2016 11:41:18 GMT], X-Android-Received-Millis=[1474285278886], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474285278862]}
,09-19 07:41:18.887   927  2951 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-19 07:41:18.887   927  2951 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-19 07:41:18.887   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:41:18.888   927  2951 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-19 07:41:20.170   927  2940 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-19 07:41:20.184   927  2951 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:41:20.190  3743  3893 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-19 07:41:20.190  3743  3893 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-19 07:41:21.540   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:41:22.428  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:22.428  5569  5615 I jxcore-log: 
,09-19 07:41:22.429  5569  5615 I jxcore-log: websocket error
09-19 07:41:22.429  5569  5615 I jxcore-log: 
09-19 07:41:22.429  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:22.429  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:22.429  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:22.429  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:22.429  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:22.429  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:22.429  5569  5615 I jxcore-log: 
,09-19 07:41:26.754   927  2951 D ConnectivityService: handlePromptUnvalidated 102
,09-19 07:41:27.516  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:27.516  5569  5615 I jxcore-log: 
,09-19 07:41:27.517  5569  5615 I jxcore-log: websocket error
09-19 07:41:27.517  5569  5615 I jxcore-log: 
09-19 07:41:27.517  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:27.517  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:27.517  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:27.517  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:27.517  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:27.517  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:27.517  5569  5615 I jxcore-log: 
,09-19 07:41:29.570   927  2940 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-19 07:41:32.583  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:32.583  5569  5615 I jxcore-log: 
,09-19 07:41:32.584  5569  5615 I jxcore-log: websocket error
09-19 07:41:32.584  5569  5615 I jxcore-log: 
09-19 07:41:32.584  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:32.584  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:32.584  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:32.584  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:32.584  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:32.584  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:32.584  5569  5615 I jxcore-log: 
,09-19 07:41:37.624  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:37.624  5569  5615 I jxcore-log: 
,09-19 07:41:37.624  5569  5615 I jxcore-log: websocket error
09-19 07:41:37.624  5569  5615 I jxcore-log: 
09-19 07:41:37.625  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:37.625  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:37.625  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:37.625  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:37.625  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:37.625  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:37.625  5569  5615 I jxcore-log: 
,09-19 07:41:40.317   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:41:40.317   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:41:40.865  3092  3092 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-19 07:41:40.905  3092  3092 W PathParser: Points are too far apart 4.030360828967057
,09-19 07:41:40.906  3092  3092 W PathParser: Points are too far apart 4.030360538880159
,09-19 07:41:41.507   927  3751 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@342417 attribute=null, token = android.os.BinderProxy@4d66ec7
,09-19 07:41:41.526  3092  3092 D PhoneStatusBar: disable: < expand icons* alerts system_info* back home recent clock search quick_settings >
,09-19 07:41:42.400  5929  5929 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-19 07:41:42.657  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:42.657  5569  5615 I jxcore-log: 
,09-19 07:41:42.657  5569  5615 I jxcore-log: websocket error
09-19 07:41:42.657  5569  5615 I jxcore-log: 
09-19 07:41:42.657  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:42.657  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:42.657  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:42.657  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:42.657  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:42.657  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:42.657  5569  5615 I jxcore-log: 
,09-19 07:41:47.700  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:47.700  5569  5615 I jxcore-log: 
,09-19 07:41:47.701  5569  5615 I jxcore-log: websocket error
09-19 07:41:47.701  5569  5615 I jxcore-log: 
09-19 07:41:47.701  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:47.701  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:47.701  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:47.701  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:47.701  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:47.701  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:47.701  5569  5615 I jxcore-log: 
,09-19 07:41:52.743  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:52.743  5569  5615 I jxcore-log: 
,09-19 07:41:52.744  5569  5615 I jxcore-log: websocket error
09-19 07:41:52.744  5569  5615 I jxcore-log: 
09-19 07:41:52.744  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:52.744  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:52.744  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:52.744  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:52.744  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:52.744  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:52.744  5569  5615 I jxcore-log: 
,09-19 07:41:55.318   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:56.319   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:57.320   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:57.773  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:41:57.773  5569  5615 I jxcore-log: 
,09-19 07:41:57.773  5569  5615 I jxcore-log: websocket error
09-19 07:41:57.773  5569  5615 I jxcore-log: 
09-19 07:41:57.773  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:41:57.773  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:41:57.773  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:41:57.773  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:57.773  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:41:57.773  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:41:57.773  5569  5615 I jxcore-log: 
,09-19 07:41:58.320   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:41:58.728   927  2940 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 07:41:59.321   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:00.322   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:42:01.070   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=349990, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:42:02.803  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:02.803  5569  5615 I jxcore-log: 
,09-19 07:42:02.804  5569  5615 I jxcore-log: websocket error
09-19 07:42:02.804  5569  5615 I jxcore-log: 
09-19 07:42:02.804  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:02.804  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:02.804  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:02.804  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:02.804  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:02.804  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:02.804  5569  5615 I jxcore-log: 
,09-19 07:42:05.323   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:06.324   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:07.326   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:07.797   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=356717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:42:07.831  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:07.831  5569  5615 I jxcore-log: 
,09-19 07:42:07.832  5569  5615 I jxcore-log: websocket error
09-19 07:42:07.832  5569  5615 I jxcore-log: 
09-19 07:42:07.832  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:07.832  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:07.832  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:07.832  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:07.832  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:07.832  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:07.832  5569  5615 I jxcore-log: 
,09-19 07:42:08.327   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:09.328   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:10.329   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:42:12.869  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:12.869  5569  5615 I jxcore-log: 
,09-19 07:42:12.870  5569  5615 I jxcore-log: websocket error
09-19 07:42:12.870  5569  5615 I jxcore-log: 
09-19 07:42:12.870  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:12.870  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:12.870  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:12.870  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:12.870  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:12.870  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:12.870  5569  5615 I jxcore-log: 
,09-19 07:42:17.908  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:17.908  5569  5615 I jxcore-log: 
,09-19 07:42:17.908  5569  5615 I jxcore-log: websocket error
09-19 07:42:17.908  5569  5615 I jxcore-log: 
09-19 07:42:17.908  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:17.908  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:17.908  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:17.908  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:17.908  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:17.908  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:17.908  5569  5615 I jxcore-log: 
,09-19 07:42:20.330   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:21.331   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:21.984   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:42:22.332   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:22.970  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:22.970  5569  5615 I jxcore-log: 
,09-19 07:42:22.970  5569  5615 I jxcore-log: websocket error
09-19 07:42:22.970  5569  5615 I jxcore-log: 
,09-19 07:42:22.970  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:22.970  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:22.970  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:22.970  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:22.970  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:22.970  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:22.970  5569  5615 I jxcore-log: 
,09-19 07:42:23.334   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:24.335   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:25.023   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:42:25.336   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:42:28.007  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:28.007  5569  5615 I jxcore-log: 
09-19 07:42:28.008  5569  5615 I jxcore-log: websocket error
09-19 07:42:28.008  5569  5615 I jxcore-log: 
09-19 07:42:28.008  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:28.008  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:28.008  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:28.008  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:28.008  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:28.008  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:28.008  5569  5615 I jxcore-log: 
,09-19 07:42:28.039   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:42:33.047  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:33.047  5569  5615 I jxcore-log: 
09-19 07:42:33.047  5569  5615 I jxcore-log: websocket error
09-19 07:42:33.047  5569  5615 I jxcore-log: 
09-19 07:42:33.047  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:33.047  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:33.047  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:33.047  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:33.047  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:33.047  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:33.047  5569  5615 I jxcore-log: 
,09-19 07:42:37.134   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:42:38.083  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:38.083  5569  5615 I jxcore-log: 
,09-19 07:42:38.084  5569  5615 I jxcore-log: websocket error
09-19 07:42:38.084  5569  5615 I jxcore-log: 
09-19 07:42:38.084  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:38.084  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:38.084  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:38.084  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:38.084  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:38.084  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:38.084  5569  5615 I jxcore-log: 
,09-19 07:42:38.735   927  2940 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 07:42:40.169   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:42:40.337   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:41.338   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:42.340   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:43.119  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:43.119  5569  5615 I jxcore-log: 
,09-19 07:42:43.120  5569  5615 I jxcore-log: websocket error
09-19 07:42:43.120  5569  5615 I jxcore-log: 
09-19 07:42:43.120  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:43.120  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:43.120  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:43.120  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:43.120  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:43.120  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:43.120  5569  5615 I jxcore-log: 
,09-19 07:42:43.341   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:44.342   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:42:45.343   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:42:48.155  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:48.155  5569  5615 I jxcore-log: 
,09-19 07:42:48.155  5569  5615 I jxcore-log: websocket error
09-19 07:42:48.155  5569  5615 I jxcore-log: 
09-19 07:42:48.155  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:48.155  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:48.155  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:48.155  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:48.155  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:48.155  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:48.155  5569  5615 I jxcore-log: 
,09-19 07:42:49.637   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=398557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:42:53.194  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:53.194  5569  5615 I jxcore-log: 
,09-19 07:42:53.194  5569  5615 I jxcore-log: websocket error
09-19 07:42:53.194  5569  5615 I jxcore-log: 
09-19 07:42:53.195  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:53.195  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:53.195  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:53.195  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:53.195  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:53.195  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:53.195  5569  5615 I jxcore-log: 
,09-19 07:42:58.184   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:42:58.233  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:42:58.233  5569  5615 I jxcore-log: 
,09-19 07:42:58.234  5569  5615 I jxcore-log: websocket error
09-19 07:42:58.234  5569  5615 I jxcore-log: 
,09-19 07:42:58.234  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:42:58.234  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:42:58.234  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:42:58.234  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:58.234  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:42:58.234  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:42:58.234  5569  5615 I jxcore-log: 
,09-19 07:42:58.736   927  2940 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 07:43:03.281  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:03.281  5569  5615 I jxcore-log: 
,09-19 07:43:03.282  5569  5615 I jxcore-log: websocket error
09-19 07:43:03.282  5569  5615 I jxcore-log: 
,09-19 07:43:03.282  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:03.282  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:03.282  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:03.282  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:03.282  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:03.282  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:03.282  5569  5615 I jxcore-log: 
,09-19 07:43:05.345   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:06.346   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:07.348   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:08.349   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:08.356  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:08.356  5569  5615 I jxcore-log: 
09-19 07:43:08.356  5569  5615 I jxcore-log: websocket error
09-19 07:43:08.356  5569  5615 I jxcore-log: 
09-19 07:43:08.356  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:08.356  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:08.356  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:08.356  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:08.356  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:08.356  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:08.356  5569  5615 I jxcore-log: 
,09-19 07:43:09.350   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:10.351   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:43:13.401  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:13.401  5569  5615 I jxcore-log: 
,09-19 07:43:13.402  5569  5615 I jxcore-log: websocket error
09-19 07:43:13.402  5569  5615 I jxcore-log: 
09-19 07:43:13.402  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:13.402  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:13.402  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:13.402  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:13.402  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:13.402  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:13.402  5569  5615 I jxcore-log: 
,09-19 07:43:15.875  4047  5991 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-19 07:43:18.450  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:18.450  5569  5615 I jxcore-log: 
09-19 07:43:18.450  5569  5615 I jxcore-log: websocket error
09-19 07:43:18.450  5569  5615 I jxcore-log: 
,09-19 07:43:18.451  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:18.451  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:18.451  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:18.451  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:18.451  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:18.451  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:18.451  5569  5615 I jxcore-log: 
,09-19 07:43:23.494  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:23.494  5569  5615 I jxcore-log: 
09-19 07:43:23.494  5569  5615 I jxcore-log: websocket error
09-19 07:43:23.494  5569  5615 I jxcore-log: 
09-19 07:43:23.494  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:23.494  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:23.494  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:23.494  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:23.494  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:23.494  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:23.494  5569  5615 I jxcore-log: 
,09-19 07:43:28.530  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:28.530  5569  5615 I jxcore-log: 
,09-19 07:43:28.531  5569  5615 I jxcore-log: websocket error
09-19 07:43:28.531  5569  5615 I jxcore-log: 
,09-19 07:43:28.531  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:28.531  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:28.531  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:28.531  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:28.531  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:28.531  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:28.531  5569  5615 I jxcore-log: 
,09-19 07:43:33.569  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:33.569  5569  5615 I jxcore-log: 
,09-19 07:43:33.570  5569  5615 I jxcore-log: websocket error
09-19 07:43:33.570  5569  5615 I jxcore-log: 
,09-19 07:43:33.570  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:33.570  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:33.570  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:33.570  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:33.570  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:33.570  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:33.570  5569  5615 I jxcore-log: 
,09-19 07:43:35.352   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:43:35.352   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:43:38.609  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:38.609  5569  5615 I jxcore-log: 
09-19 07:43:38.610  5569  5615 I jxcore-log: websocket error
09-19 07:43:38.610  5569  5615 I jxcore-log: 
,09-19 07:43:38.610  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:38.610  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:38.610  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:38.610  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:38.610  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:38.610  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:38.610  5569  5615 I jxcore-log: 
,09-19 07:43:38.742   927  2940 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 07:43:39.984   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=448904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:43:43.651  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:43.651  5569  5615 I jxcore-log: 
09-19 07:43:43.651  5569  5615 I jxcore-log: websocket error
09-19 07:43:43.651  5569  5615 I jxcore-log: 
09-19 07:43:43.651  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:43.651  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:43.651  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:43.651  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:43.651  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:43.651  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:43.651  5569  5615 I jxcore-log: 
,09-19 07:43:48.637   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:43:48.699  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:48.699  5569  5615 I jxcore-log: 
,09-19 07:43:48.700  5569  5615 I jxcore-log: websocket error
09-19 07:43:48.700  5569  5615 I jxcore-log: 
09-19 07:43:48.700  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:48.700  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:48.700  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:48.700  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:48.700  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:48.700  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:48.700  5569  5615 I jxcore-log: 
,09-19 07:43:53.768  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:53.768  5569  5615 I jxcore-log: 
,09-19 07:43:53.769  5569  5615 I jxcore-log: websocket error
09-19 07:43:53.769  5569  5615 I jxcore-log: 
09-19 07:43:53.769  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:53.769  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:53.769  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:53.769  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:53.769  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:53.769  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:53.769  5569  5615 I jxcore-log: 
,09-19 07:43:55.353   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:56.354   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:57.356   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:58.357   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:43:58.743   927  2940 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 07:43:58.805  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:43:58.805  5569  5615 I jxcore-log: 
,09-19 07:43:58.805  5569  5615 I jxcore-log: websocket error
09-19 07:43:58.805  5569  5615 I jxcore-log: 
,09-19 07:43:58.806  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:43:58.806  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:43:58.806  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:43:58.806  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:58.806  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:43:58.806  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:43:58.806  5569  5615 I jxcore-log: 
,09-19 07:43:59.358   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:00.359   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:44:03.847  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:03.847  5569  5615 I jxcore-log: 
,09-19 07:44:03.848  5569  5615 I jxcore-log: websocket error
09-19 07:44:03.848  5569  5615 I jxcore-log: 
,09-19 07:44:03.848  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:03.848  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:03.848  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:03.848  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:03.848  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:03.848  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:03.848  5569  5615 I jxcore-log: 
,09-19 07:44:05.231   927   947 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-19 07:44:05.233  3865  3865 W Binder_C: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:44:05.233  3865  3865 W Binder_C: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:44:05.241  3655  3655 I Keyboard.Facilitator: onFinishInput()
,09-19 07:44:05.361   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:05.775  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-19 07:44:05.775  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-19 07:44:05.804   927   947 I sensors : batch
,09-19 07:44:05.805   927   947 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-19 07:44:05.807  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f2a9ed3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d357136, 16908290=android.view.AbsSavedState$1@d357136}, android:focusedViewId=100}]}]
09-19 07:44:05.808  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-19 07:44:05.808  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-19 07:44:05.809  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-19 07:44:05.809   927   947 I sensors : activate
09-19 07:44:05.811   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f9d3c3c00
09-19 07:44:05.811   927   945 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-19 07:44:05.811   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-19 07:44:05.815   927  2677 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
09-19 07:44:05.815   927  2677 I hubconnection: sensorhub said: 'activate 7 enable:0'
,09-19 07:44:05.921   509   921 E Netd    : netlink response contains error (No such file or directory)
,09-19 07:44:06.110   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-19 07:44:06.112   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-19 07:44:06.112   927  3061 D SurfaceControl: Excessive delay in setPowerMode(): 302ms
,09-19 07:44:06.117   927   947 I DreamManagerService: Entering dreamland.
,09-19 07:44:06.117   927   947 I PowerManagerService: Dozing...
09-19 07:44:06.117   927   942 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-19 07:44:06.137  3804  3804 W Binder_A: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[38927]" dev="sockfs" ino=38927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:44:06.137  3804  3804 W Binder_A: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[38927]" dev="sockfs" ino=38927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:44:06.140   927  3865 I sensors : batch
09-19 07:44:06.140   927  3865 I sensors : activate
,09-19 07:44:06.144   927  2677 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
09-19 07:44:06.144   927  2677 I hubconnection: sensorhub said: 'activate 21 enable:1'
,09-19 07:44:06.145   927   927 I sensors : activate
09-19 07:44:06.147   514  3009 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-19 07:44:06.149   927  2677 I hubconnection: sensorhub said: 'activate 31 enable:0'
,09-19 07:44:06.160   927  2940 E native  : do suspend true
,09-19 07:44:06.168  3792  4521 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,09-19 07:44:06.168  3792  4521 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-19 07:44:06.169  3792  4521 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-19 07:44:06.169   527  1052 D         : oem-qmi: Connection accepted
09-19 07:44:06.169   527  1052 D         : oem-qmi: Waiting to accept connection
,09-19 07:44:06.171  3792  4521 D         : oem_qmi_lib:output 0
,09-19 07:44:06.171  3792  4521 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-19 07:44:06.236   509   921 D TetherController: Setting IP forward enable = 0
,09-19 07:44:06.362   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:07.129   509   921 D TetherController: Setting IP forward enable = 1
,09-19 07:44:07.363   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:08.364   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:09.365   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:09.632  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:09.632  5569  5615 I jxcore-log: 
,09-19 07:44:09.632  5569  5615 I jxcore-log: websocket error
09-19 07:44:09.632  5569  5615 I jxcore-log: 
,09-19 07:44:09.633  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:09.633  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:09.633  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:09.633  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:09.633  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:09.633  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:09.633  5569  5615 I jxcore-log: 
,09-19 07:44:10.280  3092  3092 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-19 07:44:10.340  3092  3092 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,09-19 07:44:10.356  3092  3092 W PathParser: Points are too far apart 4.030360828967057
09-19 07:44:10.356  3092  3092 W PathParser: Points are too far apart 4.030360538880159
,09-19 07:44:10.365   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:44:17.681  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:17.681  5569  5615 I jxcore-log: 
09-19 07:44:17.682  5569  5615 I jxcore-log: websocket error
09-19 07:44:17.682  5569  5615 I jxcore-log: 
09-19 07:44:17.682  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:17.682  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:17.682  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:17.682  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:17.682  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:17.682  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:17.682  5569  5615 I jxcore-log: 
,09-19 07:44:18.754   927  2940 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 21, 22 -> obsolete
,09-19 07:44:20.366   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:21.367   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:22.368   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:22.737  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:22.737  5569  5615 I jxcore-log: 
,09-19 07:44:22.738  5569  5615 I jxcore-log: websocket error
09-19 07:44:22.738  5569  5615 I jxcore-log: 
09-19 07:44:22.738  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:22.738  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:22.738  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:22.738  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:22.738  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:22.738  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:22.738  5569  5615 I jxcore-log: 
,09-19 07:44:23.370   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:24.371   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:25.372   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:44:27.781  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:27.781  5569  5615 I jxcore-log: 
09-19 07:44:27.782  5569  5615 I jxcore-log: websocket error
09-19 07:44:27.782  5569  5615 I jxcore-log: 
09-19 07:44:27.782  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:27.782  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:27.782  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:27.782  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:27.782  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:27.782  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:27.782  5569  5615 I jxcore-log: 
,09-19 07:44:30.437   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=499357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:44:32.830  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:32.830  5569  5615 I jxcore-log: 
,09-19 07:44:32.831  5569  5615 I jxcore-log: websocket error
09-19 07:44:32.831  5569  5615 I jxcore-log: 
09-19 07:44:32.831  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:32.831  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:32.831  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:32.831  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:32.831  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:32.831  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:32.831  5569  5615 I jxcore-log: 
,09-19 07:44:37.824   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=506744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:44:37.868  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:37.868  5569  5615 I jxcore-log: 
09-19 07:44:37.869  5569  5615 I jxcore-log: websocket error
09-19 07:44:37.869  5569  5615 I jxcore-log: 
,09-19 07:44:37.869  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:37.869  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:37.869  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:37.869  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:37.869  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:37.869  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:37.869  5569  5615 I jxcore-log: 
,09-19 07:44:40.374   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:41.375   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:42.376   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:42.927  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:42.927  5569  5615 I jxcore-log: 
,09-19 07:44:42.927  5569  5615 I jxcore-log: websocket error
09-19 07:44:42.927  5569  5615 I jxcore-log: 
09-19 07:44:42.927  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:42.927  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:42.927  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:42.927  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:42.927  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:42.927  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:42.927  5569  5615 I jxcore-log: 
,09-19 07:44:43.377   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:44.378   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:44:45.378   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:44:47.974  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:47.974  5569  5615 I jxcore-log: 
09-19 07:44:47.975  5569  5615 I jxcore-log: websocket error
09-19 07:44:47.975  5569  5615 I jxcore-log: 
09-19 07:44:47.975  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:47.975  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
,09-19 07:44:47.975  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:47.975  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:47.975  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:47.975  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:47.975  5569  5615 I jxcore-log: 
,09-19 07:44:53.013  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:53.013  5569  5615 I jxcore-log: 
,09-19 07:44:53.014  5569  5615 I jxcore-log: websocket error
09-19 07:44:53.014  5569  5615 I jxcore-log: 
09-19 07:44:53.014  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:53.014  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:53.014  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:53.014  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:53.014  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:53.014  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:53.014  5569  5615 I jxcore-log: 
,09-19 07:44:58.051  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:44:58.051  5569  5615 I jxcore-log: 
09-19 07:44:58.051  5569  5615 I jxcore-log: websocket error
09-19 07:44:58.051  5569  5615 I jxcore-log: 
09-19 07:44:58.051  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:44:58.051  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:44:58.051  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:44:58.051  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:58.051  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:44:58.051  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:44:58.051  5569  5615 I jxcore-log: 
,09-19 07:45:03.113  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:03.113  5569  5615 I jxcore-log: 
09-19 07:45:03.113  5569  5615 I jxcore-log: websocket error
09-19 07:45:03.113  5569  5615 I jxcore-log: 
09-19 07:45:03.113  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:03.113  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:03.113  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:03.113  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:03.113  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:03.113  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:03.113  5569  5615 I jxcore-log: 
,09-19 07:45:05.244  3655  5365 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-19 07:45:05.244  3655  5365 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-19 07:45:05.274  3545  3545 I ConfigService: onCreate
,09-19 07:45:05.380   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:45:06.381   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:45:07.382   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:45:08.155  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:08.155  5569  5615 I jxcore-log: 
,09-19 07:45:08.155  5569  5615 I jxcore-log: websocket error
09-19 07:45:08.155  5569  5615 I jxcore-log: 
,09-19 07:45:08.156  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:08.156  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:08.156  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:08.156  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:08.156  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:08.156  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:08.156  5569  5615 I jxcore-log: 
,09-19 07:45:08.383   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:45:09.384   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:45:10.306  3545  3545 I ConfigService: onDestroy
,09-19 07:45:10.385   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:45:13.199  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:13.199  5569  5615 I jxcore-log: 
,09-19 07:45:13.199  5569  5615 I jxcore-log: websocket error
09-19 07:45:13.199  5569  5615 I jxcore-log: 
09-19 07:45:13.200  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:13.200  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:13.200  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:13.200  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:13.200  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:13.200  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:13.200  5569  5615 I jxcore-log: 
,09-19 07:45:18.243  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:18.243  5569  5615 I jxcore-log: 
,09-19 07:45:18.243  5569  5615 I jxcore-log: websocket error
09-19 07:45:18.243  5569  5615 I jxcore-log: 
09-19 07:45:18.244  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:18.244  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:18.244  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:18.244  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:18.244  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:18.244  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:18.244  5569  5615 I jxcore-log: 
,09-19 07:45:23.293  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:23.293  5569  5615 I jxcore-log: 
09-19 07:45:23.294  5569  5615 I jxcore-log: websocket error
09-19 07:45:23.294  5569  5615 I jxcore-log: 
09-19 07:45:23.294  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:23.294  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:23.294  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:23.294  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:23.294  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:23.294  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:23.294  5569  5615 I jxcore-log: 
,09-19 07:45:28.343  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:28.343  5569  5615 I jxcore-log: 
,09-19 07:45:28.344  5569  5615 I jxcore-log: websocket error
09-19 07:45:28.344  5569  5615 I jxcore-log: 
09-19 07:45:28.344  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:28.344  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:28.344  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:28.344  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:28.344  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:28.344  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:28.344  5569  5615 I jxcore-log: 
,09-19 07:45:33.383  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:33.383  5569  5615 I jxcore-log: 
09-19 07:45:33.383  5569  5615 I jxcore-log: websocket error
09-19 07:45:33.383  5569  5615 I jxcore-log: 
09-19 07:45:33.384  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:33.384  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:33.384  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:33.384  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:33.384  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:33.384  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:33.384  5569  5615 I jxcore-log: 
,09-19 07:45:35.385   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:45:35.386   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:45:38.422  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:38.422  5569  5615 I jxcore-log: 
09-19 07:45:38.423  5569  5615 I jxcore-log: websocket error
09-19 07:45:38.423  5569  5615 I jxcore-log: 
,09-19 07:45:38.423  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:38.423  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:38.423  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:38.423  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:38.423  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:38.423  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:38.423  5569  5615 I jxcore-log: 
,09-19 07:45:43.477  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:43.477  5569  5615 I jxcore-log: 
,09-19 07:45:43.477  5569  5615 I jxcore-log: websocket error
09-19 07:45:43.477  5569  5615 I jxcore-log: 
,09-19 07:45:43.477  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:43.477  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:43.477  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:43.477  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:43.477  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:43.477  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:43.477  5569  5615 I jxcore-log: 
,09-19 07:45:44.784   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=573704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:45:48.515  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:48.515  5569  5615 I jxcore-log: 
,09-19 07:45:48.516  5569  5615 I jxcore-log: websocket error
09-19 07:45:48.516  5569  5615 I jxcore-log: 
09-19 07:45:48.516  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:48.516  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:48.516  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:48.516  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:48.516  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:48.516  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:48.516  5569  5615 I jxcore-log: 
,09-19 07:45:53.504   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=582424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:45:53.553  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:53.553  5569  5615 I jxcore-log: 
,09-19 07:45:53.553  5569  5615 I jxcore-log: websocket error
09-19 07:45:53.553  5569  5615 I jxcore-log: 
09-19 07:45:53.553  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:53.553  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:53.553  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:53.553  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:53.553  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:53.553  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:53.553  5569  5615 I jxcore-log: 
,09-19 07:45:58.789  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:45:58.789  5569  5615 I jxcore-log: 
09-19 07:45:58.789  5569  5615 I jxcore-log: websocket error
09-19 07:45:58.789  5569  5615 I jxcore-log: 
,09-19 07:45:58.790  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:45:58.790  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:45:58.790  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:45:58.790  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:58.790  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:45:58.790  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:45:58.790  5569  5615 I jxcore-log: 
,09-19 07:46:00.477   537  1229 E QC-QMI  : qmi_client [537] 8: failed to locate client data
,09-19 07:46:00.479   521   521 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-19 07:46:00.481   521   521 E QC-QMI  : QMUX qmux_client_id=8 not found in qmux client list, unable to remove
09-19 07:46:00.484   537   537 I Atfwd_Daemon: Stop the daemon....
,09-19 07:46:00.518  6153  6153 I libmdmdetect: ESOC framework not supported
09-19 07:46:00.518  6153  6153 I libmdmdetect: Found internal modem: modem
09-19 07:46:00.519  6153  6153 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-19 07:46:00.513  6153  6153 W ATFWD-daemon: type=1400 audit(0.0:128): avc: denied { read write } for name="diag" dev="tmpfs" ino=11751 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-19 07:46:00.524  6153  6153 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-19 07:46:00.524  6153  6153 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
09-19 07:46:00.525  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:01.526  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:02.528  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:03.529  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:03.835  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:03.835  5569  5615 I jxcore-log: 
,09-19 07:46:03.836  5569  5615 I jxcore-log: websocket error
09-19 07:46:03.836  5569  5615 I jxcore-log: 
09-19 07:46:03.836  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:03.836  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:03.836  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:03.836  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:03.836  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:03.836  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:03.836  5569  5615 I jxcore-log: 
,09-19 07:46:04.530  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:05.530  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:46:08.872  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:08.872  5569  5615 I jxcore-log: 
,09-19 07:46:08.874  5569  5615 I jxcore-log: websocket error
09-19 07:46:08.874  5569  5615 I jxcore-log: 
,09-19 07:46:08.874  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:08.874  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:08.874  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:08.874  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:08.874  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:08.874  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:08.874  5569  5615 I jxcore-log: 
,09-19 07:46:10.531  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:11.532  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:12.533  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:13.534  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:13.930  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:13.930  5569  5615 I jxcore-log: 
09-19 07:46:13.931  5569  5615 I jxcore-log: websocket error
09-19 07:46:13.931  5569  5615 I jxcore-log: 
09-19 07:46:13.931  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:13.931  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:13.931  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:13.931  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:13.931  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:13.931  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:13.931  5569  5615 I jxcore-log: 
,09-19 07:46:14.535  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:15.536  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:46:18.973  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:18.973  5569  5615 I jxcore-log: 
,09-19 07:46:18.973  5569  5615 I jxcore-log: websocket error
09-19 07:46:18.973  5569  5615 I jxcore-log: 
,09-19 07:46:18.973  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:18.973  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:18.973  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:18.973  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:18.973  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:18.973  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:18.973  5569  5615 I jxcore-log: 
,09-19 07:46:24.026  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:24.026  5569  5615 I jxcore-log: 
,09-19 07:46:24.026  5569  5615 I jxcore-log: websocket error
09-19 07:46:24.026  5569  5615 I jxcore-log: 
,09-19 07:46:24.027  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:24.027  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:24.027  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:24.027  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:24.027  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:24.027  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:24.027  5569  5615 I jxcore-log: 
,09-19 07:46:25.537  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:26.538  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:27.539  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:28.540  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:29.081  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:29.081  5569  5615 I jxcore-log: 
,09-19 07:46:29.081  5569  5615 I jxcore-log: websocket error
09-19 07:46:29.081  5569  5615 I jxcore-log: 
,09-19 07:46:29.081  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:29.081  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:29.081  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:29.081  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:29.081  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:29.081  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:29.081  5569  5615 I jxcore-log: 
,09-19 07:46:29.542  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:30.542  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:46:34.123  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:34.123  5569  5615 I jxcore-log: 
09-19 07:46:34.123  5569  5615 I jxcore-log: websocket error
09-19 07:46:34.123  5569  5615 I jxcore-log: 
09-19 07:46:34.123  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:34.123  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:34.123  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:34.123  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:34.123  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:34.123  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:34.123  5569  5615 I jxcore-log: 
,09-19 07:46:35.344   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=624264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:46:39.190  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:39.190  5569  5615 I jxcore-log: 
,09-19 07:46:39.190  5569  5615 I jxcore-log: websocket error
09-19 07:46:39.190  5569  5615 I jxcore-log: 
09-19 07:46:39.191  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:39.191  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:39.191  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:39.191  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:39.191  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:39.191  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:39.191  5569  5615 I jxcore-log: 
,09-19 07:46:44.157   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=633077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:46:44.765  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:44.765  5569  5615 I jxcore-log: 
,09-19 07:46:44.765  5569  5615 I jxcore-log: websocket error
09-19 07:46:44.765  5569  5615 I jxcore-log: 
09-19 07:46:44.765  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:44.765  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:44.765  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:44.765  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:44.765  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:44.765  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:44.765  5569  5615 I jxcore-log: 
,09-19 07:46:45.543  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:46.544  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:47.545  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:48.546  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:49.547  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:46:49.808  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:49.808  5569  5615 I jxcore-log: 
09-19 07:46:49.809  5569  5615 I jxcore-log: websocket error
09-19 07:46:49.809  5569  5615 I jxcore-log: 
,09-19 07:46:49.810  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:49.810  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:49.810  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:49.810  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:49.810  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:49.810  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:49.810  5569  5615 I jxcore-log: 
,09-19 07:46:50.548  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:46:54.913  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:54.913  5569  5615 I jxcore-log: 
,09-19 07:46:54.913  5569  5615 I jxcore-log: websocket error
09-19 07:46:54.913  5569  5615 I jxcore-log: 
,09-19 07:46:54.913  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:54.913  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:54.913  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:54.913  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:54.913  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:54.913  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:54.913  5569  5615 I jxcore-log: 
,09-19 07:46:59.957  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:46:59.957  5569  5615 I jxcore-log: 
,09-19 07:46:59.957  5569  5615 I jxcore-log: websocket error
09-19 07:46:59.957  5569  5615 I jxcore-log: 
09-19 07:46:59.958  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:46:59.958  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:46:59.958  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:46:59.958  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:59.958  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:46:59.958  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:46:59.958  5569  5615 I jxcore-log: 
,09-19 07:47:04.995  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:04.995  5569  5615 I jxcore-log: 
,09-19 07:47:04.995  5569  5615 I jxcore-log: websocket error
09-19 07:47:04.995  5569  5615 I jxcore-log: 
09-19 07:47:04.996  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:04.996  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:04.996  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:04.996  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:04.996  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:04.996  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:04.996  5569  5615 I jxcore-log: 
,09-19 07:47:10.037  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:10.037  5569  5615 I jxcore-log: 
09-19 07:47:10.037  5569  5615 I jxcore-log: websocket error
09-19 07:47:10.037  5569  5615 I jxcore-log: 
,09-19 07:47:10.038  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:10.038  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:10.038  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:10.038  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:10.038  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:10.038  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:10.038  5569  5615 I jxcore-log: 
,09-19 07:47:10.549  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:11.551  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:12.551  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:13.552  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:14.553  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:15.095  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:15.095  5569  5615 I jxcore-log: 
,09-19 07:47:15.095  5569  5615 I jxcore-log: websocket error
09-19 07:47:15.095  5569  5615 I jxcore-log: 
,09-19 07:47:15.095  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:15.095  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:15.095  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:15.095  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:15.095  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:15.095  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:15.095  5569  5615 I jxcore-log: 
,09-19 07:47:15.554  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:47:20.133  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:20.133  5569  5615 I jxcore-log: 
09-19 07:47:20.133  5569  5615 I jxcore-log: websocket error
09-19 07:47:20.133  5569  5615 I jxcore-log: 
09-19 07:47:20.134  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:20.134  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:20.134  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:20.134  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:20.134  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:20.134  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:20.134  5569  5615 I jxcore-log: 
,09-19 07:47:25.827  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:25.827  5569  5615 I jxcore-log: 
09-19 07:47:25.827  5569  5615 I jxcore-log: websocket error
09-19 07:47:25.827  5569  5615 I jxcore-log: 
,09-19 07:47:25.827  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:25.827  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:25.827  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:25.827  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:25.827  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:25.827  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:25.827  5569  5615 I jxcore-log: 
,09-19 07:47:26.544   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=675464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:47:30.873  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:30.873  5569  5615 I jxcore-log: 
,09-19 07:47:30.874  5569  5615 I jxcore-log: websocket error
09-19 07:47:30.874  5569  5615 I jxcore-log: 
09-19 07:47:30.874  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:30.874  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:30.874  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:30.874  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:30.874  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:30.874  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:30.874  5569  5615 I jxcore-log: 
,09-19 07:47:35.863   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=684783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:47:35.906  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:35.906  5569  5615 I jxcore-log: 
,09-19 07:47:35.907  5569  5615 I jxcore-log: websocket error
09-19 07:47:35.907  5569  5615 I jxcore-log: 
,09-19 07:47:35.907  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:35.907  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:35.907  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:35.907  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:35.907  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:35.907  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:35.907  5569  5615 I jxcore-log: 
,09-19 07:47:40.555  6153  6153 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:47:40.555  6153  6153 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:47:40.942  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:40.942  5569  5615 I jxcore-log: 
,09-19 07:47:40.942  5569  5615 I jxcore-log: websocket error
09-19 07:47:40.942  5569  5615 I jxcore-log: 
09-19 07:47:40.943  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:40.943  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:40.943  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:40.943  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:40.943  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:40.943  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:40.943  5569  5615 I jxcore-log: 
,09-19 07:47:45.556  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:45.984  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:45.984  5569  5615 I jxcore-log: 
,09-19 07:47:45.985  5569  5615 I jxcore-log: websocket error
09-19 07:47:45.985  5569  5615 I jxcore-log: 
09-19 07:47:45.985  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:45.985  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:45.985  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:45.985  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:45.985  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:45.985  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:45.985  5569  5615 I jxcore-log: 
,09-19 07:47:46.557  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:47.558  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:48.560  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:49.561  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:50.562  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:47:51.039  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:51.039  5569  5615 I jxcore-log: 
09-19 07:47:51.039  5569  5615 I jxcore-log: websocket error
09-19 07:47:51.039  5569  5615 I jxcore-log: 
,09-19 07:47:51.040  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:51.040  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:51.040  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:51.040  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:51.040  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:51.040  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:51.040  5569  5615 I jxcore-log: 
,09-19 07:47:55.563  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:56.083  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:47:56.083  5569  5615 I jxcore-log: 
,09-19 07:47:56.084  5569  5615 I jxcore-log: websocket error
09-19 07:47:56.084  5569  5615 I jxcore-log: 
09-19 07:47:56.084  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:47:56.084  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:47:56.084  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:47:56.084  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:56.084  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:47:56.084  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:47:56.084  5569  5615 I jxcore-log: 
,09-19 07:47:56.564  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:57.565  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:58.566  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:47:59.567  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:00.568  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:48:01.145  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:01.145  5569  5615 I jxcore-log: 
,09-19 07:48:01.145  5569  5615 I jxcore-log: websocket error
09-19 07:48:01.145  5569  5615 I jxcore-log: 
09-19 07:48:01.145  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:01.145  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:01.145  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:01.145  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:01.145  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:01.145  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:01.145  5569  5615 I jxcore-log: 
,09-19 07:48:06.185  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:06.185  5569  5615 I jxcore-log: 
,09-19 07:48:06.185  5569  5615 I jxcore-log: websocket error
09-19 07:48:06.185  5569  5615 I jxcore-log: 
09-19 07:48:06.186  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:06.186  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:06.186  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:06.186  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:06.186  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:06.186  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:06.186  5569  5615 I jxcore-log: 
,09-19 07:48:10.570  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:11.571  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:11.815  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:11.815  5569  5615 I jxcore-log: 
,09-19 07:48:11.816  5569  5615 I jxcore-log: websocket error
09-19 07:48:11.816  5569  5615 I jxcore-log: 
,09-19 07:48:11.816  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:11.816  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:11.816  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:11.816  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:11.816  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:11.816  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:11.816  5569  5615 I jxcore-log: 
,09-19 07:48:12.572  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:13.573  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:14.575  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:15.575  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:48:16.907  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:16.907  5569  5615 I jxcore-log: 
09-19 07:48:16.908  5569  5615 I jxcore-log: websocket error
09-19 07:48:16.908  5569  5615 I jxcore-log: 
,09-19 07:48:16.908  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:16.908  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:16.908  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:16.908  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:16.908  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:16.908  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:16.908  5569  5615 I jxcore-log: 
,09-19 07:48:17.637   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=726557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:48:21.945  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:21.945  5569  5615 I jxcore-log: 
,09-19 07:48:21.945  5569  5615 I jxcore-log: websocket error
09-19 07:48:21.945  5569  5615 I jxcore-log: 
09-19 07:48:21.946  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:21.946  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:21.946  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:21.946  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:21.946  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:21.946  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:21.946  5569  5615 I jxcore-log: 
,09-19 07:48:26.944   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=735864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:48:26.986  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:26.986  5569  5615 I jxcore-log: 
,09-19 07:48:26.986  5569  5615 I jxcore-log: websocket error
09-19 07:48:26.986  5569  5615 I jxcore-log: 
,09-19 07:48:26.987  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:26.987  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:26.987  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:26.987  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:26.987  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:26.987  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:26.987  5569  5615 I jxcore-log: 
,09-19 07:48:30.577  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:31.578  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:32.024  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:32.024  5569  5615 I jxcore-log: 
,09-19 07:48:32.024  5569  5615 I jxcore-log: websocket error
09-19 07:48:32.024  5569  5615 I jxcore-log: 
,09-19 07:48:32.024  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:32.024  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:32.024  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:32.024  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:32.024  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:32.024  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:32.024  5569  5615 I jxcore-log: 
,09-19 07:48:32.579  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:33.580  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:34.582  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:35.583  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:48:37.064  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:37.064  5569  5615 I jxcore-log: 
,09-19 07:48:37.064  5569  5615 I jxcore-log: websocket error
09-19 07:48:37.064  5569  5615 I jxcore-log: 
09-19 07:48:37.065  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:37.065  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:37.065  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:37.065  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:37.065  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:37.065  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:37.065  5569  5615 I jxcore-log: 
,09-19 07:48:42.102  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:42.102  5569  5615 I jxcore-log: 
09-19 07:48:42.102  5569  5615 I jxcore-log: websocket error
09-19 07:48:42.102  5569  5615 I jxcore-log: 
09-19 07:48:42.103  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:42.103  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:42.103  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:42.103  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:42.103  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:42.103  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:42.103  5569  5615 I jxcore-log: 
,09-19 07:48:47.147  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:47.147  5569  5615 I jxcore-log: 
,09-19 07:48:47.147  5569  5615 I jxcore-log: websocket error
09-19 07:48:47.147  5569  5615 I jxcore-log: 
09-19 07:48:47.147  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:47.147  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:47.147  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:47.147  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:47.147  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:47.147  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:47.147  5569  5615 I jxcore-log: 
,09-19 07:48:52.769  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:52.769  5569  5615 I jxcore-log: 
,09-19 07:48:52.770  5569  5615 I jxcore-log: websocket error
09-19 07:48:52.770  5569  5615 I jxcore-log: 
09-19 07:48:52.770  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:52.770  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:52.770  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:52.770  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:52.770  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:52.770  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:52.770  5569  5615 I jxcore-log: 
,09-19 07:48:55.583  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:56.584  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:57.586  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:57.812  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:48:57.812  5569  5615 I jxcore-log: 
,09-19 07:48:57.812  5569  5615 I jxcore-log: websocket error
09-19 07:48:57.812  5569  5615 I jxcore-log: 
09-19 07:48:57.813  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:48:57.813  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:48:57.813  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:48:57.813  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:57.813  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:48:57.813  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:48:57.813  5569  5615 I jxcore-log: 
,09-19 07:48:58.587  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:48:59.588  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:00.588  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:49:02.903  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:02.903  5569  5615 I jxcore-log: 
,09-19 07:49:02.904  5569  5615 I jxcore-log: websocket error
09-19 07:49:02.904  5569  5615 I jxcore-log: 
09-19 07:49:02.904  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:02.904  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:02.904  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:02.904  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:02.904  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:02.904  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:02.904  5569  5615 I jxcore-log: 
,09-19 07:49:08.730   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=777650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:49:08.948  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:08.948  5569  5615 I jxcore-log: 
09-19 07:49:08.948  5569  5615 I jxcore-log: websocket error
09-19 07:49:08.948  5569  5615 I jxcore-log: 
,09-19 07:49:08.949  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:08.949  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:08.949  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:08.949  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:08.949  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:08.949  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:08.949  5569  5615 I jxcore-log: 
,09-19 07:49:13.930   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=782850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:49:14.043  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:14.043  5569  5615 I jxcore-log: 
,09-19 07:49:14.044  5569  5615 I jxcore-log: websocket error
09-19 07:49:14.044  5569  5615 I jxcore-log: 
,09-19 07:49:14.044  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:14.044  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:14.044  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:14.044  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:14.044  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:14.044  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:14.044  5569  5615 I jxcore-log: 
,09-19 07:49:19.084  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:19.084  5569  5615 I jxcore-log: 
,09-19 07:49:19.084  5569  5615 I jxcore-log: websocket error
09-19 07:49:19.084  5569  5615 I jxcore-log: 
09-19 07:49:19.084  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:19.084  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:19.084  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:19.084  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:19.084  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:19.084  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:19.084  5569  5615 I jxcore-log: 
,09-19 07:49:24.124  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:24.124  5569  5615 I jxcore-log: 
09-19 07:49:24.124  5569  5615 I jxcore-log: websocket error
09-19 07:49:24.124  5569  5615 I jxcore-log: 
,09-19 07:49:24.124  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:24.124  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:24.124  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:24.124  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:24.124  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:24.124  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:24.124  5569  5615 I jxcore-log: 
,09-19 07:49:25.589  6153  6153 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:49:25.589  6153  6153 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:49:29.176  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:29.176  5569  5615 I jxcore-log: 
09-19 07:49:29.176  5569  5615 I jxcore-log: websocket error
09-19 07:49:29.176  5569  5615 I jxcore-log: 
09-19 07:49:29.177  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:29.177  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:29.177  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:29.177  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:29.177  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:29.177  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:29.177  5569  5615 I jxcore-log: 
,09-19 07:49:34.210  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:34.210  5569  5615 I jxcore-log: 
,09-19 07:49:34.210  5569  5615 I jxcore-log: websocket error
09-19 07:49:34.210  5569  5615 I jxcore-log: 
09-19 07:49:34.210  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:34.210  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:34.210  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:34.210  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:34.210  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:34.210  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:34.210  5569  5615 I jxcore-log: 
,09-19 07:49:35.590  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:36.591  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:37.593  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:38.594  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:39.246  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:39.246  5569  5615 I jxcore-log: 
,09-19 07:49:39.246  5569  5615 I jxcore-log: websocket error
09-19 07:49:39.246  5569  5615 I jxcore-log: 
09-19 07:49:39.246  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:39.246  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:39.246  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:39.246  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:39.246  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:39.246  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:39.246  5569  5615 I jxcore-log: 
,09-19 07:49:39.595  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:40.596  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:49:44.285  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:44.285  5569  5615 I jxcore-log: 
09-19 07:49:44.285  5569  5615 I jxcore-log: websocket error
09-19 07:49:44.285  5569  5615 I jxcore-log: 
09-19 07:49:44.285  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:44.285  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:44.285  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:44.285  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:44.285  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:44.285  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:44.285  5569  5615 I jxcore-log: 
,09-19 07:49:45.597  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:46.598  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:47.599  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:48.600  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:49.325  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:49.325  5569  5615 I jxcore-log: 
,09-19 07:49:49.325  5569  5615 I jxcore-log: websocket error
09-19 07:49:49.325  5569  5615 I jxcore-log: 
09-19 07:49:49.326  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:49.326  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:49.326  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:49.326  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:49.326  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:49.326  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:49.326  5569  5615 I jxcore-log: 
,09-19 07:49:49.601  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:49:50.602  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:49:54.371  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:54.371  5569  5615 I jxcore-log: 
09-19 07:49:54.371  5569  5615 I jxcore-log: websocket error
09-19 07:49:54.371  5569  5615 I jxcore-log: 
09-19 07:49:54.372  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:54.372  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:54.372  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:54.372  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:54.372  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:54.372  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:54.372  5569  5615 I jxcore-log: 
,09-19 07:49:55.663   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=824583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:49:59.414  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:49:59.414  5569  5615 I jxcore-log: 
,09-19 07:49:59.414  5569  5615 I jxcore-log: websocket error
09-19 07:49:59.414  5569  5615 I jxcore-log: 
09-19 07:49:59.415  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:49:59.415  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:49:59.415  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:49:59.415  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:59.415  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:49:59.415  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:49:59.415  5569  5615 I jxcore-log: 
,09-19 07:50:00.603  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:01.604  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:02.605  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:03.606  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:04.410   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=833330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:50:04.446  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:04.446  5569  5615 I jxcore-log: 
,09-19 07:50:04.446  5569  5615 I jxcore-log: websocket error
09-19 07:50:04.446  5569  5615 I jxcore-log: 
,09-19 07:50:04.446  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:04.446  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:04.446  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:04.446  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:04.446  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:04.446  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:04.446  5569  5615 I jxcore-log: 
,09-19 07:50:04.607  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:05.608  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:50:09.481  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:09.481  5569  5615 I jxcore-log: 
,09-19 07:50:09.481  5569  5615 I jxcore-log: websocket error
09-19 07:50:09.481  5569  5615 I jxcore-log: 
09-19 07:50:09.482  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:09.482  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:09.482  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:09.482  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:09.482  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:09.482  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:09.482  5569  5615 I jxcore-log: 
,09-19 07:50:14.800  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:14.800  5569  5615 I jxcore-log: 
,09-19 07:50:14.800  5569  5615 I jxcore-log: websocket error
09-19 07:50:14.800  5569  5615 I jxcore-log: 
09-19 07:50:14.801  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:14.801  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:14.801  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:14.801  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:14.801  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:14.801  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:14.801  5569  5615 I jxcore-log: 
,09-19 07:50:19.847  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:19.847  5569  5615 I jxcore-log: 
,09-19 07:50:19.847  5569  5615 I jxcore-log: websocket error
09-19 07:50:19.847  5569  5615 I jxcore-log: 
09-19 07:50:19.847  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:19.847  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:19.847  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:19.847  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:19.847  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:19.847  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:19.847  5569  5615 I jxcore-log: 
,09-19 07:50:20.610  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:21.610  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:22.611  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:23.612  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:24.613  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:24.894  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:24.894  5569  5615 I jxcore-log: 
,09-19 07:50:24.894  5569  5615 I jxcore-log: websocket error
09-19 07:50:24.894  5569  5615 I jxcore-log: 
09-19 07:50:24.894  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:24.894  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:24.894  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:24.894  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:24.894  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:24.894  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:24.894  5569  5615 I jxcore-log: 
,09-19 07:50:25.614  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:50:29.965  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:29.965  5569  5615 I jxcore-log: 
,09-19 07:50:29.965  5569  5615 I jxcore-log: websocket error
09-19 07:50:29.965  5569  5615 I jxcore-log: 
,09-19 07:50:29.966  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:29.966  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:29.966  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:29.966  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:29.966  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:29.966  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:29.966  5569  5615 I jxcore-log: 
,09-19 07:50:35.000  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:35.000  5569  5615 I jxcore-log: 
09-19 07:50:35.000  5569  5615 I jxcore-log: websocket error
09-19 07:50:35.000  5569  5615 I jxcore-log: 
,09-19 07:50:35.000  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:35.000  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:35.000  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:35.000  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:35.000  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:35.000  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:35.000  5569  5615 I jxcore-log: 
,09-19 07:50:40.043  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:40.043  5569  5615 I jxcore-log: 
,09-19 07:50:40.043  5569  5615 I jxcore-log: websocket error
09-19 07:50:40.043  5569  5615 I jxcore-log: 
,09-19 07:50:40.044  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:40.044  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:40.044  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:40.044  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:40.044  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:40.044  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:40.044  5569  5615 I jxcore-log: 
,09-19 07:50:45.100  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:45.100  5569  5615 I jxcore-log: 
,09-19 07:50:45.101  5569  5615 I jxcore-log: websocket error
09-19 07:50:45.101  5569  5615 I jxcore-log: 
09-19 07:50:45.101  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:45.101  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:45.101  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:45.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:45.101  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:45.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:45.101  5569  5615 I jxcore-log: 
,09-19 07:50:45.615  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:46.223   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=875143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:50:46.616  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:47.617  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:48.618  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:49.620  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:50:50.141  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:50.141  5569  5615 I jxcore-log: 
,09-19 07:50:50.141  5569  5615 I jxcore-log: websocket error
09-19 07:50:50.141  5569  5615 I jxcore-log: 
09-19 07:50:50.142  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:50.142  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:50.142  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:50.142  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:50.142  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:50.142  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:50.142  5569  5615 I jxcore-log: 
,09-19 07:50:50.620  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:50:55.130   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=884050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:50:55.190  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:50:55.190  5569  5615 I jxcore-log: 
,09-19 07:50:55.190  5569  5615 I jxcore-log: websocket error
09-19 07:50:55.190  5569  5615 I jxcore-log: 
09-19 07:50:55.190  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:50:55.190  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:50:55.190  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:50:55.190  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:55.190  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:50:55.190  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:50:55.190  5569  5615 I jxcore-log: 
,09-19 07:51:00.767  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:00.767  5569  5615 I jxcore-log: 
09-19 07:51:00.767  5569  5615 I jxcore-log: websocket error
09-19 07:51:00.767  5569  5615 I jxcore-log: 
09-19 07:51:00.768  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:00.768  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:00.768  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:00.768  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:00.768  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:00.768  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:00.768  5569  5615 I jxcore-log: 
,09-19 07:51:05.806  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:05.806  5569  5615 I jxcore-log: 
09-19 07:51:05.806  5569  5615 I jxcore-log: websocket error
09-19 07:51:05.806  5569  5615 I jxcore-log: 
09-19 07:51:05.807  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:05.807  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:05.807  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:05.807  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:05.807  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:05.807  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:05.807  5569  5615 I jxcore-log: 
,09-19 07:51:10.909  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:10.909  5569  5615 I jxcore-log: 
,09-19 07:51:10.909  5569  5615 I jxcore-log: websocket error
09-19 07:51:10.909  5569  5615 I jxcore-log: 
09-19 07:51:10.910  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:10.910  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:10.910  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:10.910  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:10.910  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:10.910  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:10.910  5569  5615 I jxcore-log: 
,09-19 07:51:15.621  6153  6153 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:51:15.621  6153  6153 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:51:15.954  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:15.954  5569  5615 I jxcore-log: 
,09-19 07:51:15.954  5569  5615 I jxcore-log: websocket error
09-19 07:51:15.954  5569  5615 I jxcore-log: 
09-19 07:51:15.954  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:15.954  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:15.954  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:15.954  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:15.954  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:15.954  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:15.954  5569  5615 I jxcore-log: 
,09-19 07:51:21.002  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:21.002  5569  5615 I jxcore-log: 
09-19 07:51:21.003  5569  5615 I jxcore-log: websocket error
09-19 07:51:21.003  5569  5615 I jxcore-log: 
09-19 07:51:21.003  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:21.003  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:21.003  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:21.003  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:21.003  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:21.003  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:21.003  5569  5615 I jxcore-log: 
,09-19 07:51:26.040  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:26.040  5569  5615 I jxcore-log: 
,09-19 07:51:26.041  5569  5615 I jxcore-log: websocket error
09-19 07:51:26.041  5569  5615 I jxcore-log: 
09-19 07:51:26.041  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:26.041  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:26.041  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:26.041  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:26.041  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:26.041  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:26.041  5569  5615 I jxcore-log: 
,09-19 07:51:30.622  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:31.083  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:31.083  5569  5615 I jxcore-log: 
,09-19 07:51:31.083  5569  5615 I jxcore-log: websocket error
09-19 07:51:31.083  5569  5615 I jxcore-log: 
,09-19 07:51:31.083  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:31.083  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:31.083  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:31.083  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:31.083  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:31.083  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:31.083  5569  5615 I jxcore-log: 
,09-19 07:51:31.623  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:32.625  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:33.626  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:34.627  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:35.628  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:51:36.124  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:36.124  5569  5615 I jxcore-log: 
09-19 07:51:36.124  5569  5615 I jxcore-log: websocket error
09-19 07:51:36.124  5569  5615 I jxcore-log: 
,09-19 07:51:36.124  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:36.124  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:36.124  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:36.124  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:36.124  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:36.124  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:36.124  5569  5615 I jxcore-log: 
,09-19 07:51:36.890   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=925810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:51:40.629  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:41.630  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:41.834  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:41.834  5569  5615 I jxcore-log: 
,09-19 07:51:41.835  5569  5615 I jxcore-log: websocket error
09-19 07:51:41.835  5569  5615 I jxcore-log: 
09-19 07:51:41.835  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:41.835  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:41.835  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:41.835  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:41.835  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:41.835  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:41.835  5569  5615 I jxcore-log: 
,09-19 07:51:42.631  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:43.632  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:44.633  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:45.633  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:51:46.157   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=935077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:51:46.878  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:46.878  5569  5615 I jxcore-log: 
,09-19 07:51:46.878  5569  5615 I jxcore-log: websocket error
09-19 07:51:46.878  5569  5615 I jxcore-log: 
,09-19 07:51:46.879  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:46.879  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:46.879  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:46.879  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:46.879  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:46.879  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:46.879  5569  5615 I jxcore-log: 
,09-19 07:51:51.931  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:51.931  5569  5615 I jxcore-log: 
,09-19 07:51:51.931  5569  5615 I jxcore-log: websocket error
09-19 07:51:51.931  5569  5615 I jxcore-log: 
,09-19 07:51:51.931  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:51.931  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:51.931  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:51.931  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:51.931  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:51.931  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:51.931  5569  5615 I jxcore-log: 
,09-19 07:51:55.634  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:56.635  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:56.987  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:51:56.987  5569  5615 I jxcore-log: 
,09-19 07:51:56.988  5569  5615 I jxcore-log: websocket error
09-19 07:51:56.988  5569  5615 I jxcore-log: 
09-19 07:51:56.988  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:51:56.988  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:51:56.988  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:51:56.988  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:56.988  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:51:56.988  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:51:56.988  5569  5615 I jxcore-log: 
,09-19 07:51:57.637  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:58.638  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:51:59.638  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:00.639  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:52:02.028  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:02.028  5569  5615 I jxcore-log: 
,09-19 07:52:02.029  5569  5615 I jxcore-log: websocket error
09-19 07:52:02.029  5569  5615 I jxcore-log: 
09-19 07:52:02.029  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:02.029  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:02.029  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:02.029  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:02.029  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:02.029  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:02.029  5569  5615 I jxcore-log: 
,09-19 07:52:07.070  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:07.070  5569  5615 I jxcore-log: 
,09-19 07:52:07.070  5569  5615 I jxcore-log: websocket error
09-19 07:52:07.070  5569  5615 I jxcore-log: 
,09-19 07:52:07.071  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:07.071  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:07.071  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:07.071  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:07.071  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:07.071  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:07.071  5569  5615 I jxcore-log: 
,09-19 07:52:12.109  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:12.109  5569  5615 I jxcore-log: 
,09-19 07:52:12.110  5569  5615 I jxcore-log: websocket error
09-19 07:52:12.110  5569  5615 I jxcore-log: 
09-19 07:52:12.110  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:12.110  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:12.110  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:12.110  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:12.110  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:12.110  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:12.110  5569  5615 I jxcore-log: 
,09-19 07:52:15.640  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:16.641  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:17.155  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:17.155  5569  5615 I jxcore-log: 
,09-19 07:52:17.157  5569  5615 I jxcore-log: websocket error
09-19 07:52:17.157  5569  5615 I jxcore-log: 
09-19 07:52:17.158  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:17.158  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:17.158  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:17.158  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:17.158  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:17.158  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:17.158  5569  5615 I jxcore-log: 
,09-19 07:52:17.642  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:18.643  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:19.644  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:20.644  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:52:22.217  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:22.217  5569  5615 I jxcore-log: 
,09-19 07:52:22.218  5569  5615 I jxcore-log: websocket error
09-19 07:52:22.218  5569  5615 I jxcore-log: 
,09-19 07:52:22.218  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:22.218  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:22.218  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:22.218  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:22.218  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:22.218  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:22.218  5569  5615 I jxcore-log: 
,09-19 07:52:27.260  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:27.260  5569  5615 I jxcore-log: 
,09-19 07:52:27.260  5569  5615 I jxcore-log: websocket error
09-19 07:52:27.260  5569  5615 I jxcore-log: 
09-19 07:52:27.260  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:27.260  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:27.260  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:27.260  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:27.260  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:27.260  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:27.260  5569  5615 I jxcore-log: 
,09-19 07:52:28.624   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:52:32.313  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:32.313  5569  5615 I jxcore-log: 
,09-19 07:52:32.314  5569  5615 I jxcore-log: websocket error
09-19 07:52:32.314  5569  5615 I jxcore-log: 
09-19 07:52:32.314  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:32.314  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:32.314  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:32.314  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:32.314  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:32.314  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:32.314  5569  5615 I jxcore-log: 
,09-19 07:52:37.290   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=986210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:52:37.345  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:37.345  5569  5615 I jxcore-log: 
,09-19 07:52:37.346  5569  5615 I jxcore-log: websocket error
09-19 07:52:37.346  5569  5615 I jxcore-log: 
,09-19 07:52:37.346  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:37.346  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:37.346  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:37.346  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:37.346  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:37.346  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:37.346  5569  5615 I jxcore-log: 
,09-19 07:52:40.646  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:41.647  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:42.381  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:42.381  5569  5615 I jxcore-log: 
,09-19 07:52:42.382  5569  5615 I jxcore-log: websocket error
09-19 07:52:42.382  5569  5615 I jxcore-log: 
,09-19 07:52:42.382  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:42.382  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:42.382  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:42.382  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:42.382  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:42.382  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:42.382  5569  5615 I jxcore-log: 
,09-19 07:52:42.648  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:43.649  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:44.650  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:52:45.651  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:52:47.438  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:47.438  5569  5615 I jxcore-log: 
,09-19 07:52:47.439  5569  5615 I jxcore-log: websocket error
09-19 07:52:47.439  5569  5615 I jxcore-log: 
09-19 07:52:47.439  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:47.439  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:47.439  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:47.439  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:47.439  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:47.439  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:47.439  5569  5615 I jxcore-log: 
,09-19 07:52:52.481  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:52.481  5569  5615 I jxcore-log: 
09-19 07:52:52.481  5569  5615 I jxcore-log: websocket error
09-19 07:52:52.481  5569  5615 I jxcore-log: 
09-19 07:52:52.481  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:52.481  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:52.481  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:52.481  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:52.481  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:52.481  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:52.481  5569  5615 I jxcore-log: 
,09-19 07:52:57.530  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:52:57.530  5569  5615 I jxcore-log: 
,09-19 07:52:57.531  5569  5615 I jxcore-log: websocket error
09-19 07:52:57.531  5569  5615 I jxcore-log: 
09-19 07:52:57.531  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:52:57.531  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:52:57.531  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:52:57.531  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:57.531  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:52:57.531  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:52:57.531  5569  5615 I jxcore-log: 
,09-19 07:53:02.577  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:02.577  5569  5615 I jxcore-log: 
,09-19 07:53:02.578  5569  5615 I jxcore-log: websocket error
09-19 07:53:02.578  5569  5615 I jxcore-log: 
,09-19 07:53:02.578  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:02.578  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:02.578  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:02.578  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:02.578  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:02.578  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:02.578  5569  5615 I jxcore-log: 
,09-19 07:53:07.621  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:07.621  5569  5615 I jxcore-log: 
,09-19 07:53:07.621  5569  5615 I jxcore-log: websocket error
09-19 07:53:07.621  5569  5615 I jxcore-log: 
09-19 07:53:07.622  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:07.622  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:07.622  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:07.622  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:07.622  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:07.622  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:07.622  5569  5615 I jxcore-log: 
,09-19 07:53:10.651  6153  6153 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:53:10.651  6153  6153 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:53:12.659  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:12.659  5569  5615 I jxcore-log: 
,09-19 07:53:12.659  5569  5615 I jxcore-log: websocket error
09-19 07:53:12.659  5569  5615 I jxcore-log: 
,09-19 07:53:12.660  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:12.660  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:12.660  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:12.660  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:12.660  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:12.660  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:12.660  5569  5615 I jxcore-log: 
,09-19 07:53:17.701  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:17.701  5569  5615 I jxcore-log: 
09-19 07:53:17.702  5569  5615 I jxcore-log: websocket error
09-19 07:53:17.702  5569  5615 I jxcore-log: 
,09-19 07:53:17.702  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:17.702  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:17.702  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:17.702  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:17.702  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:17.702  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:17.702  5569  5615 I jxcore-log: 
,09-19 07:53:19.077   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1027997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:53:22.769  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:22.769  5569  5615 I jxcore-log: 
,09-19 07:53:22.770  5569  5615 I jxcore-log: websocket error
09-19 07:53:22.770  5569  5615 I jxcore-log: 
09-19 07:53:22.771  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:22.771  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:22.771  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:22.771  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:22.771  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:22.771  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:22.771  5569  5615 I jxcore-log: 
,09-19 07:53:27.730   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1036650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:53:27.808  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:27.808  5569  5615 I jxcore-log: 
,09-19 07:53:27.809  5569  5615 I jxcore-log: websocket error
09-19 07:53:27.809  5569  5615 I jxcore-log: 
,09-19 07:53:27.810  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:27.810  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:27.810  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:27.810  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:27.810  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:27.810  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:27.810  5569  5615 I jxcore-log: 
,09-19 07:53:30.653  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:31.654  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:32.654  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:32.876  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:32.876  5569  5615 I jxcore-log: 
,09-19 07:53:32.877  5569  5615 I jxcore-log: websocket error
09-19 07:53:32.877  5569  5615 I jxcore-log: 
09-19 07:53:32.877  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:32.877  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:32.877  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:32.877  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:32.877  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:32.877  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:32.877  5569  5615 I jxcore-log: 
,09-19 07:53:33.655  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:34.656  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:35.657  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:53:37.917  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:37.917  5569  5615 I jxcore-log: 
,09-19 07:53:37.917  5569  5615 I jxcore-log: websocket error
09-19 07:53:37.917  5569  5615 I jxcore-log: 
09-19 07:53:37.917  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:37.917  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:37.917  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:37.917  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:37.917  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:37.917  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:37.917  5569  5615 I jxcore-log: 
,09-19 07:53:40.658  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:41.659  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:42.660  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:42.974  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:42.974  5569  5615 I jxcore-log: 
,09-19 07:53:42.974  5569  5615 I jxcore-log: websocket error
09-19 07:53:42.974  5569  5615 I jxcore-log: 
,09-19 07:53:42.974  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:42.974  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:42.974  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:42.974  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:42.974  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:42.974  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:42.974  5569  5615 I jxcore-log: 
,09-19 07:53:43.661  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:44.662  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:45.662  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:53:48.017  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:48.017  5569  5615 I jxcore-log: 
09-19 07:53:48.017  5569  5615 I jxcore-log: websocket error
09-19 07:53:48.017  5569  5615 I jxcore-log: 
,09-19 07:53:48.018  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:48.018  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:48.018  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:48.018  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:48.018  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:48.018  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:48.018  5569  5615 I jxcore-log: 
,09-19 07:53:53.057  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:53.057  5569  5615 I jxcore-log: 
09-19 07:53:53.057  5569  5615 I jxcore-log: websocket error
09-19 07:53:53.057  5569  5615 I jxcore-log: 
,09-19 07:53:53.058  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:53.058  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:53.058  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:53.058  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:53.058  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:53.058  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:53.058  5569  5615 I jxcore-log: 
,09-19 07:53:55.664  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:56.665  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:57.666  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:58.100  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:53:58.100  5569  5615 I jxcore-log: 
,09-19 07:53:58.101  5569  5615 I jxcore-log: websocket error
09-19 07:53:58.101  5569  5615 I jxcore-log: 
09-19 07:53:58.101  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:53:58.101  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:53:58.101  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:53:58.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:58.101  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:53:58.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:53:58.101  5569  5615 I jxcore-log: 
,09-19 07:53:58.668  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:53:59.668  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:00.669  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:54:03.161  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:03.161  5569  5615 I jxcore-log: 
,09-19 07:54:03.161  5569  5615 I jxcore-log: websocket error
09-19 07:54:03.161  5569  5615 I jxcore-log: 
09-19 07:54:03.161  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:03.161  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:03.161  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:03.161  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:03.161  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:03.161  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:03.161  5569  5615 I jxcore-log: 
,09-19 07:54:08.243  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:08.243  5569  5615 I jxcore-log: 
,09-19 07:54:08.244  5569  5615 I jxcore-log: websocket error
09-19 07:54:08.244  5569  5615 I jxcore-log: 
,09-19 07:54:08.244  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:08.244  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:08.244  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:08.244  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:08.244  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:08.244  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:08.244  5569  5615 I jxcore-log: 
,09-19 07:54:09.530   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1078450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:54:13.290  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:13.290  5569  5615 I jxcore-log: 
,09-19 07:54:13.290  5569  5615 I jxcore-log: websocket error
09-19 07:54:13.290  5569  5615 I jxcore-log: 
,09-19 07:54:13.291  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:13.291  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:13.291  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:13.291  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:13.291  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:13.291  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:13.291  5569  5615 I jxcore-log: 
,09-19 07:54:15.670  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:16.671  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:17.672  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:18.277   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:54:18.320  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:18.320  5569  5615 I jxcore-log: 
,09-19 07:54:18.320  5569  5615 I jxcore-log: websocket error
09-19 07:54:18.320  5569  5615 I jxcore-log: 
09-19 07:54:18.320  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:18.320  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:18.320  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:18.320  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:18.320  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:18.320  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:18.320  5569  5615 I jxcore-log: 
,09-19 07:54:18.673  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:19.675  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:20.675  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:54:23.370  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:23.370  5569  5615 I jxcore-log: 
09-19 07:54:23.370  5569  5615 I jxcore-log: websocket error
09-19 07:54:23.370  5569  5615 I jxcore-log: 
,09-19 07:54:23.371  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:23.371  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:23.371  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:23.371  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:23.371  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:23.371  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:23.371  5569  5615 I jxcore-log: 
,09-19 07:54:28.422  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:28.422  5569  5615 I jxcore-log: 
09-19 07:54:28.423  5569  5615 I jxcore-log: websocket error
09-19 07:54:28.423  5569  5615 I jxcore-log: 
09-19 07:54:28.423  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:28.423  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:28.423  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:28.423  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:28.423  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:28.423  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:28.423  5569  5615 I jxcore-log: 
,09-19 07:54:33.487  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:33.487  5569  5615 I jxcore-log: 
,09-19 07:54:33.488  5569  5615 I jxcore-log: websocket error
09-19 07:54:33.488  5569  5615 I jxcore-log: 
,09-19 07:54:33.488  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:33.488  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:33.488  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:33.488  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:33.488  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:33.488  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:33.488  5569  5615 I jxcore-log: 
,09-19 07:54:38.531  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:38.531  5569  5615 I jxcore-log: 
,09-19 07:54:38.532  5569  5615 I jxcore-log: websocket error
09-19 07:54:38.532  5569  5615 I jxcore-log: 
,09-19 07:54:38.532  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:38.532  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:38.532  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:38.532  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:38.532  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:38.532  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:38.532  5569  5615 I jxcore-log: 
,09-19 07:54:40.677  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:41.678  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:42.679  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:43.574  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:43.574  5569  5615 I jxcore-log: 
,09-19 07:54:43.574  5569  5615 I jxcore-log: websocket error
09-19 07:54:43.574  5569  5615 I jxcore-log: 
09-19 07:54:43.574  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:43.574  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:43.574  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:43.574  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:43.574  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:43.574  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:43.574  5569  5615 I jxcore-log: 
,09-19 07:54:43.680  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:44.680  6153  6153 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:54:45.681  6153  6153 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:54:48.609  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:48.609  5569  5615 I jxcore-log: 
,09-19 07:54:48.610  5569  5615 I jxcore-log: websocket error
09-19 07:54:48.610  5569  5615 I jxcore-log: 
,09-19 07:54:48.610  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:48.610  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:48.610  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:48.610  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:48.610  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:48.610  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:48.610  5569  5615 I jxcore-log: 
,09-19 07:54:53.647  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:53.647  5569  5615 I jxcore-log: 
,09-19 07:54:53.647  5569  5615 I jxcore-log: websocket error
09-19 07:54:53.647  5569  5615 I jxcore-log: 
09-19 07:54:53.647  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:53.647  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:53.647  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:53.647  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:53.647  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:53.647  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:53.647  5569  5615 I jxcore-log: 
,09-19 07:54:57.331  5874  5903 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,09-19 07:54:58.848  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:54:58.848  5569  5615 I jxcore-log: 
,09-19 07:54:58.848  5569  5615 I jxcore-log: websocket error
09-19 07:54:58.848  5569  5615 I jxcore-log: 
09-19 07:54:58.849  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:54:58.849  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:54:58.849  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:54:58.849  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:58.849  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:54:58.849  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:54:58.849  5569  5615 I jxcore-log: 
,09-19 07:55:00.090   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1129010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:55:03.885  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:03.885  5569  5615 I jxcore-log: 
,09-19 07:55:03.885  5569  5615 I jxcore-log: websocket error
09-19 07:55:03.885  5569  5615 I jxcore-log: 
09-19 07:55:03.885  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:03.885  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:03.885  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:03.885  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:03.885  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:03.885  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:03.885  5569  5615 I jxcore-log: 
,09-19 07:55:08.878   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137798, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:55:08.916  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:08.916  5569  5615 I jxcore-log: 
,09-19 07:55:08.916  5569  5615 I jxcore-log: websocket error
09-19 07:55:08.916  5569  5615 I jxcore-log: 
,09-19 07:55:08.916  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:08.916  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:08.916  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:08.916  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:08.916  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:08.916  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:08.916  5569  5615 I jxcore-log: 
,09-19 07:55:10.682  6153  6153 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-19 07:55:10.682  6153  6153 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:55:13.954  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:13.954  5569  5615 I jxcore-log: 
,09-19 07:55:13.955  5569  5615 I jxcore-log: websocket error
09-19 07:55:13.955  5569  5615 I jxcore-log: 
09-19 07:55:13.955  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:13.955  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:13.955  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:13.955  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:13.955  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:13.955  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:13.955  5569  5615 I jxcore-log: 
,09-19 07:55:18.993  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:18.993  5569  5615 I jxcore-log: 
09-19 07:55:18.993  5569  5615 I jxcore-log: websocket error
09-19 07:55:18.993  5569  5615 I jxcore-log: 
,09-19 07:55:18.994  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:18.994  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:18.994  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:18.994  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:18.994  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:18.994  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:18.994  5569  5615 I jxcore-log: 
,09-19 07:55:24.039  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:24.039  5569  5615 I jxcore-log: 
,09-19 07:55:24.039  5569  5615 I jxcore-log: websocket error
09-19 07:55:24.039  5569  5615 I jxcore-log: 
09-19 07:55:24.040  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:24.040  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:24.040  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:24.040  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:24.040  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:24.040  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:24.040  5569  5615 I jxcore-log: 
,09-19 07:55:29.077  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:29.077  5569  5615 I jxcore-log: 
,09-19 07:55:29.077  5569  5615 I jxcore-log: websocket error
09-19 07:55:29.077  5569  5615 I jxcore-log: 
09-19 07:55:29.078  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:29.078  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:29.078  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:29.078  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:29.078  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:29.078  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:29.078  5569  5615 I jxcore-log: 
,09-19 07:55:34.134  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:34.134  5569  5615 I jxcore-log: 
,09-19 07:55:34.135  5569  5615 I jxcore-log: websocket error
09-19 07:55:34.135  5569  5615 I jxcore-log: 
09-19 07:55:34.135  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:34.135  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:34.135  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:34.135  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:34.135  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:34.135  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:34.135  5569  5615 I jxcore-log: 
,09-19 07:55:35.695  6153  6155 E QC-QMI  : qmi_client [6153] 1d: failed to locate client data
,09-19 07:55:35.698   521   521 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,09-19 07:55:35.698   521   521 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-19 07:55:35.704  6153  6153 I Atfwd_Daemon: Stop the daemon....
,09-19 07:55:35.750  6163  6163 W ATFWD-daemon: type=1400 audit(0.0:129): avc: denied { read write } for name="diag" dev="tmpfs" ino=11751 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-19 07:55:35.753  6163  6163 I libmdmdetect: ESOC framework not supported
09-19 07:55:35.754  6163  6163 I libmdmdetect: Found internal modem: modem
09-19 07:55:35.755  6163  6163 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-19 07:55:35.763  6163  6163 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-19 07:55:35.763  6163  6163 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-19 07:55:35.764  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:36.767  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:37.768  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:38.769  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:39.179  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:39.179  5569  5615 I jxcore-log: 
09-19 07:55:39.180  5569  5615 I jxcore-log: websocket error
09-19 07:55:39.180  5569  5615 I jxcore-log: 
,09-19 07:55:39.180  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:39.180  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:39.180  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:39.180  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:39.180  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:39.180  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:39.180  5569  5615 I jxcore-log: 
,09-19 07:55:39.771  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:40.772  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:55:44.226  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:44.226  5569  5615 I jxcore-log: 
09-19 07:55:44.227  5569  5615 I jxcore-log: websocket error
09-19 07:55:44.227  5569  5615 I jxcore-log: 
09-19 07:55:44.227  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:44.227  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:44.227  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:44.227  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:44.227  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:44.227  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:44.227  5569  5615 I jxcore-log: 
,09-19 07:55:45.773  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:46.774  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:47.775  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:48.777  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:49.778  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:55:50.650   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1179570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:55:50.779  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:55:52.264  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:52.264  5569  5615 I jxcore-log: 
,09-19 07:55:52.265  5569  5615 I jxcore-log: websocket error
09-19 07:55:52.265  5569  5615 I jxcore-log: 
09-19 07:55:52.265  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:52.265  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:52.265  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:52.265  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:52.265  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:52.265  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:52.265  5569  5615 I jxcore-log: 
,09-19 07:55:57.264   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1186184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:55:57.301  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:55:57.301  5569  5615 I jxcore-log: 
,09-19 07:55:57.301  5569  5615 I jxcore-log: websocket error
09-19 07:55:57.301  5569  5615 I jxcore-log: 
09-19 07:55:57.302  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:55:57.302  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:55:57.302  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:55:57.302  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:57.302  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:55:57.302  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:55:57.302  5569  5615 I jxcore-log: 
,09-19 07:56:00.780  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:01.781  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:02.783  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:02.848  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:02.848  5569  5615 I jxcore-log: 
,09-19 07:56:02.848  5569  5615 I jxcore-log: websocket error
09-19 07:56:02.848  5569  5615 I jxcore-log: 
09-19 07:56:02.848  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:02.848  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:02.848  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:02.848  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:02.848  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:02.848  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:02.848  5569  5615 I jxcore-log: 
,09-19 07:56:03.784  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:04.785  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:05.397   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1194317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:56:05.785  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:56:07.894  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:07.894  5569  5615 I jxcore-log: 
,09-19 07:56:07.894  5569  5615 I jxcore-log: websocket error
09-19 07:56:07.894  5569  5615 I jxcore-log: 
,09-19 07:56:07.895  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:07.895  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:07.895  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:07.895  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:07.895  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:07.895  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:07.895  5569  5615 I jxcore-log: 
,09-19 07:56:12.890   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1201810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:56:12.931  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:12.931  5569  5615 I jxcore-log: 
,09-19 07:56:12.931  5569  5615 I jxcore-log: websocket error
09-19 07:56:12.931  5569  5615 I jxcore-log: 
09-19 07:56:12.932  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:12.932  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:12.932  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:12.932  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:12.932  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:12.932  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:12.932  5569  5615 I jxcore-log: 
,09-19 07:56:17.970  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:17.970  5569  5615 I jxcore-log: 
09-19 07:56:17.970  5569  5615 I jxcore-log: websocket error
09-19 07:56:17.970  5569  5615 I jxcore-log: 
,09-19 07:56:17.970  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:17.970  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:17.970  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:17.970  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:17.970  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:17.970  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:17.970  5569  5615 I jxcore-log: 
,09-19 07:56:20.787  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:21.024   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1209944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:56:21.788  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:22.789  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:23.012  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:23.012  5569  5615 I jxcore-log: 
,09-19 07:56:23.013  5569  5615 I jxcore-log: websocket error
09-19 07:56:23.013  5569  5615 I jxcore-log: 
,09-19 07:56:23.013  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:23.013  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:23.013  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:23.013  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:23.013  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:23.013  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:23.013  5569  5615 I jxcore-log: 
,09-19 07:56:23.791  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:24.792  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:25.793  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:56:28.010   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1216930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:56:28.047  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:28.047  5569  5615 I jxcore-log: 
,09-19 07:56:28.047  5569  5615 I jxcore-log: websocket error
09-19 07:56:28.047  5569  5615 I jxcore-log: 
09-19 07:56:28.047  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:28.047  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:28.047  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:28.047  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:28.047  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:28.047  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:28.047  5569  5615 I jxcore-log: 
,09-19 07:56:29.183   927  2908 I PowerManagerService: Waking up from dozing (uid 1000)...,
09-19 07:56:29.184   927   927 V KeyguardServiceDelegate: onStartedWakingUp()
,09-19 07:56:29.202   927   947 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
09-19 07:56:29.202   927   947 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@74eef75)
,09-19 07:56:29.204   927   947 I sensors : batch
09-19 07:56:29.204   927   947 I sensors : activate
,09-19 07:56:29.208   383   383 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7f9d3c3c00
,09-19 07:56:29.208   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-19 07:56:29.209   927   945 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
09-19 07:56:29.215   927  2677 I hubconnection: sensorhub said: 'batch 7 flags:0, sampling_rate_Hz:4.00, max_report_latency_us:0'
,09-19 07:56:29.217   927  2677 I hubconnection: sensorhub said: 'activate 7 enable:1'
09-19 07:56:29.213  6171  6171 W mdss_fb0: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 07:56:29.221   927  3865 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,09-19 07:56:29.233   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:56:29.234   927  2940 E native  : do suspend false
,09-19 07:56:29.238   927   927 I sensors : batch
,09-19 07:56:29.238   927   927 I sensors : activate
09-19 07:56:29.238   514  2973 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-19 07:56:29.241   927  2677 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,09-19 07:56:29.242   927  2677 I hubconnection: sensorhub said: 'activate 31 enable:1'
,09-19 07:56:29.252   927  2940 D WifiConfigStore: No blacklist allowed without epno enabled
,09-19 07:56:29.281   927   947 I DisplayPowerController: Unblocked screen on after 78 ms
,09-19 07:56:29.283   927   947 V KeyguardServiceDelegate: onScreenTurnedOn()
09-19 07:56:29.283   927   947 I DreamManagerService: Gently waking up from dream.
,09-19 07:56:29.284   927  3131 I DreamManagerService: Leaving dreamland.
,09-19 07:56:29.284   927   942 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
09-19 07:56:29.285   927  3742 I sensors : activate
,09-19 07:56:29.289   927  2677 I hubconnection: sensorhub said: 'activate 21 enable:0'
,09-19 07:56:29.294  3792  4521 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,09-19 07:56:29.294  3792  4521 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-19 07:56:29.294  3792  4521 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-19 07:56:29.294   527  1052 D         : oem-qmi: Connection accepted
09-19 07:56:29.295   527  1052 D         : oem-qmi: Waiting to accept connection
,09-19 07:56:29.296  3792  4521 D         : oem_qmi_lib:output 0
09-19 07:56:29.296  3792  4521 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-19 07:56:29.309  3092  3092 W PathParser: Points are too far apart 4.030360828967057
09-19 07:56:29.309  3092  3092 W PathParser: Points are too far apart 4.030360538880159
,09-19 07:56:29.366   387   387 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x9 conn_h=0x7fb6f7a000
09-19 07:56:29.366   387   387 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x9: req_h=0x9 msg_id=3: R/W request received
09-19 07:56:29.366   387   387 I rmt_storage: wakelock acquired: 1, error no: 42
09-19 07:56:29.366   387   491 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x9 Unblock worker thread (th_id: 548526879808)
,09-19 07:56:29.375   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,09-19 07:56:29.377  6176  6176 W irq/504-synapti: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 07:56:29.380   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
09-19 07:56:29.380   927  3061 D SurfaceControl: Excessive delay in setPowerMode(): 173ms
,09-19 07:56:29.466   387   491 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x9: req_h=0x9 msg_id=3: Bytes written = 1572864
,09-19 07:56:29.468   387   491 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x9: req_h=0x9 msg_id=3: Send response: res=0 err=0
09-19 07:56:29.468   387   491 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x9 About to block rmt_storage client thread (th_id: 548526879808) wakelock released: 1, error no: 0
09-19 07:56:29.468   387   491 I rmt_storage: 
,09-19 07:56:29.473   387   387 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x9 conn_h=0x7fb6f7a000
,09-19 07:56:30.143  3092  3092 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME RECENT clock SEARCH quick_settings >
,09-19 07:56:30.152  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-19 07:56:30.153  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-19 07:56:30.153  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-19 07:56:30.154  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-19 07:56:30.164   514  2961 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-19 07:56:30.167  3092  3092 D PhoneStatusBar: disable: < expand icons* alerts system_info* back HOME RECENT clock SEARCH quick_settings >
,09-19 07:56:30.177   514  2961 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
,09-19 07:56:30.177   514  2961 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
09-19 07:56:30.177   514  2961 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-19 07:56:30.180  3751  3751 W Binder_8: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:56:30.183   927  3751 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@a6579f7 attribute=android.view.inputmethod.EditorInfo@4686064, token = android.os.BinderProxy@4d66ec7
09-19 07:56:30.180  3751  3751 W Binder_8: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:56:30.184  3655  3655 I Keyboard.Facilitator: onFinishInput()
09-19 07:56:30.184  4047  4047 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
09-19 07:56:30.185  3092  3092 D PhoneStatusBar: disable: < expand icons alerts system_info back home* recent* clock search* quick_settings >
,09-19 07:56:30.190   514  2961 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-19 07:56:30.192   514  2961 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-19 07:56:30.216   927  3775 I ActivityManager: Start proc 6187:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-19 07:56:30.251  6187  6187 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,09-19 07:56:30.321  6187  6201 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,09-19 07:56:30.382  6187  6201 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,09-19 07:56:30.415  6187  6201 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-19 07:56:30.453  6187  6187 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-19 07:56:30.495  6216  6216 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads1567758116.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1567758116.dex
,09-19 07:56:30.534  6216  6216 I dex2oat : dex2oat took 39.966ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1258KB free=1045KB
,09-19 07:56:30.577  6187  6187 W InstanceID/Rpc: Found 10012
,09-19 07:56:30.915   514  2961 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-19 07:56:30.917   514  2961 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-19 07:56:30.925   514  2961 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-19 07:56:31.235   927   939 I UsageStatsService: User[0] Flushing usage stats to disk
,09-19 07:56:33.359  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:33.359  5569  5615 I jxcore-log: 
,09-19 07:56:33.359  5569  5615 I jxcore-log: websocket error
09-19 07:56:33.359  5569  5615 I jxcore-log: 
,09-19 07:56:33.360  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:33.360  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:33.360  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:33.360  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:33.360  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:33.360  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:33.360  5569  5615 I jxcore-log: 
,09-19 07:56:36.143   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1225063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:56:38.389  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:38.389  5569  5615 I jxcore-log: 
09-19 07:56:38.389  5569  5615 I jxcore-log: websocket error
09-19 07:56:38.389  5569  5615 I jxcore-log: 
09-19 07:56:38.389  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:38.389  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:38.389  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:38.389  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:38.389  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:38.389  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:38.389  5569  5615 I jxcore-log: 
,09-19 07:56:43.384   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1232304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:56:43.418  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:43.418  5569  5615 I jxcore-log: 
,09-19 07:56:43.419  5569  5615 I jxcore-log: websocket error
09-19 07:56:43.419  5569  5615 I jxcore-log: 
,09-19 07:56:43.419  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:43.419  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:43.419  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:43.419  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:43.419  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:43.419  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:43.419  5569  5615 I jxcore-log: 
,09-19 07:56:44.339   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:56:45.794  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:46.796  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:47.797  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:48.457  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:48.457  5569  5615 I jxcore-log: 
,09-19 07:56:48.457  5569  5615 I jxcore-log: websocket error
09-19 07:56:48.457  5569  5615 I jxcore-log: 
09-19 07:56:48.458  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:48.458  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:48.458  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:48.458  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:48.458  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:48.458  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:48.458  5569  5615 I jxcore-log: 
,09-19 07:56:48.799  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:49.800  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:56:50.801  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:56:53.421   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:56:53.491  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:53.491  5569  5615 I jxcore-log: 
,09-19 07:56:53.491  5569  5615 I jxcore-log: websocket error
09-19 07:56:53.491  5569  5615 I jxcore-log: 
09-19 07:56:53.491  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:53.491  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:53.491  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:53.491  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:53.491  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:53.491  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:53.491  5569  5615 I jxcore-log: 
,09-19 07:56:56.570   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:56:59.274  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:56:59.274  5569  5615 I jxcore-log: 
09-19 07:56:59.274  5569  5615 I jxcore-log: websocket error
09-19 07:56:59.274  5569  5615 I jxcore-log: 
09-19 07:56:59.274  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:56:59.274  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:56:59.274  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:56:59.274  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:59.274  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:56:59.274  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:56:59.274  5569  5615 I jxcore-log: 
,09-19 07:56:59.456   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:03.517   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1252437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:57:04.337  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:04.337  5569  5615 I jxcore-log: 
,09-19 07:57:04.337  5569  5615 I jxcore-log: websocket error
09-19 07:57:04.337  5569  5615 I jxcore-log: 
09-19 07:57:04.338  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:04.338  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:04.338  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:04.338  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:04.338  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:04.338  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:04.338  5569  5615 I jxcore-log: 
,09-19 07:57:09.377  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:09.377  5569  5615 I jxcore-log: 
,09-19 07:57:09.377  5569  5615 I jxcore-log: websocket error
09-19 07:57:09.377  5569  5615 I jxcore-log: 
09-19 07:57:09.378  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:09.378  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:09.378  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:09.378  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:09.378  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:09.378  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:09.378  5569  5615 I jxcore-log: 
,09-19 07:57:11.573   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:11.717   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:57:14.413  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:14.413  5569  5615 I jxcore-log: 
,09-19 07:57:14.413  5569  5615 I jxcore-log: websocket error
09-19 07:57:14.413  5569  5615 I jxcore-log: 
09-19 07:57:14.414  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:14.414  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:14.414  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:14.414  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:14.414  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:14.414  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:14.414  5569  5615 I jxcore-log: 
,09-19 07:57:14.587   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:15.802  6163  6163 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 07:57:15.802  6163  6163 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:57:19.411   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1268331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:57:19.450  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:19.450  5569  5615 I jxcore-log: 
,09-19 07:57:19.450  5569  5615 I jxcore-log: websocket error
09-19 07:57:19.450  5569  5615 I jxcore-log: 
,09-19 07:57:19.451  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:19.451  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:19.451  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:19.451  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:19.451  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:19.451  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:19.451  5569  5615 I jxcore-log: 
,09-19 07:57:20.804  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:21.805  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:22.807  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:23.808  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:24.488  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:24.488  5569  5615 I jxcore-log: 
09-19 07:57:24.488  5569  5615 I jxcore-log: websocket error
09-19 07:57:24.488  5569  5615 I jxcore-log: 
,09-19 07:57:24.489  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:24.489  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:24.489  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:24.489  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:24.489  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:24.489  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:24.489  5569  5615 I jxcore-log: 
,09-19 07:57:24.809  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:25.810  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:57:26.026  6187  6246 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-19 07:57:26.026  6187  6246 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-19 07:57:26.026  6187  6246 E YouTube : 	at iyz.a(SourceFile:100)
09-19 07:57:26.026  6187  6246 E YouTube : 	at iza.b(SourceFile:178)
09-19 07:57:26.026  6187  6246 E YouTube : 	at cch.a(SourceFile:2101)
09-19 07:57:26.026  6187  6246 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-19 07:57:26.026  6187  6246 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-19 07:57:26.026  6187  6246 E YouTube : 	at evv.run(Unknown Source)
09-19 07:57:26.026  6187  6246 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-19 07:57:26.026  6187  6246 E YouTube : 	at ain.a(SourceFile:117)
09-19 07:57:26.026  6187  6246 E YouTube : 	at ain.get(SourceFile:88)
09-19 07:57:26.026  6187  6246 E YouTube : 	at kdf.get(SourceFile:69)
09-19 07:57:26.026  6187  6246 E YouTube : 	at iyz.a(SourceFile:98)
09-19 07:57:26.026  6187  6246 E YouTube : 	... 5 more
09-19 07:57:26.026  6187  6246 E YouTube : Caused by: ahm
09-19 07:57:26.026  6187  6246 E YouTube : 	at ahr.a(SourceFile:142)
09-19 07:57:26.026  6187  6246 E YouTube : 	at kcq.a(SourceFile:49)
09-19 07:57:26.026  6187  6246 E YouTube : 	at agx.run(SourceFile:112)
,09-19 07:57:26.046   927   937 I ActivityManager: Killing 5444:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-19 07:57:26.706   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:27.557   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1276477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:57:29.528  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:29.528  5569  5615 I jxcore-log: 
,09-19 07:57:29.529  5569  5615 I jxcore-log: websocket error
09-19 07:57:29.529  5569  5615 I jxcore-log: 
09-19 07:57:29.530  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:29.530  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:29.530  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:29.530  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:29.530  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:29.530  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:29.530  5569  5615 I jxcore-log: 
,09-19 07:57:30.185  3655  5365 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-19 07:57:30.185  3655  5365 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-19 07:57:30.214  3545  3545 I ConfigService: onCreate
,09-19 07:57:30.811  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:31.813  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:32.744   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:32.814  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:33.815  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:34.517   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1283437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:57:34.568  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:34.568  5569  5615 I jxcore-log: 
,09-19 07:57:34.569  5569  5615 I jxcore-log: websocket error
09-19 07:57:34.569  5569  5615 I jxcore-log: 
09-19 07:57:34.569  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:34.569  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:34.569  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:34.569  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:34.569  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:34.569  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:34.569  5569  5615 I jxcore-log: 
,09-19 07:57:34.816  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:35.245  3545  3545 I ConfigService: onDestroy
,09-19 07:57:35.817  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:57:40.341  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:40.341  5569  5615 I jxcore-log: 
09-19 07:57:40.342  5569  5615 I jxcore-log: websocket error
09-19 07:57:40.342  5569  5615 I jxcore-log: 
,09-19 07:57:40.342  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:40.342  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:40.342  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:40.342  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:40.342  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:40.342  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:40.342  5569  5615 I jxcore-log: 
,09-19 07:57:42.650   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1291570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:57:44.864   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:45.385  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:45.385  5569  5615 I jxcore-log: 
,09-19 07:57:45.385  5569  5615 I jxcore-log: websocket error
09-19 07:57:45.385  5569  5615 I jxcore-log: 
09-19 07:57:45.385  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:45.385  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:45.385  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:45.385  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:45.385  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:45.385  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:45.385  5569  5615 I jxcore-log: 
,09-19 07:57:45.819  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:46.820  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:47.821  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:48.822  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:49.824  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:57:50.383   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1299304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:57:50.410  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:50.410  5569  5615 I jxcore-log: 
,09-19 07:57:50.411  5569  5615 I jxcore-log: websocket error
09-19 07:57:50.411  5569  5615 I jxcore-log: 
,09-19 07:57:50.411  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:50.411  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:50.411  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:50.411  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:50.411  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:50.411  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:50.411  5569  5615 I jxcore-log: 
,09-19 07:57:50.825  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:57:50.929   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:57:55.447  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:57:55.447  5569  5615 I jxcore-log: 
,09-19 07:57:55.448  5569  5615 I jxcore-log: websocket error
09-19 07:57:55.448  5569  5615 I jxcore-log: 
09-19 07:57:55.448  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:57:55.448  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:57:55.448  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:57:55.448  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:55.448  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:57:55.448  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:57:55.448  5569  5615 I jxcore-log: 
,09-19 07:57:58.517   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1307437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:58:00.014   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:58:00.482  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:00.482  5569  5615 I jxcore-log: 
09-19 07:58:00.483  5569  5615 I jxcore-log: websocket error
09-19 07:58:00.483  5569  5615 I jxcore-log: 
09-19 07:58:00.484  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:00.484  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:00.484  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:00.484  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:00.484  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:00.484  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:00.484  5569  5615 I jxcore-log: 
,09-19 07:58:05.477   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1314397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:58:05.515  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:05.515  5569  5615 I jxcore-log: 
,09-19 07:58:05.515  5569  5615 I jxcore-log: websocket error
09-19 07:58:05.515  5569  5615 I jxcore-log: 
,09-19 07:58:05.515  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:05.515  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:05.515  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:05.515  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:05.515  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:05.515  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:05.515  5569  5615 I jxcore-log: 
,09-19 07:58:05.826  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:06.827  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:07.829  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:08.830  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:09.101   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:58:09.831  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:10.547  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:10.547  5569  5615 I jxcore-log: 
09-19 07:58:10.547  5569  5615 I jxcore-log: websocket error
09-19 07:58:10.547  5569  5615 I jxcore-log: 
09-19 07:58:10.547  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:10.547  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:10.547  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:10.547  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:10.547  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:10.547  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:10.547  5569  5615 I jxcore-log: 
,09-19 07:58:10.832  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 07:58:13.610   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1322530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:58:15.583  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:15.583  5569  5615 I jxcore-log: 
09-19 07:58:15.583  5569  5615 I jxcore-log: websocket error
09-19 07:58:15.583  5569  5615 I jxcore-log: 
,09-19 07:58:15.583  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:15.583  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:15.583  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:15.583  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:15.583  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:15.583  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:15.583  5569  5615 I jxcore-log: 
,09-19 07:58:18.188   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:58:20.570   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1329490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:58:21.295  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:21.295  5569  5615 I jxcore-log: 
,09-19 07:58:21.295  5569  5615 I jxcore-log: websocket error
09-19 07:58:21.295  5569  5615 I jxcore-log: 
09-19 07:58:21.295  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:21.295  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:21.295  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:21.295  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:21.295  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:21.295  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:21.295  5569  5615 I jxcore-log: 
,09-19 07:58:24.236   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:58:26.332  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:26.332  5569  5615 I jxcore-log: 
,09-19 07:58:26.334  5569  5615 I jxcore-log: websocket error
09-19 07:58:26.334  5569  5615 I jxcore-log: 
09-19 07:58:26.334  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:26.334  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:26.334  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:26.334  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:26.334  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:26.334  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:26.334  5569  5615 I jxcore-log: 
,09-19 07:58:29.423   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1338343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:58:30.188  4047  5991 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-19 07:58:30.833  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:31.391  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:31.391  5569  5615 I jxcore-log: 
,09-19 07:58:31.392  5569  5615 I jxcore-log: websocket error
09-19 07:58:31.392  5569  5615 I jxcore-log: 
09-19 07:58:31.392  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:31.392  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:31.392  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:31.392  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:31.392  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:31.392  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:31.392  5569  5615 I jxcore-log: 
,09-19 07:58:31.834  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:32.835  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:33.321   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:58:33.837  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:34.838  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:58:35.839  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 07:58:36.346   927  2951 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-19 07:58:36.356   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:58:36.367   927   947 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-19 07:58:36.374  3655  3655 I Keyboard.Facilitator: onFinishInput()
,09-19 07:58:36.370  3775  3775 W Binder_9: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:58:36.370  3775  3775 W Binder_9: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[21972]" dev="sockfs" ino=21972 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:58:36.418  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:36.418  5569  5615 I jxcore-log: 
,09-19 07:58:36.418  5569  5615 I jxcore-log: websocket error
09-19 07:58:36.418  5569  5615 I jxcore-log: 
09-19 07:58:36.418  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:36.418  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:36.418  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:36.418  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:36.418  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:36.418  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:36.418  5569  5615 I jxcore-log: 
,09-19 07:58:36.916  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-19 07:58:36.917  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-19 07:58:36.946   927   947 I sensors : batch
,09-19 07:58:36.947   927   947 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-19 07:58:36.953   927   947 I sensors : activate
,09-19 07:58:36.953  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f2a9ed3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d357136, 16908290=android.view.AbsSavedState$1@d357136}, android:focusedViewId=100}]}]
,09-19 07:58:36.953  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-19 07:58:36.955   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f9d3c3c00
09-19 07:58:36.955   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-19 07:58:36.955   927   945 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-19 07:58:36.956  5569  5569 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-19 07:58:36.956  5569  5569 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-19 07:58:36.958   927  2677 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,09-19 07:58:36.962   927  2677 I hubconnection: sensorhub said: 'activate 7 enable:0'
,09-19 07:58:37.255   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-19 07:58:37.256   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-19 07:58:37.256   927  3061 D SurfaceControl: Excessive delay in setPowerMode(): 301ms
,09-19 07:58:37.257   927   947 I DreamManagerService: Entering dreamland.
,09-19 07:58:37.258   927   947 I PowerManagerService: Dozing...
09-19 07:58:37.259   927   942 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-19 07:58:37.280  3575  3575 W Binder_6: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[37886]" dev="sockfs" ino=37886 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 07:58:37.280  3575  3575 W Binder_6: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[37886]" dev="sockfs" ino=37886 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 07:58:37.285   927   937 I sensors : batch
09-19 07:58:37.286   927   937 I sensors : activate
,09-19 07:58:37.289   927  2677 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,09-19 07:58:37.290   927  2677 I hubconnection: sensorhub said: 'activate 21 enable:1'
,09-19 07:58:37.290   927   927 I sensors : activate
,09-19 07:58:37.291   514  2972 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-19 07:58:37.293   927  2677 I hubconnection: sensorhub said: 'activate 31 enable:0'
,09-19 07:58:37.302   927  2940 E native  : do suspend true
,09-19 07:58:37.314  3792  4521 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
09-19 07:58:37.314  3792  4521 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,09-19 07:58:37.314  3792  4521 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-19 07:58:37.314   527  1052 D         : oem-qmi: Connection accepted
09-19 07:58:37.315   527  1052 D         : oem-qmi: Waiting to accept connection
,09-19 07:58:37.320  3792  4521 D         : oem_qmi_lib:output 0
,09-19 07:58:37.320  3792  4521 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-19 07:58:41.429  3092  3092 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-19 07:58:41.434  3671  6314 I EventLogService: Aggregate from 1474284407092 (log), 1474284407092 (data)
,09-19 07:58:41.461  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:41.461  5569  5615 I jxcore-log: 
,09-19 07:58:41.461  5569  5615 I jxcore-log: websocket error
09-19 07:58:41.461  5569  5615 I jxcore-log: 
09-19 07:58:41.461  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:41.461  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:41.461  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:41.461  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:41.461  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:41.461  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:41.461  5569  5615 I jxcore-log: 
,09-19 07:58:41.480  3092  3092 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,09-19 07:58:41.500  3092  3092 W PathParser: Points are too far apart 4.030360828967057
09-19 07:58:41.500  3092  3092 W PathParser: Points are too far apart 4.030360538880159
,09-19 07:58:46.490  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:46.490  5569  5615 I jxcore-log: 
,09-19 07:58:46.491  5569  5615 I jxcore-log: websocket error
09-19 07:58:46.491  5569  5615 I jxcore-log: 
09-19 07:58:46.491  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:46.491  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:46.491  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:46.491  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:46.491  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:46.491  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:46.491  5569  5615 I jxcore-log: 
,09-19 07:58:49.610   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1358530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:58:51.456  6187  6308 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-19 07:58:51.456  6187  6308 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-19 07:58:51.456  6187  6308 E YouTube : 	at iyz.a(SourceFile:100)
09-19 07:58:51.456  6187  6308 E YouTube : 	at iza.b(SourceFile:178)
09-19 07:58:51.456  6187  6308 E YouTube : 	at cch.a(SourceFile:2101)
09-19 07:58:51.456  6187  6308 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-19 07:58:51.456  6187  6308 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-19 07:58:51.456  6187  6308 E YouTube : 	at evv.run(Unknown Source)
09-19 07:58:51.456  6187  6308 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-19 07:58:51.456  6187  6308 E YouTube : 	at ain.a(SourceFile:117)
09-19 07:58:51.456  6187  6308 E YouTube : 	at ain.get(SourceFile:88)
09-19 07:58:51.456  6187  6308 E YouTube : 	at kdf.get(SourceFile:69)
09-19 07:58:51.456  6187  6308 E YouTube : 	at iyz.a(SourceFile:98)
09-19 07:58:51.456  6187  6308 E YouTube : 	... 5 more
09-19 07:58:51.456  6187  6308 E YouTube : Caused by: ahm
09-19 07:58:51.456  6187  6308 E YouTube : 	at ahr.a(SourceFile:142)
09-19 07:58:51.456  6187  6308 E YouTube : 	at kcq.a(SourceFile:49)
09-19 07:58:51.456  6187  6308 E YouTube : 	at agx.run(SourceFile:112)
,09-19 07:58:51.537  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:51.537  5569  5615 I jxcore-log: 
,09-19 07:58:51.538  5569  5615 I jxcore-log: websocket error
09-19 07:58:51.538  5569  5615 I jxcore-log: 
09-19 07:58:51.538  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:51.538  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:51.538  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:51.538  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:51.538  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:51.538  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:51.538  5569  5615 I jxcore-log: 
,09-19 07:58:56.516   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1365436, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:58:56.561  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:58:56.561  5569  5615 I jxcore-log: 
,09-19 07:58:56.561  5569  5615 I jxcore-log: websocket error
09-19 07:58:56.561  5569  5615 I jxcore-log: 
09-19 07:58:56.561  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:58:56.561  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:58:56.561  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:58:56.561  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:56.561  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:58:56.561  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:58:56.561  5569  5615 I jxcore-log: 
,09-19 07:59:00.840  6163  6163 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-19 07:59:00.840  6163  6163 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 07:59:02.361  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:02.361  5569  5615 I jxcore-log: 
,09-19 07:59:02.362  5569  5615 I jxcore-log: websocket error
09-19 07:59:02.362  5569  5615 I jxcore-log: 
09-19 07:59:02.362  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:02.362  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:02.362  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:02.362  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:02.362  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:02.362  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:02.362  5569  5615 I jxcore-log: 
,09-19 07:59:04.650   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1373570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:59:07.386  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:07.386  5569  5615 I jxcore-log: 
09-19 07:59:07.386  5569  5615 I jxcore-log: websocket error
09-19 07:59:07.386  5569  5615 I jxcore-log: 
,09-19 07:59:07.386  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:07.386  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:07.386  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:07.386  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:07.386  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:07.386  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:07.386  5569  5615 I jxcore-log: 
,09-19 07:59:10.841  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:11.843  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:12.290   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1381210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:59:12.409  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:12.409  5569  5615 I jxcore-log: 
,09-19 07:59:12.409  5569  5615 I jxcore-log: websocket error
09-19 07:59:12.409  5569  5615 I jxcore-log: 
,09-19 07:59:12.409  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:12.409  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:12.409  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:12.409  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:12.409  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:12.409  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:12.409  5569  5615 I jxcore-log: 
,09-19 07:59:12.844  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:13.845  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:14.847  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:15.847  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 07:59:17.446  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:17.446  5569  5615 I jxcore-log: 
,09-19 07:59:17.447  5569  5615 I jxcore-log: websocket error
09-19 07:59:17.447  5569  5615 I jxcore-log: 
09-19 07:59:17.447  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:17.447  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:17.447  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:17.447  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:17.447  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:17.447  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:17.447  5569  5615 I jxcore-log: 
,09-19 07:59:20.437   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1389357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:59:20.849  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:21.850  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:22.493  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:22.493  5569  5615 I jxcore-log: 
09-19 07:59:22.493  5569  5615 I jxcore-log: websocket error
09-19 07:59:22.493  5569  5615 I jxcore-log: 
09-19 07:59:22.494  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:22.494  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:22.494  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:22.494  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:22.494  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:22.494  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:22.494  5569  5615 I jxcore-log: 
,09-19 07:59:22.851  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:23.853  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:24.854  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:25.855  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 07:59:27.477   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1396397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:59:27.531  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:27.531  5569  5615 I jxcore-log: 
,09-19 07:59:27.532  5569  5615 I jxcore-log: websocket error
09-19 07:59:27.532  5569  5615 I jxcore-log: 
,09-19 07:59:27.532  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:27.532  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:27.532  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:27.532  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:27.532  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:27.532  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:27.532  5569  5615 I jxcore-log: 
,09-19 07:59:32.573  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:32.573  5569  5615 I jxcore-log: 
,09-19 07:59:32.574  5569  5615 I jxcore-log: websocket error
09-19 07:59:32.574  5569  5615 I jxcore-log: 
09-19 07:59:32.574  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:32.574  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:32.574  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:32.574  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:32.574  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:32.574  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:32.574  5569  5615 I jxcore-log: 
,09-19 07:59:35.610   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1404530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:59:35.856  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:36.375  3655  5365 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-19 07:59:36.375  3655  5365 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-19 07:59:36.409  3545  3545 I ConfigService: onCreate
,09-19 07:59:36.857  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:37.610  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:37.610  5569  5615 I jxcore-log: 
09-19 07:59:37.611  5569  5615 I jxcore-log: websocket error
09-19 07:59:37.611  5569  5615 I jxcore-log: 
,09-19 07:59:37.611  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:37.611  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:37.611  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:37.611  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:37.611  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:37.611  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:37.611  5569  5615 I jxcore-log: 
,09-19 07:59:37.858  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:38.860  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:39.861  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:40.861  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 07:59:41.441  3545  3545 I ConfigService: onDestroy
,09-19 07:59:42.597   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1411517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 07:59:42.648  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:42.648  5569  5615 I jxcore-log: 
,09-19 07:59:42.648  5569  5615 I jxcore-log: websocket error
09-19 07:59:42.648  5569  5615 I jxcore-log: 
09-19 07:59:42.649  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:42.649  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:42.649  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:42.649  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:42.649  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:42.649  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:42.649  5569  5615 I jxcore-log: 
,09-19 07:59:47.688  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:47.688  5569  5615 I jxcore-log: 
09-19 07:59:47.688  5569  5615 I jxcore-log: websocket error
09-19 07:59:47.688  5569  5615 I jxcore-log: 
,09-19 07:59:47.689  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:47.689  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:47.689  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:47.689  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:47.689  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:47.689  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:47.689  5569  5615 I jxcore-log: 
,09-19 07:59:52.723  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:52.723  5569  5615 I jxcore-log: 
09-19 07:59:52.724  5569  5615 I jxcore-log: websocket error
09-19 07:59:52.724  5569  5615 I jxcore-log: 
09-19 07:59:52.724  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:52.724  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:52.724  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:52.724  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:52.724  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:52.724  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:52.724  5569  5615 I jxcore-log: 
,09-19 07:59:55.797   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1424717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 07:59:55.864  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:56.865  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:57.760  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 07:59:57.760  5569  5615 I jxcore-log: 
,09-19 07:59:57.760  5569  5615 I jxcore-log: websocket error
09-19 07:59:57.760  5569  5615 I jxcore-log: 
09-19 07:59:57.761  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 07:59:57.761  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 07:59:57.761  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 07:59:57.761  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:57.761  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 07:59:57.761  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 07:59:57.761  5569  5615 I jxcore-log: 
,09-19 07:59:57.866  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:58.867  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 07:59:59.869  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:00:00.870  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 08:00:02.757   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1431677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:00:02.823  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:02.823  5569  5615 I jxcore-log: 
09-19 08:00:02.823  5569  5615 I jxcore-log: websocket error
09-19 08:00:02.823  5569  5615 I jxcore-log: 
09-19 08:00:02.824  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:02.824  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:02.824  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:02.824  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:02.824  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:02.824  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:02.824  5569  5615 I jxcore-log: 
,09-19 08:00:07.864  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:07.864  5569  5615 I jxcore-log: 
,09-19 08:00:07.864  5569  5615 I jxcore-log: websocket error
09-19 08:00:07.864  5569  5615 I jxcore-log: 
09-19 08:00:07.865  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:07.865  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:07.865  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:07.865  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:07.865  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:07.865  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:07.865  5569  5615 I jxcore-log: 
,09-19 08:00:10.944   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1439864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:00:12.906  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:12.906  5569  5615 I jxcore-log: 
,09-19 08:00:12.907  5569  5615 I jxcore-log: websocket error
09-19 08:00:12.907  5569  5615 I jxcore-log: 
09-19 08:00:12.907  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:12.907  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:12.907  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:12.907  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:12.907  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:12.907  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:12.907  5569  5615 I jxcore-log: 
,09-19 08:00:17.890   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1446810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:00:17.939  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:17.939  5569  5615 I jxcore-log: 
,09-19 08:00:17.939  5569  5615 I jxcore-log: websocket error
09-19 08:00:17.939  5569  5615 I jxcore-log: 
,09-19 08:00:17.940  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:17.940  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:17.940  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:17.940  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:17.940  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:17.940  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:17.940  5569  5615 I jxcore-log: 
,09-19 08:00:20.871  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:00:21.873  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:00:22.874  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:00:22.982  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:22.982  5569  5615 I jxcore-log: 
09-19 08:00:22.982  5569  5615 I jxcore-log: websocket error
09-19 08:00:22.982  5569  5615 I jxcore-log: 
09-19 08:00:22.983  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:22.983  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:22.983  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:22.983  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:22.983  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:22.983  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:22.983  5569  5615 I jxcore-log: 
,09-19 08:00:23.876  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:00:24.877  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:00:25.877  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-19 08:00:27.117   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:00:28.024  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:28.024  5569  5615 I jxcore-log: 
,09-19 08:00:28.024  5569  5615 I jxcore-log: websocket error
09-19 08:00:28.024  5569  5615 I jxcore-log: 
09-19 08:00:28.025  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:28.025  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:28.025  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:28.025  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:28.025  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:28.025  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:28.025  5569  5615 I jxcore-log: 
,09-19 08:00:33.010   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1461931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:00:33.061  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:33.061  5569  5615 I jxcore-log: 
,09-19 08:00:33.061  5569  5615 I jxcore-log: websocket error
09-19 08:00:33.061  5569  5615 I jxcore-log: 
09-19 08:00:33.061  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:33.061  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:33.061  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:33.061  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:33.061  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:33.061  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:33.061  5569  5615 I jxcore-log: 
,09-19 08:00:38.100  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:38.100  5569  5615 I jxcore-log: 
,09-19 08:00:38.100  5569  5615 I jxcore-log: websocket error
09-19 08:00:38.100  5569  5615 I jxcore-log: 
09-19 08:00:38.101  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:38.101  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:38.101  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:38.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:38.101  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:38.101  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:38.101  5569  5615 I jxcore-log: 
,09-19 08:00:42.250   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1471170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:00:43.140  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:43.140  5569  5615 I jxcore-log: 
,09-19 08:00:43.140  5569  5615 I jxcore-log: websocket error
09-19 08:00:43.140  5569  5615 I jxcore-log: 
09-19 08:00:43.141  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:43.141  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:43.141  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:43.141  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:43.141  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:43.141  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:43.141  5569  5615 I jxcore-log: 
,09-19 08:00:46.763  6187  6321 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-19 08:00:46.763  6187  6321 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-19 08:00:46.763  6187  6321 E YouTube : 	at iyz.a(SourceFile:100)
09-19 08:00:46.763  6187  6321 E YouTube : 	at iza.b(SourceFile:178)
09-19 08:00:46.763  6187  6321 E YouTube : 	at cch.a(SourceFile:2101)
09-19 08:00:46.763  6187  6321 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-19 08:00:46.763  6187  6321 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-19 08:00:46.763  6187  6321 E YouTube : 	at evv.run(Unknown Source)
09-19 08:00:46.763  6187  6321 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-19 08:00:46.763  6187  6321 E YouTube : 	at ain.a(SourceFile:117)
09-19 08:00:46.763  6187  6321 E YouTube : 	at ain.get(SourceFile:88)
09-19 08:00:46.763  6187  6321 E YouTube : 	at kdf.get(SourceFile:69)
09-19 08:00:46.763  6187  6321 E YouTube : 	at iyz.a(SourceFile:98)
09-19 08:00:46.763  6187  6321 E YouTube : 	... 5 more
09-19 08:00:46.763  6187  6321 E YouTube : Caused by: ahm
09-19 08:00:46.763  6187  6321 E YouTube : 	at ahr.a(SourceFile:142)
09-19 08:00:46.763  6187  6321 E YouTube : 	at kcq.a(SourceFile:49)
09-19 08:00:46.763  6187  6321 E YouTube : 	at agx.run(SourceFile:112)
,09-19 08:00:48.130   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1477050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:00:48.174  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:48.174  5569  5615 I jxcore-log: 
,09-19 08:00:48.174  5569  5615 I jxcore-log: websocket error
09-19 08:00:48.174  5569  5615 I jxcore-log: 
09-19 08:00:48.174  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:48.174  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:48.174  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:48.174  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:48.174  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:48.174  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:48.174  5569  5615 I jxcore-log: 
,09-19 08:00:50.878  6163  6163 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 08:00:50.879  6163  6163 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-19 08:00:53.223  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:53.223  5569  5615 I jxcore-log: 
09-19 08:00:53.223  5569  5615 I jxcore-log: websocket error
09-19 08:00:53.223  5569  5615 I jxcore-log: 
09-19 08:00:53.224  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:53.224  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:53.224  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:53.224  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:53.224  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:53.224  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:53.224  5569  5615 I jxcore-log: 
,09-19 08:00:57.370   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:00:58.278  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:00:58.278  5569  5615 I jxcore-log: 
,09-19 08:00:58.279  5569  5615 I jxcore-log: websocket error
09-19 08:00:58.279  5569  5615 I jxcore-log: 
,09-19 08:00:58.279  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:00:58.279  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:00:58.279  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:00:58.279  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:58.279  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:00:58.279  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:00:58.279  5569  5615 I jxcore-log: 
,09-19 08:01:03.250   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1492170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:01:03.320  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:03.320  5569  5615 I jxcore-log: 
,09-19 08:01:03.320  5569  5615 I jxcore-log: websocket error
09-19 08:01:03.320  5569  5615 I jxcore-log: 
09-19 08:01:03.320  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:03.320  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:03.320  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:03.320  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:03.320  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:03.320  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:03.320  5569  5615 I jxcore-log: 
,09-19 08:01:05.880  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:06.881  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:07.883  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:08.441  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:08.441  5569  5615 I jxcore-log: 
09-19 08:01:08.441  5569  5615 I jxcore-log: websocket error
09-19 08:01:08.441  5569  5615 I jxcore-log: 
09-19 08:01:08.441  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:08.441  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:08.441  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:08.441  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:08.441  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:08.441  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:08.441  5569  5615 I jxcore-log: 
,09-19 08:01:08.884  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:09.886  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:10.887  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-19 08:01:12.490   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1501410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:01:13.491  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:13.491  5569  5615 I jxcore-log: 
,09-19 08:01:13.491  5569  5615 I jxcore-log: websocket error
09-19 08:01:13.491  5569  5615 I jxcore-log: 
,09-19 08:01:13.491  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:13.491  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:13.491  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:13.491  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:13.491  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:13.491  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:13.491  5569  5615 I jxcore-log: 
,09-19 08:01:15.888  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:16.890  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:17.891  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:18.477   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1507397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:01:18.537  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:18.537  5569  5615 I jxcore-log: 
,09-19 08:01:18.538  5569  5615 I jxcore-log: websocket error
09-19 08:01:18.538  5569  5615 I jxcore-log: 
,09-19 08:01:18.540  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:18.540  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:18.540  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:18.540  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:18.540  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:18.540  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:18.540  5569  5615 I jxcore-log: 
,09-19 08:01:18.893  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:19.894  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:20.895  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-19 08:01:23.586  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:23.586  5569  5615 I jxcore-log: 
,09-19 08:01:23.587  5569  5615 I jxcore-log: websocket error
09-19 08:01:23.587  5569  5615 I jxcore-log: 
09-19 08:01:23.587  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:23.587  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:23.587  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:23.587  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:23.587  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:23.587  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:23.587  5569  5615 I jxcore-log: 
,09-19 08:01:27.717   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1516637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:01:28.631  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:28.631  5569  5615 I jxcore-log: 
,09-19 08:01:28.632  5569  5615 I jxcore-log: websocket error
09-19 08:01:28.632  5569  5615 I jxcore-log: 
09-19 08:01:28.632  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:28.632  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:28.632  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:28.632  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:28.632  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:28.632  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:28.632  5569  5615 I jxcore-log: 
,09-19 08:01:30.896  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:31.897  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:32.899  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:33.610   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1522530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:01:33.723  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:33.723  5569  5615 I jxcore-log: 
,09-19 08:01:33.723  5569  5615 I jxcore-log: websocket error
09-19 08:01:33.723  5569  5615 I jxcore-log: 
,09-19 08:01:33.723  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:33.723  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:33.723  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:33.723  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:33.723  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:33.723  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:33.723  5569  5615 I jxcore-log: 
,09-19 08:01:33.900  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:34.901  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:35.902  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-19 08:01:38.895  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:38.895  5569  5615 I jxcore-log: 
,09-19 08:01:38.895  5569  5615 I jxcore-log: websocket error
09-19 08:01:38.895  5569  5615 I jxcore-log: 
09-19 08:01:38.896  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:38.896  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:38.896  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:38.896  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:38.896  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:38.896  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:38.896  5569  5615 I jxcore-log: 
,09-19 08:01:42.864   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1531784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:01:43.966  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:43.966  5569  5615 I jxcore-log: 
09-19 08:01:43.966  5569  5615 I jxcore-log: websocket error
09-19 08:01:43.966  5569  5615 I jxcore-log: 
09-19 08:01:43.967  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:43.967  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:43.967  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:43.967  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:43.967  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:43.967  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:43.967  5569  5615 I jxcore-log: 
,09-19 08:01:48.957   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1537877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:01:49.042  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:49.042  5569  5615 I jxcore-log: 
09-19 08:01:49.042  5569  5615 I jxcore-log: websocket error
09-19 08:01:49.042  5569  5615 I jxcore-log: 
09-19 08:01:49.042  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:49.042  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:49.042  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:49.042  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:49.042  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:49.042  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:49.042  5569  5615 I jxcore-log: 
,09-19 08:01:50.904  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:51.905  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:52.907  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:53.908  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:54.084  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:54.084  5569  5615 I jxcore-log: 
,09-19 08:01:54.085  5569  5615 I jxcore-log: websocket error
09-19 08:01:54.085  5569  5615 I jxcore-log: 
09-19 08:01:54.085  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:54.085  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:54.085  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:54.085  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:54.085  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:54.085  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:54.085  5569  5615 I jxcore-log: 
,09-19 08:01:54.909  6163  6163 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:01:55.910  6163  6163 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-19 08:01:58.277   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1547197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-19 08:01:59.130  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:01:59.130  5569  5615 I jxcore-log: 
,09-19 08:01:59.131  5569  5615 I jxcore-log: websocket error
09-19 08:01:59.131  5569  5615 I jxcore-log: 
09-19 08:01:59.131  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:01:59.131  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:01:59.131  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:01:59.131  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:59.131  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:01:59.131  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:01:59.131  5569  5615 I jxcore-log: 
,09-19 08:02:04.117   927  5994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1553037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-19 08:02:04.189  5569  5615 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-19 08:02:04.189  5569  5615 I jxcore-log: 
09-19 08:02:04.189  5569  5615 I jxcore-log: websocket error
09-19 08:02:04.189  5569  5615 I jxcore-log: 
09-19 08:02:04.189  5569  5615 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-19 08:02:04.189  5569  5615 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-19 08:02:04.189  5569  5615 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-19 08:02:04.189  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:02:04.189  5569  5615 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-19 08:02:04.189  5569  5615 I jxcore-log: emit@events.js:82:1
09-19 08:02:04.189  5569  5615 I jxcore-log: 
,TIME-OUT KILL (timeout was 1400000ms),09-19 08:02:08.797  6324  6324 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 08:02:08.818  6324  6324 D AndroidRuntime: CheckJNI is OFF
09-19 08:02:08.848  6324  6324 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 08:02:08.880  6324  6324 I Radio-JNI: register_android_hardware_Radio DONE
09-19 08:02:08.896  6324  6324 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-19 08:02:08.903   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-19 08:02:08.903   927   940 I ActivityManager: Killing 5569:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-19 08:02:09.007   927  3839 D GraphicsStats: Buffer count: 2
09-19 08:02:09.008   927  3775 I WindowState: WIN DEATH: Window{9f7fcf4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-19 08:02:09.008   927  2950 D WifiService: Client connection lost with reason: 4
09-19 08:02:09.018   927   951 I art     : Starting a blocking GC Explicit
09-19 08:02:09.032   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-19 08:02:09.033   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-19 08:02:09.033   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-19 08:02:09.033   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-19 08:02:09.033   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 08:02:09.033   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:02:09.033   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 08:02:09.033   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-19 08:02:09.034   927   940 I ActivityManager:   Force finishing activity ActivityRecord{d9d6e39 u0 com.test.thalitest/.MainActivity t4}
09-19 08:02:09.042   927  3839 W ActivityManager: Spurious death for ProcessRecord{ece1766 0:com.test.thalitest/u0a77}, curProc for 5569: null
09-19 08:02:09.095   927   951 I art     : Explicit concurrent mark sweep GC freed 20601(1760KB) AllocSpace objects, 18(360KB) LOS objects, 33% free, 29MB/43MB, paused 1.420ms total 77.449ms
09-19 08:02:09.113   927   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-19 08:02:09.117  6324  6324 I art     : System.exit called, status: 0
09-19 08:02:09.117  6324  6324 I AndroidRuntime: VM exiting with result code 0.
09-19 08:02:09.130   927   951 I ActivityManager: Start proc 6334:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-19 08:02:09.131   927   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-19 08:02:09.135   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-19 08:02:09.142  5874  5874 D BluetoothMapAppObserver: onReceive
09-19 08:02:09.142  5874  5874 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-19 08:02:09.145  4047  4186 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-19 08:02:09.148   927  2908 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-19 08:02:09.149  3655  3655 I Keyboard.Facilitator: resetDictionaries() : en_US
09-19 08:02:09.174  3655  6345 I Keyboard.Facilitator.DecoderInitializer: run()
09-19 08:02:09.188  3370  6349 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-19 08:02:09.189  3655  6345 I Decoder : createOrResetDecoder
09-19 08:02:09.199  3792  3792 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-19 08:02:09.224   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-19 08:02:09.233    29    29 W kworker/3:1: type=1400 audit(0.0:138): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 08:02:09.244  3545  3545 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-19 08:02:09.245  3545  3545 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-19 08:02:09.240    29    29 W kworker/3:1: type=1400 audit(0.0:139): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 08:02:09.257    29    29 W kworker/3:1: type=1400 audit(0.0:140): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-19 08:02:09.289  3671  6354 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-19 08:02:09.289  3671  6354 D AccountUtils: Clearing selected account for com.test.thalitest
09-19 08:02:09.293  3545  3545 I ConfigService: onCreate
09-19 08:02:09.301  3370  3394 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj53798A96A) - 
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-19 08:02:09.303  3545  6357 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-19 08:02:09.303  3545  6357 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-19 08:02:09.305  3545  6357 W SQLiteOpenHelper: Opened config.db in read-only mode
09-19 08:02:09.314  3655  6345 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-19 08:02:09.331  3671  6354 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-19 08:02:09.341   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-19 08:02:09.341   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
