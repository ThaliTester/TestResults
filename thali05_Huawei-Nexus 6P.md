#### Test 873356089b310a6_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 08:52:55.012   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 08:52:55.012   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 08:52:55.534  5597  5597 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 08:52:55.540  5597  5597 D AndroidRuntime: CheckJNI is OFF
09-30 08:52:55.573  5597  5597 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 08:52:55.609  5597  5597 I Radio-JNI: register_android_hardware_Radio DONE
09-30 08:52:55.625  5597  5597 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 08:52:55.630   931   942 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 08:52:55.675   931   942 I ActivityManager: Start proc 5606:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 08:52:55.680  5597  5597 D AndroidRuntime: Shutting down VM
,09-30 08:52:56.011   931  3724 I WindowManager: Screenshot max retries 4 of Token{bf49d62 ActivityRecord{844b42d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{4c53be5 u0 Starting com.test.thalitest} drawState=4
,09-30 08:52:56.085  5606  5606 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 08:52:56.121  5606  5606 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 08:52:56.147  5606  5606 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 1033-1053)
09-30 08:52:56.147  5606  5606 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 08:52:56.167  5606  5606 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {70e1df5}
09-30 08:52:56.167  5606  5606 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 08:52:56.168  5606  5606 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 08:52:56.173  5606  5606 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 08:52:56.174  5606  5606 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 08:52:56.209  5606  5606 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 08:52:56.222  5606  5606 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 08:52:56.222  5606  5606 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 08:52:56.222  5606  5606 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 08:52:56.222  5606  5606 I Adreno  : Build Date                       : 12/06/15
09-30 08:52:56.222  5606  5606 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 08:52:56.222  5606  5606 I Adreno  : Local Branch                     : mybranch17112971
09-30 08:52:56.222  5606  5606 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 08:52:56.222  5606  5606 I Adreno  : Remote Branch                    : NONE
09-30 08:52:56.222  5606  5606 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 08:52:56.284   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6224ce0:true
,09-30 08:52:56.323   657   657 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23310]" dev="sockfs" ino=23310 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 08:52:56.323   657   657 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23310]" dev="sockfs" ino=23310 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 08:52:56.341  5606  5606 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 08:52:56.352  5606  5606 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 08:52:56.382  5606  5643 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-30 08:52:56.380   656   656 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33343]" dev="sockfs" ino=33343 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 08:52:56.380   656   656 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33343]" dev="sockfs" ino=33343 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 08:52:56.383  3090  3090 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23321]" dev="sockfs" ino=23321 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 08:52:56.383  3090  3090 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[23321]" dev="sockfs" ino=23321 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 08:52:56.389  5606  5630 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 08:52:56.408  5606  5643 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 08:52:56.479   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +467ms (total +832ms)
,09-30 08:52:56.508  5606  5606 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5606
,09-30 08:52:56.598  5606  5606 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 08:52:56.800  5606  5646 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -560985808
,09-30 08:52:56.806  5606  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 08:52:56.806  5606  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 08:52:56.806  5606  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 08:52:56.806  5606  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 08:52:56.806  5606  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-30 08:52:56.806  5606  5646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77ceca2 added. We now have 1 listener(s)
,09-30 08:52:56.809  5606  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-30 08:52:56.810  5606  5646 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:52:56.811  5606  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:52:56.811  5606  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-30 08:52:56.814  5606  5646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b386e69 added. We now have 1 listener(s)
09-30 08:52:56.814  5606  5646 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:52:56.825   931  2917 D WifiService: New client listening to asynchronous messages
,09-30 08:52:56.826  5606  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:52:56.826  5606  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-30 08:52:56.826  5606  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 08:52:56.826  5606  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-30 08:52:56.826  5606  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-30 08:52:56.829  5606  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:52:56.829  5606  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 08:52:56.834  5606  5646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:52:56.834  5606  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:52:56.834  5606  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 08:52:56.834  5606  5646 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:52:56.835  5606  5646 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 08:52:56.838  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:52:56.841  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:52:56.855  5606  5606 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 08:52:57.030   931  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:52:57.575  5606  5606 I Choreographer: Skipped 40 frames!  The application may be doing too much work on its main thread.
,09-30 08:52:57.958  5606  5615 I art     : Background sticky concurrent mark sweep GC freed 76975(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.379ms total 244.883ms
,09-30 08:52:58.217  5606  5653 W jxcore-log: Initializing JXcore engine
09-30 08:52:58.217  5606  5653 W jxcore-log: JXcore engine is ready
,09-30 08:52:58.263  5653  5653 W Thread-62: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12332 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-30 08:52:58.263  5653  5653 W Thread-62: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14389]" dev="sockfs" ino=14389 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 08:52:58.263  5653  5653 W Thread-62: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 08:52:58.263  5653  5653 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33323]" dev="sockfs" ino=33323 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 08:52:58.275  5606  5653 W jxcore-log: Starting JXcore engine
,09-30 08:52:58.329  5606  5653 W jxcore-log: Platform android
09-30 08:52:58.329  5606  5653 W jxcore-log: 
,09-30 08:52:58.329  5606  5653 W jxcore-log: Process ARCH arm
09-30 08:52:58.329  5606  5653 W jxcore-log: 
,09-30 08:52:58.427  5606  5653 I jxcore-log: JXcore Cordova bridge is ready!
09-30 08:52:58.427  5606  5653 I jxcore-log: 
,09-30 08:52:58.427  5606  5653 W jxcore-log: JXcore engine is started
,09-30 08:52:58.440  5606  5646 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 08:52:58.446  5606  5606 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 08:53:05.013   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:06.015   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:07.016   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:08.018   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:08.278  5606  5653 I jxcore-log: 2016-09-30 12:53:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 08:53:08.278  5606  5653 I jxcore-log: 
,09-30 08:53:08.279  5606  5653 I jxcore-log: 2016-09-30 12:53:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 08:53:08.279  5606  5653 I jxcore-log: 
,09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:08.283  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:53:08.285  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:53:08.286  5606  5653 I jxcore-log: 2016-09-30 12:53:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 08:53:08.286  5606  5653 I jxcore-log: 
,09-30 08:53:08.288  5606  5653 I jxcore-log: 2016-09-30 12:53:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 08:53:08.288  5606  5653 I jxcore-log: 
,09-30 08:53:08.545  5606  5653 I jxcore-log: 2016-09-30 12:53:08 - DEBUG UnitTest_app: 'Running unit tests'
09-30 08:53:08.545  5606  5653 I jxcore-log: 
,09-30 08:53:08.545  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:53:08.546  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d284d7 added. We now have 2 listener(s)
09-30 08:53:08.547  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:53:08.547  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 08:53:08.547  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:53:08.547  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:53:08.547  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36641c4 added. We now have 2 listener(s)
09-30 08:53:08.547  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:53:08.548  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:53:08.550  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:08.553  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:53:08.554  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.554  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:53:08.555  5606  5653 D executeNativeTests: Running unit tests
,09-30 08:53:08.562  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:08.569  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:08.595  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:53:08.595  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 added. We now have 3 listener(s)
,09-30 08:53:08.596  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:53:08.596  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:53:08.596  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:53:08.596  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:53:08.596  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 added. We now have 3 listener(s)
09-30 08:53:08.596  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:53:08.596  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:53:08.598  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:08.600  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:08.601  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.601  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 08:53:08.602  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 08:53:08.602  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:08.602  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:08.602  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:08.603  5606  5653 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-30 08:53:08.603  5606  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 08:53:08.603  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 08:53:08.603  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:53:08.603  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:53:08.603  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:53:08.604  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:08.604  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:08.604  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:08.604  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:08.604  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.604  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:53:08.604  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:08.604  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:53:08.604  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 removed from the list
09-30 08:53:08.604  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:08.604  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 removed from the list
,09-30 08:53:08.609  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:08.615  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:08.615  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:08.615  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:08.616  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.616  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:08.616  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:08.616  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:08.616  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:08.616  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:08.617  5606  5653 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 08:53:08.618  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:08.618  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:08.618  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:08.618  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:08.618  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.618  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:08.618  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:08.618  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:08.618  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:08.618  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:08.618  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:08.618  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.618  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:08.618  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.618  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:08.618  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:08.619  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:08.619  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:08.619  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 08:53:08.621  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 08:53:08.622  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:08.622  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:08.622  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:08.622  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:08.622  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.622  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:08.622  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:08.622  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:08.622  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:08.622  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:08.622  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:08.622  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.622  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:08.622  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:08.622  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:08.623  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:08.623  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:08.623  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:08.623  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:08.623  5606  5653 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 08:53:08.624  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:08.626  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:08.627  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:08.627  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:53:08.627  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:53:08.627  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:53:08.627  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:53:08.627  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:08.627  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 08:53:08.629  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:08.631  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:08.631  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:53:08.631  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:53:08.633  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 08:53:08.634  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:53:08.634  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 08:53:08.635  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 08:53:08.636  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 08:53:08.637  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 08:53:08.637  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:53:08.637  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:53:08.637  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:53:08.637  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:53:08.637  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:53:08.639  4533  4746 D BtGatt.GattService: registerClient() - UUID=9fae4028-20b5-4a06-b785-57f7275e40ea
09-30 08:53:08.641  4533  4594 D BtGatt.GattService: onClientRegistered() - UUID=9fae4028-20b5-4a06-b785-57f7275e40ea, clientIf=5
09-30 08:53:08.641  5606  5617 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:53:08.643  4533  4547 D BtGatt.GattService: start scan with filters
09-30 08:53:08.650  4533  4597 D BtGatt.ScanManager: handling starting scan
09-30 08:53:08.650  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:53:08.650  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:53:08.650  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:53:08.650  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:53:08.650  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:53:08.650  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:53:08.651  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:53:08.652  4533  4597 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:53:08.655  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:53:08.655  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:53:08.656  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:53:08.656  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:53:08.657  5606  5653 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 08:53:08.660  4533  4594 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:53:08.660  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:08.661  4533  4597 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:53:08.669  4533  4594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:53:08.669  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:08.669  4533  4597 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:53:08.669  4533  4597 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:53:08.679  4533  4594 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:53:08.680  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:08.685  4533  4594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:53:08.685  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:09.019   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:09.158  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 08:53:09.158  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 08:53:09.158  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 08:53:10.020   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 08:53:10.926   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:53:13.661  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:53:13.661  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:13.661  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:53:13.662  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:13.662  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 08:53:13.662  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:53:13.662  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:53:13.662  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:53:13.662  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:53:13.662  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:53:13.663  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:53:13.663  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:53:13.664  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:53:13.665  4533  4547 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:53:13.667  4533  4766 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:53:13.668  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:53:13.668  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:53:13.669  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:53:13.669  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 08:53:13.669  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:53:13.669  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:53:13.669  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:53:13.670  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 08:53:13.672  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:13.673  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:53:13.673  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:53:13.673  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:53:13.674  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:53:13.675  4533  4533 D BtGatt.ScanManager: awakened up at time 238581
09-30 08:53:13.676  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:53:13.680  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:13.680  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:13.680  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:13.680  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:13.681  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:53:13.681  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:13.681  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:13.681  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:13.681  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:13.681  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:13.681  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:13.681  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:13.686  4533  4594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:53:13.686  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:13.687  4533  4597 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:53:13.697  4533  4594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 08:53:13.697  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:13.697  4533  4597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:53:13.719  4533  4594 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-30 08:53:13.719  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:13.719  4533  4594 D BtGatt.GattService: current time is 238625737252
09-30 08:53:13.720  4533  4594 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -76, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -71, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 08:53:13.721  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 08:53:13.722  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 08:53:13.722  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 08:53:13.722  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 08:53:13.723  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 08:53:13.723  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-30 08:53:13.947   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:53:13.952   931  2918 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-30 08:53:14.182  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:53:15.021   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:16.023   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:16.980   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:53:16.993   931  2918 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 08:53:17.023   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:18.025   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:18.683  5606  5653 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 08:53:18.689  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:18.701  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:53:18.704  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:18.705  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:53:18.705  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:53:18.705  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:53:18.705  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:53:18.705  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:18.705  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 08:53:18.710  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:53:18.710  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:53:18.710  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:18.715  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:18.715  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:53:18.717  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:53:18.717  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 08:53:18.722  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 08:53:18.722  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:53:18.722  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:53:18.722  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:53:18.722  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:53:18.723  5606  5653 D BluetoothAdapter: STATE_ON
,09-30 08:53:18.726  4533  4547 D BtGatt.GattService: registerClient() - UUID=476f8272-fb10-4640-b2b1-3ff06448cf1e
09-30 08:53:18.726  4533  4594 D BtGatt.GattService: onClientRegistered() - UUID=476f8272-fb10-4640-b2b1-3ff06448cf1e, clientIf=5
09-30 08:53:18.727  5606  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:53:18.727  4533  4546 D BtGatt.GattService: start scan with filters
,09-30 08:53:18.730  4533  4597 D BtGatt.ScanManager: handling starting scan
,09-30 08:53:18.731  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:53:18.731  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-30 08:53:18.731  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:53:18.731  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:53:18.731  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:53:18.731  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:53:18.731  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:53:18.734  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:53:18.734  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:53:18.734  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:53:18.736  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:53:18.738  4533  4594 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:53:18.738  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.739  4533  4597 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:53:18.739  5606  5653 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 08:53:18.744  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:18.744  5606  5653 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 08:53:18.744  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:18.744  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:53:18.744  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:18.744  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:53:18.744  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:18.745  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:53:18.745  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:53:18.745  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:53:18.745  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:53:18.745  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:53:18.745  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:53:18.746  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:53:18.746  4533  4594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:53:18.746  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:18.746  4533  4597 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:53:18.746  4533  4597 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:53:18.747  4533  4546 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:53:18.748  4533  4766 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 08:53:18.748  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:53:18.748  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:53:18.748  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:53:18.748  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:53:18.748  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:53:18.748  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:53:18.748  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:53:18.749  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:53:18.750  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:18.750  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:53:18.750  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:53:18.750  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:53:18.750  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 08:53:18.751  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:53:18.754  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:18.754  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:18.754  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:18.754  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:18.754  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:53:18.754  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:18.754  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:18.754  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:18.754  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:18.754  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:18.754  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:18.754  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:18.755  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:18.755  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:18.756  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:18.756  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:18.756  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:18.756  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:18.757  5606  5653 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 08:53:18.760  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:53:18.762  4533  4594 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 08:53:18.762  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:18.768  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:18.768  4533  4594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 08:53:18.768  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.770  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:18.770  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:53:18.770  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:53:18.770  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:53:18.770  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:53:18.771  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:18.771  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 08:53:18.773  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:18.774  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 08:53:18.774  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:53:18.775  4533  4594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:53:18.775  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.775  4533  4597 D BtGatt.ScanManager: stopping BLe Batch
09-30 08:53:18.777  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:53:18.779  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:18.780  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 08:53:18.780  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 08:53:18.781  4533  4594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:53:18.781  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.781  4533  4597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 08:53:18.783  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 08:53:18.783  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:53:18.783  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:53:18.783  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:53:18.783  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:53:18.784  5606  5653 D BluetoothAdapter: STATE_ON
,09-30 08:53:18.786  4533  4594 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 08:53:18.787  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.787  4533  4766 D BtGatt.GattService: registerClient() - UUID=49aded64-96d0-4c71-a109-cd747b3f8e03
,09-30 08:53:18.788  4533  4594 D BtGatt.GattService: onClientRegistered() - UUID=49aded64-96d0-4c71-a109-cd747b3f8e03, clientIf=5
,09-30 08:53:18.788  5606  5617 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 08:53:18.789  4533  4546 D BtGatt.GattService: start scan with filters
,09-30 08:53:18.791  4533  4597 D BtGatt.ScanManager: handling starting scan
09-30 08:53:18.791  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:53:18.791  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:53:18.791  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:53:18.791  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:53:18.791  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:53:18.791  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:53:18.792  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 08:53:18.794  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:53:18.794  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:53:18.795  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 08:53:18.796  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 08:53:18.798  4533  4594 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:53:18.798  5606  5653 I io.jxcore.node.ConnectionHelper: start: OK
09-30 08:53:18.798  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.799  4533  4597 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 08:53:18.804  4533  4594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:53:18.804  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:18.804  4533  4597 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:53:18.804  4533  4597 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 08:53:18.813  4533  4594 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:53:18.813  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:18.818  4533  4594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:53:18.818  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:19.026   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:19.296  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 08:53:19.296  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:53:19.296  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 08:53:20.024   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:53:20.027   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 08:53:23.053   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:53:23.799  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:53:23.799  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:23.799  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:53:23.799  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:23.800  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:53:23.800  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:53:23.800  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:53:23.800  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:53:23.800  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 08:53:23.800  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:53:23.801  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:53:23.801  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:53:23.803  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:53:23.804  4533  4547 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:53:23.806  4533  4746 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:53:23.808  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 08:53:23.809  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 08:53:23.809  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:53:23.809  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:53:23.810  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:53:23.810  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:53:23.810  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:53:23.811  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:53:23.812  4533  4533 D BtGatt.ScanManager: awakened up at time 248718
,09-30 08:53:23.816  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:23.816  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:53:23.816  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-30 08:53:23.816  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:53:23.816  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:53:23.817  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:53:23.819  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:23.820  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:23.820  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:23.821  4533  4594 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:53:23.821  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:23.822  4533  4597 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:53:23.831  4533  4594 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:53:23.831  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:53:23.831  4533  4597 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:53:23.851  4533  4594 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 08:53:23.852  4533  4594 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:53:23.853  4533  4594 D BtGatt.GattService: current time is 248759149408
09-30 08:53:23.853  4533  4594 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -71, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -76, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -75, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 08:53:23.854  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-30 08:53:23.854  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 08:53:23.854  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 08:53:23.855  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 08:53:23.856  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 08:53:23.856  4533  4594 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-30 08:53:24.321  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:53:24.322  5606  5606 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:24.322  5606  5606 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 08:53:28.820  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:53:28.821  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:28.821  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.821  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:53:28.821  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.822  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:53:28.822  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:53:28.822  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
,09-30 08:53:28.822  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.822  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:28.822  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.822  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.825  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.826  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.830  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:53:28.831  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.831  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.831  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.833  5606  5653 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-30 08:53:28.837  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.837  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:28.838  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.838  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.838  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.838  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.838  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.838  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.838  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.838  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:28.838  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.839  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.839  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.839  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.839  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.842  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:53:28.842  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.842  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.842  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.844  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 08:53:28.844  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:53:28.845  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:28.845  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.845  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.845  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.845  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.845  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:53:28.845  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.845  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.845  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.846  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.846  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.846  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.846  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.846  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.848  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:28.848  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.848  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.848  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:28.850  5606  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 08:53:28.851  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.851  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:28.852  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.852  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.852  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.852  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.852  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.852  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.853  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.853  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:28.853  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.853  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.853  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.853  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.854  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.857  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:28.858  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:53:28.858  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.859  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.860  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 08:53:28.861  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.861  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:28.861  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.861  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.861  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.861  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.861  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.861  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.861  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.861  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.862  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:53:28.862  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.862  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.862  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.862  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.864  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:53:28.864  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.864  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.865  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.866  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 08:53:28.866  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:28.866  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:28.866  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 08:53:28.866  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-30 08:53:28.866  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:53:28.866  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 08:53:28.867  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:28.867  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 08:53:28.867  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.867  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:28.867  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.867  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.867  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.868  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.868  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.868  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.868  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.868  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.868  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.868  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.868  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.868  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.868  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.870  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:28.870  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.870  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:28.870  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.871  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:53:28.872  5606  5653 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 08:53:28.872  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-30 08:53:28.877  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-30 08:53:28.877  5606  5653 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 08:53:28.877  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 08:53:28.877  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 08:53:28.877  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 08:53:28.877  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 08:53:28.878  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 08:53:28.879  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 08:53:28.879  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 08:53:28.880  5606  5653 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 08:53:28.880  5606  5653 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 08:53:28.880  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:53:28.880  5606  5653 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 08:53:28.881  5606  5653 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 08:53:28.881  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:53:28.881  5606  5653 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 08:53:28.882  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-30 08:53:28.890  4746  4746 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31281]" dev="sockfs" ino=31281 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 08:53:28.893  4746  4746 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31281]" dev="sockfs" ino=31281 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 08:53:28.886  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-30 08:53:28.887  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-30 08:53:28.887  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 08:53:28.888  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 08:53:28.888  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 08:53:28.888  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 08:53:28.888  5606  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 08:53:28.888  5606  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
09-30 08:53:28.889  5606  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 08:53:28.889  5606  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,09-30 08:53:28.889  5606  5654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-30 08:53:28.888  5606  5653 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 08:53:28.891  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.891  5606  5654 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 08:53:28.891  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:28.891  5606  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:53:28.891  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.892  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.892  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.892  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.892  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.892  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 08:53:28.893  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.893  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.893  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.893  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.893  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.893  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.893  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.893  5606  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
09-30 08:53:28.893  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.893  5606  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
09-30 08:53:28.893  5606  5655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
09-30 08:53:28.895  5606  5654 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-30 08:53:28.895  5606  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 08:53:28.896  5606  5654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
09-30 08:53:28.898  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:28.898  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:53:28.898  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.898  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.899  5606  5653 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 08:53:28.900  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.900  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:28.900  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.900  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.900  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.900  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.901  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.901  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.901  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.901  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.901  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.901  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.901  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.901  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.901  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.902  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:53:28.903  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.903  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.903  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.904  5606  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-30 08:53:28.904  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.904  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:28.904  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.904  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.904  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.904  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.905  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.905  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.905  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.905  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.905  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.905  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.905  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.905  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.905  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:28.906  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:28.906  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.906  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.907  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.907  5606  5653 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 08:53:28.908  5606  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 08:53:28.908  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-30 08:53:28.908  5606  5653 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 08:53:28.908  5606  5653 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 08:53:28.908  5606  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 08:53:28.908  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 08:53:28.908  5606  5653 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 08:53:28.908  5606  5653 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 08:53:28.908  5606  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 08:53:28.908  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 08:53:28.908  5606  5653 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 08:53:28.908  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:28.909  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:28.909  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:28.909  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.909  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.909  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.909  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:28.909  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.909  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.909  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.909  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.909  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.909  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.909  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:28.909  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.911  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:28.911  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:28.911  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.911  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.912  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:28.912  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.912  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:28.912  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:53:28.912  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:28.912  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:28.912  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:28.912  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:28.912  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:28.912  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:30.028   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:31.029   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:32.029   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:33.031   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:33.913  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:33.914  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:33.914  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:53:33.914  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:33.914  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.914  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 08:53:33.915  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
,09-30 08:53:33.915  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:33.915  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:33.915  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:33.916  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:33.916  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.916  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.916  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:33.917  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:33.917  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:33.917  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.917  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:33.918  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.918  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:33.918  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.918  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.922  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:33.923  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:53:33.925  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.926  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:33.931  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-30 08:53:33.932  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:53:33.933  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 08:53:33.935  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-30 08:53:33.935  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,09-30 08:53:33.936  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-30 08:53:33.936  5606  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-30 08:53:33.936  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 08:53:33.936  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:53:33.936  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 08:53:33.937  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:53:33.937  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-30 08:53:33.937  5606  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:53:33.937  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 08:53:33.937  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 08:53:33.937  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.937  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,09-30 08:53:33.937  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 08:53:33.937  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:33.937  5606  5606 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 08:53:33.938  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.938  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:53:33.938  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 08:53:33.938  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:53:33.938  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.938  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.940  5606  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-30 08:53:33.941  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:33.941  5606  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 08:53:33.941  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.941  5606  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-30 08:53:33.941  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:33.941  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:53:33.941  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:33.941  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:53:33.936  4547  4547 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29623]" dev="sockfs" ino=29623 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 08:53:33.941  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:53:33.941  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:33.941  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 08:53:33.941  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:33.941  5606  5606 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:33.942  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.942  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.942  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:33.942  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:33.942  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.942  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.942  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:33.936  4547  4547 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29623]" dev="sockfs" ino=29623 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 08:53:33.942  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.942  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:33.942  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.942  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.945  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:33.945  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:33.945  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.945  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
,09-30 08:53:33.947  5606  5653 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-30 08:53:33.948  5606  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-30 08:53:33.948  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 08:53:33.948  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:53:33.948  5606  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 08:53:33.949  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:33.949  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:33.949  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:33.949  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:33.949  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.949  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.949  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:33.949  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:33.949  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:33.949  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.949  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:33.949  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.950  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.951  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.951  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.953  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:33.953  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:33.953  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.953  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.956  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 08:53:33.957  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:33.957  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:33.957  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:33.957  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.957  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.957  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:33.957  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:33.957  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.957  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.957  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:33.957  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.957  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:33.957  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.957  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.959  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:53:33.959  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:33.959  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.959  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.960  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:53:33.960  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:53:33.960  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:53:33.960  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:53:33.960  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.960  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:33.960  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:53:33.960  5606  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1d92 not in the list
09-30 08:53:33.960  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.960  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.961  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:53:33.961  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.961  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:53:33.961  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:33.961  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:33.962  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:53:33.962  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:53:33.962  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:53:33.962  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68e4363 not in the list
09-30 08:53:33.963  5606  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 08:53:33.963  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 08:53:33.963  5606  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-30 08:53:33.963  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 08:53:33.963  5606  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 08:53:33.963  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 08:53:33.965  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 08:53:33.965  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-30 08:53:33.966  5606  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 08:53:33.967  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 08:53:33.967  5606  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-30 08:53:33.967  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 08:53:33.967  5606  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 08:53:33.967  5606  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-30 08:53:33.967  5606  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-30 08:53:33.967  5606  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 08:53:33.968  5606  5653 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-30 08:53:33.968  5606  5653 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 08:53:33.968  5606  5653 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-30 08:53:33.968  5606  5653 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-30 08:53:33.969  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:53:33.969  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28f418d added. We now have 3 listener(s)
09-30 08:53:33.969  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:53:33.971  5606  5653 D BluetoothAdapter: enable(): BT is already enabled..!
09-30 08:53:33.971   931   942 D WifiService: setWifiEnabled: true pid=5606, uid=10077
09-30 08:53:33.972   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:53:34.021  4533  4726 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-30 08:53:34.021  4533  4744 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-30 08:53:34.031   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:34.442  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:53:35.032   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 08:53:37.033   931  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:53:38.159   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 08:53:38.977  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:53:38.977  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d060f42 added. We now have 4 listener(s)
,09-30 08:53:38.978  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:53:38.990  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:38.990  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d060f42 removed from the list
,09-30 08:53:38.991  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:53:38.991  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:53:38.991  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:38.993  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:53:38.993  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@346cb53 added. We now have 4 listener(s)
,09-30 08:53:38.993  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:53:38.997  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:53:38.998  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@346cb53 removed from the list
09-30 08:53:38.999  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:53:38.999  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:53:38.999  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:53:39.000  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:53:39.000  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c4a0c90 added. We now have 4 listener(s)
09-30 08:53:39.000  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:53:39.003   931  3809 D WifiService: setWifiEnabled: false pid=5606, uid=10077
09-30 08:53:39.003   931  3809 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:53:39.007   931  2916 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 08:53:39.007   931  2916 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 08:53:39.008   931  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 08:53:39.008   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 08:53:39.012  4533  4590 D BluetoothAdapterState: Current state: ON, message: 23
09-30 08:53:39.012  4533  4590 D BluetoothAdapterProperties: Setting state to 13
09-30 08:53:39.012  4533  4590 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 08:53:39.014  4533  4590 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 08:53:39.015  4533  4590 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:53:39.017  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:53:39.020  4533  4594 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:53:39.024  4533  4590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 08:53:39.024  4533  4533 D BluetoothMapService: onReceive
09-30 08:53:39.024  4533  4533 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 08:53:39.024  4533  4533 D BluetoothMapService: STATE_TURNING_OFF
09-30 08:53:39.024  4533  4533 D BluetoothMapService: MAP Service closeService in
09-30 08:53:39.024  4533  4533 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 08:53:39.025  4533  4533 D ObexServerSockets0: shutdown(block = true)
09-30 08:53:39.025  4533  4533 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-30 08:53:39.025  4533  4533 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 08:53:39.025  4533  4767 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 08:53:39.026  4533  4768 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 08:53:39.026  4533  4744 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 08:53:39.026  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:39.027  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:39.028  4533  4533 I BtOppRfcommListener: stopping Accept Thread
09-30 08:53:39.028  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.028  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:39.028  4533  5268 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 08:53:39.028  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:53:39.029  4533  5268 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-30 08:53:39.031   931  5342 D DhcpClient: Clearing IP address
09-30 08:53:39.031   508   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:53:39.032  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:39.034  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.038  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:39.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:53:39.039  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:39.039  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:39.039   508   925 D CommandListener: Setting iface cfg
09-30 08:53:39.042  3524  5396 V NativeCrypto: Read error: ssl=0x7f79c45700: I/O error during system call, Connection timed out
09-30 08:53:39.043   931  5343 D DhcpClient: Receive thread stopped
09-30 08:53:39.045  3524  5396 V NativeCrypto: SSL shutdown failed: ssl=0x7f79c45700: I/O error during system call, Broken pipe
09-30 08:53:39.047   931  3090 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-30 08:53:39.048   931  5340 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-30 08:53:39.048   931   944 I ActivityManager: Start proc 5660:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-30 08:53:39.048  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:39.048  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:39.050   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 08:53:39.050   931  5340 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-30 08:53:39.050  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.051  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:39.051   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 08:53:39.053   535   535 E Parcel  : Reading a NULL string not supported here.
,09-30 08:53:39.056  4533  4533 D HeadsetService: Received stop request...Stopping profile...
09-30 08:53:39.058  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.058  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:39.058  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.059  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:53:39.060   931   931 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:39.060   931   931 D BluetoothHeadset: Proxy object disconnected
,09-30 08:53:39.060   931   931 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:39.060  3057  3081 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:39.061  3727  3972 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:39.061  4533  4533 D A2dpService: Received stop request...Stopping profile...
09-30 08:53:39.061  4533  4749 D A2dpStateMachine: Exit Disconnected: -1
09-30 08:53:39.061  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.061  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:53:39.062  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.062   931   931 D RttService: SCAN_AVAILABLE : 1
09-30 08:53:39.062  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:39.063   931  3024 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 08:53:39.063   931   931 D BluetoothA2dp: Proxy object disconnected
,09-30 08:53:39.064  4533  4533 D HidService: Received stop request...Stopping profile...
,09-30 08:53:39.064  4533  4533 D HidService: Stopping Bluetooth HidService
09-30 08:53:39.064  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.065  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:39.065   931  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-30 08:53:39.066  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.066  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:39.067  3686  3851 W QCNEJ   : |CORE| network lost: 100
09-30 08:53:39.067  3686  3851 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-30 08:53:39.069  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.069  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:53:39.071  4533  4533 D HealthService: Received stop request...Stopping profile...
09-30 08:53:39.072   931  2916 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 08:53:39.073  4533  4533 D PanService: Received stop request...Stopping profile...
,09-30 08:53:39.074  4533  4533 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:39.074  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.074  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.074  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.076  4533  4533 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 08:53:39.076  4533  4533 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-30 08:53:39.076  4533  4594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 08:53:39.077  4533  4726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:39.077  4533  4726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:39.077  4533  4726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:39.077  4533  4594 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 08:53:39.077  4533  4533 D BluetoothMapService: Received stop request...Stopping profile...
09-30 08:53:39.077  4533  4533 D BluetoothMapService: stop()
09-30 08:53:39.078  4533  4533 D BluetoothMapAppObserver: deinitObservers()
09-30 08:53:39.078  4533  4533 D BluetoothMapAppObserver: removeReceiver()
09-30 08:53:39.078  3057  3057 D HeadsetProfile: Bluetooth service disconnected
09-30 08:53:39.079  3057  3057 D BluetoothA2dp: Proxy object disconnected
09-30 08:53:39.079  3057  3057 D BluetoothInputDevice: Proxy object disconnected
09-30 08:53:39.079  3057  3057 D HidProfile: Bluetooth service disconnected
09-30 08:53:39.079  4533  4533 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:39.079  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.079  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.079  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.079  4533  4533 D SapService: Received stop request...Stopping profile...
09-30 08:53:39.080  4533  4533 V SapService: stop()
09-30 08:53:39.081  4533  4726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isTurningOff()=true
,09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.082  4533  4726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.082  4533  4726 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:53:39.082  4533  4726 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 08:53:39.082  4533  4726 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:53:39.082  4533  4726 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 08:53:39.082  4533  4533 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 08:53:39.082  4533  4594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 08:53:39.082  4533  4533 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 08:53:39.082  4533  4594 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.082  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.082  4533  4533 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 08:53:39.083  3057  3057 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 08:53:39.083  3057  3057 D PanProfile: Bluetooth service disconnected
09-30 08:53:39.083  4533  4533 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 08:53:39.083  3057  3057 D BluetoothMap: Proxy object disconnected
09-30 08:53:39.083  3057  3057 D MapProfile: Bluetooth service disconnected
09-30 08:53:39.083  4533  4533 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:39.083   931  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:53:39.083  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.083  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.083  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.083  4533  4533 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-30 08:53:39.083  4533  4533 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 08:53:39.084  4533  4594 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 08:53:39.084  4533  4533 D BluetoothMapService: MAP Service closeService in
,09-30 08:53:39.084  4533  4533 V BluetoothAdapterState: isTurningOff()=true
,09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isTurningOn()=false
,09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.085  4533  4533 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:39.085  4533  4590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 08:53:39.085  4533  4533 D BluetoothMapService: cleanup()
09-30 08:53:39.085  4533  4590 D BluetoothAdapterProperties: Setting state to 15
09-30 08:53:39.085  4533  4533 D BluetoothMapService: MAP Service closeService in
,09-30 08:53:39.085  4533  4590 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 08:53:39.086  4533  4590 I BluetoothAdapterState: Entering BleOnState
09-30 08:53:39.088  3057  3075 D BluetoothMap: onBluetoothStateChange: up=false
09-30 08:53:39.089   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:39.089  3727  3973 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:39.089  3057  3921 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:53:39.090   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:53:39.090   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:39.090   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:39.090  3057  3923 D BluetoothPan: onBluetoothStateChange on: false
09-30 08:53:39.091  3057  3075 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:39.091  3057  3081 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 08:53:39.092  3057  3921 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 08:53:39.093  4533  4590 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 08:53:39.094  4533  4590 D BluetoothAdapterProperties: Setting state to 16
,09-30 08:53:39.094  4533  4590 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 08:53:39.094  5660  5660 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-30 08:53:39.095  4533  4590 D BluetoothAdapterProperties: onBleDisable
09-30 08:53:39.095  4533  4590 I BluetoothAdapterState: Entering PendingCommandState
09-30 08:53:39.095  4533  4591 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 08:53:39.096  4533  4726 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 08:53:39.096  4533  4726 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:39.097  4533  4594 D BluetoothAdapterProperties: Scan Mode:20
,09-30 08:53:39.098  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.098  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:53:39.100  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.100  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:53:39.101  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.102  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.103  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.104  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.105   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:53:39.113  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:53:39.119   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1586188:true
,09-30 08:53:39.124  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:53:39.126   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:53:39.127   508   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:53:39.127   931  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-30 08:53:39.127   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 08:53:39.128   508   925 D TetherController: Setting IP forward enable = 0
,09-30 08:53:39.138   931  3748 I ActivityManager: Start proc 5682:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 08:53:39.140   931  2916 D DhcpClient: doQuit
,09-30 08:53:39.140   931  2916 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 08:53:39.141   931  5342 D DhcpClient: onQuitting
,09-30 08:53:39.141  3416  3416 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 08:53:39.143   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:53:39.144  5238  5238 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@297aa31 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-30 08:53:39.145  4860  4860 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-30 08:53:39.148  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.148  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:39.148  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.148  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:39.150  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.150  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:39.151  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.151  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:39.151  5001  5031 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 08:53:39.151  5001  5031 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 08:53:39.152  5001  5031 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 08:53:39.152  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.152  5001  5031 E SarControlService: no key has been found,reset the power
,09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:39.153  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:39.153  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 08:53:39.153  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 08:53:39.153  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 08:53:39.153  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:39.153  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:39.153  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:53:39.153  5034  5034 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 08:53:39.154  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 08:53:39.155  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 08:53:39.155  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 08:53:39.155  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:53:39.155  5034  5034 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 08:53:39.158  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000ea03000000000000ffffffff]
09-30 08:53:39.158  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:53:39.158  5034  5048 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 08:53:39.158  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:53:39.158  3416  3416 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 08:53:39.158  5001  5014 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 08:53:39.158  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:39.160  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:39.161  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.170  3416  3416 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 08:53:39.173  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000eb03000000000000ffffffff]
,09-30 08:53:39.173  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:53:39.173  5034  5048 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 08:53:39.174  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:53:39.174  5001  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 08:53:39.176  5660  5660 D LocalBluetoothProfileManager: Adding local MAP profile
09-30 08:53:39.177  5660  5660 D BluetoothMap: Create BluetoothMap proxy object
,09-30 08:53:39.186  5660  5660 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 08:53:39.193   508   925 E Netd    : netlink response contains error (No such file or directory)
09-30 08:53:39.194   508   925 D TetherController: Setting IP forward enable = 0
,09-30 08:53:39.195   931  2918 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 08:53:39.195   931  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 08:53:39.199  3416  3416 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 08:53:39.201  5682  5682 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 08:53:39.204  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:53:39.212   931   942 I ActivityManager: Killing 4934:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 08:53:39.221  3416  3416 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 08:53:39.299  4533  4594 I bt_hci  : shut_down
,09-30 08:53:39.304  4533  4598 D bt_hwcfg: hw_epilog_process
,09-30 08:53:39.304  4533  4598 I bt_vendor: low_power_mode_cb
,09-30 08:53:39.306  4533  4598 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-30 08:53:39.306  4533  4598 I bt_vendor: epilog_cb
09-30 08:53:39.306  4533  4598 I bt_hci  : epilog_finished_callback
,09-30 08:53:39.309  4533  4594 I bt_hci_h4: hal_close
,09-30 08:53:39.309  4533  4594 I bt_userial_vendor: device fd = 54 close
,09-30 08:53:39.327   931  2916 D wifi    : In wifi stop Hal
09-30 08:53:39.327   931  2916 D wifi    : halHandle = 0x7f636e2680, mVM = 0x7f7fd0d140, mCls = 0x100a02
09-30 08:53:39.327   931  3415 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 08:53:39.327   931  3415 D WifiHAL : Got a signal to exit!!!
,09-30 08:53:39.327   931  3415 I WifiHAL : Exit wifi_event_loop
09-30 08:53:39.328   931  2916 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-30 08:53:39.328   931  2916 E WifiHAL : Event processing terminated
,09-30 08:53:39.328   931  2916 D wifi    : In wifi cleaned up handler
09-30 08:53:39.328   931  2916 I WifiHAL : Internal cleanup completed
,09-30 08:53:39.329  4021  4164 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:53:39.329  4975  4975 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:53:39.330  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.331  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.332  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:39.353   931  3415 D wifi    : set interface wlan0 flags (DOWN)
,09-30 08:53:39.353   931  2916 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.402  5682  5682 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.402  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.403  5682  5682 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:53:39.403  5682  5682 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:53:39.418  4533  4591 D bt_stack_manager: event_shut_down_stack finished.
09-30 08:53:39.419  4533  4590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-30 08:53:39.420  4533  4590 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 08:53:39.420  4533  4533 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 08:53:39.421  4533  4533 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 08:53:39.421  4533  4533 D BtGatt.GattService: stop()
09-30 08:53:39.421  4533  4533 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 08:53:39.422  4533  4533 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:39.422  4533  4533 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:39.422  4533  4533 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:39.422  4533  4533 V BluetoothAdapterState: isBleTurningOff()=true
09-30 08:53:39.423  4533  4590 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 08:53:39.423  4533  4590 D BluetoothAdapterProperties: Setting state to 10
09-30 08:53:39.423  4533  4590 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 08:53:39.424  4533  4590 I BluetoothAdapterState: Entering OffState
09-30 08:53:39.424   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-30 08:53:39.429  4533  4533 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-30 08:53:39.429  4533  4533 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 08:53:39.429  4533  4533 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 08:53:39.431  4533  4591 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-30 08:53:39.436  4533  4533 I art     : System.exit called, status: 0
09-30 08:53:39.436  4533  4533 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 08:53:39.465  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 08:53:39.468   931  3809 I ActivityManager: Process com.android.bluetooth (pid 4533) has died
09-30 08:53:39.482   931   941 I ActivityManager: Start proc 5724:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-30 08:53:39.487  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:53:39.488   931   942 I ActivityManager: Killing 5084:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-30 08:53:39.555   931   948 D Tethering: InitialState.processMessage what=4
,09-30 08:53:39.558   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding HeadsetService
,09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding A2dpService
09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding HidService
09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding HealthService
09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding PanService
09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding GattService
09-30 08:53:39.572  5724  5724 D AdapterServiceConfig: Adding BluetoothMapService
09-30 08:53:39.573  5724  5724 D AdapterServiceConfig: Adding SapService
09-30 08:53:39.575   931  3517 I ActivityManager: Killing 5418:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-30 08:53:39.597  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:53:39.605  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 08:53:39.608  3815  3815 D SystemUpdateService: onCreate
,09-30 08:53:39.612  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 08:53:39.620  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 08:53:39.624  3815  5366 I iu.UploadsManager: num queued entries: 0
,09-30 08:53:39.624  3815  5366 I iu.UploadsManager: num updated entries: 0
09-30 08:53:39.625  3815  5366 I iu.SyncManager: NEXT; no task
,09-30 08:53:39.628  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 08:53:39.630  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:53:39.641   931  3110 I ActivityManager: Start proc 5738:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 08:53:39.642  3815  5736 I SystemUpdateService: active receiver: enabled
,09-30 08:53:39.648  3815  5736 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:53:39.674  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 08:53:39.677  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:53:39.685  5738  5738 D SprintDMHelper: simOperator: 
,09-30 08:53:39.685  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:53:39.686  3815  5736 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-30 08:53:39.686  3815  5736 I SystemUpdateService: now status is 0 (complete)
,09-30 08:53:39.686  3815  5736 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 08:53:39.686  3815  5736 I SystemUpdateService: file has been verified
09-30 08:53:39.686  3815  5736 I SystemUpdateService: OTA package size = 21989297
,09-30 08:53:39.697   931  3808 I ActivityManager: Start proc 5750:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 08:53:39.699  3815  5736 I SystemUpdateService: showing system update notification
,09-30 08:53:39.722  3815  3815 D SystemUpdateService: onDestroy
,09-30 08:53:39.725   931  3090 I ActivityManager: Killing 5401:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-30 08:53:39.798  4975  5764 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 08:53:39.807   931  3724 I ActivityManager: Start proc 5765:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-30 08:53:39.810   931   941 I ActivityManager: Killing 5238:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 08:53:39.869  5765  5765 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-30 08:53:39.955  5682  5711 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 08:53:40.052   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2398ae7:true
,09-30 08:53:40.058   931   941 I ActivityManager: Killing 4605:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 08:53:40.100   931  3814 I ActivityManager: Start proc 5779:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 08:53:40.131  5779  5779 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 08:53:40.138   931   941 I ActivityManager: Killing 5467:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 08:53:44.031   931  3814 D WifiService: setWifiEnabled: true pid=5606, uid=10077
,09-30 08:53:44.032   931  3814 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:53:44.041   508   925 D SoftapController: Softap fwReload - Ok
,09-30 08:53:44.046   508   925 D CommandListener: Setting iface cfg
,09-30 08:53:44.046   508   925 D CommandListener: Trying to bring down wlan0
09-30 08:53:44.047   508   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:53:44.050   931  2916 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 08:53:44.630   931  2916 D wifi    : set interface wlan0 flags (UP)
,09-30 08:53:44.634   931  2916 I WifiHAL : Initializing wifi
09-30 08:53:44.635   931  2916 I WifiHAL : Creating socket
,09-30 08:53:44.638   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 08:53:44.646   931  2916 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 08:53:44.646   931  2916 D wifi    : Did set static halHandle = 0x7f636e2680
09-30 08:53:44.646   931  2916 D wifi    : halHandle = 0x7f636e2680, mVM = 0x7f7fd0d140, mCls = 0x2019de
09-30 08:53:44.647   931  2916 D wifi    : array field set
09-30 08:53:44.647   931  2916 I WifiNative-HAL: interface[0] = wlan0
,09-30 08:53:44.649   931  5799 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547129009792
09-30 08:53:44.649   931  5799 D wifi    : waitForHalEvents called, vm = 0x7f7fd0d140, obj = 0x2019de, env = 0x7f68dd4a80
,09-30 08:53:44.722  5800  5800 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 08:53:44.736  5800  5800 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:53:44.749   931  2916 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 08:53:44.752  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:44.754  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:44.755  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:44.763  5800  5800 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:53:44.763  5800  5800 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 08:53:44.777   931  2916 D WifiConfigStore: Loading config and enabling all networks 
,09-30 08:53:44.779  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:44.779  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:44.779  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:44.779  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:44.781  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:44.781  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:44.781  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:44.781  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:44.782  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:44.782  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:44.782  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:44.782  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:53:44.789   931  2916 D WifiConfigStore: loaded 0 passpoint configs
,09-30 08:53:44.789   931  2916 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 08:53:44.790   931  2916 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 08:53:44.791   931  2916 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 08:53:44.792   931  2916 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 08:53:44.792   931  2916 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 08:53:44.793   931  2916 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 08:53:44.793   931  2916 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 08:53:44.796   931  2916 D WifiNative-HAL: Setting external_sim to 1
09-30 08:53:44.797  4975  4975 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:53:44.797   931  2916 D wifi    : setting dfs flag to true, 0x7f6731b920
,09-30 08:53:44.798   931  2916 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 08:53:44.798   931  2916 D wifi    : setting scan oui 0x7f6731b920
09-30 08:53:44.798   931  2916 D WifiHAL : Sending mac address OUI
,09-30 08:53:44.802   931  2916 E native  : do suspend false
,09-30 08:53:44.808   931  2916 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-30 08:53:44.808   931   931 D RttService: SCAN_AVAILABLE : 3
09-30 08:53:44.809   931  3024 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 08:53:44.809   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 08:53:44.810   508   925 D CommandListener: Setting iface cfg
,09-30 08:53:44.813   931  2915 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
09-30 08:53:44.813   931  2915 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 08:53:44.822   931  2915 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 08:53:44.823   931  2915 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 08:53:44.842   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=269747 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=28 mControllerEnergyUsed=106 }
,09-30 08:53:48.002  5800  5800 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-30 08:53:48.007  5800  5800 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:53:48.012  5800  5800 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:53:48.016  5800  5800 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:53:48.073   931  2916 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 08:53:48.075   931  2916 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 08:53:48.075   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:53:48.086   931  2916 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 08:53:48.120   931  2916 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 08:53:48.122  5800  5800 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 08:53:48.547  5800  5800 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 08:53:48.580  5800  5800 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 08:53:48.581  5800  5800 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 08:53:48.592   931  2916 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:53:48.592   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 08:53:48.592   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 08:53:48.610   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:53:48.623   508   925 D CommandListener: Setting iface cfg
,09-30 08:53:48.628   931  2916 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 08:53:48.635   931  5806 D DhcpClient: Receive thread started
,09-30 08:53:48.639   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 08:53:48.639   931  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 08:53:48.639   931  2918 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 08:53:48.720   931  2916 E native  : do suspend false
,09-30 08:53:48.734   931  5805 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 08:53:48.752   931  5806 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,09-30 08:53:48.753   931  5805 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,09-30 08:53:48.756   931  5805 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 08:53:48.768   931  5806 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 08:53:48.769   931  5805 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 08:53:48.772   508   925 D CommandListener: Setting iface cfg
09-30 08:53:48.777   931  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 08:53:48.783   931  5805 D DhcpClient: Scheduling renewal in 86399s
,09-30 08:53:48.791   931  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 08:53:48.792   931  2916 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 08:53:48.793   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 08:53:48.799   931  2918 D ConnectivityService: Adding iface wlan0 to network 101
09-30 08:53:48.803   931  2916 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 08:53:48.851   931  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-30 08:53:48.851   931  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 08:53:48.853   931  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 08:53:48.854   931  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 08:53:48.856   931  2918 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 08:53:48.867   931  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 08:53:48.871   931  2918 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 08:53:48.871   931  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 08:53:48.871   931  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-30 08:53:48.871   931  2916 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 08:53:48.871   931  2918 D ConnectivityService:    accepting network in place of null
09-30 08:53:48.871   931  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:53:48.872   931  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:53:48.894   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:53:48.894   931  5804 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273800, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 08:53:48.915   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:53:48.917   931  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-30 08:53:48.917  3686  3851 W QCNEJ   : |CORE| network available: 101
09-30 08:53:48.917   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 08:53:48.918   931  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-30 08:53:48.920  3686  3851 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 08:53:48.920   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:53:48.921  3686  3851 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 08:53:48.922  3686  3851 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 08:53:48.927  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:48.927  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:48.927  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:48.927  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:48.931  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:48.931  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:48.931  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:48.931  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:53:48.931  5001  5031 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 08:53:48.931  5001  5031 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 08:53:48.931  5001  5031 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 08:53:48.931  5001  5031 E SarControlService: no key has been found,reset the power
09-30 08:53:48.932  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 08:53:48.932  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 08:53:48.932  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 08:53:48.932  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:53:48.932  5034  5034 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-30 08:53:48.933  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:53:48.933  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:53:48.933  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:48.933  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:53:48.933  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-30 08:53:48.935  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 08:53:48.934  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 08:53:48.938  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 08:53:48.939  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000ec03000000000000ffffffff]
09-30 08:53:48.939  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:53:48.939  5034  5048 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 08:53:48.940  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:53:48.940  5034  5034 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 08:53:48.941  4860  4860 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-30 08:53:48.942  3815  3815 D SystemUpdateService: onCreate
09-30 08:53:48.946  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 08:53:48.948  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 08:53:48.948  5001  5014 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 08:53:48.950  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000ed03000000000000ffffffff]
09-30 08:53:48.950  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:53:48.950  5034  5048 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-30 08:53:48.951  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:53:48.951  5001  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 08:53:48.959  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 08:53:48.969  3815  5366 I iu.UploadsManager: num queued entries: 0
,09-30 08:53:48.969  3815  5366 I iu.UploadsManager: num updated entries: 0
09-30 08:53:48.970  3815  5366 I iu.SyncManager: NEXT; no task
,09-30 08:53:48.972  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 08:53:48.973  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:53:48.975  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 08:53:48.975   931  5803 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 08:53:48.979  5738  5738 D SprintDMHelper: simOperator: 
09-30 08:53:48.979  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:53:48.989  3815  5816 I SystemUpdateService: active receiver: enabled
,09-30 08:53:49.018  3815  5816 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:53:49.020  3815  5816 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 08:53:49.020  3815  5816 I SystemUpdateService: now status is 0 (complete)
09-30 08:53:49.020  3815  5816 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 08:53:49.020  3815  5816 I SystemUpdateService: file has been verified
09-30 08:53:49.021  3815  5816 I SystemUpdateService: OTA package size = 21989297
,09-30 08:53:49.026  3815  5816 I SystemUpdateService: showing system update notification
,09-30 08:53:49.028   931  5803 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 12:53:49 GMT], X-Android-Received-Millis=[1475240029027], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475240029001]}
,09-30 08:53:49.028   931  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 08:53:49.029   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-30 08:53:49.029   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-30 08:53:49.030   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 08:53:49.037  3815  3815 D SystemUpdateService: onDestroy
,09-30 08:53:49.039   931  3817 D WifiService: setWifiEnabled: false pid=5606, uid=10077
,09-30 08:53:49.039   931  3817 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:53:49.041   931  2916 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 08:53:49.041   931  2916 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 08:53:49.041   931  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:53:49.041   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:53:49.049   931  5805 D DhcpClient: Clearing IP address
,09-30 08:53:49.050   508   925 D CommandListener: Setting iface cfg
,09-30 08:53:49.051   508   925 D CommandListener: Clearing all IP addresses on wlan0
09-30 08:53:49.059  3524  5817 V NativeCrypto: SSL handshake aborted: ssl=0x7f79c45700: I/O error during system call, Connection timed out
09-30 08:53:49.063  4975  5821 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-30 08:53:49.065   931  3814 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
09-30 08:53:49.065   931  5803 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-30 08:53:49.065   931  5803 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 08:53:49.070   931  5803 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-30 08:53:49.071   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-30 08:53:49.071   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-30 08:53:49.072   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-30 08:53:49.075   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 08:53:49.075   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-30 08:53:49.076   535   535 E Parcel  : Reading a NULL string not supported here.
,09-30 08:53:49.081   931  5806 D DhcpClient: Receive thread stopped
,09-30 08:53:49.082   931   931 D RttService: SCAN_AVAILABLE : 1
09-30 08:53:49.082   931  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-30 08:53:49.082   931  3024 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 08:53:49.084  3686  3851 W QCNEJ   : |CORE| network lost: 101
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-30 08:53:49.084  4975  5821 W Ba,bel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
09-30 08:53:49.084  4975  5821 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-30 08:53:49.084  4975  5821 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-30 08:53:49.085  3686  3851 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 08:53:49.086   931  2916 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 08:53:49.089   931  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 08:53:49.107   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:53:49.126   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 08:53:49.126   508   925 D CommandListener: Clearing all IP addresses on wlan0
,09-30 08:53:49.128   931  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 08:53:49.128   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:53:49.128   931  2916 D DhcpClient: doQuit
09-30 08:53:49.128   931  2916 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 08:53:49.128   931  5805 D DhcpClient: onQuitting
,09-30 08:53:49.129  5800  5800 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-30 08:53:49.132   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:53:49.132  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:49.132  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:49.132  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:49.132  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:49.136  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:49.136  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:53:49.136  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:49.136  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:49.137  4860  4860 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-30 08:53:49.138  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:49.138  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:49.138  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:49.138  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:49.139  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:49.140  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 08:53:49.140  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:49.141  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:49.143  5001  5031 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 08:53:49.143  5001  5031 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 08:53:49.143  5001  5031 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 08:53:49.143  5001  5031 E SarControlService: no key has been found,reset the power
09-30 08:53:49.143  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 08:53:49.143  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 08:53:49.143  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 08:53:49.144  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:53:49.144  5034  5034 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 08:53:49.145  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 08:53:49.146  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-30 08:53:49.146  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 08:53:49.146  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:53:49.146  5800  5800 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 08:53:49.146  5034  5034 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 08:53:49.148  3815  3815 D SystemUpdateService: onCreate
09-30 08:53:49.149  5800  5800 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 08:53:49.152  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000ee03000000000000ffffffff]
09-30 08:53:49.152  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:53:49.152  5034  5048 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-30 08:53:49.152  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:53:49.152  5001  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 08:53:49.153  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 08:53:49.155  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000ef03000000000000ffffffff]
09-30 08:53:49.155  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 08:53:49.155  5034  5048 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 08:53:49.156  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:53:49.156  5001  5014 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 08:53:49.159  3815  5834 I SystemUpdateService: active receiver: enabled
,09-30 08:53:49.164  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 08:53:49.168  3815  5366 I iu.UploadsManager: num queued entries: 0
,09-30 08:53:49.169  3815  5366 I iu.UploadsManager: num updated entries: 0
09-30 08:53:49.169  3815  5366 I iu.SyncManager: NEXT; no task
,09-30 08:53:49.171  3815  5834 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:53:49.172  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 08:53:49.174  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:53:49.176  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:53:49.180  5738  5738 D SprintDMHelper: simOperator: 
,09-30 08:53:49.180  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:53:49.184  5800  5800 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 08:53:49.185  5800  5800 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-30 08:53:49.185   508   925 E Netd    : netlink response contains error (No such file or directory)
09-30 08:53:49.186   931  2918 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 08:53:49.187   931  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 08:53:49.188  3815  5834 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 08:53:49.189  3815  5834 I SystemUpdateService: now status is 0 (complete)
09-30 08:53:49.189  3815  5834 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 08:53:49.189  3815  5834 I SystemUpdateService: file has been verified
,09-30 08:53:49.192  4975  5838 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 08:53:49.189  3815  5834 I SystemUpdateService: OTA package size = 21989297
,09-30 08:53:49.211  3815  5834 I SystemUpdateService: showing system update notification
,09-30 08:53:49.218  3815  3815 D SystemUpdateService: onDestroy
,09-30 08:53:49.288   931  2916 D wifi    : In wifi stop Hal
,09-30 08:53:49.288   931  2916 D wifi    : halHandle = 0x7f636e2680, mVM = 0x7f7fd0d140, mCls = 0x2019de
09-30 08:53:49.289   931  5799 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 08:53:49.289   931  5799 D WifiHAL : Got a signal to exit!!!
09-30 08:53:49.289   931  5799 I WifiHAL : Exit wifi_event_loop
09-30 08:53:49.289   931  2916 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-30 08:53:49.290   931  2916 E WifiHAL : Event processing terminated
09-30 08:53:49.290   931  2916 D wifi    : In wifi cleaned up handler
09-30 08:53:49.290   931  2916 I WifiHAL : Internal cleanup completed
09-30 08:53:49.292  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:49.293  4021  4164 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:53:49.294  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:49.295  4975  4975 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 08:53:49.295  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:49.316   931  5799 D wifi    : set interface wlan0 flags (DOWN)
,09-30 08:53:49.316   931  2916 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 08:53:49.522   931   948 D Tethering: InitialState.processMessage what=4
,09-30 08:53:49.528   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 08:53:49.918   931  2918 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 08:53:50.033   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:51.034   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:52.035   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:53.036   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:54.037   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:53:54.083   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@72bfcec:true
,09-30 08:53:54.083  5724  5724 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 08:53:54.088  5724  5724 I bt_bluedroid: init
09-30 08:53:54.088  5724  5840 I BluetoothAdapterState: Entering OffState
,09-30 08:53:54.091  5724  5841 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-30 08:53:54.091  5724  5841 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 08:53:54.091  5724  5841 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 08:53:54.091  5724  5841 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 08:53:54.092  5724  5724 I bt_bluedroid: get_profile_interface socket
,09-30 08:53:54.095  5724  5844 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 08:53:54.095  5724  5724 I bt_bluedroid: get_profile_interface sdp
,09-30 08:53:54.097  5724  5844 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 08:53:54.103  5724  5735 I bt_bluedroid: config_hci_snoop_log
,09-30 08:53:54.105   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 08:53:54.110  5724  5840 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 08:53:54.110  5724  5840 D BluetoothAdapterProperties: Setting state to 14
,09-30 08:53:54.110  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 08:53:54.113  5724  5840 D BluetoothBondStateMachine: make
,09-30 08:53:54.115  5724  5845 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 08:53:54.118  5724  5840 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:53:54.119  5724  5724 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 08:53:54.122  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:53:54.123  5724  5724 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 08:53:54.124  5724  5724 D BtGatt.GattService: Received start request. Starting profile...
,09-30 08:53:54.124  5724  5724 D BtGatt.GattService: start()
09-30 08:53:54.124  5724  5724 I bt_bluedroid: get_profile_interface gatt
09-30 08:53:54.125  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:53:54.125  5724  5724 D BtGatt.AdvertiseManager: advertise manager created
,09-30 08:53:54.132  5724  5724 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:53:54.132  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:54.132  5724  5724 V BluetoothAdapterState: isBleTurningOn()=true
09-30 08:53:54.132  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:54.132  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 08:53:54.134  5724  5840 I bt_bluedroid: bt_bluedroid
09-30 08:53:54.134  5724  5841 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-30 08:53:54.135  5724  5841 I bt_hci  : start_up
,09-30 08:53:54.142  5724  5841 I bt_vendor: alloc value 0xf41b8871
,09-30 08:53:54.142  5724  5841 I bt_vendor: init
09-30 08:53:54.142  5724  5841 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 08:53:54.142  5724  5841 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 08:53:54.255  5724  5841 D bt_hci  : start_up starting async portion
,09-30 08:53:54.256  5724  5848 I bt_hci  : event_finish_startup
09-30 08:53:54.256  5724  5848 I bt_hci_h4: hal_open
09-30 08:53:54.256  5724  5848 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 08:53:54.256  5849  5849 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:53:54.259  5724  5848 I bt_userial_vendor: device fd = 54 open
,09-30 08:53:54.275  5724  5848 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 08:53:54.278  5724  5848 D bt_hwcfg: Chipset BCM4358A3
,09-30 08:53:54.278  5724  5848 D bt_hwcfg: Target name = [BCM4358A3]
,09-30 08:53:54.278  5724  5848 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 08:53:54.680  5724  5848 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 08:53:54.681  5724  5848 D bt_hwcfg: Settlement delay -- 100 ms
,09-30 08:53:54.681  5724  5848 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 08:53:54.815  5724  5848 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 08:53:54.815  5724  5848 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 08:53:54.817  5724  5848 I bt_hwcfg: vendor lib fwcfg completed
09-30 08:53:54.817  5724  5848 I bt_vendor: firmware callback
09-30 08:53:54.817  5724  5848 I bt_hci  : firmware_config_callback
,09-30 08:53:54.826  5724  5851 I bt_btu  : btu_task pending for preload complete event
09-30 08:53:54.826  5724  5851 I bt_btu_task: Bluetooth chip preload is complete
09-30 08:53:54.826  5724  5851 I bt_btu  : btu_task received preload complete event
,09-30 08:53:54.833  5724  5851 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_A2D
,09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 08:53:54.834  5724  5851 I         : BTE_InitTraceLevels -- TRC_BTM
,09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_PAN
,09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_SMP
,09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 08:53:54.835  5724  5851 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 08:53:54.916  5724  5851 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4136549
09-30 08:53:54.917  5724  5851 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4136549 
,09-30 08:53:54.935  5724  5844 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 08:53:54.937  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 08:53:54.938  5724  5844 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 08:53:54.940  5724  5844 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 08:53:54.943  5724  5844 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:53:54.943  5724  5844 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 08:53:54.943  5724  5844 D bt_hci  : do_postload posting postload work item
09-30 08:53:54.944  5724  5848 I bt_hci  : event_postload
09-30 08:53:54.944  5724  5848 I bt_vendor: sco_config_cb
09-30 08:53:54.944  5724  5848 I bt_hci  : sco_config_callback postload finished.
,09-30 08:53:54.947  5724  5844 D bt_bte_conf: Device ID record 1 : primary
,09-30 08:53:54.948  5724  5844 D bt_bte_conf:   vendorId            = 000f
09-30 08:53:54.948  5724  5844 D bt_bte_conf:   vendorIdSource      = 0001
09-30 08:53:54.948  5724  5844 D bt_bte_conf:   product             = 1200
09-30 08:53:54.948  5724  5844 D bt_bte_conf:   version             = 1436
09-30 08:53:54.948  5724  5844 D bt_bte_conf:   clientExecutableURL = 
09-30 08:53:54.948  5724  5844 D bt_bte_conf:   serviceDescription  = 
09-30 08:53:54.948  5724  5844 D bt_bte_conf:   documentationURL    = 
09-30 08:53:54.948  5724  5844 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-30 08:53:54.949  5724  5841 D bt_stack_manager: event_start_up_stack finished
09-30 08:53:54.950  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:54.950  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 08:53:54.950  5724  5840 D BluetoothAdapterProperties: Setting state to 15
,09-30 08:53:54.952  5724  5848 I bt_vendor: low_power_mode_cb
,09-30 08:53:54.953  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:54.958  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:54.950  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 08:53:54.959  5724  5840 I BluetoothAdapterState: Entering BleOnState
,09-30 08:53:54.962  5724  5840 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-30 08:53:54.962  5724  5840 D BluetoothAdapterProperties: Setting state to 11
09-30 08:53:54.962  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 08:53:54.969  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:54.971  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:54.972  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:53:54.973  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:54.973  5724  5724 D HeadsetService: Received start request. Starting profile...
,09-30 08:53:54.976  5724  5724 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-30 08:53:54.976  5724  5724 D HeadsetStateMachine: make
,09-30 08:53:54.983  5724  5840 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:53:54.986  5724  5724 D HeadsetStateMachine: max_hf_connections = 1
09-30 08:53:54.986  5724  5724 I bt_bluedroid: get_profile_interface handsfree
09-30 08:53:54.986  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-30 08:53:54.986  5724  5844 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-30 08:53:54.989  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:53:54.990  5724  5724 D A2dpService: Received start request. Starting profile...
09-30 08:53:54.990  5724  5724 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-30 08:53:54.991  5724  5724 I bt_bluedroid: get_profile_interface avrcp
,09-30 08:53:54.996  5724  5724 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 08:53:54.996  5724  5724 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 08:53:54.996  5724  5724 D A2dpStateMachine: make
09-30 08:53:54.997  5724  5724 I bt_bluedroid: get_profile_interface a2dp
,09-30 08:53:54.997  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 08:53:54.999  5724  5860 D A2dpStateMachine: Enter Disconnected: -2
,09-30 08:53:54.999  5724  5724 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 08:53:55.000  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:53:55.001  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 08:53:55.002  5660  5660 D BluetoothInputDevice: Proxy object connected
09-30 08:53:55.002  5724  5724 D HidService: Received start request. Starting profile...
,09-30 08:53:55.002  5724  5724 I bt_bluedroid: get_profile_interface hidhost
09-30 08:53:55.002  5724  5724 D HidService: setHidService(): set to: null
09-30 08:53:55.002  5660  5660 D HidProfile: Bluetooth service connected
09-30 08:53:55.003  5724  5724 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 08:53:55.003  5724  5844 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf411756d
09-30 08:53:55.004  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 08:53:55.004  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:53:55.004  5724  5724 D HealthService: Received start request. Starting profile...
,09-30 08:53:55.005  5724  5724 I bt_bluedroid: get_profile_interface health
,09-30 08:53:55.006  5724  5724 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 08:53:55.007  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:53:55.008  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:53:55.009  5660  5660 D PanProfile: Bluetooth service connected
09-30 08:53:55.009  5724  5724 D PanService: Received start request. Starting profile...
09-30 08:53:55.010  5724  5724 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 08:53:55.010  5724  5724 I bt_bluedroid: get_profile_interface pan
09-30 08:53:55.010  5724  5844 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 08:53:55.012  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:53:55.013  5660  5660 D BluetoothMap: Proxy object connected
09-30 08:53:55.013  5724  5724 D BluetoothMapService: Received start request. Starting profile...
09-30 08:53:55.013  5724  5724 D BluetoothMapService: start()
09-30 08:53:55.014  5660  5660 D MapProfile: Bluetooth service connected
09-30 08:53:55.014  5660  5660 D BluetoothMap: getConnectedDevices()
09-30 08:53:55.015  5660  5660 D BluetoothMap: Bluetooth is Not enabled
,09-30 08:53:55.016  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 08:53:55.017  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 08:53:55.017  5724  5724 D BluetoothMapAppObserver: createReceiver()
,09-30 08:53:55.019  5724  5724 D BluetoothMapAppObserver: initObservers()
,09-30 08:53:55.019  5724  5724 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 08:53:55.025  5724  5724 V SapService: SapBinder()
,09-30 08:53:55.025  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:53:55.026  5724  5724 D SapService: Received start request. Starting profile...
09-30 08:53:55.027  5724  5724 V SapService: start()
,09-30 08:53:55.028  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.028  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.029  5724  5858 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isTurningOn()=true
,09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.029  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.030  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.031  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:55.031  5724  5724 V BluetoothAdapterState: isTurningOn()=true
09-30 08:53:55.031  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:55.031  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:55.031  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 08:53:55.031  5724  5840 D BluetoothAdapterProperties: ScanMode =  20
09-30 08:53:55.031  5724  5840 D BluetoothAdapterProperties: State =  11
09-30 08:53:55.031  5724  5840 D BluetoothAdapterProperties: Setting state to 12
,09-30 08:53:55.031  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 08:53:55.032  5724  5840 I BluetoothAdapterState: Entering OnState
09-30 08:53:55.032  3057  3923 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:53:55.033  5724  5844 D BluetoothAdapterProperties: Scan Mode:21
09-30 08:53:55.034  5724  5844 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 08:53:55.034  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-30 08:53:55.035  3057  3057 D BluetoothMap: Proxy object connected
09-30 08:53:55.035  3057  3057 D MapProfile: Bluetooth service connected
09-30 08:53:55.035  3057  3057 D BluetoothMap: getConnectedDevices()
09-30 08:53:55.037   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:53:55.037  3727  3745 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:53:55.037   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:55.038  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:53:55.039  3057  3081 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:53:55.040   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:53:55.040  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:53:55.041  5660  5672 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 08:53:55.041   931   931 D BluetoothA2dp: Proxy object connected
09-30 08:53:55.041  3057  3057 D BluetoothA2dp: Proxy object connected
09-30 08:53:55.042  5660  5671 D BluetoothPan: onBluetoothStateChange on: true
09-30 08:53:55.042   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:53:55.043   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:53:55.043  3057  3923 D BluetoothPan: onBluetoothStateChange on: true
,09-30 08:53:55.044  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:53:55.045  3057  3057 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:53:55.045  3057  3081 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:53:55.045  3057  3057 D PanProfile: Bluetooth service connected
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:55.045  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:55.045  5724  5724 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 08:53:55.045  5660  5672 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:53:55.046  3057  3921 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 08:53:55.046  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:53:55.047  3057  3057 D BluetoothInputDevice: Proxy object connected
,09-30 08:53:55.047  3057  3075 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 08:53:55.047  3057  3057 D HidProfile: Bluetooth service connected
09-30 08:53:55.048  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:55.050  5660  5671 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 08:53:55.051   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 08:53:55.052  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:55.053  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:53:55.053  5660  5660 D LocalBluetoothProfileManager: Adding local A2DP profile
09-30 08:53:55.054  5724  5724 D ObexServerSockets: Succeed to create listening sockets 
09-30 08:53:55.054  5724  5724 D ObexServerSockets0: startAccept()
09-30 08:53:55.054  5724  5724 D ObexServerSockets0: prepareForNewConnect()
09-30 08:53:55.056  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:55.056  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 08:53:55.057  5660  5660 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-30 08:53:55.057  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:55.057  5724  5724 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 08:53:55.057  5724  5724 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 08:53:55.058  5724  5724 D BluetoothMapService: onReceive
,09-30 08:53:55.058  5724  5724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 08:53:55.058  5724  5724 D BluetoothMapService: STATE_ON
09-30 08:53:55.058  5724  5867 D ObexServerSockets0: Accepting socket connection...
09-30 08:53:55.058  5724  5866 D ObexServerSockets0: Accepting socket connection...
09-30 08:53:55.058  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:55.060  5724  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:53:55.061  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:55.061  5724  5868 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-30 08:53:55.061  5724  5868 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 08:53:55.066  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:53:55.070  5660  5660 D BluetoothA2dp: Proxy object connected
,09-30 08:53:55.073  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 08:53:55.074  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:53:55.079  5660  5660 D BluetoothPbap: Proxy object connected
,09-30 08:53:55.080  5660  5660 D PbapServerProfile: Bluetooth service connected
,09-30 08:53:55.082  3057  3057 D BluetoothPbap: Proxy object connected
09-30 08:53:55.082  3057  3057 D PbapServerProfile: Bluetooth service connected
,09-30 08:53:55.087  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:53:55.087  5724  5724 D ObexServerSockets0: prepareForNewConnect()
,09-30 08:53:55.090  5724  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:53:55.104  5724  5876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:53:55.105  5724  5876 I BtOppRfcommListener: Accept thread started.
,09-30 08:53:55.139   931   931 D BluetoothHeadset: Proxy object connected
,09-30 08:53:55.139   931   931 D BluetoothHeadset: Proxy object connected
09-30 08:53:55.139   931   931 D BluetoothHeadset: Proxy object connected
09-30 08:53:55.139  3057  3081 D BluetoothHeadset: Proxy object connected
09-30 08:53:55.139  3057  3057 D HeadsetProfile: Bluetooth service connected
09-30 08:53:55.139  3727  3972 D BluetoothHeadset: Proxy object connected
,09-30 08:53:55.142   931   948 D BluetoothHeadset: Proxy object connected
09-30 08:53:55.142   931   948 D BluetoothHeadset: Proxy object connected
,09-30 08:53:55.145  3057  3921 D BluetoothHeadset: Proxy object connected
,09-30 08:53:55.145  3057  3057 D HeadsetProfile: Bluetooth service connected
,09-30 08:53:55.161  5660  5672 D BluetoothHeadset: Proxy object connected
,09-30 08:53:55.162  5660  5660 D HeadsetProfile: Bluetooth service connected
,09-30 08:53:56.878   931  2918 D ConnectivityService: handlePromptUnvalidated 101
,09-30 08:53:59.055  5724  5840 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 08:53:59.056  5724  5840 D BluetoothAdapterProperties: Setting state to 13
,09-30 08:53:59.056  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-30 08:53:59.057  5724  5840 D BluetoothAdapterProperties: onBluetoothDisable()
,09-30 08:53:59.061  5724  5724 D BluetoothMapService: onReceive
,09-30 08:53:59.062  5724  5724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-30 08:53:59.062  5724  5724 D BluetoothMapService: STATE_TURNING_OFF
09-30 08:53:59.062  5724  5724 D BluetoothMapService: MAP Service closeService in
09-30 08:53:59.062  5724  5724 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 08:53:59.062  5724  5724 D ObexServerSockets0: shutdown(block = true)
09-30 08:53:59.063  5724  5724 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 08:53:59.063  5724  5724 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 08:53:59.063  5724  5853 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-30 08:53:59.065  5724  5867 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-30 08:53:59.065  5724  5866 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 08:53:59.065  5724  5840 I BluetoothAdapterState: Entering PendingCommandState
09-30 08:53:59.068  5724  5724 I BtOppRfcommListener: stopping Accept Thread
09-30 08:53:59.068  5724  5876 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 08:53:59.069  5724  5876 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 08:53:59.071  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:59.072  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:59.073  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:59.073  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:59.075  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 08:53:59.075  5724  5844 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:53:59.077  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 08:53:59.081  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:59.081  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:59.083  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:59.083  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:59.084  5724  5724 D HeadsetService: Received stop request...Stopping profile...
09-30 08:53:59.086  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:53:59.086  5606  5606 V io.jxcore.node.Connectivit,yMonitor:     - is Wi-Fi enabled: false
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:53:59.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:53:59.088  5606  5606 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 08:53:59.089  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:53:59.091  5660  5660 D DockEventReceiver: finishStartingService: stopping service
09-30 08:53:59.091  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.094   931   931 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:59.094   931   931 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:59.094   931   931 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:59.095  5660  5671 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:59.095  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.095  3057  3921 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:59.096  3727  3737 D BluetoothHeadset: Proxy object disconnected
09-30 08:53:59.097  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.097  3057  3057 D HeadsetProfile: Bluetooth service disconnected
09-30 08:53:59.100  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:53:59.103  5724  5724 D A2dpService: Received stop request...Stopping profile...
09-30 08:53:59.103  5724  5860 D A2dpStateMachine: Exit Disconnected: -1
09-30 08:53:59.103  5660  5660 D HeadsetProfile: Bluetooth service disconnected
,09-30 08:53:59.105  3057  3057 D BluetoothA2dp: Proxy object disconnected
09-30 08:53:59.105   931   931 D BluetoothA2dp: Proxy object disconnected
09-30 08:53:59.106  5724  5724 D HidService: Received stop request...Stopping profile...
09-30 08:53:59.106  5724  5724 D HidService: Stopping Bluetooth HidService
09-30 08:53:59.107  3057  3057 D BluetoothInputDevice: Proxy object disconnected
09-30 08:53:59.107  3057  3057 D HidProfile: Bluetooth service disconnected
,09-30 08:53:59.108  5724  5724 D HealthService: Received stop request...Stopping profile...
09-30 08:53:59.109  5724  5724 D PanService: Received stop request...Stopping profile...
09-30 08:53:59.110  3057  3057 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 08:53:59.110  3057  3057 D PanProfile: Bluetooth service disconnected
09-30 08:53:59.110  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.110  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.110  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:59.110  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:53:59.111  5724  5724 D BluetoothMapService: Received stop request...Stopping profile...
,09-30 08:53:59.111  5724  5724 D BluetoothMapService: stop()
09-30 08:53:59.111  5724  5724 D BluetoothMapAppObserver: deinitObservers()
09-30 08:53:59.111  5724  5724 D BluetoothMapAppObserver: removeReceiver()
09-30 08:53:59.112  3057  3057 D BluetoothMap: Proxy object disconnected
09-30 08:53:59.113  3057  3057 D MapProfile: Bluetooth service disconnected
09-30 08:53:59.113  5660  5660 D BluetoothA2dp: Proxy object disconnected
09-30 08:53:59.113  5660  5660 D BluetoothInputDevice: Proxy object disconnected
09-30 08:53:59.113  5660  5660 D HidProfile: Bluetooth service disconnected
09-30 08:53:59.113  5660  5660 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-30 08:53:59.113  5660  5660 D PanProfile: Bluetooth service disconnected
09-30 08:53:59.114  5660  5660 D BluetoothMap: Proxy object disconnected
09-30 08:53:59.114  5660  5660 D MapProfile: Bluetooth service disconnected
09-30 08:53:59.114  5724  5724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 08:53:59.114  5724  5724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 08:53:59.115  5724  5724 D SapService: Received stop request...Stopping profile...
09-30 08:53:59.115  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 08:53:59.115  5724  5724 V SapService: stop()
,09-30 08:53:59.115  5724  5851 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:59.115  5724  5851 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:59.115  5724  5851 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 08:53:59.118  5724  5844 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 08:53:59.118  3057  3057 D BluetoothPbap: Proxy object disconnected
09-30 08:53:59.118  3057  3057 D PbapServerProfile: Bluetooth service disconnected
09-30 08:53:59.118  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.118  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.118  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false,
,09-30 08:53:59.118  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:59.119  5660  5660 D BluetoothPbap: Proxy object disconnected
09-30 08:53:59.119  5660  5660 D PbapServerProfile: Bluetooth service disconnected
09-30 08:53:59.120  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.120  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.120  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:53:59.120  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:59.120  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 08:53:59.120  5724  5851 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:59.120  5724  5851 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 08:53:59.120  5724  5724 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 08:53:59.120  5724  5851 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:53:59.121  5724  5851 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 08:53:59.121  5724  5724 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 08:53:59.121  5724  5851 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 08:53:59.121  5724  5851 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 08:53:59.121  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.121  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.121  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:59.121  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:59.121  5724  5844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 08:53:59.121  5724  5724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 08:53:59.121  5724  5844 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 08:53:59.121  5724  5724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 08:53:59.122  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.122  5724  5724 V BluetoothAdapterState: isTurningOn()=false
,09-30 08:53:59.122  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:59.122  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:59.122  5724  5724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 08:53:59.122  5724  5724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 08:53:59.123  5724  5724 D BluetoothMapService: MAP Service closeService in
09-30 08:53:59.123  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.123  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.123  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:59.123  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:59.124  5724  5724 D BluetoothMapService: cleanup()
09-30 08:53:59.124  5724  5724 D BluetoothMapService: MAP Service closeService in
,09-30 08:53:59.124  5724  5724 V BluetoothAdapterState: isTurningOff()=true
09-30 08:53:59.124  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.124  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:53:59.124  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:53:59.124  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 08:53:59.124  5724  5840 D BluetoothAdapterProperties: Setting state to 15
09-30 08:53:59.124  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 08:53:59.125  5724  5840 I BluetoothAdapterState: Entering BleOnState
09-30 08:53:59.125  3057  3921 D BluetoothMap: onBluetoothStateChange: up=false
09-30 08:53:59.125   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 08:53:59.126  5660  5672 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:53:59.126  3727  3973 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:59.127  3057  3923 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:53:59.127   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 08:53:59.127  5660  5671 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 08:53:59.128  5660  5672 D BluetoothPan: onBluetoothStateChange on: false
09-30 08:53:59.128   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:59.128   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:59.128  3057  3075 D BluetoothPan: onBluetoothStateChange on: false
09-30 08:53:59.129  5660  5671 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:59.129  3057  3081 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 08:53:59.130  5660  5672 D BluetoothMap: onBluetoothStateChange: up=false
09-30 08:53:59.130  3057  3921 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 08:53:59.131  3057  3923 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 08:53:59.131  5660  5671 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 08:53:59.132  5724  5840 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 08:53:59.132  5724  5840 D BluetoothAdapterProperties: Setting state to 16
09-30 08:53:59.132  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-30 08:53:59.133  5724  5840 D BluetoothAdapterProperties: onBleDisable
09-30 08:53:59.133  5724  5840 I BluetoothAdapterState: Entering PendingCommandState
09-30 08:53:59.133  5724  5841 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 08:53:59.135  5724  5844 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:53:59.135  5724  5851 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 08:53:59.135  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 08:53:59.135  5724  5851 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 08:53:59.136  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.138  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.140  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.140  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:53:59.142  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:53:59.143  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.144  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:53:59.146  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:53:59.345  5724  5844 I bt_hci  : shut_down
,09-30 08:53:59.356  5724  5848 D bt_hwcfg: hw_epilog_process
09-30 08:53:59.357  5724  5848 I bt_vendor: low_power_mode_cb
,09-30 08:53:59.360  5724  5848 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 08:53:59.360  5724  5848 I bt_vendor: epilog_cb
09-30 08:53:59.360  5724  5848 I bt_hci  : epilog_finished_callback
,09-30 08:53:59.363  5724  5844 I bt_hci_h4: hal_close
,09-30 08:53:59.363  5724  5844 I bt_userial_vendor: device fd = 54 close
,09-30 08:53:59.479  5724  5841 D bt_stack_manager: event_shut_down_stack finished.
,09-30 08:53:59.479  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 08:53:59.484  5724  5724 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 08:53:59.484  5724  5840 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 08:53:59.485  5724  5724 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 08:53:59.486  5724  5724 D BtGatt.GattService: stop()
09-30 08:53:59.486  5724  5724 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 08:53:59.489  5724  5724 V BluetoothAdapterState: isTurningOff()=false
09-30 08:53:59.489  5724  5724 V BluetoothAdapterState: isTurningOn()=false
09-30 08:53:59.489  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:53:59.490  5724  5724 V BluetoothAdapterState: isBleTurningOff()=true
,09-30 08:53:59.490  5724  5840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-30 08:53:59.491  5724  5840 D BluetoothAdapterProperties: Setting state to 10
,09-30 08:53:59.491  5724  5840 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-30 08:53:59.493  5724  5840 I BluetoothAdapterState: Entering OffState
,09-30 08:53:59.494   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 08:53:59.504  5724  5724 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-30 08:53:59.504  5724  5724 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-30 08:53:59.505  5724  5724 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 08:53:59.507  5724  5841 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 08:53:59.514  5724  5724 I art     : System.exit called, status: 0
,09-30 08:53:59.514  5724  5724 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 08:53:59.561   931  3724 I ActivityManager: Process com.android.bluetooth (pid 5724) has died
,09-30 08:54:04.053  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:04.054  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:04.059  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:54:04.059  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c4a0c90 removed from the list
,09-30 08:54:04.059  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:04.059  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:54:04.059  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:04.063  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:54:04.064  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce9dd8e added. We now have 4 listener(s)
09-30 08:54:04.064  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:04.066  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:04.066  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce9dd8e removed from the list
09-30 08:54:04.066  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:54:04.066  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:04.066  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:04.068  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 08:54:04.068  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae8c9af added. We now have 4 listener(s)
09-30 08:54:04.069  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:54:09.079  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:09.113   931   948 I ActivityManager: Start proc 5886:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 08:54:09.207  5886  5886 D AdapterServiceConfig: Adding HeadsetService
,09-30 08:54:09.207  5886  5886 D AdapterServiceConfig: Adding A2dpService
09-30 08:54:09.207  5886  5886 D AdapterServiceConfig: Adding HidService
09-30 08:54:09.207  5886  5886 D AdapterServiceConfig: Adding HealthService
09-30 08:54:09.208  5886  5886 D AdapterServiceConfig: Adding PanService
09-30 08:54:09.208  5886  5886 D AdapterServiceConfig: Adding GattService
09-30 08:54:09.208  5886  5886 D AdapterServiceConfig: Adding BluetoothMapService
09-30 08:54:09.208  5886  5886 D AdapterServiceConfig: Adding SapService
,09-30 08:54:09.218   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@adab275:true
,09-30 08:54:09.218  5886  5886 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 08:54:09.221  5886  5886 I bt_bluedroid: init
,09-30 08:54:09.223  5886  5898 I BluetoothAdapterState: Entering OffState
,09-30 08:54:09.225  5886  5899 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 08:54:09.225  5886  5899 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 08:54:09.225  5886  5899 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 08:54:09.225  5886  5899 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 08:54:09.226  5886  5886 I bt_bluedroid: get_profile_interface socket
,09-30 08:54:09.228  5886  5902 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 08:54:09.228  5886  5886 I bt_bluedroid: get_profile_interface sdp
09-30 08:54:09.229  5886  5902 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 08:54:09.234  5886  5897 I bt_bluedroid: config_hci_snoop_log
,09-30 08:54:09.235   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 08:54:09.239  5886  5898 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 08:54:09.239  5886  5898 D BluetoothAdapterProperties: Setting state to 14
09-30 08:54:09.239  5886  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 08:54:09.241  5886  5898 D BluetoothBondStateMachine: make
,09-30 08:54:09.243  5886  5903 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 08:54:09.245  5886  5898 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:54:09.247  5886  5886 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 08:54:09.250  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:54:09.251  5886  5886 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 08:54:09.252  5886  5886 D BtGatt.GattService: Received start request. Starting profile...
09-30 08:54:09.252  5886  5886 D BtGatt.GattService: start()
09-30 08:54:09.252  5886  5886 I bt_bluedroid: get_profile_interface gatt
,09-30 08:54:09.253  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:54:09.253  5886  5886 D BtGatt.AdvertiseManager: advertise manager created
,09-30 08:54:09.258  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:09.258  5886  5886 V BluetoothAdapterState: isTurningOn()=false
09-30 08:54:09.258  5886  5886 V BluetoothAdapterState: isBleTurningOn()=true
09-30 08:54:09.258  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:54:09.258  5886  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-30 08:54:09.259  5886  5898 I bt_bluedroid: bt_bluedroid
09-30 08:54:09.259  5886  5899 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 08:54:09.260  5886  5899 I bt_hci  : start_up
,09-30 08:54:09.265  5886  5899 I bt_vendor: alloc value 0xf4226871
,09-30 08:54:09.265  5886  5899 I bt_vendor: init
09-30 08:54:09.265  5886  5899 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 08:54:09.265  5886  5899 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 08:54:09.375  5886  5899 D bt_hci  : start_up starting async portion
,09-30 08:54:09.375  5886  5906 I bt_hci  : event_finish_startup
09-30 08:54:09.375  5886  5906 I bt_hci_h4: hal_open
09-30 08:54:09.375  5886  5906 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 08:54:09.373  5907  5907 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:54:09.379  5886  5906 I bt_userial_vendor: device fd = 54 open
,09-30 08:54:09.394  5886  5906 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 08:54:09.397  5886  5906 D bt_hwcfg: Chipset BCM4358A3
09-30 08:54:09.397  5886  5906 D bt_hwcfg: Target name = [BCM4358A3]
09-30 08:54:09.397  5886  5906 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 08:54:09.905  5886  5906 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-30 08:54:09.905  5886  5906 D bt_hwcfg: Settlement delay -- 100 ms
,09-30 08:54:09.906  5886  5906 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 08:54:10.041  5886  5906 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 08:54:10.041  5886  5906 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 08:54:10.043  5886  5906 I bt_hwcfg: vendor lib fwcfg completed
09-30 08:54:10.043  5886  5906 I bt_vendor: firmware callback
09-30 08:54:10.043  5886  5906 I bt_hci  : firmware_config_callback
,09-30 08:54:10.053  5886  5909 I bt_btu  : btu_task pending for preload complete event
,09-30 08:54:10.054  5886  5909 I bt_btu_task: Bluetooth chip preload is complete
09-30 08:54:10.054  5886  5909 I bt_btu  : btu_task received preload complete event
,09-30 08:54:10.060  5886  5909 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 08:54:10.060  5886  5909 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 08:54:10.060  5886  5909 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 08:54:10.060  5886  5909 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 08:54:10.060  5886  5909 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 08:54:10.061  5886  5909 I         : BTE_InitTraceLevels -- TRC_SMP
,09-30 08:54:10.062  5886  5909 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 08:54:10.062  5886  5909 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 08:54:10.174  5886  5909 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41a4549
,09-30 08:54:10.175  5886  5909 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41a4549 
,09-30 08:54:10.194  5886  5902 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-30 08:54:10.195  5886  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 08:54:10.195  5886  5902 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 08:54:10.197  5886  5902 D BluetoothAdapterProperties: Name is: Nexus 6P
09-30 08:54:10.199  5886  5902 D BluetoothAdapterProperties: Scan Mode:20
09-30 08:54:10.199  5886  5902 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 08:54:10.199  5886  5902 D bt_hci  : do_postload posting postload work item
09-30 08:54:10.200  5886  5906 I bt_hci  : event_postload
09-30 08:54:10.200  5886  5906 I bt_vendor: sco_config_cb
,09-30 08:54:10.200  5886  5906 I bt_hci  : sco_config_callback postload finished.
,09-30 08:54:10.203  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:10.206  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:10.211  5886  5902 D bt_bte_conf: Device ID record 1 : primary
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   vendorId            = 000f
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   vendorIdSource      = 0001
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   product             = 1200
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   version             = 1436
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   clientExecutableURL = 
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   serviceDescription  = 
09-30 08:54:10.211  5886  5902 D bt_bte_conf:   documentationURL    = 
09-30 08:54:10.211  5886  5902 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-30 08:54:10.212  5886  5899 D bt_stack_manager: event_start_up_stack finished
,09-30 08:54:10.212  5886  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 08:54:10.213  5886  5898 D BluetoothAdapterProperties: Setting state to 15
09-30 08:54:10.213  5886  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 08:54:10.214  5886  5906 I bt_vendor: low_power_mode_cb
09-30 08:54:10.214  5886  5898 I BluetoothAdapterState: Entering BleOnState
,09-30 08:54:10.217  5886  5898 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 08:54:10.217  5886  5898 D BluetoothAdapterProperties: Setting state to 11
09-30 08:54:10.217  5886  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 08:54:10.227  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:54:10.228  5886  5886 D HeadsetService: Received start request. Starting profile...
09-30 08:54:10.228  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:10.231  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:10.234  5886  5886 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 08:54:10.234  5886  5886 D HeadsetStateMachine: make
,09-30 08:54:10.239  5886  5898 I BluetoothAdapterState: Entering PendingCommandState
,09-30 08:54:10.242  5886  5886 D HeadsetStateMachine: max_hf_connections = 1
09-30 08:54:10.243  5886  5886 I bt_bluedroid: get_profile_interface handsfree
09-30 08:54:10.243  5886  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 08:54:10.243  5886  5902 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-30 08:54:10.246  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:54:10.247  5886  5886 D A2dpService: Received start request. Starting profile...
,09-30 08:54:10.248  5886  5886 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 08:54:10.248  5886  5886 I bt_bluedroid: get_profile_interface avrcp
,09-30 08:54:10.255  5886  5886 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 08:54:10.255  5886  5886 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-30 08:54:10.255  5886  5886 D A2dpStateMachine: make
09-30 08:54:10.257  5886  5886 I bt_bluedroid: get_profile_interface a2dp
09-30 08:54:10.259  5886  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-30 08:54:10.260  5886  5917 D A2dpStateMachine: Enter Disconnected: -2
,09-30 08:54:10.260  5886  5886 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 08:54:10.261  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:54:10.262  5886  5886 D HidService: Received start request. Starting profile...
09-30 08:54:10.262  5886  5886 I bt_bluedroid: get_profile_interface hidhost
09-30 08:54:10.262  5886  5886 D HidService: setHidService(): set to: null
09-30 08:54:10.262  5886  5902 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf418556d
,09-30 08:54:10.262  5886  5902 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-30 08:54:10.263  5886  5886 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-30 08:54:10.264  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 08:54:10.264  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:54:10.266  5886  5886 D HealthService: Received start request. Starting profile...
,09-30 08:54:10.267  5886  5886 I bt_bluedroid: get_profile_interface health
,09-30 08:54:10.268  5886  5886 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 08:54:10.269  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:54:10.269  5886  5886 D PanService: Received start request. Starting profile...
09-30 08:54:10.269  5886  5886 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 08:54:10.269  5886  5886 I bt_bluedroid: get_profile_interface pan
09-30 08:54:10.270  5886  5902 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 08:54:10.271  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:54:10.272  5886  5886 D BluetoothMapService: Received start request. Starting profile...
09-30 08:54:10.272  5886  5886 D BluetoothMapService: start()
09-30 08:54:10.275  5886  5886 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 08:54:10.276  5886  5886 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 08:54:10.276  5886  5886 D BluetoothMapAppObserver: createReceiver()
09-30 08:54:10.277  5886  5886 D BluetoothMapAppObserver: initObservers()
09-30 08:54:10.277  5886  5886 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 08:54:10.283  5886  5886 V SapService: SapBinder()
09-30 08:54:10.283  5886  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
,09-30 08:54:10.285  5886  5886 D SapService: Received start request. Starting profile...
09-30 08:54:10.285  5886  5886 V SapService: start()
,09-30 08:54:10.288  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:10.288  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.288  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:54:10.288  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:54:10.288  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:10.288  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.289  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:54:10.289  5886  5915 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 08:54:10.289  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:54:10.289  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:10.289  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.289  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:54:10.289  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 08:54:10.290  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
09-30 08:54:10.291  5886  5886 V BluetoothAdapterState: isTurningOff()=false
09-30 08:54:10.291  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.291  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:54:10.291  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:54:10.293  5886  5886 V BluetoothAdapterState: isTurningOff()=false
,09-30 08:54:10.293  5886  5886 V BluetoothAdapterState: isTurningOn()=true
09-30 08:54:10.293  5886  5886 V BluetoothAdapterState: isBleTurningOn()=false
09-30 08:54:10.293  5886  5886 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 08:54:10.293  5886  5898 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-30 08:54:10.294  5886  5898 D BluetoothAdapterProperties: ScanMode =  20
09-30 08:54:10.294  5886  5898 D BluetoothAdapterProperties: State =  11
09-30 08:54:10.294  5886  5898 D BluetoothAdapterProperties: Setting state to 12
09-30 08:54:10.294  5886  5898 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 08:54:10.295  3057  3075 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:54:10.295  5886  5902 D BluetoothAdapterProperties: Scan Mode:21
09-30 08:54:10.295  5886  5902 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 08:54:10.295  5886  5898 I BluetoothAdapterState: Entering OnState
09-30 08:54:10.296   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 08:54:10.297  5660  5672 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 08:54:10.297  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 08:54:10.298  3057  3057 D BluetoothMap: Proxy object connected
,09-30 08:54:10.298  3057  3057 D MapProfile: Bluetooth service connected
09-30 08:54:10.298  3057  3057 D BluetoothMap: getConnectedDevices()
09-30 08:54:10.298  3727  3972 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:54:10.299  3057  3081 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:54:10.301  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:54:10.301   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 08:54:10.301  3057  3057 D BluetoothA2dp: Proxy object connected
09-30 08:54:10.302   931   931 D BluetoothA2dp: Proxy object connected
09-30 08:54:10.302  5660  5672 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 08:54:10.303  5886  5886 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:54:10.303  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:54:10.304  5886  5886 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 08:54:10.304  5660  5671 D BluetoothPan: onBluetoothStateChange on: true
09-30 08:54:10.305  5660  5660 D BluetoothA2dp: Proxy object connected
09-30 08:54:10.306  5886  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:54:10.306   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:54:10.306   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 08:54:10.307  3057  3075 D BluetoothPan: onBluetoothStateChange on: true
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:54:10.307  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:54:10.308  5886  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:54:10.308  5660  5672 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:54:10.309  3057  3923 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 08:54:10.309  5886  5886 D ObexServerSockets: Succeed to create listening sockets 
09-30 08:54:10.310  5886  5886 D ObexServerSockets0: startAccept()
09-30 08:54:10.310  5660  5671 D BluetoothMap: onBluetoothStateChange: up=true
09-30 08:54:10.310  5886  5886 D ObexServerSockets0: prepareForNewConnect()
09-30 08:54:10.310  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:54:10.311  5886  5886 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 08:54:10.312  5886  5886 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 08:54:10.312  3057  3081 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 08:54:10.313  5886  5924 D ObexServerSockets0: Accepting socket connection...
09-30 08:54:10.313  5886  5925 D ObexServerSockets0: Accepting socket connection...
09-30 08:54:10.313  3057  3057 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:54:10.313  3057  3057 D PanProfile: Bluetooth service connected
09-30 08:54:10.314  3057  3075 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 08:54:10.314  5660  5660 D BluetoothMap: Proxy object connected
09-30 08:54:10.314  5660  5660 D MapProfile: Bluetooth service connected
09-30 08:54:10.314  5660  5660 D BluetoothMap: getConnectedDevices()
09-30 08:54:10.315  3057  3057 D BluetoothInputDevice: Proxy object connected
09-30 08:54:10.315  3057  3057 D HidProfile: Bluetooth service connected
09-30 08:54:10.316  5660  5671 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 08:54:10.316  5660  5660 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 08:54:10.316  5660  5660 D PanProfile: Bluetooth service connected
09-30 08:54:10.318  5660  5660 D BluetoothInputDevice: Proxy object connected
09-30 08:54:10.318  5660  5660 D HidProfile: Bluetooth service connected
09-30 08:54:10.319  5886  5886 D BluetoothMapService: onReceive
09-30 08:54:10.319  5886  5886 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 08:54:10.319  5886  5886 D BluetoothMapService: STATE_ON
09-30 08:54:10.319  5606  5606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 08:54:10.320   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 08:54:10.320  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:10.321  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:10.322  5886  5927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 08:54:10.324  5886  5927 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 08:54:10.324  5886  5927 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 08:54:10.326  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 08:54:10.333  3524  3524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 08:54:10.335  5660  5660 D DockEventReceiver: finishStartingService: stopping service
,09-30 08:54:10.339  5660  5660 D BluetoothPbap: Proxy object connected
,09-30 08:54:10.339  5660  5660 D PbapServerProfile: Bluetooth service connected
,09-30 08:54:10.346  5886  5886 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 08:54:10.346  5886  5886 D ObexServerSockets0: prepareForNewConnect()
09-30 08:54:10.347  3057  3057 D BluetoothPbap: Proxy object connected
09-30 08:54:10.347  3057  3057 D PbapServerProfile: Bluetooth service connected
,09-30 08:54:10.348  5886  5931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:54:10.363  5886  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 08:54:10.365  5886  5935 I BtOppRfcommListener: Accept thread started.
,09-30 08:54:10.398   931   931 D BluetoothHeadset: Proxy object connected
,09-30 08:54:10.398   931   931 D BluetoothHeadset: Proxy object connected
09-30 08:54:10.398   931   931 D BluetoothHeadset: Proxy object connected
,09-30 08:54:10.398  5660  5672 D BluetoothHeadset: Proxy object connected
09-30 08:54:10.398  3057  3081 D BluetoothHeadset: Proxy object connected
09-30 08:54:10.399  3057  3057 D HeadsetProfile: Bluetooth service connected
09-30 08:54:10.399  3727  3737 D BluetoothHeadset: Proxy object connected
,09-30 08:54:10.399  5660  5660 D HeadsetProfile: Bluetooth service connected
,09-30 08:54:10.400  3727  3973 D BluetoothHeadset: Proxy object connected
,09-30 08:54:10.406   931   948 D BluetoothHeadset: Proxy object connected
09-30 08:54:10.406   931   948 D BluetoothHeadset: Proxy object connected
,09-30 08:54:10.410  5660  5671 D BluetoothHeadset: Proxy object connected
09-30 08:54:10.411  3057  3923 D BluetoothHeadset: Proxy object connected
,09-30 08:54:10.411  5660  5660 D HeadsetProfile: Bluetooth service connected
09-30 08:54:10.411  3057  3057 D HeadsetProfile: Bluetooth service connected
,09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:54:14.095  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 08:54:14.101  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:54:14.102  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:14.102  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae8c9af removed from the list
09-30 08:54:14.103  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 08:54:14.103  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:14.103  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:14.105  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:14.105  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eeb61bc added. We now have 4 listener(s)
,09-30 08:54:14.105  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:54:14.109   931   942 D WifiService: setWifiEnabled: false pid=5606, uid=10077
09-30 08:54:14.109   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:54:15.038   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:54:16.039   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:54:17.041   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:54:18.042   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:54:19.044   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:54:19.119  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:19.120   931  3817 D WifiService: setWifiEnabled: true pid=5606, uid=10077
,09-30 08:54:19.120   931  3817 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 08:54:19.127   508   925 D SoftapController: Softap fwReload - Ok
,09-30 08:54:19.133   508   925 D CommandListener: Setting iface cfg
,09-30 08:54:19.134   508   925 D CommandListener: Trying to bring down wlan0
,09-30 08:54:19.137   508   925 D CommandListener: Clearing all IP addresses on wlan0
,09-30 08:54:19.145   931  2916 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 08:54:19.816   931  2916 D wifi    : set interface wlan0 flags (UP)
,09-30 08:54:19.820   931  2916 I WifiHAL : Initializing wifi
09-30 08:54:19.820   931  2916 I WifiHAL : Creating socket
09-30 08:54:19.825   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-30 08:54:19.825   931  2916 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 08:54:19.826   931  2916 D wifi    : Did set static halHandle = 0x7f636e2680
09-30 08:54:19.826   931  2916 D wifi    : halHandle = 0x7f636e2680, mVM = 0x7f7fd0d140, mCls = 0x1586
,09-30 08:54:19.826   931  2916 D wifi    : array field set
09-30 08:54:19.827   931  2916 I WifiNative-HAL: interface[0] = wlan0
09-30 08:54:19.829   931  5940 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547129009792
09-30 08:54:19.830   931  5940 D wifi    : waitForHalEvents called, vm = 0x7f7fd0d140, obj = 0x1586, env = 0x7f68dd5a40
,09-30 08:54:19.890  5941  5941 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 08:54:19.913  5941  5941 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:54:19.923  5941  5941 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 08:54:19.923  5941  5941 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 08:54:19.932   931  2916 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 08:54:19.938  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:19.943  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:19.955   931  2916 D WifiConfigStore: Loading config and enabling all networks 
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:54:19.958  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:54:19.960  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 08:54:19.964  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 08:54:19.965   931  2916 D WifiConfigStore: loaded 0 passpoint configs
,09-30 08:54:19.965   931  2916 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 08:54:19.966   931  2916 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 08:54:19.966  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 08:54:19.967   931  2916 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-30 08:54:19.968   931  2916 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 08:54:19.968   931  2916 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 08:54:19.968   931  2916 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 08:54:19.968   931  2916 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 08:54:19.972   931  2916 D WifiNative-HAL: Setting external_sim to 1
09-30 08:54:19.972  4975  4975 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 08:54:19.972   931  2916 D wifi    : setting dfs flag to true, 0x7f6731b4e0
09-30 08:54:19.973   931  2916 D WifiStateMachine: Setting OUI to DA-A1-19
,09-30 08:54:19.973   931  2916 D wifi    : setting scan oui 0x7f6731b4e0
09-30 08:54:19.973   931  2916 D WifiHAL : Sending mac address OUI
,09-30 08:54:19.977   931  2916 E native  : do suspend false
,09-30 08:54:19.987   931  2916 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 08:54:19.987   931   931 D RttService: SCAN_AVAILABLE : 3
09-30 08:54:19.988   508   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-30 08:54:19.988   931  3024 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 08:54:19.989   508   925 D CommandListener: Setting iface cfg
,09-30 08:54:19.993   931  2915 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-30 08:54:19.993   931  2915 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 08:54:20.003   931  2915 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 08:54:20.003   931  2915 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 08:54:20.009   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304915 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-30 08:54:20.045   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 08:54:23.206  5941  5941 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:54:23.215  5941  5941 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:54:23.221  5941  5941 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:54:23.226  5941  5941 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:54:23.230  5941  5941 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 08:54:23.252   931  2916 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-30 08:54:23.253   931  2916 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 08:54:23.254   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:54:23.264   931  2916 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 08:54:23.296   931  2916 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 08:54:23.298  5941  5941 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 08:54:23.719  5941  5941 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 08:54:23.749  5941  5941 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 08:54:23.750  5941  5941 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 08:54:23.759   931  2916 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:54:23.759   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 08:54:23.759   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 08:54:23.777   931  2916 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 08:54:23.790   508   925 D CommandListener: Setting iface cfg
,09-30 08:54:23.797   931  2916 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 08:54:23.803   931  5946 D DhcpClient: Receive thread started
,09-30 08:54:23.808   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 08:54:23.808   931  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-30 08:54:23.808   931  2918 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 08:54:23.889   931  2916 E native  : do suspend false
,09-30 08:54:23.901   931  5945 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 08:54:23.913   931  5946 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 08:54:23.913   931  5945 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-30 08:54:23.915   931  5945 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 08:54:23.931   931  5946 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 08:54:23.931   931  5945 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 08:54:23.933   508   925 D CommandListener: Setting iface cfg
,09-30 08:54:23.938   931  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[],
,09-30 08:54:23.943   931  5945 D DhcpClient: Scheduling renewal in 86399s
,09-30 08:54:23.952   931  2916 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 08:54:23.953   931  2916 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 08:54:23.954   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 08:54:23.956   931  2918 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 08:54:23.967   931  2916 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 08:54:24.004   931  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 08:54:24.004   931  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 08:54:24.006   931  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 08:54:24.007   931  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 08:54:24.009   931  2918 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 08:54:24.015   931  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:54:24.019   931  2918 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 08:54:24.019   931  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 08:54:24.020   931  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 08:54:24.020   931  2916 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 08:54:24.020   931  2918 D ConnectivityService:    accepting network in place of null
09-30 08:54:24.020   931  2916 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 08:54:24.020   931  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 08:54:24.043   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:54:24.048   931  5944 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308954, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 08:54:24.066   508   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 08:54:24.069   931  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-30 08:54:24.070  3686  3851 W QCNEJ   : |CORE| network available: 102
09-30 08:54:24.070   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 08:54:24.071   931  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-30 08:54:24.071   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-30 08:54:24.074  3686  3851 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-30 08:54:24.076  3686  3851 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 08:54:24.076  3686  3851 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:24.079  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:54:24.081  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:24.082  4860  4860 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-30 08:54:24.085  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:24.086  5606  5606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 08:54:24.088  5606  5606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:24.089  5001  5031 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 08:54:24.089  5001  5031 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 08:54:24.089  5001  5031 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 08:54:24.089  5001  5031 E SarControlService: no key has been found,reset the power
09-30 08:54:24.089  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 08:54:24.089  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 08:54:24.089  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 08:54:24.090  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 08:54:24.090  5034  5034 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 08:54:24.092  5001  5046 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 08:54:24.092  5001  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 08:54:24.092  5001  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 08:54:24.092  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 08:54:24.093  5034  5034 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 08:54:24.096  3815  3815 D SystemUpdateService: onCreate
,09-30 08:54:24.097  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000f003000000000000ffffffff]
09-30 08:54:24.097  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:54:24.098  5034  5048 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-30 08:54:24.098  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:54:24.098  5001  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 08:54:24.100  5034  5048 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@df496df HexData = [00000000f103000000000000ffffffff]
,09-30 08:54:24.100  5034  5048 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 08:54:24.101  5034  5048 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 08:54:24.101  5034  5034 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 08:54:24.101  5001  5014 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 08:54:24.102  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 08:54:24.111  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 08:54:24.116  3815  5366 I iu.UploadsManager: num queued entries: 0
,09-30 08:54:24.116  3815  5366 I iu.UploadsManager: num updated entries: 0
09-30 08:54:24.116  3815  5366 I iu.SyncManager: NEXT; no task
,09-30 08:54:24.120  3815  5956 I SystemUpdateService: active receiver: enabled
,09-30 08:54:24.122  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 08:54:24.123  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 08:54:24.124  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 08:54:24.128   931  5943 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 08:54:24.128  5738  5738 D SprintDMHelper: simOperator: 
09-30 08:54:24.128  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:24.132  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:54:24.134  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:24.134  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:24.134  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eeb61bc removed from the list
09-30 08:54:24.134  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:24.134  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:24.134  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:24.138  5606  5962 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-30 08:54:24.138  5606  5962 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 08:54:24.158  3815  5956 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 08:54:24.164  3815  5956 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 08:54:24.164  3815  5956 I SystemUpdateService: now status is 0 (complete)
09-30 08:54:24.164  3815  5956 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 08:54:24.164  3815  5956 I SystemUpdateService: file has been verified
09-30 08:54:24.164  3815  5956 I SystemUpdateService: OTA package size = 21989297
,09-30 08:54:24.169  3815  5956 I SystemUpdateService: showing system update notification
,09-30 08:54:24.178  3815  3815 D SystemUpdateService: onDestroy
,09-30 08:54:24.297   931  5943 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 12:54:24 GMT], X-Android-Received-Millis=[1475240064295], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475240064168]}
,09-30 08:54:24.298   931  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 08:54:24.298   931  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-30 08:54:24.299   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:54:24.304   931  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 08:54:24.376  4975  5961 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 08:54:26.832   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:54:27.149  5606  5962 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-30 08:54:27.150  5606  5962 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 08:54:27.151  5606  5962 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:54:27.151  5606  5969 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 08:54:27.152  5606  5969 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-30 08:54:27.152  5606  5962 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:27.152  5606  5969 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:27.155  5606  5969 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:27.156  5606  5962 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 08:54:27.160  5606  5971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:27.160  5606  5971 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:27.161  5606  5969 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 08:54:27.163  5606  5972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:27.163  5606  5972 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:54:27.164  5606  5974 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:27.164  5606  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:54:27.166  5606  5973 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:27.166  5606  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:27.167  5606  5974 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:27.167  5606  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:54:27.167  5606  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:27.167  5606  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:54:27.167  5606  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 08:54:27.167  5606  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 08:54:27.168  5606  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:27.168  5606  5974 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 08:54:27.168  5606  5974 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:27.169  5606  5974 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 08:54:27.169  5606  5974 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:27.169  5606  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 08:54:27.169  5606  5972 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 158, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
09-30 08:54:27.169  5606  5972 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:27.169  5606  5972 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 08:54:27.169  5606  5972 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,09-30 08:54:27.170  5606  5972 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:54:27.170  5606  5972 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:27.170  5606  5972 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 08:54:27.171  5606  5973 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:27.171  5606  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:27.171  5606  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:27.171  5606  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:27.171  5606  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:54:27.171  5606  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:54:27.171  5606  5971 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:27.171  5606  5971 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-30 08:54:27.172  5606  5971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:27.172  5606  5971 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 08:54:27.172  5606  5973 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:27.172  5606  5973 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:54:27.172  5606  5973 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:27.172  5606  5973 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-30 08:54:27.173  5606  5973 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-30 08:54:27.173  5606  5973 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:27.173  5606  5973 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 08:54:29.862   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:54:30.146  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-30 08:54:30.148  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 08:54:30.153  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8347573 Bundle[{}]
09-30 08:54:30.155  5606  5653 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 08:54:30.155  5606  5653 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-30 08:54:30.157  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-30 08:54:30.158  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-30 08:54:30.159  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-30 08:54:30.161  5606  5653 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 08:54:30.167  5606  5653 I System.out: Running OutgoingSocketThread
,09-30 08:54:30.170  5606  5975 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 08:54:30.170  5606  5975 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 08:54:32.021   931  2918 D ConnectivityService: handlePromptUnvalidated 102
,09-30 08:54:33.180  5606  5975 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-30 08:54:33.180  5606  5976 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-30 08:54:33.180  5606  5975 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 08:54:33.180  5606  5976 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 08:54:33.180  5606  5975 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:33.180  5606  5976 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:33.182  5606  5975 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:33.182  5606  5976 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 08:54:33.183  5606  5975 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-30 08:54:33.184  5606  5976 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-30 08:54:33.187  5606  5978 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:33.187  5606  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:33.188  5606  5979 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:33.188  5606  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:54:33.190  5606  5980 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:33.190  5606  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:33.191  5606  5981 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:33.191  5606  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 08:54:33.191  5606  5980 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:33.191  5606  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:33.191  5606  5981 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:33.191  5606  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:54:33.191  5606  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:33.191  5606  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:54:33.192  5606  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:54:33.192  5606  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:54:33.192  5606  5981 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:33.192  5606  5980 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:33.192  5606  5981 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-30 08:54:33.192  5606  5980 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:54:33.193  5606  5980 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:33.193  5606  5981 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:33.193  5606  5981 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 08:54:33.193  5606  5980 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 08:54:33.193  5606  5980 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 08:54:33.193  5606  5980 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 08:54:33.195  5606  5979 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 170, thread name: IncomingSocketThread/Sender): Socket closed
,09-30 08:54:33.195  5606  5979 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:33.195  5606  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 08:54:33.195  5606  5979 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 08:54:33.195  5606  5979 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:54:33.196  5606  5979 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:33.196  5606  5979 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 08:54:33.196  5606  5978 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 08:54:33.196  5606  5978 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:33.196  5606  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 08:54:33.196  5606  5978 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 08:54:33.196  5606  5978 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 08:54:33.197  5606  5978 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 08:54:33.197  5606  5978 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 08:54:35.012   931  2916 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 08:54:36.181  5606  5653 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-30 08:54:36.183  5606  5653 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-30 08:54:36.183  5606  5653 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-30 08:54:36.188  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:54:36.188  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5681545 added. We now have 3 listener(s)
,09-30 08:54:36.190  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:54:36.191  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.191  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.191  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.191  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2a449a added. We now have 4 listener(s)
09-30 08:54:36.191  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:54:36.192  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:54:36.196  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:36.202  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:54:36.204  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.205  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:54:36.205  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.205  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beadda8 added. We now have 4 listener(s)
09-30 08:54:36.207  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.208  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.208  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.208  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:36.209  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.209  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a79c0c1 added. We now have 5 listener(s)
09-30 08:54:36.209  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.210  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:54:36.210  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:54:36.210  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:54:36.210  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.210  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.210  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:54:36.210  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.210  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.210  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5681545 removed from the list
09-30 08:54:36.210  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.210  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2a449a removed from the list
,09-30 08:54:36.212  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:36.212  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:36.212  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:36.213  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.213  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:36.214  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:54:36.214  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.214  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.214  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2a449a not in the list
09-30 08:54:36.214  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.214  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.215  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.215  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.215  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 08:54:36.215  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a79c0c1 removed from the list
09-30 08:54:36.216  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.216  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.216  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.216  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.216  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.216  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@beadda8 removed from the list
09-30 08:54:36.216  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.217  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d81066 added. We now have 3 listener(s)
,09-30 08:54:36.218  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.218  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.218  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.218  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.219  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e23fa7 added. We now have 4 listener(s)
09-30 08:54:36.219  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.219  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:54:36.222  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:36.226  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:54:36.227  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.228  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:54:36.228  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.228  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a0a7fd added. We now have 4 listener(s)
,09-30 08:54:36.229  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.229  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.230  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.230  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.230  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f44ccf2 added. We now have 5 listener(s)
,09-30 08:54:36.230  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.230  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:36.230  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:54:36.230  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:54:36.230  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:54:36.230  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 08:54:36.231  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:36.235  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:36.236  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 08:54:36.236  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 08:54:36.239  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:54:36.240  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:54:36.240  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 08:54:36.243  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 08:54:36.243  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:54:36.243  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:54:36.243  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:54:36.243  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:54:36.243  5606  5653 D BluetoothAdapter: STATE_ON
,09-30 08:54:36.246  5886  5914 D BtGatt.GattService: registerClient() - UUID=dad2c3e1-cda5-41d4-bb1e-ea92f23d05eb
09-30 08:54:36.247  5886  5902 D BtGatt.GattService: onClientRegistered() - UUID=dad2c3e1-cda5-41d4-bb1e-ea92f23d05eb, clientIf=5
,09-30 08:54:36.247  5606  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:54:36.248  5886  5926 D BtGatt.GattService: start scan with filters
,09-30 08:54:36.251  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 08:54:36.251  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:54:36.251  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:54:36.251  5886  5905 D BtGatt.ScanManager: handling starting scan
09-30 08:54:36.251  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:54:36.252  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:54:36.252  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 08:54:36.252  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 08:54:36.254  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:54:36.254  5886  5905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6367c4
09-30 08:54:36.254  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:54:36.254  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:54:36.255  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 08:54:36.258  5606  5653 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 08:54:36.258  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:54:36.258  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 08:54:36.258  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.258  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:54:36.258  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.258  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 08:54:36.258  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:54:36.258  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:54:36.258  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:54:36.258  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:54:36.258  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:54:36.259  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:54:36.260  5886  5914 D BtGatt.GattService: stopScan() - queue size =1
,09-30 08:54:36.260  5886  5926 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:54:36.261  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:54:36.261  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:54:36.261  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:54:36.261  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:54:36.261  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:54:36.261  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-30 08:54:36.261  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:54:36.261  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:54:36.261  5886  5902 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:54:36.261  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.262  5886  5905 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:54:36.262  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:54:36.262  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:54:36.262  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:54:36.262  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:54:36.263  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:54:36.263  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:54:36.264  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:54:36.264  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:54:36.264  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:54:36.266  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:54:36.266  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:54:36.266  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:54:36.266  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.266  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.266  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:54:36.266  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.266  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.266  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d81066 removed from the list
09-30 08:54:36.266  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.266  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e23fa7 removed from the list
09-30 08:54:36.266  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:36.266  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:36.267  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.267  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.267  5886  5902 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:54:36.267  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:54:36.268  5886  5905 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:54:36.268  5886  5905 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:54:36.269  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 08:54:36.269  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.269  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.269  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e23fa7 not in the list
09-30 08:54:36.269  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.269  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.270  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.271  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.271  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.271  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f44ccf2 removed from the list
09-30 08:54:36.271  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 08:54:36.271  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.271  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.271  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.271  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.271  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a0a7fd removed from the list
09-30 08:54:36.272  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.272  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54ec63e added. We now have 3 listener(s)
09-30 08:54:36.273  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.273  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.273  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 08:54:36.273  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.273  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57c9f added. We now have 4 listener(s)
09-30 08:54:36.273  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.274  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 08:54:36.276  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:54:36.278  5886  5902 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 08:54:36.278  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:36.282  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:54:36.284  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:54:36.284  5886  5902 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:54:36.284  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.284  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 08:54:36.284  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.284  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d91d9b5 added. We now have 4 listener(s)
09-30 08:54:36.285  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.286  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.286  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.286  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.286  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d084a added. We now have 5 listener(s)
09-30 08:54:36.286  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.286  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:36.287  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:36.287  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:36.287  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:54:36.287  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:54:36.287  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:54:36.287  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 08:54:36.289  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:36.292  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 08:54:36.292  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 08:54:36.294  5886  5902 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-30 08:54:36.294  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.294  5886  5905 D BtGatt.ScanManager: stopping BLe Batch
,09-30 08:54:36.296  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 08:54:36.297  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 08:54:36.297  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 08:54:36.299  5886  5902 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 08:54:36.299  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.299  5886  5905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:54:36.301  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 08:54:36.301  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:54:36.301  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:54:36.301  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:54:36.301  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 08:54:36.302  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:54:36.303  5886  5897 D BtGatt.GattService: registerClient() - UUID=19b84e20-b4d8-4ad7-b0e6-21a48988cdba
,09-30 08:54:36.304  5886  5902 D BtGatt.GattService: onClientRegistered() - UUID=19b84e20-b4d8-4ad7-b0e6-21a48988cdba, clientIf=5
09-30 08:54:36.304  5606  5617 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:54:36.304  5886  5902 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 08:54:36.304  5886  5896 D BtGatt.GattService: start scan with filters
09-30 08:54:36.304  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:54:36.306  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 08:54:36.306  5886  5905 D BtGatt.ScanManager: handling starting scan
09-30 08:54:36.306  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:54:36.306  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:54:36.306  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:54:36.306  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-30 08:54:36.306  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 08:54:36.307  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:54:36.308  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:54:36.309  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:54:36.309  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:54:36.309  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:54:36.311  5886  5902 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:54:36.311  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.311  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:36.311  5606  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 08:54:36.311  5886  5905 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:54:36.312  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:54:36.312  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:54:36.312  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:54:36.312  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.312  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.312  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:54:36.312  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.312  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.312  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54ec63e removed from the list
09-30 08:54:36.312  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.312  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57c9f removed from the list
09-30 08:54:36.312  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:36.312  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:54:36.313  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.313  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 08:54:36.313  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.313  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 08:54:36.316  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.316  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.316  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.316  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e57c9f not in the list
09-30 08:54:36.316  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:54:36.316  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 08:54:36.316  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:54:36.316  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:54:36.316  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 08:54:36.316  5886  5902 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:54:36.316  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.316  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:54:36.317  5886  5905 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:54:36.317  5886  5905 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:54:36.317  5886  5896 D BtGatt.GattService: stopScan() - queue size =1
09-30 08:54:36.318  5886  5922 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:54:36.318  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 08:54:36.318  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:54:36.318  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:54:36.318  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:54:36.318  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:54:36.318  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:54:36.318  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:54:36.318  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:54:36.319  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:54:36.319  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 08:54:36.319  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:54:36.319  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-30 08:54:36.319  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:54:36.320  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.320  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.321  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.321  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.321  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:54:36.321  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d084a removed from the list
09-30 08:54:36.321  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.321  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:54:36.321  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.321  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:54:36.321  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.321  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.321  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.321  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d91d9b5 removed from the list
09-30 08:54:36.321  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 08:54:36.322  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b5f16 added. We now have 3 listener(s)
09-30 08:54:36.323  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.323  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.323  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.323  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.323  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c846097 added. We now have 4 listener(s)
09-30 08:54:36.323  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.324  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:54:36.326  5886  5902 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:54:36.326  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.327  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:54:36.330  5886  5902 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 08:54:36.331  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:36.332  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:54:36.334  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 08:54:36.334  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:54:36.334  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.335  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d08a6d added. We now have 4 listener(s)
,09-30 08:54:36.336  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.336  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.336  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.336  5886  5902 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:54:36.336  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.336  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:36.336  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.336  5886  5905 D BtGatt.ScanManager: stopping BLe Batch
09-30 08:54:36.337  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14656a2 added. We now have 5 listener(s)
09-30 08:54:36.337  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 08:54:36.337  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:36.337  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 08:54:36.337  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 08:54:36.337  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 08:54:36.337  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 08:54:36.339  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 08:54:36.340  5606  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 08:54:36.340  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 08:54:36.342  5886  5902 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:54:36.342  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.342  5886  5905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 08:54:36.343  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 08:54:36.343  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 08:54:36.343  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 08:54:36.347  5886  5902 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-30 08:54:36.347  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.347  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 08:54:36.347  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 08:54:36.347  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 08:54:36.347  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 08:54:36.347  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-30 08:54:36.348  5606  5653 D BluetoothAdapter: STATE_ON
,09-30 08:54:36.350  5886  5897 D BtGatt.GattService: registerClient() - UUID=ff1f9b32-c2f6-41b8-840a-f780edf23bcb
09-30 08:54:36.350  5886  5902 D BtGatt.GattService: onClientRegistered() - UUID=ff1f9b32-c2f6-41b8-840a-f780edf23bcb, clientIf=5
,09-30 08:54:36.350  5606  5617 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 08:54:36.350  5886  5896 D BtGatt.GattService: start scan with filters
,09-30 08:54:36.352  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 08:54:36.352  5886  5905 D BtGatt.ScanManager: handling starting scan
09-30 08:54:36.352  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 08:54:36.352  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:54:36.352  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 08:54:36.352  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 08:54:36.352  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 08:54:36.353  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 08:54:36.354  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 08:54:36.354  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 08:54:36.354  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 08:54:36.355  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 08:54:36.357  5886  5902 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 08:54:36.357  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.357  5886  5905 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 08:54:36.359  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:54:36.359  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:54:36.359  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:54:36.359  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.359  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:54:36.359  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 08:54:36.359  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.359  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.359  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b5f16 removed from the list
09-30 08:54:36.359  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.359  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c846097 removed from the list
09-30 08:54:36.359  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:36.359  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:54:36.360  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.360  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 08:54:36.360  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:54:36.360  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:54:36.361  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.361  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.361  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.361  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c846097 not in the list
09-30 08:54:36.361  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 08:54:36.361  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 08:54:36.361  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 08:54:36.361  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 08:54:36.361  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 08:54:36.361  5886  5902 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 08:54:36.361  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.361  5886  5905 D BtGatt.ScanManager: Starting BLE batch scan
09-30 08:54:36.362  5886  5905 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 08:54:36.362  5606  5653 D BluetoothAdapter: STATE_ON
09-30 08:54:36.362  5886  5926 D BtGatt.GattService: stopScan() - queue size =1
,09-30 08:54:36.363  5886  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 08:54:36.363  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 08:54:36.363  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 08:54:36.363  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 08:54:36.363  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 08:54:36.363  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 08:54:36.363  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 08:54:36.363  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 08:54:36.363  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 08:54:36.364  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:54:36.364  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 08:54:36.364  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 08:54:36.365  5606  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 08:54:36.365  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 08:54:36.365  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.366  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.366  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.366  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.366  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:54:36.366  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14656a2 removed from the list
09-30 08:54:36.366  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.366  5606  5606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 08:54:36.366  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.366  5606  5606 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 08:54:36.366  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.366  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.366  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.366  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d08a6d removed from the list
09-30 08:54:36.367  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.367  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d73aee added. We now have 3 listener(s)
09-30 08:54:36.368  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 08:54:36.368  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 08:54:36.368  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.368  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.368  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5accb8f added. We now have 4 listener(s)
09-30 08:54:36.369  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.369  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 08:54:36.371  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 08:54:36.371  5886  5902 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 08:54:36.371  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 08:54:36.375  5606  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 08:54:36.377  5606  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 08:54:36.377  5886  5902 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 08:54:36.377  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.377  5606  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 08:54:36.377  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 08:54:36.377  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ad9a25 added. We now have 4 listener(s)
,09-30 08:54:36.378  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 08:54:36.378  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 08:54:36.378  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 08:54:36.378  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 08:54:36.378  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48017fa added. We now have 5 listener(s)
09-30 08:54:36.379  5606  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 08:54:36.379  5606  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 08:54:36.379  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 08:54:36.379  5606  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 08:54:36.379  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.379  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.379  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 08:54:36.379  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.379  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.379  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d73aee removed from the list
09-30 08:54:36.379  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.379  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5accb8f removed from the list
09-30 08:54:36.379  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:36.381  5606  5606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 08:54:36.382  5606  5653 D io.jxcore.node.ConnectivityMonitor: stop
09-30 08:54:36.382  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:36.382  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.382  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.383  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.383  5886  5902 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 08:54:36.383  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 08:54:36.383  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.383  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.383  5606  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5accb8f not in the list
09-30 08:54:36.383  5886  5905 D BtGatt.ScanManager: stopping BLe Batch
09-30 08:54:36.383  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 08:54:36.383  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 08:54:36.385  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 08:54:36.385  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 08:54:36.385  5606  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 08:54:36.385  5606  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48017fa removed from the list
09-30 08:54:36.385  5606  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 08:54:36.385  5606  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 08:54:36.385  5606  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 08:54:36.385  5606  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 08:54:36.385  5606  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 08:54:36.385  5606  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ad9a25 removed from the list
09-30 08:54:36.386  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 08:54:36.386  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-30 08:54:36.386  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-30 08:54:36.386  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:36.386  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 08:54:36.386  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 08:54:36.387  5886  5902 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 08:54:36.387  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 08:54:36.388  5886  5905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 08:54:36.392  5886  5902 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 08:54:36.392  5886  5902 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 08:54:36.765  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:54:36.821  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:54:36.866  5606  5606 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 08:54:38.556  5606  5982 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 08:54:38.556  5606  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:39.362  5606  5982 W !!      : call onHalfStreamCopied
,09-30 08:54:39.363  5606  5982 I testCopyDataAndClose: closing input stream
,09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 08:54:40.137  5606  5982 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 08:54:43.912  5606  5983 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:43.912  5606  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:45.045   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 08:54:45.046   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 08:54:45.912  5606  5653 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-30 08:54:45.912  5606  5653 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:45.912  5606  5653 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-30 08:54:45.964  5606  5983 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 08:54:45.964  5606  5983 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:45.964  5606  5983 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-30 08:54:46.058  5606  5984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 08:54:46.058  5606  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 08:54:47.682  5606  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 08:54:48.125   931  5944 D NetlinkSocketObserver: NeighborEvent{elapsedMs=333030, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 08:54:51.466  5606  5985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:51.466  5606  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 08:54:51.466  5606  5985 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:51.466  5606  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 08:54:51.467  5606  5985 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 08:54:51.468  5606  5985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:51.468  5606  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-30 08:54:51.469  5606  5653 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 08:54:51.472  5606  5986 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:51.472  5606  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 08:54:51.472  5606  5986 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
09-30 08:54:51.473  5606  5986 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:51.473  5606  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 08:54:51.473  5606  5986 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,09-30 08:54:51.473  5606  5986 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 08:54:51.473  5606  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 08:54:51.478  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 08:54:51.478  5606  5653 I jxcore-log: 
,09-30 08:54:51.478  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Number of passed tests:  83'
09-30 08:54:51.478  5606  5653 I jxcore-log: 
09-30 08:54:51.478  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Number of failed tests:  1'
09-30 08:54:51.478  5606  5653 I jxcore-log: 
09-30 08:54:51.479  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 08:54:51.479  5606  5653 I jxcore-log: 
09-30 08:54:51.479  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Total duration:  102880'
09-30 08:54:51.479  5606  5653 I jxcore-log: 
,09-30 08:54:51.480  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Failures: 
09-30 08:54:51.480  5606  5653 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 08:54:51.480  5606  5653 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 08:54:51.480  5606  5653 I jxcore-log:      but: was ""
09-30 08:54:51.480  5606  5653 I jxcore-log: '
09-30 08:54:51.480  5606  5653 I jxcore-log: 
09-30 08:54:51.480  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 08:54:51.480  5606  5653 I jxcore-log: 
,09-30 08:54:51.482  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 08:54:51.482  5606  5653 I jxcore-log: 
,09-30 08:54:51.484  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.484  5606  5653 I jxcore-log: 
,09-30 08:54:51.485  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.485  5606  5653 I jxcore-log: 
09-30 08:54:51.485  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.485  5606  5653 I jxcore-log: 
09-30 08:54:51.486  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.486  5606  5653 I jxcore-log: 
,09-30 08:54:51.486  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 08:54:51.486  5606  5653 I jxcore-log: 
09-30 08:54:51.487  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:54:51.487  5606  5653 I jxcore-log: 
09-30 08:54:51.487  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.487  5606  5653 I jxcore-log: 
09-30 08:54:51.487  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.487  5606  5653 I jxcore-log: 
09-30 08:54:51.487  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 08:54:51.487  5606  5653 I jxcore-log: 
,09-30 08:54:51.488  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:54:51.488  5606  5653 I jxcore-log: 
,09-30 08:54:51.488  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:54:51.488  5606  5653 I jxcore-log: 
09-30 08:54:51.488  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.488  5606  5653 I jxcore-log: 
09-30 08:54:51.488  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.488  5606  5653 I jxcore-log: 
09-30 08:54:51.488  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.488  5606  5653 I jxcore-log: 
09-30 08:54:51.489  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.489  5606  5653 I jxcore-log: 
09-30 08:54:51.489  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.489  5606  5653 I jxcore-log: 
09-30 08:54:51.489  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.489  5606  5653 I jxcore-log: 
,09-30 08:54:51.490  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.490  5606  5653 I jxcore-log: 
09-30 08:54:51.490  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.490  5606  5653 I jxcore-log: 
09-30 08:54:51.490  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.490  5606  5653 I jxcore-log: 
09-30 08:54:51.491  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.491  5606  5653 I jxcore-log: 
09-30 08:54:51.491  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.491  5606  5653 I jxcore-log: 
09-30 08:54:51.492  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.492  5606  5653 I jxcore-log: 
09-30 08:54:51.493  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.493  5606  5653 I jxcore-log: 
09-30 08:54:51.493  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.493  5606  5653 I jxcore-log: 
,09-30 08:54:51.493  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.493  5606  5653 I jxcore-log: 
09-30 08:54:51.493  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.493  5606  5653 I jxcore-log: 
09-30 08:54:51.494  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.494  5606  5653 I jxcore-log: 
09-30 08:54:51.494  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.494  5606  5653 I jxcore-log: 
09-30 08:54:51.494  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.494  5606  5653 I jxcore-log: 
09-30 08:54:51.494  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.494  5606  5653 I jxcore-log: 
09-30 08:54:51.494  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.494  5606  5653 I jxcore-log: 
09-30 08:54:51.495  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.495  5606  5653 I jxcore-log: 
09-30 08:54:51.495  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.495  5606  5653 I jxcore-log: 
09-30 08:54:51.495  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.495  5606  5653 I jxcore-log: 
09-30 08:54:51.495  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.495  5606  5653 I jxcore-log: 
09-30 08:54:51.496  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.496  5606  5653 I jxcore-log: 
09-30 08:54:51.496  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 08:54:51.496  5606  5653 I jxcore-log: 
09-30 08:54:51.496  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.496  5606  5653 I jxcore-log: 
,09-30 08:54:51.496  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 08:54:51.496  5606  5653 I jxcore-log: 
09-30 08:54:51.496  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.496  5606  5653 I jxcore-log: 
09-30 08:54:51.497  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.497  5606  5653 I jxcore-log: 
09-30 08:54:51.497  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.497  5606  5653 I jxcore-log: 
09-30 08:54:51.497  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.497  5606  5653 I jxcore-log: 
09-30 08:54:51.497  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.497  5606  5653 I jxcore-log: 
09-30 08:54:51.497  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 08:54:51.498  5606  5653 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-30 08:54:51.498  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.498  5606  5653 I jxcore-log: 
09-30 08:54:51.498  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.498  5606  5653 I jxcore-log: 
09-30 08:54:51.498  5606  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 08:54:51.498  5606  5653 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 08:54:51.498  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 08:54:51.498  5606  5653 I jxcore-log: 
09-30 08:54:51.499  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:54:51.499  5606  5653 I jxcore-log: 
,09-30 08:54:51.499  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:54:51.499  5606  5653 I jxcore-log: 
09-30 08:54:51.499  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 08:54:51.499  5606  5653 I jxcore-log: 
09-30 08:54:51.500  5606  5606 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-30 08:54:51.504  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 08:54:51.504  5606  5653 I jxcore-log: 
09-30 08:54:51.505  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - WARN testUtils: 'myNameCallback not set!'
09-30 08:54:51.505  5606  5653 I jxcore-log: 
,09-30 08:54:51.506  5606  5653 I jxcore-log: 2016-09-30 12:54:51 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 08:54:51.506  5606  5653 I jxcore-log: 
,09-30 08:54:53.539  5606  5653 I jxcore-log: 2016-09-30 12:54:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 08:54:53.539  5606  5653 I jxcore-log: 
,09-30 08:54:53.878  5606  5653 I jxcore-log: 2016-09-30 12:54:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 08:54:53.878  5606  5653 I jxcore-log: 
,09-30 08:54:53.891  5606  5653 I jxcore-log: 2016-09-30 12:54:53 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 08:54:53.891  5606  5653 I jxcore-log: 
,09-30 08:54:55.001  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 08:54:55.001  5606  5653 I jxcore-log: 
,09-30 08:54:55.162  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 08:54:55.162  5606  5653 I jxcore-log: 
,09-30 08:54:55.167  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 08:54:55.167  5606  5653 I jxcore-log: 
,09-30 08:54:55.171  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 08:54:55.171  5606  5653 I jxcore-log: 
,09-30 08:54:55.718  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 08:54:55.718  5606  5653 I jxcore-log: 
,09-30 08:54:55.770  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 08:54:55.770  5606  5653 I jxcore-log: 
,09-30 08:54:55.783  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 08:54:55.783  5606  5653 I jxcore-log: 
,09-30 08:54:55.787  5606  5653 I jxcore-log: 2016-09-30 12:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 08:54:55.787  5606  5653 I jxcore-log: 
,09-30 08:54:56.070  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 08:54:56.070  5606  5653 I jxcore-log: 
,09-30 08:54:56.196  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 08:54:56.196  5606  5653 I jxcore-log: 
,09-30 08:54:56.428  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 08:54:56.428  5606  5653 I jxcore-log: 
,09-30 08:54:56.437  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 08:54:56.437  5606  5653 I jxcore-log: 
,09-30 08:54:56.441  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 08:54:56.441  5606  5653 I jxcore-log: 
,09-30 08:54:56.576  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 08:54:56.576  5606  5653 I jxcore-log: 
,09-30 08:54:56.583  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 08:54:56.583  5606  5653 I jxcore-log: 
,09-30 08:54:56.610  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 08:54:56.610  5606  5653 I jxcore-log: 
,09-30 08:54:56.644  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 08:54:56.644  5606  5653 I jxcore-log: 
,09-30 08:54:56.651  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 08:54:56.651  5606  5653 I jxcore-log: 
,09-30 08:54:56.656  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 08:54:56.656  5606  5653 I jxcore-log: 
,09-30 08:54:56.670  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 08:54:56.670  5606  5653 I jxcore-log: 
,09-30 08:54:56.674  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 08:54:56.674  5606  5653 I jxcore-log: 
,09-30 08:54:56.679  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 08:54:56.679  5606  5653 I jxcore-log: 
,09-30 08:54:56.683  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 08:54:56.683  5606  5653 I jxcore-log: 
,09-30 08:54:56.695  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 08:54:56.695  5606  5653 I jxcore-log: 
,09-30 08:54:56.714  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 08:54:56.714  5606  5653 I jxcore-log: 
,09-30 08:54:56.723  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 08:54:56.723  5606  5653 I jxcore-log: 
,09-30 08:54:56.734  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 08:54:56.734  5606  5653 I jxcore-log: 
,09-30 08:54:56.743  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 08:54:56.743  5606  5653 I jxcore-log: 
,09-30 08:54:56.755  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 08:54:56.755  5606  5653 I jxcore-log: 
,09-30 08:54:56.765  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 08:54:56.765  5606  5653 I jxcore-log: 
,09-30 08:54:56.770  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 08:54:56.770  5606  5653 I jxcore-log: 
,09-30 08:54:56.791  5606  5653 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 08:54:56.792  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 08:54:56.792  5606  5653 I jxcore-log: 
,09-30 08:54:56.943  5606  5653 I jxcore-log: 2016-09-30 12:54:56 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 08:54:56.943  5606  5653 I jxcore-log: 
,09-30 08:54:57.478  5606  5653 I jxcore-log: TAP version 13
09-30 08:54:57.478  5606  5653 I jxcore-log: 
,09-30 08:54:57.520  5606  5653 I jxcore-log: # setup
09-30 08:54:57.520  5606  5653 I jxcore-log: 
,09-30 08:54:58.242  5606  5653 I jxcore-log: # calling createNativeListener directly rejects
09-30 08:54:58.242  5606  5653 I jxcore-log: 
,09-30 08:54:58.756  5606  5653 I jxcore-log: 2016-09-30 12:54:58 - DEBUG createNativeListener: 'creating native server'
09-30 08:54:58.756  5606  5653 I jxcore-log: 
,09-30 08:54:58.762  5606  5653 I jxcore-log: 2016-09-30 12:54:58 - DEBUG createNativeListener: 'listening 42273'
09-30 08:54:58.762  5606  5653 I jxcore-log: 
,09-30 08:54:58.772  5606  5653 I jxcore-log: ok 1 Should throw
09-30 08:54:58.772  5606  5653 I jxcore-log: 
,09-30 08:54:58.782  5606  5653 I jxcore-log: # teardown
09-30 08:54:58.782  5606  5653 I jxcore-log: 
,09-30 08:54:59.656  5606  5653 I jxcore-log: # setup
09-30 08:54:59.656  5606  5653 I jxcore-log: 
,09-30 08:54:59.861  5606  5653 I jxcore-log: # emits incomingConnectionState
09-30 08:54:59.861  5606  5653 I jxcore-log: 
,09-30 08:55:00.046   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:00.783  5606  5653 I jxcore-log: 2016-09-30 12:55:00 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:00.783  5606  5653 I jxcore-log: 
,09-30 08:55:00.788  5606  5653 I jxcore-log: 2016-09-30 12:55:00 - DEBUG createNativeListener: 'listening 37793'
09-30 08:55:00.788  5606  5653 I jxcore-log: 
,09-30 08:55:00.798  5606  5653 I jxcore-log: 2016-09-30 12:55:00 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:00.798  5606  5653 I jxcore-log: 
,09-30 08:55:00.801  5606  5653 I jxcore-log: 2016-09-30 12:55:00 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:00.801  5606  5653 I jxcore-log: 
,09-30 08:55:00.812  5606  5653 I jxcore-log: 2016-09-30 12:55:00 - DEBUG createNativeListener: 'new mux'
09-30 08:55:00.812  5606  5653 I jxcore-log: 
,09-30 08:55:00.818  5606  5653 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 08:55:00.818  5606  5653 I jxcore-log: 
,09-30 08:55:00.836  5606  5653 I jxcore-log: 2016-09-30 12:55:00 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:00.836  5606  5653 I jxcore-log: 
,09-30 08:55:00.837  5606  5653 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 08:55:00.837  5606  5653 I jxcore-log: 
,09-30 08:55:00.845  5606  5653 I jxcore-log: # teardown
09-30 08:55:00.845  5606  5653 I jxcore-log: 
,09-30 08:55:01.047   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:01.197  5606  5653 I jxcore-log: # setup
09-30 08:55:01.197  5606  5653 I jxcore-log: 
,09-30 08:55:01.864   931  5944 D NetlinkSocketObserver: NeighborEvent{elapsedMs=346770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 08:55:02.048   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:02.134  5606  5653 I jxcore-log: # emits routerPortConnectionFailed
09-30 08:55:02.134  5606  5653 I jxcore-log: 
,09-30 08:55:02.264  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:02.264  5606  5653 I jxcore-log: 
,09-30 08:55:02.267  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'listening 38685'
09-30 08:55:02.267  5606  5653 I jxcore-log: 
,09-30 08:55:02.275  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:02.275  5606  5653 I jxcore-log: 
,09-30 08:55:02.277  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:02.277  5606  5653 I jxcore-log: 
,09-30 08:55:02.280  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'new mux'
09-30 08:55:02.280  5606  5653 I jxcore-log: 
,09-30 08:55:02.307  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:02.307  5606  5653 I jxcore-log: 
,09-30 08:55:02.310  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:02.310  5606  5653 I jxcore-log: 
,09-30 08:55:02.315  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: ' $c@net.js:837:7
09-30 08:55:02.315  5606  5653 I jxcore-log: $09@net.js:829:13
09-30 08:55:02.315  5606  5653 I jxcore-log: '
09-30 08:55:02.315  5606  5653 I jxcore-log: 
,09-30 08:55:02.316  5606  5653 I jxcore-log: ok 4 tried to connect to right port
09-30 08:55:02.316  5606  5653 I jxcore-log: 
09-30 08:55:02.317  5606  5653 I jxcore-log: ok 5 failed due to refused connection
09-30 08:55:02.317  5606  5653 I jxcore-log: 
09-30 08:55:02.318  5606  5653 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 08:55:02.318  5606  5653 I jxcore-log: 
,09-30 08:55:02.323  5606  5653 I jxcore-log: # teardown
09-30 08:55:02.323  5606  5653 I jxcore-log: 
,09-30 08:55:02.325  5606  5653 I jxcore-log: 2016-09-30 12:55:02 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:02.325  5606  5653 I jxcore-log: 
,09-30 08:55:03.049   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:03.091   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:55:03.329  5606  5653 I jxcore-log: 2016-09-30 12:55:03 - DEBUG createNativeListener: 'mux close'
09-30 08:55:03.329  5606  5653 I jxcore-log: 
,09-30 08:55:03.336  5606  5653 I jxcore-log: 2016-09-30 12:55:03 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:03.336  5606  5653 I jxcore-log: 
,09-30 08:55:03.350  5606  5653 I jxcore-log: # setup
09-30 08:55:03.350  5606  5653 I jxcore-log: 
,09-30 08:55:04.006   931  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:55:04.051   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:04.145  5606  5653 I jxcore-log: # native server connections all up
09-30 08:55:04.145  5606  5653 I jxcore-log: 
,09-30 08:55:04.403  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:04.403  5606  5653 I jxcore-log: 
,09-30 08:55:04.409  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'listening 44635'
09-30 08:55:04.409  5606  5653 I jxcore-log: 
,09-30 08:55:04.418  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:04.418  5606  5653 I jxcore-log: 
,09-30 08:55:04.420  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:04.420  5606  5653 I jxcore-log: 
09-30 08:55:04.422  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'new mux'
09-30 08:55:04.422  5606  5653 I jxcore-log: 
,09-30 08:55:04.452  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:04.452  5606  5653 I jxcore-log: 
,09-30 08:55:04.455  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:04.455  5606  5653 I jxcore-log: 
,09-30 08:55:04.459  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:04.459  5606  5653 I jxcore-log: 
,09-30 08:55:04.462  5606  5653 I jxcore-log: 2016-09-30 12:55:04 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:04.462  5606  5653 I jxcore-log: 
,09-30 08:55:04.485  5606  5653 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 08:55:04.485  5606  5653 I jxcore-log: 
,09-30 08:55:04.486  5606  5653 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 08:55:04.486  5606  5653 I jxcore-log: 
,09-30 08:55:04.489  5606  5653 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 08:55:04.489  5606  5653 I jxcore-log: 
,09-30 08:55:04.489  5606  5653 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 08:55:04.489  5606  5653 I jxcore-log: 
09-30 08:55:04.493  5606  5653 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 08:55:04.493  5606  5653 I jxcore-log: 
,09-30 08:55:04.501  5606  5653 I jxcore-log: # teardown
09-30 08:55:04.501  5606  5653 I jxcore-log: 
,09-30 08:55:05.051   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 08:55:05.492  5606  5653 I jxcore-log: 2016-09-30 12:55:05 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:05.492  5606  5653 I jxcore-log: 
,09-30 08:55:05.495  5606  5653 I jxcore-log: 2016-09-30 12:55:05 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:05.495  5606  5653 I jxcore-log: 
09-30 08:55:05.498  5606  5653 I jxcore-log: 2016-09-30 12:55:05 - DEBUG createNativeListener: 'mux close'
09-30 08:55:05.498  5606  5653 I jxcore-log: 
,09-30 08:55:05.504  5606  5653 I jxcore-log: 2016-09-30 12:55:05 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:05.504  5606  5653 I jxcore-log: 
,09-30 08:55:05.517  5606  5653 I jxcore-log: # setup
09-30 08:55:05.517  5606  5653 I jxcore-log: 
,09-30 08:55:06.123   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:55:06.402  5606  5653 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 08:55:06.402  5606  5653 I jxcore-log: 
,09-30 08:55:06.816  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:06.816  5606  5653 I jxcore-log: 
,09-30 08:55:06.821  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'listening 40038'
09-30 08:55:06.821  5606  5653 I jxcore-log: 
,09-30 08:55:06.828  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:06.828  5606  5653 I jxcore-log: 
,09-30 08:55:06.829  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:06.829  5606  5653 I jxcore-log: 
,09-30 08:55:06.834  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'new mux'
09-30 08:55:06.834  5606  5653 I jxcore-log: 
,09-30 08:55:06.845  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:06.845  5606  5653 I jxcore-log: 
,09-30 08:55:06.848  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:06.848  5606  5653 I jxcore-log: 
,09-30 08:55:06.858  5606  5653 I jxcore-log: 2016-09-30 12:55:06 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:06.858  5606  5653 I jxcore-log: 
,09-30 08:55:06.869  5606  5653 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 08:55:06.869  5606  5653 I jxcore-log: 
,09-30 08:55:06.870  5606  5653 I jxcore-log: ok 13 incoming remains open
09-30 08:55:06.870  5606  5653 I jxcore-log: 
,09-30 08:55:06.877  5606  5653 I jxcore-log: # teardown
09-30 08:55:06.877  5606  5653 I jxcore-log: 
,09-30 08:55:07.624  5606  5653 I jxcore-log: 2016-09-30 12:55:07 - DEBUG createNativeListener: 'mux close'
09-30 08:55:07.624  5606  5653 I jxcore-log: 
,09-30 08:55:07.634  5606  5653 I jxcore-log: 2016-09-30 12:55:07 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:07.634  5606  5653 I jxcore-log: 
,09-30 08:55:07.644  5606  5653 I jxcore-log: # setup
09-30 08:55:07.644  5606  5653 I jxcore-log: 
,09-30 08:55:08.143  5606  5653 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 08:55:08.143  5606  5653 I jxcore-log: 
,09-30 08:55:08.961  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:08.961  5606  5653 I jxcore-log: 
09-30 08:55:08.965  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'listening 40342'
09-30 08:55:08.965  5606  5653 I jxcore-log: 
,09-30 08:55:08.972  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:08.972  5606  5653 I jxcore-log: 
,09-30 08:55:08.974  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:08.974  5606  5653 I jxcore-log: 
,09-30 08:55:08.977  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'new mux'
09-30 08:55:08.977  5606  5653 I jxcore-log: 
,09-30 08:55:08.987  5606  5653 I jxcore-log: ok 14 we should not have gotten an error
09-30 08:55:08.987  5606  5653 I jxcore-log: 
,09-30 08:55:08.992  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:08.992  5606  5653 I jxcore-log: 
,09-30 08:55:08.998  5606  5653 I jxcore-log: 2016-09-30 12:55:08 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:08.998  5606  5653 I jxcore-log: 
,09-30 08:55:09.008  5606  5653 I jxcore-log: 2016-09-30 12:55:09 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:09.008  5606  5653 I jxcore-log: 
,09-30 08:55:09.010  5606  5653 I jxcore-log: 2016-09-30 12:55:09 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:09.010  5606  5653 I jxcore-log: 
,09-30 08:55:09.021  5606  5653 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 08:55:09.021  5606  5653 I jxcore-log: 
,09-30 08:55:09.021  5606  5653 I jxcore-log: ok 16 incoming is cleaned up
09-30 08:55:09.021  5606  5653 I jxcore-log: 
,09-30 08:55:09.032  5606  5653 I jxcore-log: # teardown
09-30 08:55:09.032  5606  5653 I jxcore-log: 
,09-30 08:55:09.483  5606  5653 I jxcore-log: # setup
09-30 08:55:09.483  5606  5653 I jxcore-log: 
,09-30 08:55:10.052   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:11.006  5606  5653 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 08:55:11.006  5606  5653 I jxcore-log: 
,09-30 08:55:11.050  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:11.050  5606  5653 I jxcore-log: 
,09-30 08:55:11.055   537   537 I ServiceManager: Waiting for service AtCmdFwd...
09-30 08:55:11.056  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'listening 43775'
09-30 08:55:11.056  5606  5653 I jxcore-log: 
,09-30 08:55:11.064  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:11.064  5606  5653 I jxcore-log: 
09-30 08:55:11.066  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:11.066  5606  5653 I jxcore-log: 
,09-30 08:55:11.069  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'new mux'
09-30 08:55:11.069  5606  5653 I jxcore-log: 
,09-30 08:55:11.082  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:11.082  5606  5653 I jxcore-log: 
,09-30 08:55:11.085  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:11.085  5606  5653 I jxcore-log: 
,09-30 08:55:11.100  5606  5653 I jxcore-log: 2016-09-30 12:55:11 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:11.100  5606  5653 I jxcore-log: 
,09-30 08:55:11.110  5606  5653 I jxcore-log: ok 17 stream was closed
09-30 08:55:11.110  5606  5653 I jxcore-log: 
,09-30 08:55:11.111  5606  5653 I jxcore-log: ok 18 incoming should survive
09-30 08:55:11.111  5606  5653 I jxcore-log: 
,09-30 08:55:11.112  5606  5653 I jxcore-log: ok 19 mux should have no streams
09-30 08:55:11.112  5606  5653 I jxcore-log: 
,09-30 08:55:11.117  5606  5653 I jxcore-log: # teardown
09-30 08:55:11.117  5606  5653 I jxcore-log: 
,09-30 08:55:12.056   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:12.124  5606  5653 I jxcore-log: 2016-09-30 12:55:12 - DEBUG createNativeListener: 'mux close'
09-30 08:55:12.124  5606  5653 I jxcore-log: 
,09-30 08:55:12.146  5606  5653 I jxcore-log: 2016-09-30 12:55:12 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:12.146  5606  5653 I jxcore-log: 
,09-30 08:55:12.160  5606  5653 I jxcore-log: # setup
09-30 08:55:12.160  5606  5653 I jxcore-log: 
,09-30 08:55:13.058   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:13.885  5606  5653 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 08:55:13.885  5606  5653 I jxcore-log: 
,09-30 08:55:14.059   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:14.175  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:14.175  5606  5653 I jxcore-log: 
,09-30 08:55:14.180  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'listening 37580'
09-30 08:55:14.180  5606  5653 I jxcore-log: 
,09-30 08:55:14.190  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:14.190  5606  5653 I jxcore-log: 
,09-30 08:55:14.192  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:14.192  5606  5653 I jxcore-log: 
,09-30 08:55:14.194  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'new mux'
09-30 08:55:14.194  5606  5653 I jxcore-log: 
,09-30 08:55:14.202  5606  5653 I jxcore-log: ok 20 we should not have gotten an error
09-30 08:55:14.202  5606  5653 I jxcore-log: 
,09-30 08:55:14.207  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:14.207  5606  5653 I jxcore-log: 
,09-30 08:55:14.210  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:14.210  5606  5653 I jxcore-log: 
,09-30 08:55:14.218  5606  5653 I jxcore-log: ok 21 Buffers are identical
09-30 08:55:14.218  5606  5653 I jxcore-log: 
,09-30 08:55:14.220  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:14.220  5606  5653 I jxcore-log: 
,09-30 08:55:14.223  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'mux close'
09-30 08:55:14.223  5606  5653 I jxcore-log: 
,09-30 08:55:14.225  5606  5653 I jxcore-log: ok 22 native server is nulled out
09-30 08:55:14.225  5606  5653 I jxcore-log: 
,09-30 08:55:14.225  5606  5653 I jxcore-log: ok 23 native server should be closed
09-30 08:55:14.225  5606  5653 I jxcore-log: 
09-30 08:55:14.225  5606  5653 I jxcore-log: ok 24 incoming has been removed
09-30 08:55:14.225  5606  5653 I jxcore-log: 
09-30 08:55:14.226  5606  5653 I jxcore-log: ok 25 Incoming should be done
09-30 08:55:14.226  5606  5653 I jxcore-log: 
09-30 08:55:14.226  5606  5653 I jxcore-log: ok 26 The mux object should be closed
09-30 08:55:14.226  5606  5653 I jxcore-log: 
09-30 08:55:14.226  5606  5653 I jxcore-log: ok 27 The mux stream should be closed
09-30 08:55:14.226  5606  5653 I jxcore-log: 
,09-30 08:55:14.227  5606  5653 I jxcore-log: 2016-09-30 12:55:14 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:14.227  5606  5653 I jxcore-log: 
,09-30 08:55:14.239  5606  5653 I jxcore-log: # teardown
09-30 08:55:14.239  5606  5653 I jxcore-log: 
,09-30 08:55:15.059   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 08:55:15.319  5606  5653 I jxcore-log: # setup
09-30 08:55:15.319  5606  5653 I jxcore-log: 
,09-30 08:55:15.492  5606  5653 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 08:55:15.492  5606  5653 I jxcore-log: 
,09-30 08:55:16.427  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:16.427  5606  5653 I jxcore-log: 
,09-30 08:55:16.432  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'listening 46232'
09-30 08:55:16.432  5606  5653 I jxcore-log: 
,09-30 08:55:16.466  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.466  5606  5653 I jxcore-log: 
,09-30 08:55:16.467  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.467  5606  5653 I jxcore-log: 
,09-30 08:55:16.468  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.468  5606  5653 I jxcore-log: 
,09-30 08:55:16.472  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.472  5606  5653 I jxcore-log: 
,09-30 08:55:16.473  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.473  5606  5653 I jxcore-log: 
09-30 08:55:16.474  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.474  5606  5653 I jxcore-log: 
,09-30 08:55:16.477  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.477  5606  5653 I jxcore-log: 
,09-30 08:55:16.478  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.478  5606  5653 I jxcore-log: 
,09-30 08:55:16.479  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.479  5606  5653 I jxcore-log: 
,09-30 08:55:16.483  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.483  5606  5653 I jxcore-log: 
,09-30 08:55:16.484  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.484  5606  5653 I jxcore-log: 
,09-30 08:55:16.485  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.485  5606  5653 I jxcore-log: 
,09-30 08:55:16.489  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.489  5606  5653 I jxcore-log: 
,09-30 08:55:16.490  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.490  5606  5653 I jxcore-log: 
,09-30 08:55:16.493  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.493  5606  5653 I jxcore-log: 
,09-30 08:55:16.496  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.496  5606  5653 I jxcore-log: 
,09-30 08:55:16.497  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.497  5606  5653 I jxcore-log: 
,09-30 08:55:16.498  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.498  5606  5653 I jxcore-log: 
,09-30 08:55:16.506  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.506  5606  5653 I jxcore-log: 
,09-30 08:55:16.506  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.506  5606  5653 I jxcore-log: 
,09-30 08:55:16.507  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.507  5606  5653 I jxcore-log: 
,09-30 08:55:16.509  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.509  5606  5653 I jxcore-log: 
09-30 08:55:16.509  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.509  5606  5653 I jxcore-log: 
09-30 08:55:16.510  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.510  5606  5653 I jxcore-log: 
,09-30 08:55:16.511  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.511  5606  5653 I jxcore-log: 
,09-30 08:55:16.511  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.511  5606  5653 I jxcore-log: 
09-30 08:55:16.512  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.512  5606  5653 I jxcore-log: 
,09-30 08:55:16.513  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:16.513  5606  5653 I jxcore-log: 
,09-30 08:55:16.513  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:16.513  5606  5653 I jxcore-log: 
09-30 08:55:16.514  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new mux'
09-30 08:55:16.514  5606  5653 I jxcore-log: 
,09-30 08:55:16.566  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.566  5606  5653 I jxcore-log: 
,09-30 08:55:16.568  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.568  5606  5653 I jxcore-log: 
,09-30 08:55:16.570  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.570  5606  5653 I jxcore-log: 
,09-30 08:55:16.571  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.571  5606  5653 I jxcore-log: 
09-30 08:55:16.572  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.572  5606  5653 I jxcore-log: 
,09-30 08:55:16.573  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.573  5606  5653 I jxcore-log: 
,09-30 08:55:16.574  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.574  5606  5653 I jxcore-log: 
09-30 08:55:16.575  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.575  5606  5653 I jxcore-log: 
,09-30 08:55:16.577  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.577  5606  5653 I jxcore-log: 
,09-30 08:55:16.578  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.578  5606  5653 I jxcore-log: 
09-30 08:55:16.578  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.578  5606  5653 I jxcore-log: 
,09-30 08:55:16.579  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.579  5606  5653 I jxcore-log: 
09-30 08:55:16.580  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.580  5606  5653 I jxcore-log: 
09-30 08:55:16.581  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.581  5606  5653 I jxcore-log: 
,09-30 08:55:16.582  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.582  5606  5653 I jxcore-log: 
09-30 08:55:16.582  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.582  5606  5653 I jxcore-log: 
,09-30 08:55:16.584  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.584  5606  5653 I jxcore-log: 
09-30 08:55:16.585  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.585  5606  5653 I jxcore-log: 
,09-30 08:55:16.585  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.585  5606  5653 I jxcore-log: 
09-30 08:55:16.586  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.586  5606  5653 I jxcore-log: 
09-30 08:55:16.587  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.587  5606  5653 I jxcore-log: 
,09-30 08:55:16.588  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.588  5606  5653 I jxcore-log: 
09-30 08:55:16.588  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.588  5606  5653 I jxcore-log: 
,09-30 08:55:16.589  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.589  5606  5653 I jxcore-log: 
09-30 08:55:16.590  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.590  5606  5653 I jxcore-log: 
,09-30 08:55:16.591  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.591  5606  5653 I jxcore-log: 
09-30 08:55:16.592  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.592  5606  5653 I jxcore-log: 
09-30 08:55:16.593  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.593  5606  5653 I jxcore-log: 
,09-30 08:55:16.593  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.593  5606  5653 I jxcore-log: 
09-30 08:55:16.594  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.594  5606  5653 I jxcore-log: 
,09-30 08:55:16.595  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.595  5606  5653 I jxcore-log: 
09-30 08:55:16.595  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.595  5606  5653 I jxcore-log: 
09-30 08:55:16.596  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.596  5606  5653 I jxcore-log: 
09-30 08:55:16.597  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.597  5606  5653 I jxcore-log: 
09-30 08:55:16.597  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.597  5606  5653 I jxcore-log: 
,09-30 08:55:16.598  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.598  5606  5653 I jxcore-log: 
,09-30 08:55:16.599  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.599  5606  5653 I jxcore-log: 
09-30 08:55:16.599  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.599  5606  5653 I jxcore-log: 
,09-30 08:55:16.600  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.600  5606  5653 I jxcore-log: 
09-30 08:55:16.601  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.601  5606  5653 I jxcore-log: 
,09-30 08:55:16.601  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.601  5606  5653 I jxcore-log: 
,09-30 08:55:16.602  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.602  5606  5653 I jxcore-log: 
,09-30 08:55:16.603  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.603  5606  5653 I jxcore-log: 
09-30 08:55:16.603  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.603  5606  5653 I jxcore-log: 
,09-30 08:55:16.604  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.604  5606  5653 I jxcore-log: 
09-30 08:55:16.605  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.605  5606  5653 I jxcore-log: 
,09-30 08:55:16.605  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.605  5606  5653 I jxcore-log: 
09-30 08:55:16.606  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.606  5606  5653 I jxcore-log: 
,09-30 08:55:16.612  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.612  5606  5653 I jxcore-log: 
,09-30 08:55:16.613  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.613  5606  5653 I jxcore-log: 
,09-30 08:55:16.614  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.614  5606  5653 I jxcore-log: 
09-30 08:55:16.614  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.614  5606  5653 I jxcore-log: 
,09-30 08:55:16.615  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.615  5606  5653 I jxcore-log: 
09-30 08:55:16.616  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.616  5606  5653 I jxcore-log: 
,09-30 08:55:16.616  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.616  5606  5653 I jxcore-log: 
09-30 08:55:16.617  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.617  5606  5653 I jxcore-log: 
,09-30 08:55:16.618  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.618  5606  5653 I jxcore-log: 
,09-30 08:55:16.619  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.619  5606  5653 I jxcore-log: 
,09-30 08:55:16.619  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.619  5606  5653 I jxcore-log: 
09-30 08:55:16.620  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.620  5606  5653 I jxcore-log: 
,09-30 08:55:16.621  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.621  5606  5653 I jxcore-log: 
09-30 08:55:16.621  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.621  5606  5653 I jxcore-log: 
,09-30 08:55:16.622  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.622  5606  5653 I jxcore-log: 
09-30 08:55:16.622  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.622  5606  5653 I jxcore-log: 
,09-30 08:55:16.623  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.623  5606  5653 I jxcore-log: 
,09-30 08:55:16.624  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.624  5606  5653 I jxcore-log: 
09-30 08:55:16.625  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.625  5606  5653 I jxcore-log: 
,09-30 08:55:16.625  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.625  5606  5653 I jxcore-log: 
09-30 08:55:16.626  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.626  5606  5653 I jxcore-log: 
09-30 08:55:16.627  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.627  5606  5653 I jxcore-log: 
,09-30 08:55:16.627  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.627  5606  5653 I jxcore-log: 
09-30 08:55:16.628  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.628  5606  5653 I jxcore-log: 
,09-30 08:55:16.629  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.629  5606  5653 I jxcore-log: 
,09-30 08:55:16.630  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.630  5606  5653 I jxcore-log: 
,09-30 08:55:16.630  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.630  5606  5653 I jxcore-log: 
09-30 08:55:16.631  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.631  5606  5653 I jxcore-log: 
09-30 08:55:16.631  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.631  5606  5653 I jxcore-log: 
09-30 08:55:16.632  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.632  5606  5653 I jxcore-log: 
09-30 08:55:16.632  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:16.632  5606  5653 I jxcore-log: 
,09-30 08:55:16.633  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:16.633  5606  5653 I jxcore-log: 
,09-30 08:55:16.678  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.678  5606  5653 I jxcore-log: 
,09-30 08:55:16.679  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.679  5606  5653 I jxcore-log: 
,09-30 08:55:16.680  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.680  5606  5653 I jxcore-log: 
,09-30 08:55:16.681  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.681  5606  5653 I jxcore-log: 
,09-30 08:55:16.682  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.682  5606  5653 I jxcore-log: 
,09-30 08:55:16.682  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.682  5606  5653 I jxcore-log: 
,09-30 08:55:16.683  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.683  5606  5653 I jxcore-log: 
,09-30 08:55:16.683  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.683  5606  5653 I jxcore-log: 
,09-30 08:55:16.683  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.683  5606  5653 I jxcore-log: 
09-30 08:55:16.684  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.684  5606  5653 I jxcore-log: 
,09-30 08:55:16.684  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.684  5606  5653 I jxcore-log: 
09-30 08:55:16.685  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.685  5606  5653 I jxcore-log: 
,09-30 08:55:16.685  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.685  5606  5653 I jxcore-log: 
09-30 08:55:16.686  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.686  5606  5653 I jxcore-log: 
,09-30 08:55:16.686  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.686  5606  5653 I jxcore-log: 
,09-30 08:55:16.687  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.687  5606  5653 I jxcore-log: 
09-30 08:55:16.688  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.688  5606  5653 I jxcore-log: 
,09-30 08:55:16.688  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.688  5606  5653 I jxcore-log: 
09-30 08:55:16.688  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.688  5606  5653 I jxcore-log: 
,09-30 08:55:16.689  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.689  5606  5653 I jxcore-log: 
09-30 08:55:16.689  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.689  5606  5653 I jxcore-log: 
09-30 08:55:16.690  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.690  5606  5653 I jxcore-log: 
,09-30 08:55:16.690  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.690  5606  5653 I jxcore-log: 
09-30 08:55:16.690  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.690  5606  5653 I jxcore-log: 
,09-30 08:55:16.691  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.691  5606  5653 I jxcore-log: 
09-30 08:55:16.692  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.692  5606  5653 I jxcore-log: 
09-30 08:55:16.692  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.692  5606  5653 I jxcore-log: 
09-30 08:55:16.692  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.692  5606  5653 I jxcore-log: 
09-30 08:55:16.693  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.693  5606  5653 I jxcore-log: 
09-30 08:55:16.693  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.693  5606  5653 I jxcore-log: 
,09-30 08:55:16.694  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.694  5606  5653 I jxcore-log: 
09-30 08:55:16.694  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.694  5606  5653 I jxcore-log: 
09-30 08:55:16.695  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.695  5606  5653 I jxcore-log: 
09-30 08:55:16.695  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.695  5606  5653 I jxcore-log: 
09-30 08:55:16.696  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.696  5606  5653 I jxcore-log: 
09-30 08:55:16.696  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.696  5606  5653 I jxcore-log: 
09-30 08:55:16.696  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.696  5606  5653 I jxcore-log: 
09-30 08:55:16.697  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.697  5606  5653 I jxcore-log: 
,09-30 08:55:16.697  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.697  5606  5653 I jxcore-log: 
09-30 08:55:16.698  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.698  5606  5653 I jxcore-log: 
09-30 08:55:16.698  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.698  5606  5653 I jxcore-log: 
09-30 08:55:16.698  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.698  5606  5653 I jxcore-log: 
09-30 08:55:16.699  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.699  5606  5653 I jxcore-log: 
09-30 08:55:16.699  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.699  5606  5653 I jxcore-log: 
,09-30 08:55:16.701  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.701  5606  5653 I jxcore-log: 
,09-30 08:55:16.701  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.701  5606  5653 I jxcore-log: 
,09-30 08:55:16.702  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.702  5606  5653 I jxcore-log: 
,09-30 08:55:16.704  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.704  5606  5653 I jxcore-log: 
,09-30 08:55:16.705  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:16.705  5606  5653 I jxcore-log: 
09-30 08:55:16.705  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'mux close'
09-30 08:55:16.705  5606  5653 I jxcore-log: 
,09-30 08:55:16.707  5606  5653 I jxcore-log: ok 28 native server is nulled out
09-30 08:55:16.707  5606  5653 I jxcore-log: 
,09-30 08:55:16.707  5606  5653 I jxcore-log: ok 29 native server should be closed
09-30 08:55:16.707  5606  5653 I jxcore-log: 
09-30 08:55:16.708  5606  5653 I jxcore-log: ok 30 incoming has been removed
09-30 08:55:16.708  5606  5653 I jxcore-log: 
09-30 08:55:16.708  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.708  5606  5653 I jxcore-log: 
,09-30 08:55:16.709  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.709  5606  5653 I jxcore-log: 
09-30 08:55:16.709  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.709  5606  5653 I jxcore-log: 
,09-30 08:55:16.710  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.710  5606  5653 I jxcore-log: 
09-30 08:55:16.710  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.710  5606  5653 I jxcore-log: 
09-30 08:55:16.710  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.710  5606  5653 I jxcore-log: 
,09-30 08:55:16.710  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.710  5606  5653 I jxcore-log: 
09-30 08:55:16.710  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.710  5606  5653 I jxcore-log: 
09-30 08:55:16.711  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.711  5606  5653 I jxcore-log: 
09-30 08:55:16.711  5606  5653 I jxcore-log: 2016-09-30 12:55:16 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:16.711  5606  5653 I jxcore-log: 
,09-30 08:55:16.783  5606  5653 I jxcore-log: # teardown
09-30 08:55:16.783  5606  5653 I jxcore-log: 
,09-30 08:55:17.262  5606  5653 I jxcore-log: # setup
09-30 08:55:17.262  5606  5653 I jxcore-log: 
,09-30 08:55:18.997  5606  5653 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 08:55:18.997  5606  5653 I jxcore-log: 
,09-30 08:55:19.052  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:19.052  5606  5653 I jxcore-log: 
,09-30 08:55:19.057  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'listening 39595'
09-30 08:55:19.057  5606  5653 I jxcore-log: 
,09-30 08:55:19.067  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:19.067  5606  5653 I jxcore-log: 
,09-30 08:55:19.069  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:19.069  5606  5653 I jxcore-log: 
,09-30 08:55:19.071  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'new mux'
09-30 08:55:19.071  5606  5653 I jxcore-log: 
,09-30 08:55:19.080  5606  5653 I jxcore-log: ok 31 we should not have gotten an error
09-30 08:55:19.080  5606  5653 I jxcore-log: 
,09-30 08:55:19.084  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:19.084  5606  5653 I jxcore-log: 
,09-30 08:55:19.087  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:19.087  5606  5653 I jxcore-log: 
,09-30 08:55:19.095  5606  5653 I jxcore-log: ok 32 Buffers are identical
09-30 08:55:19.095  5606  5653 I jxcore-log: 
,09-30 08:55:19.096  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:19.096  5606  5653 I jxcore-log: 
,09-30 08:55:19.099  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'mux close'
09-30 08:55:19.099  5606  5653 I jxcore-log: 
,09-30 08:55:19.110  5606  5653 I jxcore-log: 2016-09-30 12:55:19 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:19.110  5606  5653 I jxcore-log: 
,09-30 08:55:19.111  5606  5653 I jxcore-log: ok 33 server should be fine
09-30 08:55:19.111  5606  5653 I jxcore-log: 
09-30 08:55:19.111  5606  5653 I jxcore-log: ok 34 server should be open
09-30 08:55:19.111  5606  5653 I jxcore-log: 
09-30 08:55:19.111  5606  5653 I jxcore-log: ok 35 incoming has been removed
09-30 08:55:19.111  5606  5653 I jxcore-log: 
09-30 08:55:19.111  5606  5653 I jxcore-log: ok 36 The mux object should be closed
09-30 08:55:19.111  5606  5653 I jxcore-log: 
09-30 08:55:19.112  5606  5653 I jxcore-log: ok 37 The mux stream should be closed
09-30 08:55:19.112  5606  5653 I jxcore-log: 
,09-30 08:55:19.117  5606  5653 I jxcore-log: # teardown
09-30 08:55:19.117  5606  5653 I jxcore-log: 
,09-30 08:55:20.840  5606  5653 I jxcore-log: # setup
09-30 08:55:20.840  5606  5653 I jxcore-log: 
,09-30 08:55:21.154  5606  5653 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 08:55:21.154  5606  5653 I jxcore-log: 
,09-30 08:55:21.652  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'creating native server'
09-30 08:55:21.652  5606  5653 I jxcore-log: 
,09-30 08:55:21.659  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'listening 41333'
09-30 08:55:21.659  5606  5653 I jxcore-log: 
,09-30 08:55:21.668  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'new incoming socket'
09-30 08:55:21.668  5606  5653 I jxcore-log: 
,09-30 08:55:21.670  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'creating incoming mux'
09-30 08:55:21.670  5606  5653 I jxcore-log: 
09-30 08:55:21.672  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'new mux'
09-30 08:55:21.672  5606  5653 I jxcore-log: 
,09-30 08:55:21.679  5606  5653 I jxcore-log: ok 38 we should not have gotten an error
09-30 08:55:21.679  5606  5653 I jxcore-log: 
,09-30 08:55:21.682  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'new stream: '
09-30 08:55:21.682  5606  5653 I jxcore-log: 
,09-30 08:55:21.685  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'new outgoing socket'
09-30 08:55:21.685  5606  5653 I jxcore-log: 
,09-30 08:55:21.692  5606  5653 I jxcore-log: ok 39 Buffers are identical
09-30 08:55:21.692  5606  5653 I jxcore-log: 
,09-30 08:55:21.697  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 08:55:21.697  5606  5653 I jxcore-log: 
,09-30 08:55:21.699  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'stream close:'
09-30 08:55:21.699  5606  5653 I jxcore-log: 
,09-30 08:55:21.701  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'mux close'
09-30 08:55:21.701  5606  5653 I jxcore-log: 
,09-30 08:55:21.707  5606  5653 I jxcore-log: 2016-09-30 12:55:21 - DEBUG createNativeListener: 'incoming socket close'
09-30 08:55:21.707  5606  5653 I jxcore-log: 
,09-30 08:55:21.708  5606  5653 I jxcore-log: ok 40 server should be fine
09-30 08:55:21.708  5606  5653 I jxcore-log: 
09-30 08:55:21.709  5606  5653 I jxcore-log: ok 41 server should be open
09-30 08:55:21.709  5606  5653 I jxcore-log: 
09-30 08:55:21.709  5606  5653 I jxcore-log: ok 42 incoming has been removed
09-30 08:55:21.709  5606  5653 I jxcore-log: 
09-30 08:55:21.709  5606  5653 I jxcore-log: ok 43 The mux object should be closed
09-30 08:55:21.709  5606  5653 I jxcore-log: 
09-30 08:55:21.710  5606  5653 I jxcore-log: ok 44 The mux stream should be closed
09-30 08:55:21.710  5606  5653 I jxcore-log: 
,09-30 08:55:21.716  5606  5653 I jxcore-log: # teardown
09-30 08:55:21.716  5606  5653 I jxcore-log: 
,09-30 08:55:22.513  5606  5653 I jxcore-log: # setup
09-30 08:55:22.513  5606  5653 I jxcore-log: 
,09-30 08:55:22.636  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 08:55:22.636  5606  5653 I jxcore-log: 
,09-30 08:55:22.835  5606  5653 I jxcore-log: 2016-09-30 12:55:22 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 08:55:22.835  5606  5653 I jxcore-log: 
,09-30 08:55:22.836  5606  5653 I jxcore-log: ok 45 Got right error
09-30 08:55:22.836  5606  5653 I jxcore-log: 
,09-30 08:55:22.841  5606  5653 I jxcore-log: # teardown
09-30 08:55:22.841  5606  5653 I jxcore-log: 
,09-30 08:55:22.883  5606  5653 I jxcore-log: # setup
09-30 08:55:22.883  5606  5653 I jxcore-log: 
,09-30 08:55:22.960  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 08:55:22.960  5606  5653 I jxcore-log: 
,09-30 08:55:23.071  5606  5653 I jxcore-log: 2016-09-30 12:55:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 08:55:23.071  5606  5653 I jxcore-log: 
,09-30 08:55:23.072  5606  5653 I jxcore-log: ok 46 Got socket hang up
09-30 08:55:23.072  5606  5653 I jxcore-log: 
,09-30 08:55:23.078  5606  5653 I jxcore-log: # teardown
09-30 08:55:23.078  5606  5653 I jxcore-log: 
,09-30 08:55:23.172  5606  5653 I jxcore-log: # setup
09-30 08:55:23.172  5606  5653 I jxcore-log: 
,09-30 08:55:23.316  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 08:55:23.316  5606  5653 I jxcore-log: 
,09-30 08:55:23.563  5606  5653 I jxcore-log: 2016-09-30 12:55:23 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 08:55:23.563  5606  5653 I jxcore-log: 
,09-30 08:55:23.565  5606  5653 I jxcore-log: ok 47 Got 500 as expected
09-30 08:55:23.565  5606  5653 I jxcore-log: 
,09-30 08:55:23.570  5606  5653 I jxcore-log: # teardown
09-30 08:55:23.570  5606  5653 I jxcore-log: 
,09-30 08:55:23.603  5606  5653 I jxcore-log: # setup
09-30 08:55:23.603  5606  5653 I jxcore-log: 
,09-30 08:55:23.643  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 08:55:23.643  5606  5653 I jxcore-log: 
,09-30 08:55:24.009   931  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:55:25.060   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:25.077  5606  5653 I jxcore-log: ok 48 should be equal
09-30 08:55:25.077  5606  5653 I jxcore-log: 
,09-30 08:55:25.078  5606  5653 I jxcore-log: ok 49 revs are equal
09-30 08:55:25.078  5606  5653 I jxcore-log: 
,09-30 08:55:25.082  5606  5653 I jxcore-log: # teardown
09-30 08:55:25.082  5606  5653 I jxcore-log: 
,09-30 08:55:25.122  5606  5653 I jxcore-log: # setup
09-30 08:55:25.122  5606  5653 I jxcore-log: 
,09-30 08:55:25.862  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 08:55:25.862  5606  5653 I jxcore-log: 
,09-30 08:55:26.061   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:26.996  5606  5653 I jxcore-log: ok 50 should be equal
09-30 08:55:26.996  5606  5653 I jxcore-log: 
,09-30 08:55:26.996  5606  5653 I jxcore-log: ok 51 revs are equal
09-30 08:55:26.996  5606  5653 I jxcore-log: 
,09-30 08:55:27.002  5606  5653 I jxcore-log: # teardown
09-30 08:55:27.002  5606  5653 I jxcore-log: 
,09-30 08:55:27.062   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:27.741  5606  5653 I jxcore-log: # setup
09-30 08:55:27.741  5606  5653 I jxcore-log: 
,09-30 08:55:28.063   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:28.724  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 08:55:28.724  5606  5653 I jxcore-log: 
,09-30 08:55:29.065   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:29.750  5606  5653 I jxcore-log: ok 52 should be equal
09-30 08:55:29.750  5606  5653 I jxcore-log: 
,09-30 08:55:29.750  5606  5653 I jxcore-log: ok 53 revs are equal
09-30 08:55:29.750  5606  5653 I jxcore-log: 
,09-30 08:55:29.916  5606  5653 I jxcore-log: ok 54 should be equal
09-30 08:55:29.916  5606  5653 I jxcore-log: 
,09-30 08:55:29.917  5606  5653 I jxcore-log: ok 55 revs are equal
09-30 08:55:29.917  5606  5653 I jxcore-log: 
,09-30 08:55:30.065   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 08:55:30.110  5606  5653 I jxcore-log: ok 56 should be equal
09-30 08:55:30.110  5606  5653 I jxcore-log: 
,09-30 08:55:30.111  5606  5653 I jxcore-log: ok 57 revs are equal
09-30 08:55:30.111  5606  5653 I jxcore-log: 
,09-30 08:55:30.118  5606  5653 I jxcore-log: # teardown
09-30 08:55:30.118  5606  5653 I jxcore-log: 
,09-30 08:55:30.595  5606  5653 I jxcore-log: # setup
09-30 08:55:30.595  5606  5653 I jxcore-log: 
,09-30 08:55:31.077  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 08:55:31.077  5606  5653 I jxcore-log: 
,09-30 08:55:32.705  5606  5653 I jxcore-log: 2016-09-30 12:55:32 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 08:55:32.705  5606  5653 I jxcore-log: 
,09-30 08:55:32.706  5606  5653 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 08:55:32.706  5606  5653 I jxcore-log: 
,09-30 08:55:32.710  5606  5653 I jxcore-log: # teardown
09-30 08:55:32.710  5606  5653 I jxcore-log: 
,09-30 08:55:32.849  5606  5653 I jxcore-log: # setup
09-30 08:55:32.849  5606  5653 I jxcore-log: 
,09-30 08:55:32.890  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 08:55:32.890  5606  5653 I jxcore-log: 
,09-30 08:55:32.996  5606  5653 I jxcore-log: ok 59 confirm stop caused failure
09-30 08:55:32.996  5606  5653 I jxcore-log: 
,09-30 08:55:33.007  5606  5653 I jxcore-log: # teardown
09-30 08:55:33.007  5606  5653 I jxcore-log: 
,09-30 08:55:33.032  5606  5653 I jxcore-log: # setup
09-30 08:55:33.032  5606  5653 I jxcore-log: 
,09-30 08:55:33.131  5606  5653 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 08:55:33.131  5606  5653 I jxcore-log: 
,09-30 08:55:33.443  5606  5653 I jxcore-log: 2016-09-30 12:55:33 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 08:55:33.443  5606  5653 I jxcore-log: 
,09-30 08:55:33.445  5606  5653 I jxcore-log: ok 60 stop caused us to fail
09-30 08:55:33.445  5606  5653 I jxcore-log: 
,09-30 08:55:33.446  5606  5653 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 08:55:33.446  5606  5653 I jxcore-log: 
,09-30 08:55:33.451  5606  5653 I jxcore-log: # teardown
09-30 08:55:33.451  5606  5653 I jxcore-log: 
,09-30 08:55:33.600  5606  5653 I jxcore-log: # setup
09-30 08:55:33.600  5606  5653 I jxcore-log: 
,09-30 08:55:33.661  5606  5653 I jxcore-log: # #update - fail if stop is called
09-30 08:55:33.661  5606  5653 I jxcore-log: 
,09-30 08:55:33.745  5606  5653 I jxcore-log: ok 62 failed due to stop
09-30 08:55:33.745  5606  5653 I jxcore-log: 
,09-30 08:55:33.747  5606  5653 I jxcore-log: ok 63 failed due to stop
09-30 08:55:33.747  5606  5653 I jxcore-log: 
,09-30 08:55:33.755  5606  5653 I jxcore-log: # teardown
09-30 08:55:33.755  5606  5653 I jxcore-log: 
,09-30 08:55:33.844  5606  5653 I jxcore-log: # setup
09-30 08:55:33.844  5606  5653 I jxcore-log: 
,09-30 08:55:33.883  5606  5653 I jxcore-log: # #update - set seq for first time
09-30 08:55:33.883  5606  5653 I jxcore-log: 
,09-30 08:55:34.433  5606  5653 I jxcore-log: ok 64 should be equal
09-30 08:55:34.433  5606  5653 I jxcore-log: 
,09-30 08:55:34.440  5606  5653 I jxcore-log: # teardown
09-30 08:55:34.440  5606  5653 I jxcore-log: 
,09-30 08:55:34.509  5606  5653 I jxcore-log: # setup
09-30 08:55:34.509  5606  5653 I jxcore-log: 
,09-30 08:55:34.568  5606  5653 I jxcore-log: # #update - Fail on bad seq value
09-30 08:55:34.568  5606  5653 I jxcore-log: 
,09-30 08:55:34.980  5606  5653 I jxcore-log: 2016-09-30 12:55:34 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 08:55:34.980  5606  5653 I jxcore-log: 
,09-30 08:55:34.982  5606  5653 I jxcore-log: ok 65 Expected bad seq error
09-30 08:55:34.982  5606  5653 I jxcore-log: 
09-30 08:55:34.986  5606  5653 I jxcore-log: # teardown
09-30 08:55:34.986  5606  5653 I jxcore-log: 
,09-30 08:55:35.032  5606  5653 I jxcore-log: # setup
09-30 08:55:35.032  5606  5653 I jxcore-log: 
,09-30 08:55:35.089  5606  5653 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 08:55:35.089  5606  5653 I jxcore-log: 
,09-30 08:55:36.581  5606  5653 I jxcore-log: ok 66 Different promises
09-30 08:55:36.581  5606  5653 I jxcore-log: 
,09-30 08:55:36.584  5606  5653 I jxcore-log: ok 67 Timer was cancelled
09-30 08:55:36.584  5606  5653 I jxcore-log: 
,09-30 08:55:36.736  5606  5653 I jxcore-log: ok 68 should be equal
09-30 08:55:36.736  5606  5653 I jxcore-log: 
,09-30 08:55:36.743  5606  5653 I jxcore-log: # teardown
09-30 08:55:36.743  5606  5653 I jxcore-log: 
,09-30 08:55:36.941  5606  5653 I jxcore-log: # setup
09-30 08:55:36.941  5606  5653 I jxcore-log: 
,09-30 08:55:36.972  5606  5653 I jxcore-log: # #update - do we wait for blocked update
09-30 08:55:36.972  5606  5653 I jxcore-log: 
,09-30 08:55:37.098  5606  5653 I jxcore-log: ok 69 One go and one blocked
09-30 08:55:37.098  5606  5653 I jxcore-log: 
,09-30 08:55:37.098  5606  5653 I jxcore-log: ok 70 All blocked
09-30 08:55:37.098  5606  5653 I jxcore-log: 
09-30 08:55:37.098  5606  5653 I jxcore-log: ok 71 Still blocked
09-30 08:55:37.098  5606  5653 I jxcore-log: 
,09-30 08:55:37.539  5606  5653 I jxcore-log: ok 72 should be equal
09-30 08:55:37.539  5606  5653 I jxcore-log: 
,09-30 08:55:37.546  5606  5653 I jxcore-log: # teardown
09-30 08:55:37.546  5606  5653 I jxcore-log: 
,09-30 08:55:37.619  5606  5653 I jxcore-log: # setup
09-30 08:55:37.619  5606  5653 I jxcore-log: 
,09-30 08:55:37.682  5606  5653 I jxcore-log: # #update - test that we wait long enough
09-30 08:55:37.682  5606  5653 I jxcore-log: 
,09-30 08:55:39.310   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:55:39.408  5606  5653 I jxcore-log: ok 73 We waited long enough
09-30 08:55:39.408  5606  5653 I jxcore-log: 
,09-30 08:55:39.511  5606  5653 I jxcore-log: ok 74 should be equal
09-30 08:55:39.511  5606  5653 I jxcore-log: 
,09-30 08:55:39.518  5606  5653 I jxcore-log: # teardown
09-30 08:55:39.518  5606  5653 I jxcore-log: 
,09-30 08:55:42.340   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:55:44.012   931  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:55:45.066   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:46.068   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:47.069   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:48.070   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:49.072   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:55:50.073   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 08:56:09.608   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:56:10.074   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:56:10.719   931  5944 D NetlinkSocketObserver: NeighborEvent{elapsedMs=415625, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 08:56:11.075   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:56:12.076   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:56:12.638   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:56:13.077   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:56:14.078   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 08:56:15.079   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 08:56:17.104   931  5944 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 08:56:24.017   931  2916 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 08:56:35.678   931  5944 D NetlinkSocketObserver: NeighborEvent{elapsedMs=440584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 08:56:36.859   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:56:39.540  5606  5653 I jxcore-log: 2016-09-30 12:56:39 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-30 08:56:39.540  5606  5653 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-30 08:56:39.540  5606  5653 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-30 08:56:39.540  5606  5653 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-30 08:56:39.540  5606  5653 I jxcore-log:     at $9@timers.js:120:1
09-30 08:56:39.540  5606  5653 I jxcore-log: ''
09-30 08:56:39.540  5606  5653 I jxcore-log: 
,09-30 08:56:39.543  5606  5653 I jxcore-log: 2016-09-30 12:56:39 - DEBUG CoordinatedClient: 'test client failed'
09-30 08:56:39.543  5606  5653 I jxcore-log: 
,09-30 08:56:39.551  5606  5653 I jxcore-log: 2016-09-30 12:56:39 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-30 08:56:39.551  5606  5653 I jxcore-log: 
,09-30 08:56:39.556  5606  5653 I jxcore-log: 2016-09-30 12:56:39 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-30 08:56:39.556  5606  5653 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-30 08:56:39.556  5606  5653 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-30 08:56:39.556  5606  5653 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-30 08:56:39.556  5606  5653 I jxcore-log:     at $9@timers.js:120:1
09-30 08:56:39.556  5606  5653 I jxcore-log: ''
09-30 08:56:39.556  5606  5653 I jxcore-log: 
,09-30 08:56:39.557  5606  5653 I jxcore-log: 2016-09-30 12:56:39 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 08:56:39.557  5606  5653 I jxcore-log: 
,09-30 08:56:39.891   931  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 08:56:40.079   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 08:56:40.080   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 08:56:40.084  5999  5999 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 08:56:40.090  5999  5999 D AndroidRuntime: CheckJNI is OFF
,09-30 08:56:40.122  5999  5999 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 08:56:40.156  5999  5999 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 08:56:40.172  5999  5999 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 08:56:40.180   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-30 08:56:40.181   931   944 I ActivityManager: Killing 5606:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 08:56:40.290   931  3540 I WindowState: WIN DEATH: Window{452ae10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-30 08:56:40.290   931  3739 D GraphicsStats: Buffer count: 2
09-30 08:56:40.291   931  2917 D WifiService: Client connection lost with reason: 4
,09-30 08:56:40.333   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-30 08:56:40.333   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-30 08:56:40.335   931   944 E ActivityManager: Failure starting process com.test.thalitest
09-30 08:56:40.335   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 08:56:40.335   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.335   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.335   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:56:40.335   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 08:56:40.335   931   944 I ActivityManager:   Force finishing activity ActivityRecord{844b42d u0 com.test.thalitest/.MainActivity t2}
09-30 08:56:40.337   931   954 I art     : Starting a blocking GC Explicit
,09-30 08:56:40.342   931   941 W ActivityManager: Spurious death for ProcessRecord{591665 0:com.test.thalitest/u0a77}, curProc for 5606: null
,09-30 08:56:40.347   931   949 W WindowManager: Attempted to add application window with unknown token Token{bf49d62 ActivityRecord{844b42d u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 08:56:40.347   931   949 W WindowManager: Token{bf49d62 ActivityRecord{844b42d u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{bf49d62 ActivityRecord{844b42d u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 08:56:40.347   931   949 W WindowManager: view not successfully added to wm, removing view
09-30 08:56:40.347   931   949 W WindowManager: Exception when adding starting window
09-30 08:56:40.347   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{c9691f4 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 08:56:40.347   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 08:56:40.347   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 08:56:40.347   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 08:56:40.347   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 08:56:40.347   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 08:56:40.347   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.347   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.347   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:56:40.347   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 08:56:40.427   931   954 I art     : Explicit concurrent mark sweep GC freed 93025(6MB) AllocSpace objects, 47(1860KB) LOS objects, 33% free, 29MB/43MB, paused 1.411ms total 90.338ms
,09-30 08:56:40.448   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 08:56:40.450  5999  5999 I art     : System.exit called, status: 0
,09-30 08:56:40.450  5999  5999 I AndroidRuntime: VM exiting with result code 0.
,09-30 08:56:40.467   931   954 I ActivityManager: Start proc 6009:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-30 08:56:40.468   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 08:56:40.474   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 08:56:40.479  3622  3622 I Keyboard.Facilitator: resetDictionaries() : en_US
09-30 08:56:40.478  5886  5886 D BluetoothMapAppObserver: onReceive
09-30 08:56:40.479  5886  5886 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-30 08:56:40.481  4021  4134 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-30 08:56:40.488   931  2882 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-30 08:56:40.508  3335  6022 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 08:56:40.510  3622  6021 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 08:56:40.533  3727  3727 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 08:56:40.540  5996  5996 W kworker/1:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:56:40.542  3622  6021 I Decoder : createOrResetDecoder
,09-30 08:56:40.543  5996  5996 W kworker/1:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:56:40.553  5996  5996 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 08:56:40.552  3524  3524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-30 08:56:40.553  3524  3524 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-30 08:56:40.554  3524  3524 E AndroidRuntime: FATAL EXCEPTION: main
09-30 08:56:40.554  3524  3524 E AndroidRuntime: Process: com.google.process.gapps, PID: 3524
09-30 08:56:40.554  3524  3524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-30 08:56:40.554  3524  3524 E AndroidRuntime: 	... 8 more
,09-30 08:56:40.558   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-30 08:56:40.559   931   943 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-30 08:56:40.560   931   943 E PackageManager: Failed to write settings, restoring backup
09-30 08:56:40.560   931   943 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-30 08:56:40.560   931   943 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-30 08:56:40.560   931   943 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-30 08:56:40.560   931   943 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-30 08:56:40.560   931   943 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-30 08:56:40.560   931   943 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.560   931   943 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.560   931   943 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:56:40.560   931  6028 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:56:40.560   931  6028 E DropBoxManagerService: 	... 5 more
09-30 08:56:40.562   931   944 E DropBoxManagerService: Can't write: system_server_wtf
09-30 08:56:40.562   931   944 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:,12346)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 08:56:40.562   931   944 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:56:40.562   931   944 E DropBoxManagerService: 	... 13 more
09-30 08:56:40.563  3524  3524 I Process : Sending signal. PID: 3524 SIG: 9
,09-30 08:56:40.577  3755  3873 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-30 08:56:40.590   931  3808 I ActivityManager: Start proc 6029:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-30 08:56:40.591  3755  3873 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-30 08:56:40.591  3755  3873 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3755
09-30 08:56:40.591  3755  3873 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.591  3755  3873 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 08:56:40.594   931   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:56:40.596   931  6035 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:56:40.596   931  6035 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:56:40.596   931  6035 E DropBoxManagerService: 	... 5 more
,09-30 08:56:40.599   931  3748 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1868)
,09-30 08:56:40.599   931  3748 W ActivityManager: Application dead when creating service ServiceRecord{3cb77c6 u0 com.google.android.gms/.config.ConfigService}
,09-30 08:56:40.606  3335  3357 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjDDDC18938) - 
,09-30 08:56:40.618   931  2917 D WifiService: Client connection lost with reason: 4
,09-30 08:56:40.624   931  3748 I ActivityManager: Process com.google.process.gapps (pid 3524) has died
,09-30 08:56:40.625   931  3748 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-30 08:56:40.625   931  3748 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
09-30 08:56:40.625   931  3748 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-30 08:56:40.625   931  3748 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 31000ms
,09-30 08:56:40.626   931  3748 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 84000ms
,09-30 08:56:40.627   931  3748 W ActivityManager: Exception when starting service com.google.android.gms/.config.ConfigService
09-30 08:56:40.627   931  3748 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-30 08:56:40.627   931  3748 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:985)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-30 08:56:40.627   931  3748 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,09-30 08:56:40.630   931  3540 W ActivityManager: Spurious death for ProcessRecord{574f24c 0:com.google.process.gapps/u0a12}, curProc for 3524: null
09-30 08:56:40.634  3755  3873 I Process : Sending signal. PID: 3755 SIG: 9
,09-30 08:56:40.656  3335  6022 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-30 08:56:40.656  3335  6022 I Process : Sending signal. PID: 3335 SIG: 9
,09-30 08:56:40.660   931  3809 I ActivityManager: Start proc 6044:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-30 08:56:40.699   931  3540 D GraphicsStats: Buffer count: 1
09-30 08:56:40.699   931  3809 I WindowState: WIN DEATH: Window{52bbd2f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-30 08:56:40.699   931  2881 W InputDispatcher: channel '52bbd2f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-30 08:56:40.699   931  2881 E InputDispatcher: channel '52bbd2f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-30 08:56:40.700   931  3809 W InputDispatcher: Attempted to unregister already unregistered input channel '52bbd2f com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-30 08:56:40.704   931  3814 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3755) has died
,09-30 08:56:40.705   931  3814 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-30 08:56:40.706   931  3814 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 08:56:40.720   931   944 I ActivityManager: Start proc 6057:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:56:40.729   931  3817 I ActivityManager: Process android.process.acore (pid 3335) has died
,09-30 08:56:40.729   931  3817 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-30 08:56:40.769  6057  6057 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:56:40.769  6057  6057 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 08:56:40.769  6057  6057 D AndroidRuntime: Shutting down VM
,09-30 08:56:40.776  6057  6057 E AndroidRuntime: FATAL EXCEPTION: main
09-30 08:56:40.776  6057  6057 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6057
09-30 08:56:40.776  6057  6057 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 08:56:40.776  6057  6057 E AndroidRuntime: 	... 10 more
09-30 08:56:40.778   931  3748 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-30 08:56:40.778   931  6070 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:56:40.778   931  6070 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:56:40.778   931  6070 E DropBoxManagerService: 	... 5 more
09-30 08:56:40.779  6057  6057 I Process : Sending signal. PID: 6057 SIG: 9
,09-30 08:56:40.791   931  3540 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6057) has died
,09-30 08:56:40.793   931  3540 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 08:56:40.807   931   944 I ActivityManager: Start proc 6071:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:56:40.862  6071  6071 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:56:40.862  6071  6071 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 08:56:40.862  6071  6071 D AndroidRuntime: Shutting down VM
,09-30 08:56:40.870  6071  6071 E AndroidRuntime: FATAL EXCEPTION: main
09-30 08:56:40.870  6071  6071 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6071
09-30 08:56:40.870  6071  6071 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 08:56:40.870  6071  6071 E AndroidRuntime: 	... 10 more
,09-30 08:56:40.873   931  3808 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:56:40.874   931  6083 E DropBoxManagerService: Can't write: system_app_crash
09-30 08:56:40.874   931  6083 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 08:56:40.874   931  6083 E DropBoxManagerService: 	... 5 more
09-30 08:56:40.874  6071  6071 I Process : Sending signal. PID: 6071 SIG: 9
,09-30 08:56:40.889   931   941 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6071) has died
,09-30 08:56:40.890   931   941 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 08:56:40.905   931   944 I ActivityManager: Start proc 6084:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 08:56:40.938   383   473 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
