#### Test 871169230429d0a_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of system
09-28 10:44:03.514   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-28 10:44:04.038  5625  5625 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 10:44:04.044  5625  5625 D AndroidRuntime: CheckJNI is OFF
09-28 10:44:04.069  5625  5625 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 10:44:04.101  5625  5625 I Radio-JNI: register_android_hardware_Radio DONE
09-28 10:44:04.117  5625  5625 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-28 10:44:04.126   928  3167 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 10:44:04.166   928  3167 I ActivityManager: Start proc 5634:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 10:44:04.170  5625  5625 D AndroidRuntime: Shutting down VM
,09-28 10:44:04.512   928   939 I WindowManager: Screenshot max retries 4 of Token{f1dcaf1 ActivityRecord{2acf298 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{1f37cb0 u0 Starting com.test.thalitest} drawState=2
,09-28 10:44:04.582  5634  5634 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 10:44:04.617  5634  5634 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 10:44:04.644  5634  5634 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 8450-8470)
,09-28 10:44:04.644  5634  5634 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 10:44:04.664  5634  5634 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17efcc4}
,09-28 10:44:04.664  5634  5634 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 10:44:04.664  5634  5634 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 10:44:04.669  5634  5634 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-28 10:44:04.671  5634  5634 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 10:44:04.706  5634  5634 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 10:44:04.719  5634  5634 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 10:44:04.719  5634  5634 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 10:44:04.719  5634  5634 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 10:44:04.719  5634  5634 I Adreno  : Build Date                       : 12/06/15
09-28 10:44:04.719  5634  5634 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 10:44:04.719  5634  5634 I Adreno  : Local Branch                     : mybranch17112971
09-28 10:44:04.719  5634  5634 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 10:44:04.719  5634  5634 I Adreno  : Remote Branch                    : NONE
09-28 10:44:04.719  5634  5634 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 10:44:04.776   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3443a47:true
,09-28 10:44:04.813  4181  4181 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34063]" dev="sockfs" ino=34063 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:04.813  4181  4181 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34063]" dev="sockfs" ino=34063 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:04.824  5634  5634 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 10:44:04.832  5634  5634 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 10:44:04.856  4181  4181 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32903]" dev="sockfs" ino=32903 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:04.859  5634  5671 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-28 10:44:04.856  4181  4181 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32903]" dev="sockfs" ino=32903 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:04.859   939   939 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14062]" dev="sockfs" ino=14062 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:04.859   939   939 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14062]" dev="sockfs" ino=14062 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:04.865  5634  5658 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 10:44:04.888  5634  5671 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 10:44:04.967   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +451ms (total +829ms)
,09-28 10:44:05.008  5634  5634 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5634
,09-28 10:44:05.104  5634  5634 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 10:44:05.290  5634  5673 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -568329936
,09-28 10:44:05.296  5634  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 10:44:05.296  5634  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 10:44:05.296  5634  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 10:44:05.296  5634  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 10:44:05.296  5634  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-28 10:44:05.297  5634  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afb1925 added. We now have 1 listener(s)
,09-28 10:44:05.299  5634  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-28 10:44:05.300  5634  5673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:44:05.300  5634  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:44:05.300  5634  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-28 10:44:05.304  5634  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8151b08 added. We now have 1 listener(s)
09-28 10:44:05.304  5634  5673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 10:44:05.310   928  2982 D WifiService: New client listening to asynchronous messages
,09-28 10:44:05.311  5634  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:44:05.311  5634  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 10:44:05.311  5634  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 10:44:05.311  5634  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-28 10:44:05.311  5634  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-28 10:44:05.313  5634  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:05.313  5634  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 10:44:05.321  5634  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:05.322  5634  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:05.322  5634  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-28 10:44:05.322  5634  5673 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:44:05.322  5634  5673 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 10:44:05.325  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:05.329  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:05.356  5634  5634 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 10:44:05.510   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 10:44:05.510   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 10:44:06.319  5634  5634 I Choreographer: Skipped 54 frames!  The application may be doing too much work on its main thread.
,09-28 10:44:06.557   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 10:44:06.659  5634  5643 I art     : Background sticky concurrent mark sweep GC freed 79588(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 1.422ms total 196.347ms
,09-28 10:44:06.753  5634  5680 W jxcore-log: Initializing JXcore engine
09-28 10:44:06.753  5634  5680 W jxcore-log: JXcore engine is ready
,09-28 10:44:06.796  5680  5680 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12073 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-28 10:44:06.796  5680  5680 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14461]" dev="sockfs" ino=14461 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-28 10:44:06.796  5680  5680 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-28 10:44:06.796  5680  5680 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32070]" dev="sockfs" ino=32070 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 10:44:06.805  5634  5680 W jxcore-log: Starting JXcore engine
,09-28 10:44:06.857  5634  5680 W jxcore-log: Platform android
09-28 10:44:06.857  5634  5680 W jxcore-log: 
,09-28 10:44:06.857  5634  5680 W jxcore-log: Process ARCH arm
09-28 10:44:06.857  5634  5680 W jxcore-log: 
,09-28 10:44:06.954  5634  5680 I jxcore-log: JXcore Cordova bridge is ready!
09-28 10:44:06.954  5634  5680 I jxcore-log: 
,09-28 10:44:06.955  5634  5680 W jxcore-log: JXcore engine is started
,09-28 10:44:06.966  5634  5673 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 10:44:06.974  5634  5634 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 10:44:08.035   928  2972 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 10:44:13.838  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-28 10:44:13.838  5634  5680 I jxcore-log: 
,09-28 10:44:13.839  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-28 10:44:13.839  5634  5680 I jxcore-log: 
,09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:13.844  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:13.845  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:13.847  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-28 10:44:13.847  5634  5680 I jxcore-log: 
,09-28 10:44:13.848  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-28 10:44:13.848  5634  5680 I jxcore-log: 
,09-28 10:44:14.079  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 10:44:14.080  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59dd8b3 added. We now have 2 listener(s)
09-28 10:44:14.080  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:14.080  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 10:44:14.080  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 10:44:14.081  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 10:44:14.081  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9adfe70 added. We now have 2 listener(s)
09-28 10:44:14.081  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:44:14.081  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 10:44:14.083  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:14.085  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:14.086  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:14.086  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:44:14.086  5634  5680 D ExecuteNativeTests: Running unit tests
09-28 10:44:14.087  5634  5680 D BluetoothAdapter: enable(): BT is already enabled..!
09-28 10:44:14.087   928  3167 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 10:44:14.087   928  3167 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-28 10:44:14.088  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:14.089  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:15.511   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:16.513   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:17.514   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:18.516   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:19.517   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:20.517   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 10:44:24.094  5634  5680 I com.test.thalitest.ThaliTestRunner: Running UT
,09-28 10:44:24.163  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:44:24.163  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142ad82 added. We now have 3 listener(s)
,09-28 10:44:24.164  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:24.164  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:44:24.164  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:44:24.164  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:44:24.164  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecdac93 added. We now have 3 listener(s)
,09-28 10:44:24.164  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:44:24.165  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:44:24.168  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:24.173  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:24.177  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:24.177  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:44:24.181  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:24.182  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:24.184  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-28 10:44:24.184  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-28 10:44:24.184  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:24.185  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:24.185  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:24.185  5634  5680 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-28 10:44:24.185  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 10:44:24.185  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 10:44:24.186  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:24.186  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:24.186  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-28 10:44:24.186  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-28 10:44:24.187  5634  5680 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-28 10:44:24.188  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-28 10:44:24.190  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,09-28 10:44:24.190  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-28 10:44:24.190  5634  5680 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-28 10:44:24.190  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-28 10:44:24.190  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-28 10:44:24.191  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:24.191  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 10:44:24.191  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-28 10:44:24.191  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:24.192  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 10:44:24.194  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-28 10:44:24.194  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-28 10:44:24.194  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 10:44:24.194  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-28 10:44:24.194  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:24.194  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:44:24.194  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:44:24.196  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:44:24.196  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 10:44:24.198  5634  5682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:44:24.201  5634  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:44:24.199  4829  4829 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34080]" dev="sockfs" ino=34080 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:24.201  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:44:24.199  4829  4829 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34080]" dev="sockfs" ino=34080 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:24.202  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:44:24.202  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:44:24.204  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 10:44:24.204  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:24.204  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-28 10:44:24.204  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.205  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.205  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 10:44:24.205  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 10:44:24.208  4606  4837 D BtGatt.GattService: registerClient() - UUID=f07aa9cd-ccb4-4c80-90ec-759f97fe3fb9
,09-28 10:44:24.209  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=f07aa9cd-ccb4-4c80-90ec-759f97fe3fb9, clientIf=5
,09-28 10:44:24.211  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:24.213  4606  4682 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:24.216  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:24.230  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:24.238  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:24.240  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-28 10:44:24.240  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:44:24.241  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:44:24.242  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 10:44:24.242  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:24.242  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-28 10:44:24.242  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:44:24.242  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:24.243  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-28 10:44:24.243  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-28 10:44:24.246  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:24.247  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:24.745  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 10:44:24.745  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 10:44:24.745  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 10:44:24.745  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 10:44:24.746  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 10:44:24.747  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-28 10:44:24.748  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-28 10:44:24.748  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-28 10:44:24.749  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 10:44:24.749  5634  5680 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-28 10:44:24.749  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-28 10:44:24.749  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 10:44:24.749  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 10:44:24.749  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:44:24.750  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 10:44:24.750  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:44:24.750  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-28 10:44:24.750  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:44:24.750  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:44:24.750  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:44:24.751  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:44:24.751  5634  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-28 10:44:24.751  5634  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:44:24.751  5634  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 10:44:24.751  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:44:24.753  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:24.754  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 10:44:24.754  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 10:44:24.754  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 10:44:24.756  4606  4682 D BtGatt.AdvertiseManager: message : 1
,09-28 10:44:24.758  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:24.774  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:44:24.775  4606  4680 D BtGatt.GattService: Client app is not null!
,09-28 10:44:24.776  4606  4626 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:24.777  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:44:24.777  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-28 10:44:24.777  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-28 10:44:24.777  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-28 10:44:24.777  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-28 10:44:24.780  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:24.780  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:44:24.780  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:44:24.782  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:44:24.784  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:44:24.784  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-28 10:44:24.786  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-28 10:44:24.786  5634  5680 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-28 10:44:24.786  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-28 10:44:24.787  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-28 10:44:24.787  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:44:24.787  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:24.787  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 10:44:24.787  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 10:44:24.787  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:24.788  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 10:44:24.789  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 10:44:24.789  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-28 10:44:24.789  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 10:44:24.789  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:44:24.789  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:24.789  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:44:24.790  5634  5685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:44:24.793  4626  4626 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29643]" dev="sockfs" ino=29643 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:24.793  4626  4626 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29643]" dev="sockfs" ino=29643 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:24.794  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:44:24.794  5634  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:44:24.794  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:44:24.799  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:44:24.802  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:44:24.802  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:44:24.804  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 10:44:24.804  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:24.805  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-28 10:44:24.805  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.805  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.805  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-28 10:44:24.805  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 10:44:24.808  4606  4837 D BtGatt.GattService: registerClient() - UUID=c902ce5f-27c8-4422-9037-024bdcea42ce
09-28 10:44:24.809  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=c902ce5f-27c8-4422-9037-024bdcea42ce, clientIf=5
09-28 10:44:24.809  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:24.810  4606  4682 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:24.813  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:24.825  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:24.833  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:24.833  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:24.834  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:44:24.835  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:44:24.836  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
09-28 10:44:24.837  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:24.837  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-28 10:44:24.838  5634  5634 D BluetoothAdapter: STATE_ON
,09-28 10:44:24.838  5634  5634 D BluetoothLeScanner: could not find callback wrapper
09-28 10:44:24.838  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:24.838  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 10:44:24.839  4606  4682 D BtGatt.AdvertiseManager: message : 1
,09-28 10:44:24.839  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:24.847  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:44:24.847  4606  4680 D BtGatt.GattService: Client app is not null!
,09-28 10:44:24.848  4606  4626 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:24.848  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:44:24.848  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
09-28 10:44:24.848  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-28 10:44:24.849  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:44:24.849  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:44:24.850  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:44:24.850  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:44:24.855  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:44:24.855  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:44:24.856  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:44:24.858  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-28 10:44:24.858  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:24.859  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-28 10:44:24.859  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.859  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.859  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-28 10:44:24.860  5634  5634 D BluetoothAdapter: STATE_ON
09-28 10:44:24.864  4606  4622 D BtGatt.GattService: registerClient() - UUID=cc51c69a-5c77-4475-ac02-2a06e0f69b9c
09-28 10:44:24.865  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=cc51c69a-5c77-4475-ac02-2a06e0f69b9c, clientIf=5
09-28 10:44:24.865  5634  5645 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:24.867  4606  4682 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:24.869  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:24.880  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:24.886  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:24.887  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:24.887  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 10:44:24.889  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:44:24.890  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:44:24.891  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:44:24.893  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:24.893  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-28 10:44:24.893  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:24.894  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-28 10:44:24.894  4606  4682 D BtGatt.AdvertiseManager: message : 1
09-28 10:44:24.895  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:24.902  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-28 10:44:24.902  4606  4680 D BtGatt.GattService: Client app is not null!
09-28 10:44:24.903  4606  4622 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:24.903  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:44:24.903  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,09-28 10:44:24.903  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-28 10:44:24.904  5634  5634 D BluetoothAdapter: STATE_ON
09-28 10:44:24.907  4606  4622 D BtGatt.GattService: registerClient() - UUID=071ef91a-2e4f-4769-b6d8-633333f01584
,09-28 10:44:24.907  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=071ef91a-2e4f-4769-b6d8-633333f01584, clientIf=5
09-28 10:44:24.907  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:24.908  4606  4682 D BtGatt.AdvertiseManager: message : 0
09-28 10:44:24.911  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:24.922  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:24.929  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:24.930  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:24.930  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
09-28 10:44:24.930  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 10:44:24.931  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:44:24.932  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:44:24.933  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-28 10:44:24.933  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:24.933  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:44:24.933  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:24.933  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-28 10:44:24.933  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to RUNNING
09-28 10:44:24.933  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:24.933  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 10:44:24.934  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-28 10:44:24.935  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:44:24.935  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:44:24.935  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:24.935  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 10:44:24.935  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:44:24.935  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:44:24.935  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 10:44:25.435  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-28 10:44:25.435  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 10:44:25.519   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:26.520   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:27.521   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:28.522   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:29.524   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:29.842  5634  5686 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,09-28 10:44:29.850  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-28 10:44:29.850  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-28 10:44:29.851  5634  5680 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-28 10:44:29.851  5634  5680 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 10:44:29.851  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-28 10:44:29.851  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-28 10:44:29.852  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-28 10:44:29.854  4606  4682 D BtGatt.AdvertiseManager: message : 1
,09-28 10:44:29.855  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:29.869  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:44:29.869  4606  4680 D BtGatt.GattService: Client app is not null!
,09-28 10:44:29.871  4606  4829 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:29.871  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:44:29.872  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-28 10:44:29.872  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:44:29.872  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 10:44:29.872  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:29.872  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-28 10:44:29.872  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:29.873  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:29.873  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 10:44:29.874  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:29.877  4606  4829 D BtGatt.GattService: registerClient() - UUID=d181c641-b24c-46f1-9d03-70aa0ed3659f
09-28 10:44:29.878  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=d181c641-b24c-46f1-9d03-70aa0ed3659f, clientIf=5
,09-28 10:44:29.879  5634  5645 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-28 10:44:29.880  4606  4682 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:29.886  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:29.896  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:29.902  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:29.902  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:44:29.902  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:29.902  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 10:44:29.902  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-28 10:44:29.903  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:44:29.903  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:29.903  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 10:44:29.903  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 10:44:29.903  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 10:44:29.904  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
,09-28 10:44:29.904  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 10:44:29.904  5634  5680 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-28 10:44:29.904  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:44:29.905  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:44:29.906  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:29.907  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
09-28 10:44:29.907  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:29.907  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-28 10:44:29.907  4606  4682 D BtGatt.AdvertiseManager: message : 1
09-28 10:44:29.908  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:29.914  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:44:29.914  4606  4680 D BtGatt.GattService: Client app is not null!
,09-28 10:44:29.915  4606  4622 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:29.915  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:44:29.915  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-28 10:44:29.915  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 10:44:29.916  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 10:44:29.918  4606  4622 D BtGatt.GattService: registerClient() - UUID=9eb66035-e1b6-452e-8f8c-7d91f1b53dfb
,09-28 10:44:29.919  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=9eb66035-e1b6-452e-8f8c-7d91f1b53dfb, clientIf=5
09-28 10:44:29.919  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-28 10:44:29.920  4606  4682 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:29.923  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:29.934  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:29.939  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:29.940  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:44:29.940  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:29.940  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
,09-28 10:44:29.940  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 10:44:29.940  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:44:29.940  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:29.942  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:44:29.944  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-28 10:44:29.944  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
09-28 10:44:29.944  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:29.945  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 10:44:29.945  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-28 10:44:29.945  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:44:29.945  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:44:29.945  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 10:44:29.945  5634  5685 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 10:44:29.945  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:44:29.945  5634  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:44:29.945  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:44:29.945  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:44:29.945  5634  5685 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 10:44:29.945  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:44:29.945  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:44:29.945  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:44:29.945  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:44:29.946  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:29.946  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 10:44:29.946  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:29.946  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 10:44:29.947  4606  4682 D BtGatt.AdvertiseManager: message : 1
09-28 10:44:29.947  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:29.952  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:44:29.952  4606  4680 D BtGatt.GattService: Client app is not null!
09-28 10:44:29.952  4606  4837 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:29.953  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:44:29.953  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-28 10:44:29.953  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-28 10:44:29.953  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-28 10:44:29.953  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-28 10:44:29.954  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:29.954  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:44:29.954  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:44:29.955  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:44:29.956  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:29.956  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:29.956  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:29.958  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-28 10:44:29.958  5634  5680 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-28 10:44:29.959  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-28 10:44:29.959  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 10:44:29.960  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-28 10:44:29.960  5634  5680 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-28 10:44:29.960  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 10:44:29.960  5634  5680 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-28 10:44:29.961  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-28 10:44:29.961  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 10:44:29.962  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-28 10:44:29.962  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:29.962  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:29.962  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:29.962  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 10:44:29.963  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-28 10:44:29.963  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:44:29.963  5634  5680 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 10:44:29.963  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 10:44:29.965  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:44:29.965  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-28 10:44:29.965  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 10:44:29.966  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 10:44:29.967  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 10:44:29.967  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 10:44:29.967  5634  5680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 10:44:29.967  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-28 10:44:29.967  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:44:29.967  5634  5680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 10:44:29.967  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-28 10:44:29.967  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:44:29.967  5634  5680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 10:44:29.968  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-28 10:44:29.976  4626  4626 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[29670]" dev="sockfs" ino=29670 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:29.976  4626  4626 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29670]" dev="sockfs" ino=29670 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:29.972  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-28 10:44:29.973  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-28 10:44:29.973  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-28 10:44:29.974  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 10:44:29.974  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-28 10:44:29.974  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 10:44:29.974  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 10:44:29.974  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 10:44:29.974  5634  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
09-28 10:44:29.975  5634  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-28 10:44:29.975  5634  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:29.975  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-28 10:44:29.975  5634  5680 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 10:44:29.977  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-28 10:44:29.977  5634  5680 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 10:44:29.977  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-28 10:44:29.978  5634  5680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 10:44:29.978  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 10:44:29.978  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 10:44:29.978  5634  5680 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 10:44:29.978  5634  5680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 10:44:29.978  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 10:44:29.978  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 10:44:29.978  5634  5680 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-28 10:44:29.978  5634  5680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 10:44:29.978  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 10:44:29.978  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 10:44:29.978  5634  5680 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 10:44:29.979  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-28 10:44:29.979  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-28 10:44:29.979  5634  5680 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-28 10:44:29.979  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-28 10:44:29.979  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-28 10:44:29.980  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:29.980  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 10:44:29.980  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 10:44:29.980  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:29.981  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 10:44:29.982  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 10:44:29.982  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 10:44:29.982  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 10:44:29.982  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:44:29.982  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:44:29.982  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:29.982  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:44:29.982  5634  5690 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:29.985  5634  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:44:29.983  4837  4837 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32933]" dev="sockfs" ino=32933 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:29.983  4837  4837 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32933]" dev="sockfs" ino=32933 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:29.987  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:44:29.987  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 10:44:29.990  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:44:29.991  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:44:29.991  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:44:29.992  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 10:44:29.993  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:29.993  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-28 10:44:29.993  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:29.993  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:29.993  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 10:44:29.994  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:29.997  4606  4837 D BtGatt.GattService: registerClient() - UUID=cb331d5c-b8aa-4373-a65c-7cf99f5b375e
09-28 10:44:29.997  4606  4680 D BtGatt.GattService: onClientRegistered() - UUID=cb331d5c-b8aa-4373-a65c-7cf99f5b375e, clientIf=5
09-28 10:44:29.998  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-28 10:44:29.998  4606  4682 D BtGatt.AdvertiseManager: message : 0
09-28 10:44:30.000  4606  4682 D BtGatt.AdvertiseManager: starting multi advertising
09-28 10:44:30.008  4606  4680 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-28 10:44:30.013  4606  4680 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-28 10:44:30.014  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:30.014  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:44:30.015  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:44:30.016  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
09-28 10:44:30.016  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-28 10:44:30.016  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-28 10:44:30.016  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:44:30.016  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:30.016  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 10:44:30.016  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-28 10:44:30.018  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-28 10:44:30.018  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:30.516  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:44:30.517  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 10:44:30.517  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:44:30.517  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-28 10:44:30.518  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:44:30.518  5634  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 10:44:30.518  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-28 10:44:30.518  5634  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:44:30.518  5634  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 10:44:30.518  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:44:30.518  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-28 10:44:30.519  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-28 10:44:30.520  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:44:30.520  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:44:30.523  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142ad82 removed from the list
09-28 10:44:30.523  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:44:30.523  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 10:44:30.523  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:44:30.523  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:44:30.524  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:44:30.524  5634  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
,09-28 10:44:30.524  5634  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
09-28 10:44:30.525  4606  4827 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-28 10:44:30.525   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 10:44:30.525  5634  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
09-28 10:44:30.526  5634  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
09-28 10:44:30.527  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:30.527  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 10:44:30.527  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:30.527  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 10:44:30.529  4606  4682 D BtGatt.AdvertiseManager: message : 1
,09-28 10:44:30.530  4606  4682 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:30.542  4606  4680 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-28 10:44:30.542  4606  4680 D BtGatt.GattService: Client app is not null!
,09-28 10:44:30.543  4606  4622 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:30.544  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 10:44:30.544  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-28 10:44:30.544  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-28 10:44:30.544  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-28 10:44:30.544  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-28 10:44:30.546  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:44:30.546  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:44:30.547  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 10:44:30.547  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:44:30.550  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:30.550  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecdac93 removed from the list
,09-28 10:44:30.550  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:44:30.550  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:30.550  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:44:30.550  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:30.553  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,09-28 10:44:30.554  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 10:44:30.554  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:30.556  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 10:44:30.556  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 10:44:30.557  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 10:44:30.557  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-28 10:44:30.557  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-28 10:44:30.557  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:44:30.558  5634  5692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:30.558  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,09-28 10:44:30.559  5634  5680 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-28 10:44:30.560  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-28 10:44:30.560  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-28 10:44:30.560  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:30.560  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 10:44:30.559  4837  4837 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29676]" dev="sockfs" ino=29676 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:30.561  5634  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:44:30.561  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-28 10:44:30.559  4837  4837 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29676]" dev="sockfs" ino=29676 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:30.568  5634  5680 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
09-28 10:44:30.568  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:44:30.568  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 10:44:30.568  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:44:30.568  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 10:44:30.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:44:30.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 10:44:30.569  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142ad82 not in the list
09-28 10:44:30.569  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:44:30.569  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:44:30.569  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:44:30.569  5634  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-28 10:44:30.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:44:30.569  5634  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:44:30.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:44:30.569  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:44:30.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:44:30.569  5634  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-28 10:44:30.571  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:30.572  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecdac93 not in the list
09-28 10:44:30.572  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:30.572  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:44:30.572  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:44:30.572  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 10:44:30.572  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:44:30.572  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:44:30.572  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:44:30.574  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,09-28 10:44:30.574  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-28 10:44:30.574  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 10:44:30.574  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 10:44:30.574  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 10:44:30.574  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-28 10:44:30.574  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 10:44:30.575  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-28 10:44:30.576  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
09-28 10:44:30.578  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-28 10:44:30.578  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 10:44:30.578  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-28 10:44:30.579  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,09-28 10:44:30.579  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-28 10:44:30.579  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 10:44:30.579  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-28 10:44:30.579  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 10:44:30.580  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-28 10:44:30.580  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-28 10:44:30.580  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-28 10:44:30.581  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 10:44:30.581  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-28 10:44:30.581  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,09-28 10:44:30.582  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-28 10:44:30.582  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-28 10:44:30.582  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 10:44:30.582  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-28 10:44:30.583  5634  5680 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-28 10:44:30.583  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:44:30.583  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c6fa39 added. We now have 3 listener(s)
,09-28 10:44:30.585  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:44:30.585  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:44:30.585  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:44:30.585  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:44:30.585  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0c187e added. We now have 3 listener(s)
09-28 10:44:30.586  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:44:30.586  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:44:30.589  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:30.593  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:30.595  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:30.595  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 10:44:30.597  5634  5680 D BluetoothAdapter: enable(): BT is already enabled..!
,09-28 10:44:30.597   928  3708 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 10:44:30.597   928  3708 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-28 10:44:30.598  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:30.599  5634  5680 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,09-28 10:44:30.602  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:30.602  5634  5680 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,09-28 10:44:30.603  5634  5680 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-28 10:44:30.606   928   938 D WifiService: setWifiEnabled: false pid=5634, uid=10077
,09-28 10:44:30.606   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:30.608   928  2972 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-28 10:44:30.608   928  2972 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 10:44:30.608   928  2972 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 10:44:30.609   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:44:30.617   928  5383 D DhcpClient: Clearing IP address
09-28 10:44:30.617   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:44:30.624   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:30.628  3577  5437 V NativeCrypto: Read error: ssl=0x7f8d585700: I/O error during system call, Connection timed out
,09-28 10:44:30.629  3577  5437 V NativeCrypto: SSL shutdown failed: ssl=0x7f8d585700: I/O error during system call, Broken pipe
,09-28 10:44:30.631   928   938 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-28 10:44:30.632   928  5381 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-28 10:44:30.634   928  5381 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-28 10:44:30.635   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-28 10:44:30.635   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-28 10:44:30.637   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 10:44:30.639   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 10:44:30.639   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-28 10:44:30.641   536   536 E Parcel  : Reading a NULL string not supported here.
,09-28 10:44:30.646   928   928 D RttService: SCAN_AVAILABLE : 1
09-28 10:44:30.646   928  3090 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-28 10:44:30.648   928  2984 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-28 10:44:30.652  3755  3920 W QCNEJ   : |CORE| network lost: 100
09-28 10:44:30.652  3755  3920 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 10:44:30.653   928  5384 D DhcpClient: Receive thread stopped
,09-28 10:44:30.668   928  2972 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 10:44:30.678   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:30.682   928  2972 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 10:44:30.701   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:30.701   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-28 10:44:30.702   928  2984 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-28 10:44:30.702   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 10:44:30.702   507   922 D TetherController: Setting IP forward enable = 0
09-28 10:44:30.705   928   945 D Tethering: MasterInitialState.processMessage what=3
09-28 10:44:30.706  5294  5294 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3a37df0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:30.712  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:30.712  5051  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 10:44:30.713  5051  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:44:30.713  5051  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 10:44:30.713  5051  5073 E SarControlService: no key has been found,reset the power
09-28 10:44:30.713  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:44:30.713  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:44:30.713  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 10:44:30.716  3702  3702 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 10:44:30.716  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:30.716  5076  5076 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:44:30.717  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:44:30.717  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:44:30.718  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:44:30.718  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:30.721  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:30.721  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 10:44:30.721  5076  5076 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 10:44:30.724  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:30.727  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:30.728  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:30.732  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000ea03000000000000ffffffff]
,09-28 10:44:30.732  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:44:30.732  5076  5090 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 10:44:30.733  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:30.734  5051  5061 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 10:44:30.735  3702  3702 D SystemUpdateService: onCreate
09-28 10:44:30.737  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000eb03000000000000ffffffff]
09-28 10:44:30.737  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:44:30.737  5076  5090 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-28 10:44:30.737  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:30.737  5051  5062 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 10:44:30.740  3702  3702 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 10:44:30.745  3702  5711 I SystemUpdateService: active receiver: enabled
,09-28 10:44:30.750  3702  3702 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 10:44:30.754  3702  5408 I iu.UploadsManager: num queued entries: 0
,09-28 10:44:30.755  3702  5408 I iu.UploadsManager: num updated entries: 0
09-28 10:44:30.755  3702  5408 I iu.SyncManager: NEXT; no task
,09-28 10:44:30.757  3702  5711 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:44:30.758  3702  3702 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-28 10:44:30.759  3702  3702 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:44:30.762  5411  5411 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-28 10:44:30.766  5411  5411 D SprintDMHelper: simOperator: 
09-28 10:44:30.766  5411  5411 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:44:30.771  3702  5711 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 10:44:30.771  3702  5711 I SystemUpdateService: now status is 0 (complete)
09-28 10:44:30.772  3702  5711 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:44:30.772  3702  5711 I SystemUpdateService: file has been verified
,09-28 10:44:30.775  3702  5711 I SystemUpdateService: OTA package size = 21989297
,09-28 10:44:30.776  5026  5713 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 10:44:30.793  3702  5711 I SystemUpdateService: showing system update notification
,09-28 10:44:30.801  3702  3702 D SystemUpdateService: onDestroy
,09-28 10:44:31.072  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:44:31.110   928  3708 D WifiService: setWifiEnabled: false pid=5634, uid=10077
,09-28 10:44:31.110   928  3708 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:31.613   928   938 D WifiService: setWifiEnabled: false pid=5634, uid=10077
,09-28 10:44:31.614   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:31.791   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-28 10:44:31.792   928  2984 E NetdConnector: NDC Command {112 network destroy 100} took too long (1088ms)
09-28 10:44:31.793   928  2984 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 10:44:31.793   928  2984 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 10:44:31.793   928  2972 E NetdConnector: NDC Command {113 interface ipv6 wlan0 disable} took too long (1087ms)
,09-28 10:44:31.795   928  2954 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1083ms)
,09-28 10:44:31.795   507   922 D TetherController: Setting IP forward enable = 0
,09-28 10:44:31.795   928  2972 D DhcpClient: doQuit
09-28 10:44:31.796   928  2972 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 10:44:31.797  3446  3446 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 10:44:31.798   928  5383 D DhcpClient: onQuitting
,09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:31.809  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:31.810  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:31.815  3446  3446 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:31.817  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:31.819  3446  3446 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 10:44:31.821  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:44:31.822   928   941 I ActivityManager: Start proc 5719:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:31.827  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:31.829  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:31.852  5719  5719 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 10:44:31.859   928  3859 I ActivityManager: Killing 4991:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 10:44:31.864  3446  3446 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 10:44:31.871  3446  3446 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 10:44:31.975   928  2972 D wifi    : In wifi stop Hal
,09-28 10:44:31.975   928  2972 D wifi    : halHandle = 0x7f76f91680, mVM = 0x7f9360d140, mCls = 0x100a02
09-28 10:44:31.975   928  3445 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 10:44:31.975   928  3445 D WifiHAL : Got a signal to exit!!!
09-28 10:44:31.975   928  3445 I WifiHAL : Exit wifi_event_loop
09-28 10:44:31.975  5026  5026 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:44:31.975   928  2972 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 10:44:31.976   928  2972 E WifiHAL : Event processing terminated
09-28 10:44:31.977   928  2972 D wifi    : In wifi cleaned up handler
,09-28 10:44:31.977   928  2972 I WifiHAL : Internal cleanup completed
09-28 10:44:31.978  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:31.980  4080  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:44:31.981  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:31.982  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:32.000   928  3445 D wifi    : set interface wlan0 flags (DOWN)
,09-28 10:44:32.001   928  2972 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 10:44:32.119  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:32.122   928  3146 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 10:44:32.123   928  3146 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:32.205   507   922 D SoftapController: Softap fwReload - Ok
,09-28 10:44:32.207   928   945 D Tethering: InitialState.processMessage what=4
,09-28 10:44:32.213   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:32.213   507   922 D CommandListener: Trying to bring down wlan0
09-28 10:44:32.214   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-28 10:44:32.215   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:44:32.221   928  2972 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 10:44:32.627   928  3167 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 10:44:32.629   928  3167 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:32.827   928  2972 D wifi    : set interface wlan0 flags (UP)
09-28 10:44:32.828   928  2972 I WifiHAL : Initializing wifi
,09-28 10:44:32.829   928  2972 I WifiHAL : Creating socket
09-28 10:44:32.832   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 10:44:32.838   928  2972 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 10:44:32.839   928  2972 D wifi    : Did set static halHandle = 0x7f76f91680
,09-28 10:44:32.839   928  2972 D wifi    : halHandle = 0x7f76f91680, mVM = 0x7f9360d140, mCls = 0x101976
,09-28 10:44:32.839   928  2972 D wifi    : array field set
09-28 10:44:32.839   928  2972 I WifiNative-HAL: interface[0] = wlan0
09-28 10:44:32.841   928  5733 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547456882304
,09-28 10:44:32.841   928  5733 D wifi    : waitForHalEvents called, vm = 0x7f9360d140, obj = 0x101976, env = 0x7f74cb9200
,09-28 10:44:32.926  5734  5734 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 10:44:32.947   928  2972 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-28 10:44:32.952  5734  5734 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:44:32.953  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:32.959  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:32.961  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:32.973  5734  5734 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:44:32.973  5734  5734 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 10:44:32.987   928  2972 D WifiConfigStore: Loading config and enabling all networks 
,09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:32.992  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:32.994  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:32.997   928  2972 D WifiConfigStore: loaded 0 passpoint configs
,09-28 10:44:32.997   928  2972 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 10:44:32.997   928  2972 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 10:44:32.998   928  2972 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:32.998  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:32.999   928  2972 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 10:44:32.999   928  2972 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 10:44:32.999   928  2972 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 10:44:32.999   928  2972 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 10:44:33.000  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:33.001   928  2972 D WifiNative-HAL: Setting external_sim to 1
09-28 10:44:33.001   928  2972 D wifi    : setting dfs flag to true, 0x7f7bfbebe0
,09-28 10:44:33.001  5026  5026 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:44:33.002   928  2972 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 10:44:33.002   928  2972 D wifi    : setting scan oui 0x7f7bfbebe0
09-28 10:44:33.002   928  2972 D WifiHAL : Sending mac address OUI
,09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:33.004  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:33.005   928  2972 E native  : do suspend false
09-28 10:44:33.006  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:33.013   928  2972 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-28 10:44:33.013   928   928 D RttService: SCAN_AVAILABLE : 3
09-28 10:44:33.013   928  3090 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 10:44:33.013   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 10:44:33.014   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:33.017   928  2955 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
09-28 10:44:33.017   928  2955 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 10:44:33.025   928  2955 D WifiNative-HAL: p2pGetDeviceAddress
09-28 10:44:33.025   928  2955 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 10:44:33.030   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=246857 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-28 10:44:33.134  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.145  4606  4676 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 10:44:33.146  4606  4676 D BluetoothAdapterProperties: Setting state to 13
09-28 10:44:33.146  4606  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 10:44:33.147  4606  4676 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 10:44:33.148  4606  4676 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:44:33.152  4606  4680 D BluetoothAdapterProperties: Scan Mode:20
,09-28 10:44:33.152  4606  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-28 10:44:33.157  4606  4606 D HeadsetService: Received stop request...Stopping profile...
,09-28 10:44:33.160  3151  3161 D BluetoothHeadset: Proxy object disconnected
,09-28 10:44:33.160  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:33.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:33.161  3151  3151 D HeadsetProfile: Bluetooth service disconnected
,09-28 10:44:33.161  4606  4606 D A2dpService: Received stop request...Stopping profile...
,09-28 10:44:33.161   928   928 D BluetoothHeadset: Proxy object disconnected
09-28 10:44:33.162  4606  4832 D A2dpStateMachine: Exit Disconnected: -1
09-28 10:44:33.162  3791  4054 D BluetoothHeadset: Proxy object disconnected
09-28 10:44:33.162  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:33.162  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:33.162   928   928 D BluetoothHeadset: Proxy object disconnected
,09-28 10:44:33.162   928   928 D BluetoothHeadset: Proxy object disconnected
09-28 10:44:33.164   928   928 D BluetoothA2dp: Proxy object disconnected
09-28 10:44:33.165  3151  3151 D BluetoothA2dp: Proxy object disconnected
09-28 10:44:33.166  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.166  4606  4606 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:33.166  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.166  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.168  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:33.168  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:33.169  4606  4606 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 10:44:33.169  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:33.169  4606  4606 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 10:44:33.169  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:44:33.169  4606  4810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:33.169  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.169  4606  4810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:33.170  4606  4606 V BluetoothAdapterState: isTurningOn()=false
,09-28 10:44:33.170  4606  4810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:33.170  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.170  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.170  4606  4680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 10:44:33.170  4606  4680 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 10:44:33.172  4606  4680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 10:44:33.172  4606  4810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 10:44:33.172  4606  4810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:33.173  4606  4810 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:44:33.173  4606  4810 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:44:33.173  4606  4810 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:44:33.173  4606  4810 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:44:33.173  4606  4606 D HidService: Received stop request...Stopping profile...
09-28 10:44:33.173  4606  4606 D HidService: Stopping Bluetooth HidService
09-28 10:44:33.176  3151  3151 D BluetoothInputDevice: Proxy object disconnected
,09-28 10:44:33.176  3151  3151 D HidProfile: Bluetooth service disconnected
09-28 10:44:33.176  4606  4606 D HealthService: Received stop request...Stopping profile...
09-28 10:44:33.177  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:33.177  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:33.178  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:33.179  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:33.179  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.179  4606  4606 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:33.179  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.179  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.179  4606  4606 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 10:44:33.180  4606  4680 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:44:33.180  4606  4606 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 10:44:33.181  4606  4606 D PanService: Received stop request...Stopping profile...
,09-28 10:44:33.182  3151  3151 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-28 10:44:33.182  3151  3151 D PanProfile: Bluetooth service disconnected
,09-28 10:44:33.183  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.183  4606  4606 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:33.183  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.183  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.183  4606  4606 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-28 10:44:33.184  4606  4680 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 10:44:33.184  4606  4606 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-28 10:44:33.184  4606  4606 D BluetoothMapService: Received stop request...Stopping profile...
09-28 10:44:33.185  4606  4606 D BluetoothMapService: stop()
,09-28 10:44:33.185  4606  4606 D BluetoothMapAppObserver: deinitObservers()
09-28 10:44:33.185  4606  4606 D BluetoothMapAppObserver: removeReceiver()
,09-28 10:44:33.187  3151  3151 D BluetoothMap: Proxy object disconnected
,09-28 10:44:33.187  3151  3151 D MapProfile: Bluetooth service disconnected
09-28 10:44:33.187  4606  4606 D SapService: Received stop request...Stopping profile...
09-28 10:44:33.187  4606  4606 V SapService: stop()
,09-28 10:44:33.189  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.189  4606  4606 V BluetoothAdapterState: isTurningOn()=false
,09-28 10:44:33.189  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.189  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.189  4606  4606 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 10:44:33.189  4606  4606 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-28 10:44:33.190  4606  4606 D BluetoothMapService: MAP Service closeService in
09-28 10:44:33.190  4606  4606 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 10:44:33.190  4606  4606 D ObexServerSockets0: shutdown(block = true)
,09-28 10:44:33.191  4606  4606 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 10:44:33.191  4606  4848 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 10:44:33.191  4606  4606 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 10:44:33.191  4606  4849 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 10:44:33.192  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.192  4606  4606 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:33.192  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 10:44:33.192  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.192  4606  4827 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 10:44:33.192  4606  4606 D BluetoothMapService: cleanup()
09-28 10:44:33.192  4606  4606 D BluetoothMapService: MAP Service closeService in
09-28 10:44:33.193  4606  4606 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:33.193  4606  4606 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:33.193  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.193  4606  4606 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:33.194  4606  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 10:44:33.194  4606  4676 D BluetoothAdapterProperties: Setting state to 15
09-28 10:44:33.194  4606  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 10:44:33.194  4606  4676 I BluetoothAdapterState: Entering BleOnState
,09-28 10:44:33.198  4606  4606 I BtOppRfcommListener: stopping Accept Thread
,09-28 10:44:33.199  4606  5310 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 10:44:33.199  4606  5310 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 10:44:33.201  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.202  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.204  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.211   928   941 I ActivityManager: Start proc 5738:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-28 10:44:33.211   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:44:33.212  3151  3161 D BluetoothPbap: onBluetoothStateChange: up=false
,09-28 10:44:33.215   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:44:33.215   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:44:33.215  3151  3162 D BluetoothPan: onBluetoothStateChange on: false
09-28 10:44:33.216   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:44:33.216  3791  4005 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:44:33.216  3151  3970 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:44:33.217  3151  3973 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:44:33.217  3151  3161 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-28 10:44:33.218  3151  3162 D BluetoothMap: onBluetoothStateChange: up=false
09-28 10:44:33.219  4606  4676 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 10:44:33.219  4606  4676 D BluetoothAdapterProperties: Setting state to 16
09-28 10:44:33.219  4606  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 10:44:33.223  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.223  4606  4676 D BluetoothAdapterProperties: onBleDisable
09-28 10:44:33.223  4606  4676 I BluetoothAdapterState: Entering PendingCommandState
09-28 10:44:33.224  4606  4677 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 10:44:33.226  4606  4680 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:44:33.225  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:33.228  4606  4810 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 10:44:33.228  4606  4810 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:33.230  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:33.232  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:33.234  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:33.236  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.257  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-28 10:44:33.268  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:44:33.276   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@55f722b:true
09-28 10:44:33.276  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:44:33.289   928  3167 I ActivityManager: Start proc 5750:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 10:44:33.306  5738  5738 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 10:44:33.317  5738  5738 D BluetoothMap: Create BluetoothMap proxy object
,09-28 10:44:33.330  5750  5750 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 10:44:33.331  5738  5738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 10:44:33.342  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:44:33.351   928  3886 I ActivityManager: Killing 5294:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 10:44:33.434  4606  4680 I bt_hci  : shut_down
,09-28 10:44:33.439  4606  4685 D bt_hwcfg: hw_epilog_process
,09-28 10:44:33.439  4606  4685 I bt_vendor: low_power_mode_cb
,09-28 10:44:33.441  4606  4685 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 10:44:33.441  4606  4685 I bt_vendor: epilog_cb
09-28 10:44:33.441  4606  4685 I bt_hci  : epilog_finished_callback
,09-28 10:44:33.443  4606  4680 I bt_hci_h4: hal_close
,09-28 10:44:33.444  4606  4680 I bt_userial_vendor: device fd = 54 close
,09-28 10:44:33.522  5750  5750 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.522  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 10:44:33.523  5750  5750 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 10:44:33.523  5750  5750 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.523  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:44:33.524  5750  5750 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 10:44:33.524  5,750  5750 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 10:44:33.524  5750  5750 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 10:44:33.524  5750  5750 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:44:33.524  5750  5750 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.524,  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:44:33.524  5750  5750 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 10:44:33.524  5750  5750 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 10:44:33.529  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:44:33.535  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:44:33.538  5738  5738 D DockEventReceiver: finishStartingService: stopping service
,09-28 10:44:33.544   928  3859 I ActivityManager: Killing 4690:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 10:44:33.578  4606  4677 D bt_stack_manager: event_shut_down_stack finished.
,09-28 10:44:33.578  4606  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 10:44:33.580  4606  4676 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 10:44:33.580  4606  4606 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:44:33.581  4606  4606 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 10:44:33.581  4606  4606 D BtGatt.GattService: stop()
09-28 10:44:33.581  4606  4606 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 10:44:33.583  4606  4606 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:44:33.583  4606  4606 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:33.583  4606  4606 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:33.583  4606  4606 V BluetoothAdapterState: isBleTurningOff()=true
09-28 10:44:33.583  4606  4676 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-28 10:44:33.583  4606  4676 D BluetoothAdapterProperties: Setting state to 10
09-28 10:44:33.583  4606  4676 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 10:44:33.584  4606  4676 I BluetoothAdapterState: Entering OffState
,09-28 10:44:33.585   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-28 10:44:33.591  4606  4606 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 10:44:33.591  4606  4606 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 10:44:33.591  4606  4606 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 10:44:33.592  4606  4677 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 10:44:33.604  4606  4677 D bt_stack_manager: event_clean_up_stack finished.
,09-28 10:44:33.607  4606  4606 I art     : System.exit called, status: 0
,09-28 10:44:33.608  4606  4606 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 10:44:33.642  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:33.644   380   380 E lowmemorykiller: Error opening /proc/4606/oom_score_adj; errno=2
,09-28 10:44:33.645   928   945 W ActivityManager: Application dead when creating service ServiceRecord{19b5082 u0 com.android.bluetooth/.btservice.AdapterService}
,09-28 10:44:33.645   928   945 I ActivityManager: Process com.android.bluetooth (pid 4606) has died
09-28 10:44:33.646   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
09-28 10:44:33.647   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,09-28 10:44:33.648   928   945 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
09-28 10:44:33.648   928   945 W ActivityManager: android.os.DeadObjectException
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:33.648   928   945 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:44:33.648   928   945 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-28 10:44:33.648   928   938 W ActivityManager: Spurious death for ProcessRecord{338a4a8 0:com.android.bluetooth/1002}, curProc for 4606: null
,09-28 10:44:33.787  5750  5774 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 10:44:33.798   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1424fd0:true
,09-28 10:44:36.183  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:36.188  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:36.193  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:36.198  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:36.251   928  2972 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-28 10:44:36.252   928  2972 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 10:44:36.253   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:44:36.267   928  2972 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 10:44:36.302   928  2972 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 10:44:36.304  5734  5734 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 10:44:36.643   928   945 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,09-28 10:44:36.690   928   945 I ActivityManager: Start proc 5785:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 10:44:36.721  5734  5734 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 10:44:36.754  5734  5734 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 10:44:36.754  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 10:44:36.759   928  2972 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:44:36.759   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 10:44:36.759   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 10:44:36.770   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:44:36.778   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:36.781  5785  5785 D AdapterServiceConfig: Adding HeadsetService
09-28 10:44:36.781  5785  5785 D AdapterServiceConfig: Adding A2dpService
09-28 10:44:36.781  5785  5785 D AdapterServiceConfig: Adding HidService
09-28 10:44:36.781  5785  5785 D AdapterServiceConfig: Adding HealthService
09-28 10:44:36.781  5785  5785 D AdapterServiceConfig: Adding PanService
09-28 10:44:36.782  5785  5785 D AdapterServiceConfig: Adding GattService
09-28 10:44:36.782  5785  5785 D AdapterServiceConfig: Adding BluetoothMapService
09-28 10:44:36.782   928  2972 D WifiStateMachine: Start Dhcp Watchdog 2
09-28 10:44:36.782  5785  5785 D AdapterServiceConfig: Adding SapService
09-28 10:44:36.789   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 10:44:36.789   928  2972 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-28 10:44:36.789   928  2984 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-28 10:44:36.793   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d28819:true
,09-28 10:44:36.793  5785  5785 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 10:44:36.794   928  5803 D DhcpClient: Receive thread started
,09-28 10:44:36.797  5785  5785 I bt_bluedroid: init
,09-28 10:44:36.797  5785  5802 I BluetoothAdapterState: Entering OffState
,09-28 10:44:36.799  5785  5804 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-28 10:44:36.799  5785  5804 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-28 10:44:36.799  5785  5804 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 10:44:36.799  5785  5804 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 10:44:36.799  5785  5785 I bt_bluedroid: get_profile_interface socket
,09-28 10:44:36.801  5785  5807 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:44:36.801  5785  5785 I bt_bluedroid: get_profile_interface sdp
09-28 10:44:36.802  5785  5807 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:44:36.805  5785  5796 I bt_bluedroid: config_hci_snoop_log
,09-28 10:44:36.806   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-28 10:44:36.809  5785  5802 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 10:44:36.809  5785  5802 D BluetoothAdapterProperties: Setting state to 14
09-28 10:44:36.810  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 10:44:36.811  5785  5802 D BluetoothBondStateMachine: make
,09-28 10:44:36.812  5785  5808 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 10:44:36.814  5785  5802 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:44:36.815  5785  5785 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 10:44:36.817  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:36.817  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:44:36.818  5785  5785 D BtGatt.GattService: Received start request. Starting profile...
09-28 10:44:36.818  5785  5785 D BtGatt.GattService: start()
09-28 10:44:36.818  5785  5785 I bt_bluedroid: get_profile_interface gatt
,09-28 10:44:36.819  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:36.819  5785  5785 D BtGatt.AdvertiseManager: advertise manager created
09-28 10:44:36.823  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:36.823  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:36.823  5785  5785 V BluetoothAdapterState: isBleTurningOn()=true
09-28 10:44:36.823  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:36.823  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 10:44:36.824  5785  5802 I bt_bluedroid: bt_bluedroid
09-28 10:44:36.824  5785  5804 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 10:44:36.824  5785  5804 I bt_hci  : start_up
,09-28 10:44:36.829  5785  5804 I bt_vendor: alloc value 0xf3d37871
,09-28 10:44:36.829  5785  5804 I bt_vendor: init
09-28 10:44:36.829  5785  5804 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 10:44:36.829  5785  5804 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 10:44:36.874   928  2972 E native  : do suspend false
,09-28 10:44:36.881   928  5801 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 10:44:36.894   928  5803 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172591, domain null
,09-28 10:44:36.894   928  5801 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172591 seconds
,09-28 10:44:36.895   928  5801 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 10:44:36.907   928  5803 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 10:44:36.907   928  5801 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 10:44:36.908   507   922 D CommandListener: Setting iface cfg
09-28 10:44:36.910   928  2972 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 10:44:36.911   928  5801 D DhcpClient: Scheduling renewal in 86399s
,09-28 10:44:36.917   928  2972 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 10:44:36.917   928  2972 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 10:44:36.917   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-28 10:44:36.918   928  2984 D ConnectivityService: Adding iface wlan0 to network 101
,09-28 10:44:36.921   928  2972 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 10:44:36.936  5785  5804 D bt_hci  : start_up starting async portion
,09-28 10:44:36.936  5785  5811 I bt_hci  : event_finish_startup
09-28 10:44:36.936  5785  5811 I bt_hci_h4: hal_open
09-28 10:44:36.936  5785  5811 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-28 10:44:36.937  5785  5811 I bt_userial_vendor: device fd = 54 open
,09-28 10:44:36.936  5814  5814 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:44:36.944   928  2984 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 10:44:36.944   928  2984 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-28 10:44:36.946   928  2984 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-28 10:44:36.947   928  2984 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 10:44:36.948   928  2984 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 10:44:36.949  5785  5811 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 10:44:36.952  5785  5811 D bt_hwcfg: Chipset BCM4358A3
09-28 10:44:36.952  5785  5811 D bt_hwcfg: Target name = [BCM4358A3]
09-28 10:44:36.952  5785  5811 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 10:44:36.958   928  2984 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 10:44:36.961   928  2984 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-28 10:44:36.962   928  2984 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-28 10:44:36.962   928  2984 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-28 10:44:36.962   928  2972 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 10:44:36.962   928  2984 D ConnectivityService:    accepting network in place of null
09-28 10:44:36.962   928  2972 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 10:44:36.963   928  2984 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:44:36.974   928  5800 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250801, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 10:44:36.982   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:37.002   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:37.005   928  2984 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-28 10:44:37.005   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 10:44:37.005  3755  3920 W QCNEJ   : |CORE| network available: 101
09-28 10:44:37.006   928  2984 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-28 10:44:37.008   928   945 D Tethering: MasterInitialState.processMessage what=3
09-28 10:44:37.014  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.014  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:37.014  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.015  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.017  3755  3920 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 10:44:37.018  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.018  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:37.018  3755  3920 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 10:44:37.019  3755  3920 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-28 10:44:37.019  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.019  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetwork,Changed: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.020  5051  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 10:44:37.020  5051  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:44:37.020  5051  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 10:44:37.020  5051  5073 E SarControlService: no key has been found,reset the power
09-28 10:44:37.020  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:44:37.021  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:44:37.021  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 10:44:37.021  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:37.021  5076  5076 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:44:37.023  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-28 10:44:37.023  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:44:37.023  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.023  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.023  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:37.023  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:37.024  5076  5076 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 10:44:37.024  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:37.024  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.025  3702  3702 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 10:44:37.029  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000ec03000000000000ffffffff]
,09-28 10:44:37.029  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-28 10:44:37.029  5076  5090 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 10:44:37.029  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000ed03000000000000ffffffff]
09-28 10:44:37.029  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:44:37.029  5076  5090 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-28 10:44:37.030  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:37.031  5051  5061 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 10:44:37.031  3702  3702 D SystemUpdateService: onCreate
09-28 10:44:37.033  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:37.033  5051  5062 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 10:44:37.036  3702  3702 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 10:44:37.044   928  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.238,2a00:1450:4001:817::200e
,09-28 10:44:37.046  3702  3702 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 10:44:37.054  3702  5408 I iu.UploadsManager: num queued entries: 0
,09-28 10:44:37.054  3702  5408 I iu.UploadsManager: num updated entries: 0
09-28 10:44:37.055  3702  5408 I iu.SyncManager: NEXT; no task
,09-28 10:44:37.056  3702  3702 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 10:44:37.058  3702  3702 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:44:37.059  5411  5411 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:44:37.063  5411  5411 D SprintDMHelper: simOperator: 
09-28 10:44:37.063  5411  5411 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:44:37.063  3702  5824 I SystemUpdateService: active receiver: enabled
,09-28 10:44:37.093  3702  5824 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:44:37.101  3702  5824 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 10:44:37.101  3702  5824 I SystemUpdateService: now status is 0 (complete)
09-28 10:44:37.101  3702  5824 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:44:37.101  3702  5824 I SystemUpdateService: file has been verified
09-28 10:44:37.101  3702  5824 I SystemUpdateService: OTA package size = 21989297
,09-28 10:44:37.104   928  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 14:44:37 GMT], X-Android-Received-Millis=[1475073877103], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475073877073]}
,09-28 10:44:37.104   928  2984 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 10:44:37.104   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-28 10:44:37.104   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 10:44:37.105   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 10:44:37.109  3702  5824 I SystemUpdateService: showing system update notification
,09-28 10:44:37.117  3702  3702 D SystemUpdateService: onDestroy
,09-28 10:44:37.160  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-28 10:44:37.196  5026  5828 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 10:44:37.258  5785  5811 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 10:44:37.258  5785  5811 D bt_hwcfg: Settlement delay -- 100 ms
09-28 10:44:37.258  5785  5811 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 10:44:37.383  5785  5811 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:44:37.384  5785  5811 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-28 10:44:37.385  5785  5811 I bt_hwcfg: vendor lib fwcfg completed
,09-28 10:44:37.385  5785  5811 I bt_vendor: firmware callback
09-28 10:44:37.385  5785  5811 I bt_hci  : firmware_config_callback
,09-28 10:44:37.389  5785  5836 I bt_btu  : btu_task pending for preload complete event
,09-28 10:44:37.390  5785  5836 I bt_btu_task: Bluetooth chip preload is complete
09-28 10:44:37.390  5785  5836 I bt_btu  : btu_task received preload complete event
,09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_BNEP
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_BTM
,09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_SMP
,09-28 10:44:37.394  5785  5836 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 10:44:37.395  5785  5836 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 10:44:37.473  5785  5836 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cb5549
,09-28 10:44:37.473  5785  5836 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cb5549 
,09-28 10:44:37.482  5785  5807 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 10:44:37.483  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:44:37.484  5785  5807 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:44:37.486  5785  5807 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:44:37.489  5785  5807 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:44:37.490  5785  5807 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:44:37.490  5785  5807 D bt_hci  : do_postload posting postload work item
,09-28 10:44:37.490  5785  5811 I bt_hci  : event_postload
,09-28 10:44:37.490  5785  5811 I bt_vendor: sco_config_cb
,09-28 10:44:37.490  5785  5811 I bt_hci  : sco_config_callback postload finished.
09-28 10:44:37.497  5785  5811 I bt_vendor: low_power_mode_cb
09-28 10:44:37.499  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.501  5785  5807 D bt_bte_conf: Device ID record 1 : primary
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   vendorId            = 000f
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   vendorIdSource      = 0001
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   product             = 1200
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   version             = 1436
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   clientExecutableURL = 
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   serviceDescription  = 
09-28 10:44:37.502  5785  5807 D bt_bte_conf:   documentationURL    = 
09-28 10:44:37.502  5785  5807 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 10:44:37.503  5785  5804 D bt_stack_manager: event_start_up_stack finished
,09-28 10:44:37.504  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-28 10:44:37.504  5785  5802 D BluetoothAdapterProperties: Setting state to 15
09-28 10:44:37.504  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 10:44:37.504  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.505  5785  5802 I BluetoothAdapterState: Entering BleOnState
09-28 10:44:37.509  5785  5802 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 10:44:37.509  5785  5802 D BluetoothAdapterProperties: Setting state to 11
09-28 10:44:37.510  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 10:44:37.511  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.519  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:37.520  5785  5785 D HeadsetService: Received start request. Starting profile...
09-28 10:44:37.524  5785  5785 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 10:44:37.524  5785  5785 D HeadsetStateMachine: make
,09-28 10:44:37.529  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.532  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.536  5785  5802 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:44:37.536  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.537  5785  5785 D HeadsetStateMachine: max_hf_connections = 1
,09-28 10:44:37.537  5785  5785 I bt_bluedroid: get_profile_interface handsfree
09-28 10:44:37.538  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 10:44:37.538  5785  5807 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-28 10:44:37.541  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:37.542  5785  5785 D A2dpService: Received start request. Starting profile...
09-28 10:44:37.542  5785  5785 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 10:44:37.543  5785  5785 I bt_bluedroid: get_profile_interface avrcp
,09-28 10:44:37.549  5785  5785 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 10:44:37.549  5785  5785 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 10:44:37.549  5785  5785 D A2dpStateMachine: make
,09-28 10:44:37.551  5785  5785 I bt_bluedroid: get_profile_interface a2dp
,09-28 10:44:37.552  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-28 10:44:37.554  5785  5785 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 10:44:37.555  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:37.556  5738  5738 D BluetoothInputDevice: Proxy object connected
09-28 10:44:37.556  5785  5844 D A2dpStateMachine: Enter Disconnected: -2
09-28 10:44:37.556  5785  5785 D HidService: Received start request. Starting profile...
,09-28 10:44:37.556  5785  5785 I bt_bluedroid: get_profile_interface hidhost
09-28 10:44:37.556  5785  5785 D HidService: setHidService(): set to: null
09-28 10:44:37.556  5738  5738 D HidProfile: Bluetooth service connected
09-28 10:44:37.556  5785  5807 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9656d
09-28 10:44:37.557  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-28 10:44:37.558  5785  5785 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-28 10:44:37.559  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:37.560  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:44:37.562  5785  5785 D HealthService: Received start request. Starting profile...
,09-28 10:44:37.563  5785  5785 I bt_bluedroid: get_profile_interface health
,09-28 10:44:37.564  5785  5785 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 10:44:37.565  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:37.566  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:44:37.566  5785  5785 D PanService: Received start request. Starting profile...
09-28 10:44:37.566  5785  5785 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 10:44:37.566  5785  5785 I bt_bluedroid: get_profile_interface pan
09-28 10:44:37.566  5738  5738 D PanProfile: Bluetooth service connected
,09-28 10:44:37.569  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:37.570  5738  5738 D BluetoothMap: Proxy object connected
,09-28 10:44:37.571  5738  5738 D MapProfile: Bluetooth service connected
09-28 10:44:37.571  5738  5738 D BluetoothMap: getConnectedDevices()
09-28 10:44:37.572  5785  5785 D BluetoothMapService: Received start request. Starting profile...
09-28 10:44:37.572  5785  5785 D BluetoothMapService: start()
09-28 10:44:37.573  5785  5807 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 10:44:37.575  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-28 10:44:37.577  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 10:44:37.577  5785  5785 D BluetoothMapAppObserver: createReceiver()
09-28 10:44:37.578  5785  5785 D BluetoothMapAppObserver: initObservers()
,09-28 10:44:37.578  5785  5785 D BluetoothMapAppObserver: getEnabledAccountItems()
09-28 10:44:37.583  5738  5738 D BluetoothMap: Bluetooth is Not enabled
,09-28 10:44:37.587  5785  5785 V SapService: SapBinder()
,09-28 10:44:37.587  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:37.588  5785  5785 D SapService: Received start request. Starting profile...
,09-28 10:44:37.588  5785  5785 V SapService: start()
,09-28 10:44:37.589  5785  5785 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:37.590  5785  5841 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isTurningOn()=true
,09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:37.590  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.591  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:44:37.591  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:37.591  5785  5785 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:37.591  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.591  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isTurningOn()=true
,09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.592  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:44:37.593  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:37.593  5785  5785 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:37.593  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.593  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:44:37.593  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 10:44:37.594  5785  5802 D BluetoothAdapterProperties: ScanMode =  20
,09-28 10:44:37.594  5785  5802 D BluetoothAdapterProperties: State =  11
09-28 10:44:37.595  5785  5807 D BluetoothAdapterProperties: Scan Mode:21
09-28 10:44:37.595  5785  5807 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:44:37.595  5785  5802 D BluetoothAdapterProperties: Setting state to 12
09-28 10:44:37.595  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-28 10:44:37.596  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 10:44:37.596  5785  5802 I BluetoothAdapterState: Entering OnState
09-28 10:44:37.596   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:37.596  3151  3161 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:44:37.598   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 10:44:37.598   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:44:37.599  5738  5748 D BluetoothPan: onBluetoothStateChange on: true
09-28 10:44:37.599  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-28 10:44:37.599  3151  3970 D BluetoothPan: onBluetoothStateChange on: true
09-28 10:44:37.600   928   928 D BluetoothA2dp: Proxy object connected
,09-28 10:44:37.601  5634  5634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-28 10:44:37.602  3151  3151 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:44:37.602  3151  3151 D PanProfile: Bluetooth service connected
09-28 10:44:37.604   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:37.604  3791  3824 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:37.605  3151  3162 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:37.605  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:44:37.606  5785  5785 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.606  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:37.607  5738  5749 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:44:37.609  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:37.609  3151  3161 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:44:37.610  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:37.611  3151  3151 D BluetoothA2dp: Proxy object connected
09-28 10:44:37.611  3151  3970 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.613  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:37.613  3151  3151 D BluetoothInputDevice: Proxy object connected
09-28 10:44:37.613  3151  3151 D HidProfile: Bluetooth service connected
09-28 10:44:37.614  5738  5748 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 10:44:37.614  3151  3161 D BluetoothMap: onBluetoothStateChange: up=true
09-28 10:44:37.615  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:44:37.615  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:37.616  5785  5785 D ObexServerSockets: Succeed to create listening sockets 
09-28 10:44:37.616  5785  5785 D ObexServerSockets0: startAccept()
09-28 10:44:37.616  3151  3151 D BluetoothMap: Proxy object connected
,09-28 10:44:37.616  3151  3151 D MapProfile: Bluetooth service connected
,09-28 10:44:37.616  3151  3151 D BluetoothMap: getConnectedDevices()
09-28 10:44:37.616  5785  5785 D ObexServerSockets0: prepareForNewConnect()
09-28 10:44:37.618   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-28 10:44:37.619  5785  5785 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-28 10:44:37.620  5785  5785 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-28 10:44:37.620  5738  5738 D LocalBluetoothProfileManager: Adding local A2DP profile
09-28 10:44:37.621  5785  5851 D ObexServerSockets0: Accepting socket connection...
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.621  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:37.621  5785  5785 D BluetoothMapService: onReceive
09-28 10:44:37.622  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 10:44:37.622  5785  5785 D BluetoothMapService: STATE_ON
09-28 10:44:37.622  5785  5850 D ObexServerSockets0: Accepting socket connection...
09-28 10:44:37.624  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.624  5738  5738 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-28 10:44:37.627  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.628  5785  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:37.629  5785  5853 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 10:44:37.629  5785  5853 D BluetoothSdpJni: SDP Create record success - handle: 1
09-28 10:44:37.629  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.631  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.635  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:44:37.637  5738  5738 D BluetoothA2dp: Proxy object connected
,09-28 10:44:37.642  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:44:37.644  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-28 10:44:37.650  3151  3151 D BluetoothPbap: Proxy object connected
09-28 10:44:37.650  3151  3151 D PbapServerProfile: Bluetooth service connected
,09-28 10:44:37.650  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 10:44:37.650  5785  5785 D ObexServerSockets0: prepareForNewConnect()
,09-28 10:44:37.654  5738  5738 D BluetoothPbap: Proxy object connected
,09-28 10:44:37.654  5738  5738 D PbapServerProfile: Bluetooth service connected
,09-28 10:44:37.658  5785  5857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:44:37.662  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.663  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:44:37.663  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:44:37.665  5634  5680 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-28 10:44:37.665  5634  5680 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,09-28 10:44:37.668  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.668  5785  5802 D BluetoothAdapterState: Current state: ON, message: 23
09-28 10:44:37.668  5785  5802 D BluetoothAdapterProperties: Setting state to 13
09-28 10:44:37.668  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-28 10:44:37.668  5785  5802 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 10:44:37.669  5785  5802 I BluetoothAdapterState: Entering PendingCommandState
09-28 10:44:37.672  5785  5807 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:44:37.672  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 10:44:37.673  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:44:37.675  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.675  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:37.676  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-28 10:44:37.676  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.676  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:37.679  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:37.679  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:37.680  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:37.680  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:37.683  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.685  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.685  5785  5785 D BluetoothMapService: onReceive
09-28 10:44:37.685  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-28 10:44:37.685  5785  5785 D BluetoothMapService: STATE_TURNING_OFF
,09-28 10:44:37.687  5785  5785 D HeadsetService: Received stop request...Stopping profile...
09-28 10:44:37.689  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:44:37.690  5785  5785 D A2dpService: Received stop request...Stopping profile...
,09-28 10:44:37.691  5785  5844 D A2dpStateMachine: Exit Disconnected: -1
09-28 10:44:37.693   928   928 D BluetoothA2dp: Proxy object disconnected
09-28 10:44:37.693  3151  3151 D BluetoothA2dp: Proxy object disconnected
09-28 10:44:37.693  5738  5738 D BluetoothA2dp: Proxy object disconnected
09-28 10:44:37.694  5785  5785 D HidService: Received stop request...Stopping profile...
09-28 10:44:37.694  5785  5785 D HidService: Stopping Bluetooth HidService
09-28 10:44:37.694  3151  3151 D BluetoothInputDevice: Proxy object disconnected
09-28 10:44:37.694  3151  3151 D HidProfile: Bluetooth service disconnected
09-28 10:44:37.695  5785  5785 D HealthService: Received stop request...Stopping profile...
09-28 10:44:37.695  5738  5738 D BluetoothInputDevice: Proxy object disconnected
09-28 10:44:37.695  5738  5738 D HidProfile: Bluetooth service disconnected
,09-28 10:44:37.696  5785  5785 D PanService: Received stop request...Stopping profile...
09-28 10:44:37.696  5785  5785 D BluetoothMapService: MAP Service closeService in
09-28 10:44:37.696  5738  5738 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 10:44:37.697  5738  5738 D PanProfile: Bluetooth service disconnected
09-28 10:44:37.697  5785  5785 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 10:44:37.697  5785  5785 D ObexServerSockets0: shutdown(block = true)
09-28 10:44:37.697  3151  3151 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 10:44:37.697  3151  3151 D PanProfile: Bluetooth service disconnected
09-28 10:44:37.697  5785  5850 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 10:44:37.697  5785  5785 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 10:44:37.697  5785  5785 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 10:44:37.697  5785  5838 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 10:44:37.697  5785  5851 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-28 10:44:37.698  5785  5785 D BluetoothMapService: Received stop request...Stopping profile...
,09-28 10:44:37.699  5785  5785 D BluetoothMapService: stop()
,09-28 10:44:37.699  5785  5785 D BluetoothMapAppObserver: deinitObservers()
09-28 10:44:37.699  5785  5785 D BluetoothMapAppObserver: removeReceiver()
09-28 10:44:37.700  3151  3151 D BluetoothMap: Proxy object disconnected
,09-28 10:44:37.700  3151  3151 D MapProfile: Bluetooth service disconnected
,09-28 10:44:37.701  5738  5738 D BluetoothMap: Proxy object disconnected
09-28 10:44:37.701  5738  5738 D MapProfile: Bluetooth service disconnected
09-28 10:44:37.701  5738  5738 D BluetoothPbap: Proxy object disconnected
09-28 10:44:37.701  5738  5738 D PbapServerProfile: Bluetooth service disconnected
09-28 10:44:37.702  3151  3151 D BluetoothPbap: Proxy object disconnected
09-28 10:44:37.702  3151  3151 D PbapServerProfile: Bluetooth service disconnected
09-28 10:44:37.702  5785  5785 D SapService: Received stop request...Stopping profile...
09-28 10:44:37.702  5785  5785 V SapService: stop()
09-28 10:44:37.703  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.703  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.703  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.703  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.704  5785  5785 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 10:44:37.705  5785  5785 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 10:44:37.705  5785  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:37.705  5785  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:37.705  5785  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:37.706  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.706  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.706  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.706  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.707  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 10:44:37.707  5785  5807 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-28 10:44:37.707  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 10:44:37.707  5785  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:37.707  5785  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:37.708  5785  5836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:44:37.708  5785  5836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:44:37.708  5785  5836 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 10:44:37.708  5785  5836 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 10:44:37.708  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.708  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.708  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.708  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.708  5785  5785 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 10:44:37.708  5785  5785 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 10:44:37.709  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.709  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.709  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.709  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.709  5785  5785 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 10:44:37.709  5785  5785 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 10:44:37.710  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.710  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.710  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.710  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.710  5785  5785 W Bluetoot,hPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 10:44:37.710  5785  5785 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 10:44:37.710  5785  5807 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:44:37.711  5785  5807 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 10:44:37.711  5785  5785 D BluetoothMapService: MAP Service closeService in
09-28 10:44:37.711  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.711  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.711  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.711  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.711  5785  5785 D BluetoothMapService: cleanup()
09-28 10:44:37.712  5785  5785 D BluetoothMapService: MAP Service closeService in
09-28 10:44:37.712  5785  5785 V BluetoothAdapterState: isTurningOff()=true
09-28 10:44:37.712  5785  5785 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:37.712  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:37.712  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:37.712  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 10:44:37.712  5785  5802 D BluetoothAdapterProperties: Setting state to 15
09-28 10:44:37.712  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 10:44:37.713  5785  5802 I BluetoothAdapterState: Entering BleOnState
,09-28 10:44:37.715  5738  5748 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-28 10:44:37.721   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:44:37.722  3151  3161 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 10:44:37.722   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:44:37.722   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:44:37.722  5738  5749 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:44:37.722  5738  5748 D BluetoothPan: onBluetoothStateChange on: false
,09-28 10:44:37.723  3151  3162 D BluetoothPan: onBluetoothStateChange on: false
,09-28 10:44:37.723   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:44:37.724  3791  4054 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 10:44:37.724  3151  3973 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 10:44:37.724  5738  5749 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 10:44:37.724  3151  3970 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:44:37.725  3151  3161 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 10:44:37.725  5738  5748 D BluetoothMap: onBluetoothStateChange: up=false
09-28 10:44:37.726  3151  3162 D BluetoothMap: onBluetoothStateChange: up=false
09-28 10:44:37.726  5738  5749 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 10:44:37.727  5785  5802 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 10:44:37.727  5785  5802 D BluetoothAdapterProperties: Setting state to 16
09-28 10:44:37.727  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 10:44:37.727  5785  5802 D BluetoothAdapterProperties: onBleDisable
09-28 10:44:37.727  5785  5802 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:44:37.728  5785  5804 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 10:44:37.729  5785  5807 D BluetoothAdapterProperties: Scan Mode:20
09-28 10:44:37.730  5785  5836 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 10:44:37.730  5785  5836 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 10:44:37.731  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 10:44:37.731  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.734  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.736  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:37.736  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 10:44:37.737  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-28 10:44:37.738  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:37.931  5785  5807 I bt_hci  : shut_down
,09-28 10:44:37.931  5785  5811 D bt_hwcfg: hw_epilog_process
,09-28 10:44:37.933  5785  5811 I bt_vendor: low_power_mode_cb
,09-28 10:44:37.936  5785  5811 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 10:44:37.937  5785  5811 I bt_vendor: epilog_cb
09-28 10:44:37.937  5785  5811 I bt_hci  : epilog_finished_callback
09-28 10:44:37.938  5785  5807 I bt_hci_h4: hal_close
,09-28 10:44:37.939  5785  5807 I bt_userial_vendor: device fd = 54 close
,09-28 10:44:38.006   928  2984 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 10:44:38.063  5785  5804 D bt_stack_manager: event_shut_down_stack finished.
,09-28 10:44:38.064  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 10:44:38.069  5785  5802 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-28 10:44:38.069  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:44:38.070  5785  5785 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 10:44:38.070  5785  5785 D BtGatt.GattService: stop()
,09-28 10:44:38.070  5785  5785 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 10:44:38.073  5785  5785 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:38.073  5785  5785 V BluetoothAdapterState: isTurningOn()=false
,09-28 10:44:38.073  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 10:44:38.073  5785  5785 V BluetoothAdapterState: isBleTurningOff()=true
09-28 10:44:38.074  5785  5802 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-28 10:44:38.074  5785  5802 D BluetoothAdapterProperties: Setting state to 10
09-28 10:44:38.074  5785  5802 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 10:44:38.075  5785  5802 I BluetoothAdapterState: Entering OffState
09-28 10:44:38.076   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 10:44:38.092  5785  5785 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 10:44:38.092  5785  5785 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 10:44:38.092  5785  5804 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-28 10:44:38.094  5785  5785 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-28 10:44:38.100  5785  5785 I art     : System.exit called, status: 0
,09-28 10:44:38.100  5785  5785 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 10:44:38.126   928  3554 I ActivityManager: Process com.android.bluetooth (pid 5785) has died
,09-28 10:44:38.168  5634  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:38.169  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:38.169  5634  5693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 10:44:38.169  5634  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:38.176  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:38.198   928   945 I ActivityManager: Start proc 5866:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 10:44:38.264  5866  5866 D AdapterServiceConfig: Adding HeadsetService
,09-28 10:44:38.265  5866  5866 D AdapterServiceConfig: Adding A2dpService
09-28 10:44:38.265  5866  5866 D AdapterServiceConfig: Adding HidService
09-28 10:44:38.265  5866  5866 D AdapterServiceConfig: Adding HealthService
09-28 10:44:38.265  5866  5866 D AdapterServiceConfig: Adding PanService
09-28 10:44:38.265  5866  5866 D AdapterServiceConfig: Adding GattService
,09-28 10:44:38.265  5866  5866 D AdapterServiceConfig: Adding BluetoothMapService
09-28 10:44:38.266  5866  5866 D AdapterServiceConfig: Adding SapService
,09-28 10:44:38.277   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68e0e02:true
,09-28 10:44:38.278  5866  5866 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 10:44:38.281  5866  5866 I bt_bluedroid: init
,09-28 10:44:38.281  5866  5878 I BluetoothAdapterState: Entering OffState
,09-28 10:44:38.283  5866  5879 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 10:44:38.283  5866  5879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 10:44:38.283  5866  5879 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-28 10:44:38.283  5866  5879 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 10:44:38.283  5866  5866 I bt_bluedroid: get_profile_interface socket
09-28 10:44:38.285  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:44:38.285  5866  5866 I bt_bluedroid: get_profile_interface sdp
,09-28 10:44:38.286  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:44:38.290  5866  5877 I bt_bluedroid: config_hci_snoop_log
,09-28 10:44:38.290   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 10:44:38.294  5866  5878 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 10:44:38.294  5866  5878 D BluetoothAdapterProperties: Setting state to 14
09-28 10:44:38.294  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 10:44:38.296  5866  5878 D BluetoothBondStateMachine: make
,09-28 10:44:38.297  5866  5883 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 10:44:38.300  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
09-28 10:44:38.300  5866  5866 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 10:44:38.302  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:38.302  5866  5866 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 10:44:38.303  5866  5866 D BtGatt.GattService: Received start request. Starting profile...
09-28 10:44:38.303  5866  5866 D BtGatt.GattService: start()
09-28 10:44:38.303  5866  5866 I bt_bluedroid: get_profile_interface gatt
,09-28 10:44:38.304  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:38.304  5866  5866 D BtGatt.AdvertiseManager: advertise manager created
,09-28 10:44:38.308  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:44:38.308  5866  5866 V BluetoothAdapterState: isTurningOn()=false
09-28 10:44:38.308  5866  5866 V BluetoothAdapterState: isBleTurningOn()=true
09-28 10:44:38.308  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:38.308  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 10:44:38.309  5866  5878 I bt_bluedroid: bt_bluedroid
09-28 10:44:38.309  5866  5879 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 10:44:38.310  5866  5879 I bt_hci  : start_up
,09-28 10:44:38.314  5866  5879 I bt_vendor: alloc value 0xf3d37871
09-28 10:44:38.315  5866  5879 I bt_vendor: init
,09-28 10:44:38.315  5866  5879 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 10:44:38.315  5866  5879 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 10:44:38.424  5866  5879 D bt_hci  : start_up starting async portion
,09-28 10:44:38.424  5866  5886 I bt_hci  : event_finish_startup
09-28 10:44:38.425  5866  5886 I bt_hci_h4: hal_open
09-28 10:44:38.425  5866  5886 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-28 10:44:38.423  5887  5887 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:44:38.426  5866  5886 I bt_userial_vendor: device fd = 54 open
,09-28 10:44:38.438  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:44:38.440  5866  5886 D bt_hwcfg: Chipset BCM4358A3
,09-28 10:44:38.440  5866  5886 D bt_hwcfg: Target name = [BCM4358A3]
09-28 10:44:38.441  5866  5886 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 10:44:38.678  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-28 10:44:38.819  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 10:44:38.820  5866  5886 D bt_hwcfg: Settlement delay -- 100 ms
09-28 10:44:38.820  5866  5886 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 10:44:38.944  5866  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 10:44:38.944  5866  5886 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-28 10:44:38.946  5866  5886 I bt_hwcfg: vendor lib fwcfg completed
,09-28 10:44:38.946  5866  5886 I bt_vendor: firmware callback
,09-28 10:44:38.946  5866  5886 I bt_hci  : firmware_config_callback
,09-28 10:44:38.955  5866  5889 I bt_btu  : btu_task pending for preload complete event
,09-28 10:44:38.955  5866  5889 I bt_btu_task: Bluetooth chip preload is complete
09-28 10:44:38.955  5866  5889 I bt_btu  : btu_task received preload complete event
,09-28 10:44:38.962  5866  5889 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 10:44:38.963  5866  5889 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-28 10:44:38.963  5866  5889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 10:44:38.963  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 10:44:38.963  5866  5889 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-28 10:44:38.963  5866  5889 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 10:44:38.963  5866  5889 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_PAN
,09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-28 10:44:38.964  5866  5889 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 10:44:39.047  5866  5889 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cb5549
,09-28 10:44:39.047  5866  5889 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cb5549 
,09-28 10:44:39.058  5866  5882 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 10:44:39.059  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 10:44:39.060  5866  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 10:44:39.062  5866  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 10:44:39.065  5866  5882 D BluetoothAdapterProperties: Scan Mode:20
,09-28 10:44:39.065  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 10:44:39.065  5866  5882 D bt_hci  : do_postload posting postload work item
,09-28 10:44:39.065  5866  5886 I bt_hci  : event_postload
,09-28 10:44:39.066  5866  5886 I bt_vendor: sco_config_cb
09-28 10:44:39.066  5866  5886 I bt_hci  : sco_config_callback postload finished.
,09-28 10:44:39.067  5866  5882 D bt_bte_conf: Device ID record 1 : primary
09-28 10:44:39.067  5866  5882 D bt_bte_conf:   vendorId            = 000f
09-28 10:44:39.067  5866  5882 D bt_bte_conf:   vendorIdSource      = 0001
09-28 10:44:39.067  5866  5882 D bt_bte_conf:   product             = 1200
09-28 10:44:39.067  5866  5882 D bt_bte_conf:   version             = 1436
,09-28 10:44:39.068  5866  5882 D bt_bte_conf:   clientExecutableURL = 
09-28 10:44:39.068  5866  5882 D bt_bte_conf:   serviceDescription  = 
09-28 10:44:39.068  5866  5882 D bt_bte_conf:   documentationURL    = 
,09-28 10:44:39.068  5866  5882 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 10:44:39.068  5866  5879 D bt_stack_manager: event_start_up_stack finished
09-28 10:44:39.069  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 10:44:39.069  5866  5878 D BluetoothAdapterProperties: Setting state to 15
,09-28 10:44:39.070  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 10:44:39.071  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.072  5866  5878 I BluetoothAdapterState: Entering BleOnState
09-28 10:44:39.076  5866  5878 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-28 10:44:39.076  5866  5878 D BluetoothAdapterProperties: Setting state to 11
09-28 10:44:39.076  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-28 10:44:39.076  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.077  5866  5886 I bt_vendor: low_power_mode_cb
09-28 10:44:39.084  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:39.092  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.093  3151  3973 D BluetoothHeadset: Proxy object connected
09-28 10:44:39.093   928   928 D BluetoothHeadset: Proxy object connected
09-28 10:44:39.093  3151  3151 D HeadsetProfile: Bluetooth service connected
09-28 10:44:39.094  5866  5866 D HeadsetService: Received start request. Starting profile...
09-28 10:44:39.094  3791  4005 D BluetoothHeadset: Proxy object connected
09-28 10:44:39.094   928   928 D BluetoothHeadset: Proxy object connected
09-28 10:44:39.094   928   928 D BluetoothHeadset: Proxy object connected
,09-28 10:44:39.095  5738  5748 D BluetoothHeadset: Proxy object connected
,09-28 10:44:39.096  5866  5866 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 10:44:39.097  5866  5866 D HeadsetStateMachine: make
09-28 10:44:39.098  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.099  5738  5738 D HeadsetProfile: Bluetooth service connected
,09-28 10:44:39.109  5866  5878 I BluetoothAdapterState: Entering PendingCommandState
,09-28 10:44:39.111  5866  5866 D HeadsetStateMachine: max_hf_connections = 1
,09-28 10:44:39.111  5866  5866 I bt_bluedroid: get_profile_interface handsfree
09-28 10:44:39.111  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 10:44:39.111  5866  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-28 10:44:39.114  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:39.115  5866  5866 D A2dpService: Received start request. Starting profile...
09-28 10:44:39.115  5866  5866 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 10:44:39.116  5866  5866 I bt_bluedroid: get_profile_interface avrcp
,09-28 10:44:39.121  5866  5866 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 10:44:39.121  5866  5866 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 10:44:39.121  5866  5866 D A2dpStateMachine: make
09-28 10:44:39.122  5866  5866 I bt_bluedroid: get_profile_interface a2dp
,09-28 10:44:39.122  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 10:44:39.124  5866  5899 D A2dpStateMachine: Enter Disconnected: -2
,09-28 10:44:39.126  5866  5866 I BluetoothHidServiceJni: classInitNative: succeeds
,09-28 10:44:39.127  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:39.127  5866  5866 D HidService: Received start request. Starting profile...
09-28 10:44:39.127  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 10:44:39.128  5866  5866 I bt_bluedroid: get_profile_interface hidhost
09-28 10:44:39.128  5866  5866 D HidService: setHidService(): set to: null
09-28 10:44:39.128  5866  5882 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c9656d
09-28 10:44:39.128  5866  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 10:44:39.128  5866  5866 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 10:44:39.129  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:39.130  5866  5866 D HealthService: Received start request. Starting profile...
,09-28 10:44:39.131  5866  5866 I bt_bluedroid: get_profile_interface health
,09-28 10:44:39.131  5866  5866 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 10:44:39.132  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:39.133  5866  5866 D PanService: Received start request. Starting profile...
,09-28 10:44:39.133  5866  5866 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 10:44:39.133  5866  5866 I bt_bluedroid: get_profile_interface pan
09-28 10:44:39.133  5866  5882 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 10:44:39.135  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
09-28 10:44:39.136  5866  5866 D BluetoothMapService: Received start request. Starting profile...
09-28 10:44:39.136  5866  5866 D BluetoothMapService: start()
,09-28 10:44:39.138  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 10:44:39.139  5866  5866 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 10:44:39.139  5866  5866 D BluetoothMapAppObserver: createReceiver()
,09-28 10:44:39.140  5866  5866 D BluetoothMapAppObserver: initObservers()
09-28 10:44:39.140  5866  5866 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 10:44:39.147  5866  5866 V SapService: SapBinder()
,09-28 10:44:39.148  5866  5866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:39.148  5866  5866 D SapService: Received start request. Starting profile...
09-28 10:44:39.148  5866  5866 V SapService: start()
,09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.150  5866  5897 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.150  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isTurningOff()=false
,09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:39.151  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isTurningOn()=true
,09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isTurningOff()=false
09-28 10:44:39.152  5866  5866 V BluetoothAdapterState: isTurningOn()=true
09-28 10:44:39.153  5866  5866 V BluetoothAdapterState: isBleTurningOn()=false
09-28 10:44:39.153  5866  5866 V BluetoothAdapterState: isBleTurningOff()=false
09-28 10:44:39.153  5866  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 10:44:39.153  5866  5878 D BluetoothAdapterProperties: ScanMode =  20
09-28 10:44:39.153  5866  5878 D BluetoothAdapterProperties: State =  11
09-28 10:44:39.154  5866  5882 D BluetoothAdapterProperties: Scan Mode:21
,09-28 10:44:39.154  5866  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 10:44:39.155  5866  5878 D BluetoothAdapterProperties: Setting state to 12
09-28 10:44:39.155  5866  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 10:44:39.156  5866  5878 I BluetoothAdapterState: Entering OnState
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:39.158  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:39.160  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:39.164  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:39.165  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:44:39.165  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:39.166  5738  5749 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 10:44:39.166  5866  5866 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-28 10:44:39.167  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:39.168   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:39.168  3151  3162 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:44:39.169  5866  5866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:39.169   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:39.169   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:44:39.170  5738  5748 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 10:44:39.170  5738  5895 D BluetoothPan: onBluetoothStateChange on: true
09-28 10:44:39.170  5866  5866 D ObexServerSockets: Succeed to create listening sockets 
,09-28 10:44:39.170  5866  5866 D ObexServerSockets0: startAccept()
,09-28 10:44:39.171  5866  5866 D ObexServerSockets0: prepareForNewConnect()
09-28 10:44:39.172  3151  3970 D BluetoothPan: onBluetoothStateChange on: true
,09-28 10:44:39.172  5866  5866 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-28 10:44:39.172  5866  5866 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 10:44:39.173  5866  5905 D ObexServerSockets0: Accepting socket connection...
09-28 10:44:39.173  5866  5904 D ObexServerSockets0: Accepting socket connection...
09-28 10:44:39.173   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:39.174  3791  3824 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:39.174  5738  5738 D BluetoothInputDevice: Proxy object connected
,09-28 10:44:39.174  5738  5738 D HidProfile: Bluetooth service connected
09-28 10:44:39.174  3151  3161 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 10:44:39.174   928   928 D BluetoothA2dp: Proxy object connected
09-28 10:44:39.175  5738  5748 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 10:44:39.175  3151  3151 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:44:39.175  3151  3151 D PanProfile: Bluetooth service connected
09-28 10:44:39.176  3151  3162 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:44:39.178  3151  3161 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 10:44:39.178  3151  3151 D BluetoothA2dp: Proxy object connected
,09-28 10:44:39.180  5738  5895 D BluetoothMap: onBluetoothStateChange: up=true
09-28 10:44:39.181  3151  3151 D BluetoothInputDevice: Proxy object connected
09-28 10:44:39.181  3151  3151 D HidProfile: Bluetooth service connected
09-28 10:44:39.181  3151  3970 D BluetoothMap: onBluetoothStateChange: up=true
09-28 10:44:39.183  5738  5738 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 10:44:39.183  5738  5738 D PanProfile: Bluetooth service connected
09-28 10:44:39.183  5738  5738 D BluetoothMap: Proxy object connected
09-28 10:44:39.183  5738  5738 D MapProfile: Bluetooth service connected
09-28 10:44:39.183  5738  5738 D BluetoothMap: getConnectedDevices()
09-28 10:44:39.183  5738  5748 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:39.184  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:39.184  3151  3151 D BluetoothMap: Proxy object connected
09-28 10:44:39.184  3151  3151 D MapProfile: Bluetooth service connected
09-28 10:44:39.184  3151  3151 D BluetoothMap: getConnectedDevices()
09-28 10:44:39.186  5738  5738 D BluetoothA2dp: Proxy object connected
09-28 10:44:39.187  5866  5866 D BluetoothMapService: onReceive
09-28 10:44:39.187  5866  5866 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 10:44:39.187  5866  5866 D BluetoothMapService: STATE_ON
,09-28 10:44:39.188  5634  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:39.189  5634  5680 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-28 10:44:39.189   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 10:44:39.189   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-28 10:44:39.191   928  3593 D WifiService: setWifiEnabled: false pid=5634, uid=10077
09-28 10:44:39.191   928  3593 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-28 10:44:39.191  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.192  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:39.193  5738  5738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 10:44:39.194   928  2972 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-28 10:44:39.194   928  2972 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 10:44:39.194   928  2972 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:44:39.194   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 10:44:39.194  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.195  5866  5907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:39.198  5866  5907 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-28 10:44:39.198  5866  5907 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 10:44:39.202  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 10:44:39.203  5738  5738 D DockEventReceiver: finishStartingService: stopping service
09-28 10:44:39.207   928  5801 D DhcpClient: Clearing IP address
09-28 10:44:39.207   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:44:39.209  5738  5738 D BluetoothPbap: Proxy object connected
09-28 10:44:39.210  5738  5738 D PbapServerProfile: Bluetooth service connected
,09-28 10:44:39.213   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:39.214  5866  5866 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 10:44:39.214  5866  5866 D ObexServerSockets0: prepareForNewConnect()
,09-28 10:44:39.216  5866  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:39.218  3577  5834 V NativeCrypto: Read error: ssl=0x7f78218c00: I/O error during system call, Connection timed out
09-28 10:44:39.219   928  5803 D DhcpClient: Receive thread stopped
09-28 10:44:39.220  3577  5834 V NativeCrypto: SSL shutdown failed: ssl=0x7f78218c00: I/O error during system call, Broken pipe
09-28 10:44:39.221   928  3593 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-28 10:44:39.222   928  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-28 10:44:39.223   928  5799 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-28 10:44:39.224   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-28 10:44:39.224   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 10:44:39.225   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 10:44:39.227  3151  3151 D BluetoothPbap: Proxy object connected
09-28 10:44:39.227  3151  3151 D PbapServerProfile: Bluetooth service connected
,09-28 10:44:39.241   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-28 10:44:39.241   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-28 10:44:39.245   536   536 E Parcel  : Reading a NULL string not supported here.
09-28 10:44:39.246   928  2984 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-28 10:44:39.246   928   928 D RttService: SCAN_AVAILABLE : 1
09-28 10:44:39.246   928  3090 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 10:44:39.248  3755  3920 W QCNEJ   : |CORE| network lost: 101
09-28 10:44:39.248  3755  3920 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 10:44:39.249  5866  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 10:44:39.252  5866  5918 I BtOppRfcommListener: Accept thread started.
,09-28 10:44:39.257   928  2972 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 10:44:39.266   928  2972 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 10:44:39.273   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:39.292   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:39.293   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-28 10:44:39.293   928  2984 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 10:44:39.293   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 10:44:39.295   928   945 D Tethering: MasterInitialState.processMessage what=3
09-28 10:44:39.296   928  2972 D DhcpClient: doQuit
09-28 10:44:39.296   928  2972 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 10:44:39.297   928  5801 D DhcpClient: onQuitting
09-28 10:44:39.298  5734  5734 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:39.305  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:39.305  3702  3702 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 10:44:39.307  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:39.307  5051  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 10:44:39.307  5051  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-28 10:44:39.307  5051  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 10:44:39.307  5051  5073 E SarControlService: no key has been found,reset the power
09-28 10:44:39.307  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-28 10:44:39.308  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-28 10:44:39.308  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 10:44:39.308  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:39.309  5076  5076 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:39.309  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:39.310  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:44:39.310  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-28 10:44:39.310  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:44:39.310  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:44:39.310  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:39.310  5076  5076 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:39.312  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:39.313  3702  3702 D SystemUpdateService: onCreate
,09-28 10:44:39.314  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:44:39.314  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000ee03000000000000ffffffff]
09-28 10:44:39.314  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:44:39.314  5076  5090 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,09-28 10:44:39.315  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:39.315  5734  5734 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 10:44:39.315  5051  5062 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 10:44:39.316  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:39.317  3702  3702 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 10:44:39.318  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000ef03000000000000ffffffff]
09-28 10:44:39.319  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-28 10:44:39.319  5076  5090 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-28 10:44:39.320  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:39.320  5051  5061 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 10:44:39.322  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 10:44:39.325  3702  3702 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 10:44:39.329  3702  5924 I SystemUpdateService: active receiver: enabled
,09-28 10:44:39.332  3702  3702 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 10:44:39.333  3702  3702 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:44:39.335  5411  5411 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:44:39.339  5411  5411 D SprintDMHelper: simOperator: 
09-28 10:44:39.339  5411  5411 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:44:39.330  3702  5408 I iu.UploadsManager: num queued entries: 0
,09-28 10:44:39.348  3702  5408 I iu.UploadsManager: num updated entries: 0
,09-28 10:44:39.349  3702  5408 I iu.SyncManager: NEXT; no task
09-28 10:44:39.352  5026  5928 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 10:44:39.352   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-28 10:44:39.353   928  2984 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 10:44:39.353   928  2984 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 10:44:39.351  3702  5924 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:44:39.362  5734  5734 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 10:44:39.363  3702  5924 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 10:44:39.363  3702  5924 I SystemUpdateService: now status is 0 (complete)
09-28 10:44:39.363  3702  5924 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:44:39.364  3702  5924 I SystemUpdateService: file has been verified
09-28 10:44:39.364  3702  5924 I SystemUpdateService: OTA package size = 21989297
,09-28 10:44:39.368  3702  5924 I SystemUpdateService: showing system update notification
,09-28 10:44:39.377  3702  3702 D SystemUpdateService: onDestroy
,09-28 10:44:39.379  5734  5734 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 10:44:39.481   928  2972 D wifi    : In wifi stop Hal
,09-28 10:44:39.481   928  2972 D wifi    : halHandle = 0x7f76f91680, mVM = 0x7f9360d140, mCls = 0x101976
09-28 10:44:39.481   928  5733 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 10:44:39.481   928  5733 D WifiHAL : Got a signal to exit!!!
09-28 10:44:39.482   928  5733 I WifiHAL : Exit wifi_event_loop
,09-28 10:44:39.482   928  2972 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-28 10:44:39.483   928  2972 E WifiHAL : Event processing terminated
09-28 10:44:39.483   928  2972 D wifi    : In wifi cleaned up handler
09-28 10:44:39.483   928  2972 I WifiHAL : Internal cleanup completed
,09-28 10:44:39.481  5026  5026 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:44:39.488  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:39.492  4080  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 10:44:39.493  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:39.509   928  5733 D wifi    : set interface wlan0 flags (DOWN)
,09-28 10:44:39.509   928  2972 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:39.701  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:39.706  5634  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:39.710   928   939 D WifiService: setWifiEnabled: true pid=5634, uid=10077
09-28 10:44:39.710   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:39.714  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:39.716   928   945 D Tethering: InitialState.processMessage what=4
,09-28 10:44:39.717   507   922 D SoftapController: Softap fwReload - Ok
09-28 10:44:39.720   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 10:44:39.722   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:39.722   507   922 D CommandListener: Trying to bring down wlan0
,09-28 10:44:39.724   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-28 10:44:39.727   928  2972 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 10:44:40.215   928  3146 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 10:44:40.220   928  3146 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:40.335   928  2972 D wifi    : set interface wlan0 flags (UP)
,09-28 10:44:40.335   928  2972 I WifiHAL : Initializing wifi
09-28 10:44:40.335   928  2972 I WifiHAL : Creating socket
,09-28 10:44:40.339   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 10:44:40.345   928  2972 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 10:44:40.346   928  2972 D wifi    : Did set static halHandle = 0x7f76f91680
,09-28 10:44:40.346   928  2972 D wifi    : halHandle = 0x7f76f91680, mVM = 0x7f9360d140, mCls = 0x2018aa
,09-28 10:44:40.346   928  2972 D wifi    : array field set
09-28 10:44:40.346   928  2972 I WifiNative-HAL: interface[0] = wlan0
09-28 10:44:40.348   928  5932 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547456882304
09-28 10:44:40.349   928  5932 D wifi    : waitForHalEvents called, vm = 0x7f9360d140, obj = 0x2018aa, env = 0x7f74cb8300
,09-28 10:44:40.395  5933  5933 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 10:44:40.417  5933  5933 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:44:40.428  5933  5933 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 10:44:40.428  5933  5933 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 10:44:40.449   928  2972 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 10:44:40.456  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:40.463   928  2972 D WifiConfigStore: Loading config and enabling all networks 
,09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:40.463  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 10:44:40.465  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:40.470  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:40.472  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 10:44:40.473   928  2972 D WifiConfigStore: loaded 0 passpoint configs
09-28 10:44:40.473   928  2972 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 10:44:40.474  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 10:44:40.474   928  2972 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-28 10:44:40.475   928  2972 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-28 10:44:40.476   928  2972 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 10:44:40.476   928  2972 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 10:44:40.476   928  2972 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 10:44:40.476   928  2972 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 10:44:40.479   928  2972 D WifiNative-HAL: Setting external_sim to 1
,09-28 10:44:40.479  5026  5026 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 10:44:40.480   928  2972 D wifi    : setting dfs flag to true, 0x7f79f3c0e0
,09-28 10:44:40.480   928  2972 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 10:44:40.480   928  2972 D wifi    : setting scan oui 0x7f79f3c0e0
09-28 10:44:40.481   928  2972 D WifiHAL : Sending mac address OUI
,09-28 10:44:40.485   928  2972 E native  : do suspend false
,09-28 10:44:40.492   928  2972 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-28 10:44:40.492   928   928 D RttService: SCAN_AVAILABLE : 3
09-28 10:44:40.492   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 10:44:40.492   928  3090 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 10:44:40.493   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:40.496   928  2955 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-28 10:44:40.496   928  2955 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 10:44:40.505   928  2955 D WifiNative-HAL: p2pGetDeviceAddress
09-28 10:44:40.505   928  2955 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 10:44:40.510   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=254337 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-28 10:44:40.526   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:40.725  5634  5693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:40.731  5634  5693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:40.734  5634  5680 D BluetoothAdapter: enable(): BT is already enabled..!
,09-28 10:44:40.735   928   938 D WifiService: setWifiEnabled: true pid=5634, uid=10077
09-28 10:44:40.735   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 10:44:40.736  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:44:40.736  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:44:40.737  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 10:44:40.737  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-28 10:44:40.737  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c6fa39 removed from the list
09-28 10:44:40.737  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 10:44:40.737  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0c187e removed from the list
09-28 10:44:40.737  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:44:40.738  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 10:44:40.738  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:44:40.740  5634  5680 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,09-28 10:44:40.742  5634  5680 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-28 10:44:40.745  5634  5935 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-28 10:44:40.745  5634  5935 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 10:44:41.272  5634  5937 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-28 10:44:41.272  5634  5935 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-28 10:44:41.273  5634  5937 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:44:41.274  5634  5935 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-28 10:44:41.274  5634  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:44:41.274  5634  5935 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:44:41.277  5634  5937 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:44:41.277  5634  5935 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:44:41.280  5634  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: IncomingSocketThread/Sender)
,09-28 10:44:41.282  5634  5937 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 10:44:41.282  5634  5935 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-28 10:44:41.284  5634  5940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
09-28 10:44:41.284  5634  5942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Receiver)
,09-28 10:44:41.286  5634  5942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: OutgoingSocketThread/Receiver)
,09-28 10:44:41.286  5634  5941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Receiver)
09-28 10:44:41.286  5634  5942 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 10:44:41.286  5634  5942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 10:44:41.287  5634  5941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: IncomingSocketThread/Receiver)
09-28 10:44:41.288  5634  5941 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-28 10:44:41.288  5634  5941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 10:44:41.527   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:41.751  5634  5680 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-28 10:44:41.752  5634  5680 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-28 10:44:41.756  5634  5680 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-28 10:44:41.760  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-28 10:44:41.761  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 10:44:41.763  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
09-28 10:44:41.763  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 10:44:41.764  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-28 10:44:41.769  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-28 10:44:41.770  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fb43a Bundle[{}]
09-28 10:44:41.770  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-28 10:44:41.771  5634  5680 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 10:44:41.771  5634  5680 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-28 10:44:41.771  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-28 10:44:41.772  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-28 10:44:41.772  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-28 10:44:41.772  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-28 10:44:41.773  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-28 10:44:41.773  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-28 10:44:41.773  5634  5680 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
09-28 10:44:41.774  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-28 10:44:41.775  5634  5680 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
09-28 10:44:41.778  5634  5680 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-28 10:44:41.780  5634  5680 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
09-28 10:44:41.780  5634  5680 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
09-28 10:44:41.781  5634  5680 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
09-28 10:44:41.782  5634  5680 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
09-28 10:44:41.783  5634  5680 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-28 10:44:41.786  5634  5943 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-28 10:44:41.786  5634  5943 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 10:44:41.790  5634  5943 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-28 10:44:41.791  5634  5943 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:44:41.791  5634  5943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:44:41.791  5634  5943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:44:41.792  5634  5945 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-28 10:44:41.792  5634  5945 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 10:44:41.792  5634  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: OutgoingSocketThread/Sender)
,09-28 10:44:41.792  5634  5945 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 10:44:41.792  5634  5943 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 10:44:41.793  5634  5945 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:44:41.794  5634  5945 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 10:44:41.794  5634  5948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: IncomingSocketThread/Sender)
,09-28 10:44:41.797  5634  5947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: OutgoingSocketThread/Receiver)
,09-28 10:44:41.797  5634  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: IncomingSocketThread/Receiver)
,09-28 10:44:41.797  5634  5947 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: OutgoingSocketThread/Receiver)
09-28 10:44:41.797  5634  5947 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 10:44:41.797  5634  5947 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 10:44:41.798  5634  5949 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: IncomingSocketThread/Receiver)
,09-28 10:44:41.798  5634  5949 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 10:44:41.798  5634  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 10:44:42.291  5634  5680 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-28 10:44:42.293  5634  5680 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,09-28 10:44:42.295  5634  5680 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-28 10:44:42.299  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-28 10:44:42.321  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-28 10:44:42.322  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-28 10:44:42.322  5634  5680 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 188)
,09-28 10:44:42.323  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
09-28 10:44:42.323  5634  5680 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-28 10:44:42.323  5634  5680 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 189)
09-28 10:44:42.324  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-28 10:44:42.326  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-28 10:44:42.327  5634  5680 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
09-28 10:44:42.327  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 10:44:42.327  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eaddcfb added. We now have 3 listener(s)
,09-28 10:44:42.329  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 10:44:42.329  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 10:44:42.329  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 10:44:42.329  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 10:44:42.329  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7dc118 added. We now have 3 listener(s)
09-28 10:44:42.329  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 10:44:42.330  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 10:44:42.332  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 10:44:42.335  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 10:44:42.342  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 10:44:42.342  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 10:44:42.343  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:42.345  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 10:44:42.347  5634  5680 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,09-28 10:44:42.347  5634  5680 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-28 10:44:42.347  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-28 10:44:42.348  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-28 10:44:42.348  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-28 10:44:42.348  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 10:44:42.348  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 10:44:42.348  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:42.349  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 10:44:42.349  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 10:44:42.349  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 10:44:42.349  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:44:42.350  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-28 10:44:42.349  5876  5876 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35928]" dev="sockfs" ino=35928 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:42.350  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-28 10:44:42.350  5634  5950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:42.350  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:42.351  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 10:44:42.352  5634  5950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:44:42.349  5876  5876 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35928]" dev="sockfs" ino=35928 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 10:44:42.357  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:44:42.357  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:44:42.360  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:44:42.361  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 10:44:42.361  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:44:42.362  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 10:44:42.362  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:42.362  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-28 10:44:42.363  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:42.363  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:42.363  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-28 10:44:42.363  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 10:44:42.366  5866  5906 D BtGatt.GattService: registerClient() - UUID=9dece13b-cdf6-43c1-b36b-94d1b02f3c61
09-28 10:44:42.367  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=9dece13b-cdf6-43c1-b36b-94d1b02f3c61, clientIf=5
,09-28 10:44:42.367  5634  5765 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:42.369  5866  5884 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:42.371  5866  5884 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:42.381  5866  5882 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:42.386  5866  5882 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:42.387  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-28 10:44:42.387  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:44:42.388  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:44:42.389  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:42.390  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:44:42.390  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:44:42.390  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 10:44:42.390  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 10:44:42.390  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-28 10:44:42.393  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:42.393  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:42.528   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:42.894  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-28 10:44:42.894  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 10:44:42.895  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 10:44:43.528   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:43.707  5933  5933 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:43.715  5933  5933 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:43.721  5933  5933 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:43.728  5933  5933 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 10:44:43.756   928  2972 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 10:44:43.757   928  2972 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-28 10:44:43.757   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:44:43.768   928  2972 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 10:44:43.801   928  2972 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 10:44:43.803  5933  5933 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 10:44:44.226  5933  5933 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 10:44:44.262  5933  5933 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 10:44:44.264  5933  5933 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 10:44:44.275   928  2972 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:44:44.275   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 10:44:44.275   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 10:44:44.293   928  2972 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 10:44:44.305   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:44.311   928  2972 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 10:44:44.317   928  5955 D DhcpClient: Receive thread started
,09-28 10:44:44.322   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 10:44:44.322   928  2972 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 10:44:44.322   928  2984 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 10:44:44.403   928  2972 E native  : do suspend false
,09-28 10:44:44.417   928  5954 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 10:44:44.431   928  5955 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,09-28 10:44:44.432   928  5954 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,09-28 10:44:44.434   928  5954 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 10:44:44.450   928  5955 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 10:44:44.450   928  5954 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 10:44:44.454   507   922 D CommandListener: Setting iface cfg
,09-28 10:44:44.459   928  2972 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 10:44:44.466   928  5954 D DhcpClient: Scheduling renewal in 86399s
,09-28 10:44:44.478   928  2972 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 10:44:44.480   928  2972 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 10:44:44.482   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 10:44:44.484   928  2984 D ConnectivityService: Adding iface wlan0 to network 102
,09-28 10:44:44.503   928  2972 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 10:44:44.529   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 10:44:44.543   928  2984 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 10:44:44.544   928  2984 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-28 10:44:44.546   928  2984 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-28 10:44:44.553   928  2984 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-28 10:44:44.558   928  2984 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 10:44:44.566   928  2984 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:44:44.570   928  2984 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-28 10:44:44.571   928  2984 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 10:44:44.571   928  2984 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 10:44:44.571   928  2972 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 10:44:44.571   928  2984 D ConnectivityService:    accepting network in place of null
09-28 10:44:44.571   928  2972 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 10:44:44.571   928  2984 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 10:44:44.584   928  5953 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 10:44:44.595   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:44.617   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 10:44:44.621   928  2984 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-28 10:44:44.621  3755  3920 W QCNEJ   : |CORE| network available: 102
,09-28 10:44:44.621   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 10:44:44.622   928  2984 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-28 10:44:44.623   928   945 D Tethering: MasterInitialState.processMessage what=3
09-28 10:44:44.625  3755  3920 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 10:44:44.627  3755  3920 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 10:44:44.627  3755  3920 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:44.632  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 10:44:44.635  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:44.638  3702  3702 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 10:44:44.640  5051  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 10:44:44.640  5051  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 10:44:44.640  5051  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 10:44:44.640  5051  5073 E SarControlService: no key has been found,reset the power
09-28 10:44:44.640  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 10:44:44.640  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 10:44:44.640  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 10:44:44.641  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:44.641  5076  5076 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-28 10:44:44.641  5051  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 10:44:44.641  5051  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:44.641  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:44.641  5051  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 10:44:44.642  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 10:44:44.642  5076  5076 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-28 10:44:44.643  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 10:44:44.645  3702  3702 D SystemUpdateService: onCreate
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 10:44:44.647  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 10:44:44.648  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000f003000000000000ffffffff]
09-28 10:44:44.648  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:44:44.648  5076  5090 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-28 10:44:44.648  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:44.649  5051  5062 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 10:44:44.649  5076  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca3ef56 HexData = [00000000f103000000000000ffffffff]
09-28 10:44:44.649  5076  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 10:44:44.649  5076  5090 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 10:44:44.650  5076  5076 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 10:44:44.650  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 10:44:44.650  5051  5061 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 10:44:44.650  3702  3702 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 10:44:44.660  3702  3702 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-28 10:44:44.663   928  5952 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,09-28 10:44:44.664  3702  5408 I iu.UploadsManager: num queued entries: 0
,09-28 10:44:44.664  3702  5408 I iu.UploadsManager: num updated entries: 0
09-28 10:44:44.665  3702  5408 I iu.SyncManager: NEXT; no task
,09-28 10:44:44.668  3702  5965 I SystemUpdateService: active receiver: enabled
,09-28 10:44:44.670  3702  3702 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 10:44:44.671  3702  3702 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 10:44:44.673  5411  5411 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 10:44:44.676  5411  5411 D SprintDMHelper: simOperator: 
09-28 10:44:44.676  5411  5411 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 10:44:44.701  3702  5965 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 10:44:44.711  3702  5965 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 10:44:44.711  3702  5965 I SystemUpdateService: now status is 0 (complete)
09-28 10:44:44.711  3702  5965 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 10:44:44.711  3702  5965 I SystemUpdateService: file has been verified
09-28 10:44:44.711  3702  5965 I SystemUpdateService: OTA package size = 21989297
,09-28 10:44:44.717  3702  5965 I SystemUpdateService: showing system update notification
,09-28 10:44:44.727  3702  3702 D SystemUpdateService: onDestroy
,09-28 10:44:44.741   928  5952 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 14:44:44 GMT], X-Android-Received-Millis=[1475073884740], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475073884699]}
09-28 10:44:44.741   928  2984 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 10:44:44.742   928  2984 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-28 10:44:44.742   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 10:44:44.743   928  2984 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 10:44:44.802  5026  5970 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 10:44:44.962   928  2984 D ConnectivityService: handlePromptUnvalidated 101
,09-28 10:44:45.530   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 10:44:45.621   928  2984 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-28 10:44:45.892  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-28 10:44:45.892  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 10:44:45.892  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 10:44:45.892  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:44:45.893  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 10:44:45.893  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:44:45.893  5634  5950 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-28 10:44:45.893  5634  5950 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:44:45.893  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 10:44:45.894  5634  5950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 10:44:45.894  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 10:44:45.894  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:44:45.894  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:44:45.894  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:44:45.894  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 10:44:45.894  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:44:45.898  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:45.898  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 10:44:45.898  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:45.898  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 10:44:45.900  5866  5884 D BtGatt.AdvertiseManager: message : 1
,09-28 10:44:45.902  5866  5884 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:45.916  5866  5882 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-28 10:44:45.916  5866  5882 D BtGatt.GattService: Client app is not null!
,09-28 10:44:45.919  5866  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 10:44:45.920  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:44:45.920  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-28 10:44:45.921  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-28 10:44:45.921  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-28 10:44:45.921  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-28 10:44:45.923  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:45.923  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 10:44:45.923  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:44:45.924  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 10:44:45.926  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 10:44:45.926  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-28 10:44:45.926  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:44:45.927  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:45.927  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:45.927  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:44:45.935  5634  5680 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,09-28 10:44:45.935  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 10:44:45.936  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 10:44:45.936  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 10:44:45.937  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 10:44:45.937  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 10:44:45.937  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 10:44:45.942  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 10:44:45.942  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 10:44:45.947  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 10:44:45.949  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:44:45.949  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 10:44:45.955  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 10:44:45.955  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-28 10:44:45.956  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:44:45.958  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:45.961  5866  5906 D BtGatt.GattService: registerClient() - UUID=7342eebb-b4d8-4640-84ac-c3018784bd6a
09-28 10:44:45.962  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=7342eebb-b4d8-4640-84ac-c3018784bd6a, clientIf=5
09-28 10:44:45.962  5634  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:45.964  5866  5877 D BtGatt.GattService: start scan with filters
,09-28 10:44:45.970  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 10:44:45.970  5866  5885 D BtGatt.ScanManager: handling starting scan
,09-28 10:44:45.971  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:44:45.971  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 10:44:45.971  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 10:44:45.974  5866  5885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2afdecf
,09-28 10:44:45.976  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 10:44:45.976  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:44:45.976  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 10:44:45.978  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 10:44:45.984  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 10:44:45.984  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:45.985  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:44:45.994  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 10:44:45.994  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:45.995  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:44:45.995  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 10:44:46.011  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:44:46.011  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:46.019  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 10:44:46.019  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:46.477  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 10:44:46.478  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:44:46.478  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 10:44:47.342   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:44:48.026   928  2972 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 18 -> obsolete
,09-28 10:44:48.036   928  2972 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 18 -> obsolete
,09-28 10:44:48.985  5634  5680 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
09-28 10:44:48.985  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-28 10:44:48.985  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-28 10:44:48.986  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 10:44:48.986  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 10:44:48.989  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 10:44:48.991  5866  5877 D BtGatt.GattService: stopScan() - queue size =1
09-28 10:44:48.994  5866  5894 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 10:44:48.995  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:48.995  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:44:48.995  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 10:44:48.995  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 10:44:48.995  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 10:44:48.996  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 10:44:48.998  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 10:44:49.002  5866  5866 D BtGatt.ScanManager: awakened up at time 262829
09-28 10:44:49.002  5866  5896 D BtGatt.GattService: registerClient() - UUID=5a12e49d-45cb-4b8e-9e47-3b779faac609
09-28 10:44:49.003  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=5a12e49d-45cb-4b8e-9e47-3b779faac609, clientIf=5
,09-28 10:44:49.003  5634  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 10:44:49.005  5866  5877 D BtGatt.GattService: start scan with filters
09-28 10:44:49.008  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 10:44:49.008  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:49.008  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 10:44:49.008  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 10:44:49.008  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
09-28 10:44:49.008  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:49.009  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 10:44:49.009  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 10:44:49.009  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 10:44:49.010  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 10:44:49.010  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 10:44:49.011  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-28 10:44:49.011  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 10:44:49.011  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-28 10:44:49.011  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 10:44:49.011  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 10:44:49.011  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 10:44:49.012  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:49.012  5634  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 10:44:49.013  5896  5896 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33203]" dev="sockfs" ino=33203 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:49.013  5896  5896 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33203]" dev="sockfs" ino=33203 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 10:44:49.014  5866  5877 D BtGatt.GattService: stopScan() - queue size =0
09-28 10:44:49.015  5866  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 10:44:49.015  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 10:44:49.015  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:49.015  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:49.015  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 10:44:49.015  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 10:44:49.015  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 10:44:49.016  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 10:44:49.016  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 10:44:49.016  5634  5978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 10:44:49.017  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:49.018  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 10:44:49.023  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-28 10:44:49.023  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 10:44:49.023  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
,09-28 10:44:49.023  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:49.023  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 10:44:49.023  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 10:44:49.024  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:49.027  5866  5896 D BtGatt.GattService: registerClient() - UUID=a20a6d40-5de8-4b0a-bcd7-3905bee47938
09-28 10:44:49.027  5866  5882 D BtGatt.GattService: onClientRegistered() - UUID=a20a6d40-5de8-4b0a-bcd7-3905bee47938, clientIf=5
,09-28 10:44:49.027  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-28 10:44:49.029  5866  5884 D BtGatt.AdvertiseManager: message : 0
,09-28 10:44:49.032  5866  5884 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 10:44:49.033  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-28 10:44:49.033  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:49.033  5866  5882 D BtGatt.GattService: current time is 262860216229
,09-28 10:44:49.033  5866  5882 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -87, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 10:44:49.034  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 10:44:49.034  5866  5885 D BtGatt.ScanManager: handling starting scan
09-28 10:44:49.035  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 10:44:49.035  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 10:44:49.035  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-28 10:44:49.036  5866  5882 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-28 10:44:49.046  5866  5882 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 10:44:49.050  5866  5882 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 10:44:49.050  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:49.050  5866  5885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 10:44:49.054  5866  5882 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 10:44:49.055  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-28 10:44:49.055  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 10:44:49.056  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 10:44:49.058  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:49.058  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:44:49.058  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 10:44:49.058  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 10:44:49.058  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-28 10:44:49.059  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-28 10:44:49.059  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-28 10:44:49.059  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 10:44:49.059  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:49.059  5866  5885 D BtGatt.ScanManager: Starting BLE batch scan
09-28 10:44:49.059  5866  5885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 10:44:49.062  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-28 10:44:49.062  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 10:44:49.068  5866  5882 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 10:44:49.068  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:49.074  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 10:44:49.074  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:49.080  5866  5882 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 10:44:49.080  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:49.081  5866  5885 D BtGatt.ScanManager: stopping BLe Batch
,09-28 10:44:49.086  5866  5882 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 10:44:49.086  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 10:44:49.086  5866  5885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 10:44:49.091  5866  5882 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-28 10:44:49.091  5866  5882 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 10:44:49.563  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-28 10:44:49.563  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 10:44:49.563  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 10:44:50.369   928  2984 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 10:44:52.562  5634  5680 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
09-28 10:44:52.563  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 10:44:52.563  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 10:44:52.563  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 10:44:52.564  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 10:44:52.564  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 10:44:52.564  5634  5978 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 10:44:52.564  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 10:44:52.564  5634  5978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 10:44:52.565  5634  5978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 10:44:52.565  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 10:44:52.565  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 10:44:52.565  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eaddcfb removed from the list
09-28 10:44:52.565  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 10:44:52.565  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 10:44:52.565  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 10:44:52.565  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 10:44:52.565  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 10:44:52.566  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 10:44:52.568  5634  5680 D BluetoothAdapter: STATE_ON
09-28 10:44:52.568  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 10:44:52.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 10:44:52.569  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-28 10:44:52.571  5866  5884 D BtGatt.AdvertiseManager: message : 1
09-28 10:44:52.572  5866  5884 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 10:44:52.572   928  2984 D ConnectivityService: handlePromptUnvalidated 102
,09-28 10:44:52.587  5866  5882 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-28 10:44:52.587  5866  5882 D BtGatt.GattService: Client app is not null!
,09-28 10:44:52.589  5866  5906 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 10:44:52.590  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 10:44:52.590  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-28 10:44:52.590  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-28 10:44:52.590  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-28 10:44:52.590  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-28 10:44:52.594  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 10:44:52.595  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 10:44:52.595  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 10:44:52.596  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 10:44:52.598  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7dc118 removed from the list
09-28 10:44:52.598  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:52.598  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 10:44:52.598  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 10:44:52.598  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 10:44:52.598  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 10:44:52.602  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-28 10:44:52.602  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-28 10:44:52.602  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 10:44:52.602  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 10:44:52.602  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 10:44:52.604  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 10:44:52.604  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 10:44:52.605  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,09-28 10:44:52.607  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-28 10:44:52.609  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-28 10:44:52.610  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-28 10:44:52.611  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-28 10:44:52.612  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-28 10:44:52.612  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,09-28 10:44:52.614  5634  5680 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,09-28 10:44:52.615  5634  5680 I StreamCopyingThreadTest: Starting test: testRun
,09-28 10:44:52.619  5634  5980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 202, name: My test thread name)
,09-28 10:44:53.099  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 10:44:54.162  5634  5980 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 202
,09-28 10:44:54.162  5634  5980 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 202, name: My test thread name)
09-28 10:44:54.162  5634  5980 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 202, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-28 10:44:54.624  5634  5680 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-28 10:44:54.627  5634  5982 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: My test thread name)
,09-28 10:44:54.628  5634  5982 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 204, thread name: My test thread name)
09-28 10:44:54.628  5634  5982 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-28 10:44:54.631  5634  5680 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-28 10:44:54.633  5634  5680 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 10:44:54.637  5634  5680 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-28 10:44:54.640  5634  5983 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 208, name: My test thread name)
09-28 10:44:54.641  5634  5983 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 208, thread name: My test thread name): Test exception.
,09-28 10:44:54.641  5634  5983 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 208, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 10:44:54.643  5634  5680 E com.test.thalitest.ThaliTestRunner: testStart(io.jxcore.node.ConnectionHelperTest)
,09-28 10:44:54.644  5634  5680 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
09-28 10:44:54.644  5634  5680 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-28 10:44:54.644  5634  5680 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStart(ConnectionHelperTest.java:286)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at o,rg.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:72)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:54.647  5634  5680 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-28 10:44:54.651  5634  5680 I jxcore-log: *Native tests were executed*
09-28 10:44:54.651  5634  5680 I jxcore-log: 
09-28 10:44:54.651  5634  5680 I jxcore-log: Total number of executed tests:  82
09-28 10:44:54.651  5634  5680 I jxcore-log: 
09-28 10:44:54.652  5634  5680 I jxcore-log: Number of passed tests:  81
09-28 10:44:54.652  5634  5680 I jxcore-log: 
,09-28 10:44:54.653  5634  5680 I jxcore-log: Number of failed tests:  1
09-28 10:44:54.653  5634  5680 I jxcore-log: 
09-28 10:44:54.653  5634  5680 I jxcore-log: Number of ignored tests:  0
09-28 10:44:54.653  5634  5680 I jxcore-log: 
,09-28 10:44:54.655  5634  5680 I jxcore-log: Total duration:  30481
09-28 10:44:54.655  5634  5680 I jxcore-log: 
,09-28 10:44:54.656  5634  5680 I jxcore-log: Failed to execute UT.
09-28 10:44:54.656  5634  5680 I jxcore-log: 
,09-28 10:44:54.656  5634  5680 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-28 10:44:54.656  5634  5680 I jxcore-log: 
,09-28 10:44:54.664  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.664  5634  5680 I jxcore-log: 
09-28 10:44:54.670  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.670  5634  5680 I jxcore-log: 
09-28 10:44:54.672  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.672  5634  5680 I jxcore-log: 
09-28 10:44:54.674  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-28 10:44:54.674  5634  5680 I jxcore-log: 
09-28 10:44:54.676  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-28 10:44:54.676  5634  5680 I jxcore-log: 
,09-28 10:44:54.678  5634  5634 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-28 10:44:54.679  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-28 10:44:54.679  5634  5680 I jxcore-log: 
,09-28 10:44:54.683  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.683  5634  5680 I jxcore-log: 
,09-28 10:44:54.685  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.685  5634  5680 I jxcore-log: 
09-28 10:44:54.686  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.686  5634  5680 I jxcore-log: 
09-28 10:44:54.687  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.687  5634  5680 I jxcore-log: 
,09-28 10:44:54.689  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-28 10:44:54.689  5634  5680 I jxcore-log: 
,09-28 10:44:54.690  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-28 10:44:54.690  5634  5680 I jxcore-log: 
09-28 10:44:54.691  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-28 10:44:54.691  5634  5680 I jxcore-log: 
09-28 10:44:54.691  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-28 10:44:54.691  5634  5680 I jxcore-log: 
09-28 10:44:54.692  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.692  5634  5680 I jxcore-log: 
,09-28 10:44:54.694  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.694  5634  5680 I jxcore-log: 
,09-28 10:44:54.695  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.695  5634  5680 I jxcore-log: 
,09-28 10:44:54.696  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.696  5634  5680 I jxcore-log: 
,09-28 10:44:54.698  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.698  5634  5680 I jxcore-log: 
,09-28 10:44:54.699  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.699  5634  5680 I jxcore-log: 
,09-28 10:44:54.700  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.700  5634  5680 I jxcore-log: 
,09-28 10:44:54.701  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.701  5634  5680 I jxcore-log: 
09-28 10:44:54.702  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.702  5634  5680 I jxcore-log: 
09-28 10:44:54.703  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.703  5634  5680 I jxcore-log: 
,09-28 10:44:54.705  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.705  5634  5680 I jxcore-log: 
,09-28 10:44:54.706  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.706  5634  5680 I jxcore-log: 
09-28 10:44:54.707  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.707  5634  5680 I jxcore-log: 
,09-28 10:44:54.708  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.708  5634  5680 I jxcore-log: 
,09-28 10:44:54.709  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.709  5634  5680 I jxcore-log: 
09-28 10:44:54.710  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.710  5634  5680 I jxcore-log: 
,09-28 10:44:54.711  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.711  5634  5680 I jxcore-log: 
,09-28 10:44:54.712  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.712  5634  5680 I jxcore-log: 
09-28 10:44:54.712  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.712  5634  5680 I jxcore-log: 
09-28 10:44:54.713  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-28 10:44:54.713  5634  5680 I jxcore-log: 
,09-28 10:44:54.714  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-28 10:44:54.714  5634  5680 I jxcore-log: 
,09-28 10:44:54.715  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-28 10:44:54.715  5634  5680 I jxcore-log: 
09-28 10:44:54.716  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.716  5634  5680 I jxcore-log: 
09-28 10:44:54.716  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.716  5634  5680 I jxcore-log: 
,09-28 10:44:54.717  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.717  5634  5680 I jxcore-log: 
,09-28 10:44:54.718  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-28 10:44:54.718  5634  5680 I jxcore-log: 
09-28 10:44:54.719  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-28 10:44:54.719  5634  5680 I jxcore-log: 
09-28 10:44:54.719  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.719  5634  5680 I jxcore-log: 
,09-28 10:44:54.721  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.721  5634  5680 I jxcore-log: 
,09-28 10:44:54.722  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-28 10:44:54.722  5634  5680 I jxcore-log: 
,09-28 10:44:54.723  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-28 10:44:54.723  5634  5680 I jxcore-log: 
,09-28 10:44:54.724  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-28 10:44:54.724  5634  5680 I jxcore-log: 
,09-28 10:44:54.725  5634  5680 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-28 10:44:54.725  5634  5680 I jxcore-log: 
,09-28 10:44:55.173  5984  5984 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-28 10:44:55.179  5984  5984 D AndroidRuntime: CheckJNI is OFF
,09-28 10:44:55.212  5984  5984 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-28 10:44:55.247  5984  5984 I Radio-JNI: register_android_hardware_Radio DONE
,09-28 10:44:55.264  5984  5984 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-28 10:44:55.271   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-28 10:44:55.272   928   941 I ActivityManager: Killing 5634:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-28 10:44:55.318   928  3554 D GraphicsStats: Buffer count: 2
,09-28 10:44:55.319   928  3593 I WindowState: WIN DEATH: Window{2a4337 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-28 10:44:55.319   928  2982 D WifiService: Client connection lost with reason: 4
,09-28 10:44:55.419   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-28 10:44:55.420   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-28 10:44:55.421   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-28 10:44:55.421   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-28 10:44:55.421   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:55.421   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:55.421   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:44:55.421   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 10:44:55.421   928   941 I ActivityManager:   Force finishing activity ActivityRecord{2acf298 u0 com.test.thalitest/.MainActivity t2}
,09-28 10:44:55.426   928   939 W ActivityManager: Spurious death for ProcessRecord{3d58285 0:com.test.thalitest/u0a77}, curProc for 5634: null
,09-28 10:44:55.427   928   951 I art     : Starting a blocking GC Explicit
,09-28 10:44:55.432   928   946 W WindowManager: Attempted to add application window with unknown token Token{f1dcaf1 ActivityRecord{2acf298 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-28 10:44:55.433   928   946 W WindowManager: Token{f1dcaf1 ActivityRecord{2acf298 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{f1dcaf1 ActivityRecord{2acf298 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
,09-28 10:44:55.434   928   946 W WindowManager: view not successfully added to wm, removing view
09-28 10:44:55.434   928   946 W WindowManager: Exception when adding starting window
09-28 10:44:55.434   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{7b30e94 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-28 10:44:55.434   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-28 10:44:55.434   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-28 10:44:55.434   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-28 10:44:55.434   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-28 10:44:55.434   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-28 10:44:55.434   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 10:44:55.434   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:55.434   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:44:55.434   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 10:44:55.507   928  2972 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,09-28 10:44:55.518   928   951 I art     : Explicit concurrent mark sweep GC freed 51240(3MB) AllocSpace objects, 10(352KB) LOS objects, 33% free, 29MB/43MB, paused 1.646ms total 90.853ms
,09-28 10:44:55.540   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-28 10:44:55.542  5984  5984 I art     : System.exit called, status: 0
,09-28 10:44:55.543  5984  5984 I AndroidRuntime: VM exiting with result code 0.
,09-28 10:44:55.548   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-28 10:44:55.558   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-28 10:44:55.565  5866  5866 D BluetoothMapAppObserver: onReceive
,09-28 10:44:55.565  5866  5866 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-28 10:44:55.566  3662  3662 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-28 10:44:55.570  4080  4167 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-28 10:44:55.579   928  2921 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-28 10:44:55.600  3662  5995 I Keyboard.Facilitator.DecoderInitializer: run()
,09-28 10:44:55.597  3401  5996 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-28 10:44:55.617  3791  3791 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-28 10:44:55.616    17    17 W kworker/2:0: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:44:55.619    17    17 W kworker/2:0: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:44:55.627  3577  3577 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-28 10:44:55.627  3577  3577 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-28 10:44:55.636  3662  5995 I Decoder : createOrResetDecoder
,09-28 10:44:55.640   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-28 10:44:55.640  3702  6001 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-28 10:44:55.643    17    17 W kworker/2:0: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 10:44:55.641  3702  6001 D AccountUtils: Clearing selected account for com.test.thalitest
,09-28 10:44:55.642  3836  3940 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-28 10:44:55.656   928  3146 I ActivityManager: Start proc 6003:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-28 10:44:55.657  3836  3940 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-28 10:44:55.657  3836  3940 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3836
09-28 10:44:55.657  3836  3940 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 10:44:55.657  3836  3940 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: Can't write: system_app_crash
09-28 10:44:55.660   928  6011 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 10:44:55.660   928  6011 E DropBoxManagerService: 	... 5 more
09-28 10:44:55.661   928  3554 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-28 10:44:55.664  3836  3940 I Process : Sending signal. PID: 3836 SIG: 9
,09-28 10:44:55.756  3577  3577 I ConfigService: onCreate
,09-28 10:44:55.809   928  3146 D GraphicsStats: Buffer count: 1
,09-28 10:44:55.809   928  3593 I WindowState: WIN DEATH: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
,09-28 10:44:55.814   928   939 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3836) has died
,09-28 10:44:55.814   928   939 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-28 10:44:55.822   928   946 E WindowState: getStack: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{a8f9429 token=Token{3bfbdb0 ActivityRecord{e6e0cf3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,09-28 10:44:55.822   928   946 E WindowState: getStack: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{a8f9429 token=Token{3bfbdb0 ActivityRecord{e6e0cf3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
09-28 10:44:55.822   928   946 E WindowState: getStack: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{a8f9429 token=Token{3bfbdb0 ActivityRecord{e6e0cf3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
09-28 10:44:55.823   928   946 E WindowState: getStack: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{a8f9429 token=Token{3bfbdb0 ActivityRecord{e6e0cf3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-28 10:44:55.823   928   946 E WindowState: getStack: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{a8f9429 token=Token{3bfbdb0 ActivityRecord{e6e0cf3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
09-28 10:44:55.823   928   946 E WindowState: getStack: Window{708372 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{a8f9429 token=Token{3bfbdb0 ActivityRecord{e6e0cf3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,09-28 10:44:56.007   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
