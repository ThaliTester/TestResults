#### Test 85046911f11c404_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 06:25:53.712   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 06:25:54.714   537   537 I ServiceManager: Waiting for service AtCmdFwd...
09-22 06:25:55.211  5418  5418 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 06:25:55.217  5418  5418 D AndroidRuntime: CheckJNI is OFF
09-22 06:25:55.245  5418  5418 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 06:25:55.277  5418  5418 I Radio-JNI: register_android_hardware_Radio DONE
09-22 06:25:55.293  5418  5418 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 06:25:55.308   925  3426 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 06:25:55.350   925  3426 I ActivityManager: Start proc 5427:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 06:25:55.355  5418  5418 D AndroidRuntime: Shutting down VM
,09-22 06:25:55.693   925  3090 I WindowManager: Screenshot max retries 4 of Token{54d6da5 ActivityRecord{9e75f9c u0 com.test.thalitest/.MainActivity t2}} appWin=Window{de60634 u0 Starting com.test.thalitest} drawState=2
,09-22 06:25:55.714   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-22 06:25:55.769  5427  5427 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-22 06:25:55.799  5427  5427 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-22 06:25:55.871  5427  5427 I LibraryLoader: Time to load native libraries: 66 ms (timestamps 8645-8711)
,09-22 06:25:55.872  5427  5427 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-22 06:25:55.906  5427  5427 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d48dfb5}
,09-22 06:25:55.906  5427  5427 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 06:25:55.907  5427  5427 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-22 06:25:55.912  5427  5427 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-22 06:25:55.914  5427  5427 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-22 06:25:55.963  5427  5427 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-22 06:25:55.979  5427  5427 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 06:25:55.979  5427  5427 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-22 06:25:55.979  5427  5427 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 06:25:55.979  5427  5427 I Adreno  : Build Date                       : 12/06/15
09-22 06:25:55.979  5427  5427 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 06:25:55.979  5427  5427 I Adreno  : Local Branch                     : mybranch17112971
09-22 06:25:55.979  5427  5427 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 06:25:55.979  5427  5427 I Adreno  : Remote Branch                    : NONE
09-22 06:25:55.979  5427  5427 I Adreno  : Reconstruct Branch               : NOTHING
,09-22 06:25:56.038   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e0fe7cc:true
,09-22 06:25:56.072   404   404 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22319]" dev="sockfs" ino=22319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 06:25:56.072   404   404 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22319]" dev="sockfs" ino=22319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:25:56.087  5427  5427 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-22 06:25:56.097  5427  5427 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-22 06:25:56.125   404   404 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32177]" dev="sockfs" ino=32177 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-22 06:25:56.125   404   404 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32177]" dev="sockfs" ino=32177 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 06:25:56.129  5427  5464 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-22 06:25:56.132  3446  3446 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14135]" dev="sockfs" ino=14135 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 06:25:56.132  3446  3446 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14135]" dev="sockfs" ino=14135 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-22 06:25:56.137  5427  5451 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-22 06:25:56.165  5427  5464 I OpenGLRenderer: Initialized EGL, version 1.4
,09-22 06:25:56.254   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +559ms (total +932ms)
,09-22 06:25:56.282  5427  5427 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5427
,09-22 06:25:56.389  5427  5427 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 06:25:56.612  5427  5467 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -565180112
,09-22 06:25:56.631  5427  5467 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 06:25:56.631  5427  5467 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 06:25:56.631  5427  5467 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 06:25:56.631  5427  5467 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 06:25:56.631  5427  5467 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-22 06:25:56.631  5427  5467 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea7c362 added. We now have 1 listener(s)
,09-22 06:25:56.634  5427  5467 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-22 06:25:56.635  5427  5467 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 06:25:56.635  5427  5467 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 06:25:56.636  5427  5467 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-22 06:25:56.639  5427  5467 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df74429 added. We now have 1 listener(s)
09-22 06:25:56.639  5427  5467 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 06:25:56.648   925  2889 D WifiService: New client listening to asynchronous messages
,09-22 06:25:56.649  5427  5467 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 06:25:56.649  5427  5467 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 06:25:56.649  5427  5467 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-22 06:25:56.649  5427  5467 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 06:25:56.649  5427  5467 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-22 06:25:56.651  5427  5467 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 06:25:56.651  5427  5467 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-22 06:25:56.657  5427  5467 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:25:56.657  5427  5467 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 06:25:56.657  5427  5467 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 06:25:56.657  5427  5467 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 06:25:56.658  5427  5467 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-22 06:25:56.659  5427  5427 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:25:56.663  5427  5427 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 06:25:56.684  5427  5427 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-22 06:25:57.414  5427  5436 I art     : Background sticky concurrent mark sweep GC freed 78227(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 1.893ms total 265.116ms
,09-22 06:25:57.528  5427  5473 W jxcore-log: Initializing JXcore engine
,09-22 06:25:57.528  5427  5473 W jxcore-log: JXcore engine is ready
,09-22 06:25:57.585  5473  5473 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12606 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-22 06:25:57.585  5473  5473 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13654]" dev="sockfs" ino=13654 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 06:25:57.585  5473  5473 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 06:25:57.585  5473  5473 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32154]" dev="sockfs" ino=32154 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-22 06:25:57.601  5427  5473 W jxcore-log: Starting JXcore engine
,09-22 06:25:57.661  5427  5473 W jxcore-log: Platform android
09-22 06:25:57.661  5427  5473 W jxcore-log: 
,09-22 06:25:57.661  5427  5473 W jxcore-log: Process ARCH arm
09-22 06:25:57.661  5427  5473 W jxcore-log: 
,09-22 06:25:57.753  5427  5473 I jxcore-log: JXcore Cordova bridge is ready!
09-22 06:25:57.753  5427  5473 I jxcore-log: 
,09-22 06:25:57.753  5427  5473 W jxcore-log: JXcore engine is started
,09-22 06:25:57.760  5427  5467 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-22 06:25:57.766  5427  5427 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 06:26:04.491  5427  5473 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 06:26:04.491  5427  5473 I jxcore-log: 
,09-22 06:26:04.493  5427  5473 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 06:26:04.493  5427  5473 I jxcore-log: 
,09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 06:26:04.497  5427  5473 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 06:26:04.498  5427  5473 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 06:26:04.500  5427  5473 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 06:26:04.500  5427  5473 I jxcore-log: 
,09-22 06:26:04.501  5427  5473 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 06:26:04.501  5427  5473 I jxcore-log: 
,09-22 06:26:04.853  5427  5473 D executeNativeTests: Running unit tests
,09-22 06:26:04.865  5427  5473 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-22 06:26:04.865  5427  5473 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-22 06:26:04.865  5427  5473 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-22 06:26:04.865  5427  5473 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 06:26:04.865  5427  5473 D com.test.thalitest.ThaliTestRunner: Total duration: 2 ms
09-22 06:26:04.866  5427  5473 I jxcore-log: *Native tests were executed*
09-22 06:26:04.866  5427  5473 I jxcore-log: 
,09-22 06:26:04.866  5427  5473 I jxcore-log: Total number of executed tests:  1
09-22 06:26:04.866  5427  5473 I jxcore-log: 
,09-22 06:26:04.867  5427  5473 I jxcore-log: Number of passed tests:  1
09-22 06:26:04.867  5427  5473 I jxcore-log: 
,09-22 06:26:04.867  5427  5473 I jxcore-log: Number of failed tests:  0
09-22 06:26:04.867  5427  5473 I jxcore-log: 
09-22 06:26:04.867  5427  5473 I jxcore-log: Number of ignored tests:  0
09-22 06:26:04.867  5427  5473 I jxcore-log: 
09-22 06:26:04.867  5427  5473 I jxcore-log: Total duration:  2
09-22 06:26:04.867  5427  5473 I jxcore-log: 
09-22 06:26:04.867  5427  5473 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 06:26:04.867  5427  5473 I jxcore-log: 
09-22 06:26:04.869  5427  5473 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 06:26:04.869  5427  5473 I jxcore-log: 
,09-22 06:26:04.893  5427  5427 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-22 06:26:05.359  5474  5474 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 06:26:05.364  5474  5474 D AndroidRuntime: CheckJNI is OFF
,09-22 06:26:05.391  5474  5474 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 06:26:05.419  5474  5474 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 06:26:05.434  5474  5474 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 06:26:05.443   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-22 06:26:05.443   925   938 I ActivityManager: Killing 5427:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-22 06:26:05.532   925  3090 I WindowState: WIN DEATH: Window{ce2c10b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 06:26:05.532   925  2889 D WifiService: Client connection lost with reason: 4
09-22 06:26:05.532   925  3096 D GraphicsStats: Buffer count: 2
,09-22 06:26:05.581   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-22 06:26:05.581   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-22 06:26:05.583   925   948 I art     : Starting a blocking GC Explicit
09-22 06:26:05.583   925   938 E ActivityManager: Failure starting process com.test.thalitest
09-22 06:26:05.583   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-22 06:26:05.583   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:26:05.583   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:26:05.583   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 06:26:05.583   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 06:26:05.584   925   938 I ActivityManager:   Force finishing activity ActivityRecord{9e75f9c u0 com.test.thalitest/.MainActivity t2}
,09-22 06:26:05.589   925  3428 W ActivityManager: Spurious death for ProcessRecord{f5367e 0:com.test.thalitest/u0a77}, curProc for 5427: null
,09-22 06:26:05.594   925   943 W WindowManager: Attempted to add application window with unknown token Token{54d6da5 ActivityRecord{9e75f9c u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-22 06:26:05.595   925   943 W WindowManager: Token{54d6da5 ActivityRecord{9e75f9c u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{54d6da5 ActivityRecord{9e75f9c u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-22 06:26:05.595   925   943 W WindowManager: view not successfully added to wm, removing view
09-22 06:26:05.595   925   943 W WindowManager: Exception when adding starting window
09-22 06:26:05.595   925   943 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{6384d71 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 06:26:05.595   925   943 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-22 06:26:05.595   925   943 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-22 06:26:05.595   925   943 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-22 06:26:05.595   925   943 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-22 06:26:05.595   925   943 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-22 06:26:05.595   925   943 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:26:05.595   925   943 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:26:05.595   925   943 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 06:26:05.595   925   943 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 06:26:05.667   925   948 I art     : Explicit concurrent mark sweep GC freed 53110(3MB) AllocSpace objects, 19(504KB) LOS objects, 33% free, 28MB/43MB, paused 1.660ms total 84.344ms
,09-22 06:26:05.688   925   948 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-22 06:26:05.691  5474  5474 I art     : System.exit called, status: 0
,09-22 06:26:05.691  5474  5474 I AndroidRuntime: VM exiting with result code 0.
,09-22 06:26:05.695   925   948 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-22 06:26:05.702   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-22 06:26:05.706  4329  4329 D BluetoothMapAppObserver: onReceive
09-22 06:26:05.706  4329  4329 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-22 06:26:05.710  3320  3320 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-22 06:26:05.712  3512  3857 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-22 06:26:05.718   925  2861 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-22 06:26:05.739  3320  5485 I Keyboard.Facilitator.DecoderInitializer: run()
,09-22 06:26:05.745  3405  3405 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-22 06:26:05.759  3303  5487 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-22 06:26:05.761  3320  5485 I Decoder : createOrResetDecoder
,09-22 06:26:05.786   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-22 06:26:05.799    28    28 W kworker/1:1: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:26:05.802  3491  3491 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-22 06:26:05.802  3491  3491 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-22 06:26:05.802    28    28 W kworker/1:1: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:26:05.822  3811  5491 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-22 06:26:05.822  3811  5491 D AccountUtils: Clearing selected account for com.test.thalitest
,09-22 06:26:05.824  3491  3491 I ConfigService: onCreate
,09-22 06:26:05.822    28    28 W kworker/1:1: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 06:26:05.829  3491  5492 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-22 06:26:05.848  3320  5485 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-22 06:26:05.894  3811  5491 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-22 06:26:05.904  3303  3336 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjC985BA98F) - 
,--------- beginning of crash
09-22 06:26:05.934  3303  3336 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-22 06:26:05.934  3303  3336 E AndroidRuntime: Process: android.process.acore, PID: 3303
09-22 06:26:05.934  3303  3336 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	,at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 06:26:05.934  3303  3336 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 06:26:05.953  3303  3336 I Process : Sending signal. PID: 3303 SIG: 9
,09-22 06:26:06.197   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
