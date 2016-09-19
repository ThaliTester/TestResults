#### Test 8504691185ffef1_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-19 08:38:40.891   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-19 08:38:40.892   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-19 08:38:41.360  5599  5599 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-19 08:38:41.366  5599  5599 D AndroidRuntime: CheckJNI is OFF
09-19 08:38:41.394  5599  5599 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-19 08:38:41.425  5599  5599 I Radio-JNI: register_android_hardware_Radio DONE
09-19 08:38:41.440  5599  5599 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-19 08:38:41.445   928  3555 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-19 08:38:41.490   928  3555 I ActivityManager: Start proc 5608:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-19 08:38:41.514  5599  5599 D AndroidRuntime: Shutting down VM
,09-19 08:38:41.835   928  3832 I WindowManager: Screenshot max retries 4 of Token{538a806 ActivityRecord{e6572e1 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{2809d19 u0 Starting com.test.thalitest} drawState=2
,09-19 08:38:41.901  5608  5608 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-19 08:38:41.935  5608  5608 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-19 08:38:41.960  5608  5608 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 9850-9868)
,09-19 08:38:41.960  5608  5608 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-19 08:38:41.981  5608  5608 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {94358e0}
,09-19 08:38:41.982  5608  5608 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-19 08:38:41.982  5608  5608 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-19 08:38:41.987  5608  5608 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-19 08:38:41.989  5608  5608 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-19 08:38:42.025  5608  5608 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-19 08:38:42.046  5608  5608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-19 08:38:42.046  5608  5608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-19 08:38:42.046  5608  5608 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-19 08:38:42.046  5608  5608 I Adreno  : Build Date                       : 12/06/15
09-19 08:38:42.046  5608  5608 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-19 08:38:42.046  5608  5608 I Adreno  : Local Branch                     : mybranch17112971
09-19 08:38:42.046  5608  5608 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-19 08:38:42.046  5608  5608 I Adreno  : Remote Branch                    : NONE
09-19 08:38:42.046  5608  5608 I Adreno  : Reconstruct Branch               : NOTHING
,09-19 08:38:42.092   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a772b24:true
,09-19 08:38:42.126   734   734 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25383]" dev="sockfs" ino=25383 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 08:38:42.126   734   734 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25383]" dev="sockfs" ino=25383 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 08:38:42.140  5608  5608 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-19 08:38:42.148  5608  5608 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-19 08:38:42.175  5608  5645 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-19 08:38:42.173   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31946]" dev="sockfs" ino=31946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-19 08:38:42.173   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31946]" dev="sockfs" ino=31946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-19 08:38:42.176  3555  3555 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[25395]" dev="sockfs" ino=25395 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-19 08:38:42.176  3555  3555 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[25395]" dev="sockfs" ino=25395 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-19 08:38:42.182  5608  5632 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-19 08:38:42.203  5608  5645 I OpenGLRenderer: Initialized EGL, version 1.4
,09-19 08:38:42.277   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +437ms (total +816ms)
,09-19 08:38:42.336  5608  5608 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5608
,09-19 08:38:42.440  5608  5608 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-19 08:38:42.585  5608  5647 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -579339984
,09-19 08:38:42.590  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-19 08:38:42.590  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-19 08:38:42.590  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-19 08:38:42.590  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-19 08:38:42.590  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-19 08:38:42.590  5608  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@816b691 added. We now have 1 listener(s)
,09-19 08:38:42.592  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-19 08:38:42.592  5608  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-19 08:38:42.593  5608  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-19 08:38:42.593  5608  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-19 08:38:42.595  5608  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f2b864 added. We now have 1 listener(s)
,09-19 08:38:42.595  5608  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-19 08:38:42.601   928  2947 D WifiService: New client listening to asynchronous messages
,09-19 08:38:42.601  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-19 08:38:42.601  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-19 08:38:42.602  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-19 08:38:42.602  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-19 08:38:42.602  5608  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-19 08:38:42.605  5608  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-19 08:38:42.605  5608  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-19 08:38:42.610  5608  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 08:38:42.611  5608  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 08:38:42.611  5608  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-19 08:38:42.611  5608  5647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-19 08:38:42.611  5608  5647 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-19 08:38:42.614  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 08:38:42.616  5608  5608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-19 08:38:42.633  5608  5608 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-19 08:38:42.671   928  2939 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-19 08:38:42.924  5608  5654 W jxcore-log: Initializing JXcore engine
09-19 08:38:42.924  5608  5654 W jxcore-log: JXcore engine is ready
,09-19 08:38:42.946  5654  5654 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11687 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-19 08:38:42.946  5654  5654 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14454]" dev="sockfs" ino=14454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-19 08:38:42.946  5654  5654 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-19 08:38:42.946  5654  5654 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32919]" dev="sockfs" ino=32919 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-19 08:38:42.955  5608  5654 W jxcore-log: Starting JXcore engine
,09-19 08:38:43.012  5608  5654 W jxcore-log: Platform android
09-19 08:38:43.012  5608  5654 W jxcore-log: 
09-19 08:38:43.012  5608  5654 W jxcore-log: Process ARCH arm
09-19 08:38:43.012  5608  5654 W jxcore-log: 
,09-19 08:38:43.117  5608  5654 I jxcore-log: JXcore Cordova bridge is ready!
09-19 08:38:43.117  5608  5654 I jxcore-log: 
,09-19 08:38:43.117  5608  5654 W jxcore-log: JXcore engine is started
,09-19 08:38:43.123  5608  5647 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-19 08:38:43.129  5608  5608 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-19 08:38:47.407   928  2948 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-19 08:38:49.721  5608  5654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-19 08:38:49.721  5608  5654 I jxcore-log: 
,09-19 08:38:49.723  5608  5654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-19 08:38:49.723  5608  5654 I jxcore-log: 
,09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-19 08:38:49.727  5608  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-19 08:38:49.728  5608  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-19 08:38:49.730  5608  5654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-19 08:38:49.730  5608  5654 I jxcore-log: 
09-19 08:38:49.732  5608  5654 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-19 08:38:49.732  5608  5654 I jxcore-log: 
,09-19 08:38:50.088  5608  5654 D executeNativeTests: Running unit tests
,09-19 08:38:50.102  5608  5654 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-19 08:38:50.102  5608  5654 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-19 08:38:50.102  5608  5654 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-19 08:38:50.102  5608  5654 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-19 08:38:50.102  5608  5654 D com.test.thalitest.ThaliTestRunner: Total duration: 2 ms
09-19 08:38:50.103  5608  5654 I jxcore-log: *Native tests were executed*
09-19 08:38:50.103  5608  5654 I jxcore-log: 
,09-19 08:38:50.104  5608  5654 I jxcore-log: Total number of executed tests:  1
09-19 08:38:50.104  5608  5654 I jxcore-log: 
09-19 08:38:50.104  5608  5654 I jxcore-log: Number of passed tests:  1
09-19 08:38:50.104  5608  5654 I jxcore-log: 
09-19 08:38:50.104  5608  5654 I jxcore-log: Number of failed tests:  0
09-19 08:38:50.104  5608  5654 I jxcore-log: 
09-19 08:38:50.104  5608  5654 I jxcore-log: Number of ignored tests:  0
09-19 08:38:50.104  5608  5654 I jxcore-log: 
09-19 08:38:50.104  5608  5654 I jxcore-log: Total duration:  2
09-19 08:38:50.104  5608  5654 I jxcore-log: 
09-19 08:38:50.104  5608  5654 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-19 08:38:50.104  5608  5654 I jxcore-log: 
,09-19 08:38:50.106  5608  5654 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-19 08:38:50.106  5608  5654 I jxcore-log: 
,09-19 08:38:50.131  5608  5608 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-19 08:38:50.425   928  2948 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-19 08:38:50.588  5656  5656 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-19 08:38:50.593  5656  5656 D AndroidRuntime: CheckJNI is OFF
,09-19 08:38:50.621  5656  5656 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-19 08:38:50.651  5656  5656 I Radio-JNI: register_android_hardware_Radio DONE
,09-19 08:38:50.666  5656  5656 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-19 08:38:50.672   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-19 08:38:50.673   928   941 I ActivityManager: Killing 5608:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-19 08:38:50.760   928  3379 D GraphicsStats: Buffer count: 2
,09-19 08:38:50.761   928  3379 I WindowState: WIN DEATH: Window{98da554 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-19 08:38:50.763   928  2947 D WifiService: Client connection lost with reason: 4
,09-19 08:38:50.811   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-19 08:38:50.812   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-19 08:38:50.812   928   951 I art     : Starting a blocking GC Explicit
09-19 08:38:50.812   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-19 08:38:50.812   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-19 08:38:50.812   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 08:38:50.812   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:38:50.812   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 08:38:50.812   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-19 08:38:50.813   928   941 I ActivityManager:   Force finishing activity ActivityRecord{e6572e1 u0 com.test.thalitest/.MainActivity t4}
,09-19 08:38:50.822   928  3125 W ActivityManager: Spurious death for ProcessRecord{78270bb 0:com.test.thalitest/u0a77}, curProc for 5608: null
,09-19 08:38:50.824   928   946 W WindowManager: Attempted to add application window with unknown token Token{538a806 ActivityRecord{e6572e1 u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
,09-19 08:38:50.824   928   946 W WindowManager: Token{538a806 ActivityRecord{e6572e1 u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{538a806 ActivityRecord{e6572e1 u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-19 08:38:50.824   928   946 W WindowManager: view not successfully added to wm, removing view
09-19 08:38:50.825   928   946 W WindowManager: Exception when adding starting window
09-19 08:38:50.825   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{e7d37a2 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-19 08:38:50.825   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-19 08:38:50.825   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-19 08:38:50.825   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-19 08:38:50.825   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-19 08:38:50.825   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-19 08:38:50.825   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 08:38:50.825   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:38:50.825   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 08:38:50.825   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-19 08:38:50.892   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-19 08:38:50.898   928   951 I art     : Explicit concurrent mark sweep GC freed 70438(5MB) AllocSpace objects, 32(864KB) LOS objects, 33% free, 28MB/43MB, paused 1.667ms total 85.865ms
,09-19 08:38:50.918   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-19 08:38:50.921  5656  5656 I art     : System.exit called, status: 0
09-19 08:38:50.921  5656  5656 I AndroidRuntime: VM exiting with result code 0.
,09-19 08:38:50.926   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-19 08:38:50.933   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-19 08:38:50.938  4568  4568 D BluetoothMapAppObserver: onReceive
,09-19 08:38:50.938  4568  4568 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-19 08:38:50.942  3642  3642 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-19 08:38:50.947  4056  4161 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-19 08:38:50.950   928  2887 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-19 08:38:50.993  3783  3783 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-19 08:38:50.993  3363  5669 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-19 08:38:50.996  3642  5667 I Keyboard.Facilitator.DecoderInitializer: run()
,09-19 08:38:51.003  3540  3540 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-19 08:38:51.003  3540  3540 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-19 08:38:50.999   502   502 W kworker/3:2: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 08:38:51.006   502   502 W kworker/3:2: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 08:38:51.021  3642  5667 I Decoder : createOrResetDecoder
,09-19 08:38:51.023  3666  5673 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-19 08:38:51.024  3666  5673 D AccountUtils: Clearing selected account for com.test.thalitest
09-19 08:38:51.029   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-19 08:38:51.026   502   502 W kworker/3:2: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-19 08:38:51.037  3798  3934 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-19 08:38:51.055   928  3378 I ActivityManager: Start proc 5676:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-19 08:38:51.055  3798  3934 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-19 08:38:51.055  3798  3934 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3798
09-19 08:38:51.055  3798  3934 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:38:51.055  3798  3934 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-19 08:38:51.059   928  5687 E DropBoxManagerService: Can't write: system_app_crash
09-19 08:38:51.059   928  5687 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-19 08:38:51.059   928  5687 E DropBoxManagerService: 	... 5 more
,09-19 08:38:51.060   928   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-19 08:38:51.068  3798  3934 I Process : Sending signal. PID: 3798 SIG: 9
,09-19 08:38:51.091  3540  3540 I ConfigService: onCreate
,09-19 08:38:51.094  3540  5689 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-19 08:38:51.094  3540  5689 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-19 08:38:51.095  3540  5689 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-19 08:38:51.097  3540  5689 W SQLiteOpenHelper: Opened config.db in read-only mode
09-19 08:38:51.102  3666  5673 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:38:51.124  3666  5673 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:38:51.124  3666  5673 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 08:38:51.086  3363  3387 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjD5EFD7905) - 
,09-19 08:38:51.138  3666  5673 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
09-19 08:38:51.142  3642  5667 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-19 08:38:51.190   928  2886 W InputDispatcher: channel 'db09ec6 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-19 08:38:51.190   928  2886 E InputDispatcher: channel 'db09ec6 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-19 08:38:51.191   928  3554 D GraphicsStats: Buffer count: 1
,09-19 08:38:51.191   928   938 I WindowState: WIN DEATH: Window{db09ec6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-19 08:38:51.191   928   938 W InputDispatcher: Attempted to unregister already unregistered input channel 'db09ec6 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-19 08:38:51.206  3363  3387 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-19 08:38:51.206  3363  3387 E AndroidRuntime: Process: android.process.acore, PID: 3363
09-19 08:38:51.206  3363  3387 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-19 08:38:51.206  3363  3387 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-19 08:38:51.207   928  3832 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3798) has died
,09-19 08:38:51.208   928  3832 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-19 08:38:51.212  3363  3387 I Process : Sending signal. PID: 3363 SIG: 9
,09-19 08:38:51.238  3666  5694 I GMPM-SVC: App measurement is starting up
,09-19 08:38:51.242  3666  5694 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-19 08:38:51.243  3666  5694 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-19 08:38:51.398   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
